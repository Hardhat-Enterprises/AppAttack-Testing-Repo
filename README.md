# AppAttack – Pentesting Findings Automation & Workflow Research

This repository is for testing automation workflows for the pen-testing findings process. **It does not contain any real findings or data.** It exists purely to trial and refine how AppAttack contributions and GitHub-based systems automation should work before rolling processes out to live repositories.

## Purpose

- Prototype and validate the contribution workflow for pen-testing findings (branch protection, pull requests, folder structure, review process).
- Test GitHub automation (branch rules, GitHub Actions, etc.) in a safe, disposable environment.
- Provide a reference structure that mirrors the real project repositories, without exposing any actual findings or sensitive data.

## Repository Structure

This repo mirrors the folder layout used across the real project repositories:

```
Trimester_2_2026/
├── DUMMY/
│   └── findings/
|   └── qa-failed/
|   └── ready-for-final-report/
└── DUMMY2/
    └── findings/
    └── qa-failed/
    └── ready-for-final-report/
```

Each project folder contains a `findings/` sub-folder, which is where contributions relating to that project's pen-testing findings should be added by a RP and moved to the correct project folder.

## Notes for Contributors

- This is a **testing and research repository only** — do not upload real client data, real findings, or sensitive information here.
- Use this space freely to experiment with workflow, automation, and folder structure changes before they're proposed for the live repositories if you are assigned/contributing to this space.
- If you're testing something destructive (force pushes, deleting branches, etc.), please note it in your PR description so others aren't caught off guard.
