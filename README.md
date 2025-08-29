# DocuSync — LLM-Assisted Documentation
Automates product documentation from codebase & release metadata with an LLM + CI/CD.

![<ALT TEXT GOES HERE>](./reports/figures/docusync_og.png)

## 1) Problem
Manual doc writing slowed releases and produced inconsistencies.

## 2) Approach
- Parse release metadata + code diffs
- Generate draft docs via LLM (OpenAI API)
- Human-in-the-loop review in PR
- CI/CD integration to trigger suggestions

## 3) Results
- **-70%** manual doc effort
- **2×** faster turnaround
- Better cross-team visibility

## 4) How to Run (local)
```bash
pip install -r requirements.txt
export OPENAI_API_KEY=...
python src/generate_docs.py --release_notes path/to/notes.md
```

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Status](https://img.shields.io/badge/status-in_progress-yellow)
![License: MIT](https://img.shields.io/badge/License-MIT-green)





