### Hi, I'm Ryan

WSU Cybersecurity, class of 2028. I build agent-operated systems and LLM evaluation harnesses, and I own the requirements and review for every change an agent makes.

#### What I'm building

- **Agent-operated homelab** (Python, Linux, Proxmox): I run AI coding agents against real systems behind a quality gate: a change isn't done until there's a real commit and a passing test, with a matrix linking each requirement to its test. *Private, demo on request.*
- **LLM evaluation harnesses** (Python, llama.cpp): Score local models against ground truth before anything depends on them. A quantized Qwen3-4B hit 18/20 on an announcement-extraction eval at ~9s per item; a commit-replay harness caught a 7B coding model failing 0/10. *Write-up coming.*
- **Coursework archive with an MCP server** (Python, SQLite, REST): Syncs current-term coursework, full-text search, and 16 read-only tools a coding agent queries directly. Cut API traffic ~4.5x by syncing only the active term. *Private, demo on request.*

Still developing: deeper systems security, and taking these evals from one-off harnesses toward reusable tooling.

#### Public work you can read

- [course-rag](https://github.com/brenner-ryan/course-rag): retrieval-augmented generation over course material in Python.
- [python-ci-student-lab](https://github.com/brenner-ryan/python-ci-student-lab): a Python lab wired for continuous integration.
- [python-ci-demo-test](https://github.com/brenner-ryan/python-ci-demo-test): a small CI demo showing the test-and-build pipeline.
- [lab-agile-planning](https://github.com/brenner-ryan/lab-agile-planning): agile planning artifacts from a software engineering lab.
- [BARD](https://github.com/BradyZapf/CptS_322_BARD): a team software-engineering project with CI, specs, and requirement-to-test traceability (course team repo).

#### Skills

- **Languages:** C++, C, Python, Java, JavaScript
- **AI & tools:** LLM evaluation, llama.cpp, quantized local inference, MCP, agent harnesses
- **Systems:** Linux, Git, Proxmox, systemd, FastAPI, SQLite
- **Practices:** pytest, CI, Agile/Kanban, spec-driven development with quality gates

#### Contact

[github.com/brenner-ryan](https://github.com/brenner-ryan) · ryan.brenner@wsu.edu
