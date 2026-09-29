# Hey, I'm Mohib

Software engineer in Karachi. I build AI agent security tools, backend systems, and firmware for nRF hardware.

These days most of my time goes into agent security and evaluation: scanning agent skills before they run, and measuring how well other scanners and models catch malicious ones.

## What I work with

**Agent security and evaluation**: agent-skill scanning, static analysis, LLM adjudication, benchmark harnesses, SARIF
**AI/ML**: PyTorch, computer vision (YOLO, RF-DETR, ByteTrack)
**Backend**: Python, Django REST, FastAPI, PostgreSQL, Redis, Docker
**Web**: TypeScript, React, Next.js, Tailwind
**Embedded**: C++, nRF54L15, BLE, Zigbee, FPGA edge inference (Vitis AI)
**Systems**: Rust

## Projects

**[clawvet](https://www.npmjs.com/package/clawvet)** (PyPI, npm)
Security scanner for AI agent skills. Static triage first, LLM adjudication second. Two independent research papers used it as their baseline.

**[jev-skillbench](https://github.com/MohibShaikh/jev-skillbench)**
Benchmark harness for TypeSafe's Jev model as a malicious-skill detector. Ran all 7,944 skills in MalSkillBench across three inference backends.

**[unix-ancillary](https://crates.io/crates/unix-ancillary)** (Rust)
Safe file descriptor passing over Unix sockets (SCM_RIGHTS). Used by the systemd-nspawn plugin for Forgejo's CI runner.

**[overruled](https://github.com/MohibShaikh/overruled)** (PyPI, GitHub Action)
Verdict auditor for AI SOC agents. Replays ground-truth cases and grades the rulings, with no LLM in the grading path.

**[hwcontract](https://github.com/MohibShaikh/hwcontract)** (PyPI)
Temporal assertions over hardware traces. Runs as a pytest plugin, a GitHub Action, and an MCP server.

## Open source contributions

- Zed editor: merged PR #48870, credited in v0.224.0-pre
- Roboflow: merged an RF-DETR and ByteTrack sports tracking pipeline

## Research

- "Comparative Assessment of YOLO Nano Architectures for High-Speed Steel Detection"
- "Secure Edge Deployment of Machine Vision System on FPGA Platform", IEEE CW 2026, accepted

## Contact

[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:mohibuddin9@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000?style=flat&logo=vercel&logoColor=white)](https://mohibuddin.com)
