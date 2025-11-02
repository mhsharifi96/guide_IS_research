# Guide Information System Research
This repository collects materials, notes, data pointers, and reproducible artifacts for Information Systems research.

## Overview
- Purpose: centralize experiments, code, and documentation for IS research projects and replication.
- Audience: researchers, students, and collaborators.

## Prerequisites
- Dev container: Ubuntu 24.04 (configured for this workspace).
- Common tools: git, docker, python (3.11+ recommended), R (optional).

## Quick start
1. Clone the repo:
    - git clone <repo-url>
2. Open in dev container or run locally.
3. Create a virtual environment and install dependencies:
    - python -m venv .venv
    - source .venv/bin/activate
    - pip install -r requirements.txt

## Repository layout
- /data — raw and processed data (sensitive data should not be committed)
- /notebooks — analysis and exploratory notebooks
- /src — code for experiments and utilities
- /figures — generated plots and images
- /docs — supplementary documents and protocols

## Reproducibility
- Include scripts to reproduce figures and results in /src/repro
- Use explicit random seeds and record software versions (pip freeze > requirements.txt)

## Data and ethics
- Do not commit personally identifiable or restricted data. Provide instructions or scripts to fetch and preprocess data instead.

## Contributing
- Fork → branch → pull request
- Document changes in CHANGELOG.md
- Run tests before submitting (pytest)

## License & Citation
- Add license file (e.g., MIT or CC-BY) and preferred citation in CITATION.cff

## Contact
- Create an issue or PR for questions or corrections.
- Maintain a short README per subproject for project-specific instructions.
