# Agent Briefing: stakeholder-outreach-draft-generator

## 1. Repository Overview & Purpose
- **Repository**: `webdev0814/stakeholder-outreach-draft-generator`
- **Visibility**: `Public`
- **Default Branch**: `main`
- **Last Updated / Pushed**: 2026-09-08
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
- `[7615609]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[d3ee2d2]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[38906af]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[c266f21]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[51e41f4]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[c289629]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[5aee257]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[29b85b7]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[56ac2d9]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol
- `[22af379]` (2026-09-08) docs: update agent briefing with multi-computer handoff protocol

---

## 5. Current State & Immediate Next Steps
- **Current State**: Project is active under branch `main`.
- **When picking up this repo**:
  1. Inspect the top-level files and recent commits to understand the active feature or bugfix context.
  2. Verify all required credentials and environment variables before running integration scripts.
  3. Ensure all tests and linting pass after making modifications.
  4. Follow the repository conventions and preserve existing architecture patterns.

---

## 6. Multi-Computer Handoff & Git Sync Protocol
- **On Session Start**: Always run `git pull` when opening this repository on any computer to synchronize the latest changes.
- **On Task Completion**: Before ending any agent session, the agent **MUST**:
  1. Update Section 5 (Current State & Next Steps) in this `AGENTS.md` file.
  2. Stage all modifications (`git add .`).
  3. Commit with a concise conventional message (`git commit -m "feat/fix: ..."`).
  4. Push directly to GitHub (`git push`).
- **Secret Hygiene**: NEVER commit plain-text API keys, tokens, or credentials into repository files.
