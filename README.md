# Fresu Electronics — Artifacts Library

Private central repository for all interactive HTML artifacts created by Fresu Electronics.

## Structure

```
fresu-artifacts/
├── emc-fundamentals/          # PCB EMC Fundamentals Interactive Guide
├── top-10-pcb-mistakes/       # Reference to public repo
├── [future-artifact]/
└── README.md
```

## Usage

Each artifact folder contains:
- `index.html` — the standalone artifact (single-file, self-contained)
- `README.md` — description, topic, target audience, creation date

## Fetching an artifact

```python
import requests, base64

TOKEN = "your_token"
REPO  = "dariofresu/fresu-artifacts"
headers = {"Authorization": f"token {TOKEN}"}

def fetch_artifact(path):
    r = requests.get(f"https://api.github.com/repos/{REPO}/contents/{path}", headers=headers)
    if r.status_code == 200:
        return base64.b64decode(r.json()['content']).decode('utf-8')
    return None

html = fetch_artifact("emc-fundamentals/index.html")
```

## Artifacts Index

| Artifact | Folder | Topic | Status |
|----------|--------|-------|--------|
| EMC Fundamentals Guide | `emc-fundamentals/` | PCB EMC design principles, calculators, quiz | ✅ Active |

---
*Fresu Electronics — fresuelectronics.com*
