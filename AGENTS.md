# Agent Briefing: stakeholder-outreach-draft-generator

## 1. Repository Overview & Purpose
- **Repository**: `webdev0814/stakeholder-outreach-draft-generator`
- **Visibility**: `Public`
- **Default Branch**: `main`
- **Last Updated / Pushed**: 2026-09-04
- **Description**: Automated directory cleaning, DNS MX checking, sheets syncing, and throttled outreach draft generation in Gmail.
- **Context from README**: A human-in-the-loop workflow for cleaning stakeholder directories, segmenting contacts, synchronizing structured data with Google Sheets, and generating context-aware Gmail drafts for manual review. This project demonstrates how an AI-enabled workflow can improve operational throughput without remov...
- **Topics/Tags**: automation, dns, email-verification, gmail-api

---

## 2. Tech Stack & Architecture
- **Primary Language / Ecosystem**: Python
- **Key Directories**: Single root directory structure.
- **Notable Top-Level Files**: `.gitignore`, `AGENTS.md`, `CLAUDE.md`, `GEMINI.md`, `LICENSE`, `README.md`, `SECURITY.md`, `agent_workflow_contract.md`, `email_templates.md`, `process_contacts.py`, `purge_bounces.py`, `run_outreach.py`

---

## 3. Setup & Execution Commands
### Environment Setup & Installation
```bash
# Review repository files and install dependencies corresponding to the language/runtime.
```

### Running / Starting
```bash
python3 <entrypoint>.py
```

### Testing / Verification
```bash
# Run relevant unit/integration tests (e.g. pytest or npm test)
```

---

## 4. Recent Commit Activity (Where We Left Off)
The most recent commits show the latest development trajectory:
- `[14d0cad]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[38057a3]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[a6a0f17]` (2026-09-08) docs: update agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[4a875ac]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[39553a3]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[46b2c61]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[1918f71]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[818ad87]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[b7dea55]` (2026-09-04) docs: add comprehensive agent briefing (AGENTS.md, GEMINI.md, CLAUDE.md)
- `[0c5f988]` (2026-09-03) Add security reporting and repository hygiene policy

---

## 5. Current State & Immediate Next Steps
- **Current State**: Project is active under branch `main`.
- **When picking up this repo**:
  1. Inspect the top-level files and recent commits to understand the active feature or bugfix context.
  2. Verify all required credentials and environment variables before running integration scripts.
  3. Ensure all tests and linting pass after making modifications.
  4. Follow the repository conventions and preserve existing architecture patterns.

---

## 6. Agent Working Guidelines & Gotchas
- **Cross-Platform Compatibility**: Code may run across Windows, macOS, or Linux agent environments. Ensure path manipulations use OS-agnostic methods (e.g. `pathlib.Path` or `path.join`).
- **Secret Hygiene**: NEVER commit plain-text API keys, tokens, or credentials into repository files.
- **Git Commit Etiquette**: Use concise, conventional commit messages (e.g., `feat:`, `fix:`, `docs:`, `refactor:`).
- **Tooling Compatibility**: This briefing is kept aligned for Antigravity (`GEMINI.md`), Claude Code / Codex (`CLAUDE.md`), and general autonomous agents (`AGENTS.md`).
