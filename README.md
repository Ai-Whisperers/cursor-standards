# AI Whisperers — Cursor Development Framework

Rules, prompts, and validation scripts used across AI Whisperers repos.

This is **not** company documentation.

| Topic | Repository |
|-------|------------|
| Company narrative, services, ICPs | [company](https://github.com/Ai-Whisperers/company) |
| Legal & EAS formation | [legal](https://github.com/Ai-Whisperers/legal) |
| Marketing playbook | [marketing-strategy](https://github.com/Ai-Whisperers/marketing-strategy) |

## Structure

- `.cursor/rules/` — coding, git, quality, ticket standards
- `.cursor/prompts/` — reusable agent prompts
- `.cursor/scripts/` — validation and housekeeping
- `.claude/` — Claude Code commands and settings (if present)

## Usage

**Option A — Copy into a project**

```powershell
Copy-Item -Recurse .cursor\ path\to\your-repo\.cursor\
```

**Option B — Submodule**

```bash
git submodule add https://github.com/Ai-Whisperers/cursor-standards.git .cursor-standards
```

**Option C — Open alongside your work in Cursor**

Clone this repo next to your project and reference rules from both workspaces.

## Versioning

Tagged releases (`v1.0.0`, etc.) snapshot the framework for reproducible agent behavior.

## Origin

Extracted from archived [Company-Information](https://github.com/Ai-Whisperers/Company-Information) during the July 2026 documentation migration.
