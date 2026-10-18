# Life Commons — Agent Operating Contract

Scope: All repositories under the **Life-Commons** GitHub Organization (https://bluelifecommons.org).
Brand register: `life-commons`

## Responsible Agent Team & Governance

| Role | Assigned Owner |
| :--- | :--- |
| **Human Codeowner** | `@frankxai` |
| **Organization Steward** | `steward-commons` |
| **Executive Seat** | CSO (Impact, Longevity & Ethics Guardian) |
| **Universal IS** | Health IS,Family IS,Self IS,Marine Intelligence |
| **Council Lead** | starlight-embodiment,starlight-relational,starlight-sage |
| **Primary Harnesses** | `Claude Code`, `Antigravity`, `Hermes` |

## Core Guardrails

1. **Think before coding.** State assumptions and surface tradeoffs. Verify file contents and branch state before writing.
2. **Surgical changes.** Touch only the files required for the active slice. Never overwrite or reset another agent's uncommitted worktree.
3. **Branch and worktree discipline.** Never push directly to `main`. Work on `agent/<harness>/<scope>` in a dedicated worktree and open a **draft** pull request first.
4. **Maker != Checker.** The harness that authors a pull request never approves or merges its own pull request.
5. **CI budget discipline.** Keep pull requests in draft until local verification (`lint`, `typecheck`, `test`, `build`) passes. Mark ready for review once.
6. **Non-waivable safety.**
   - Never commit secrets, API keys, or `.env` files.
   - Preserve repository visibility parity: never copy or mirror private repository contents into a public repository.
   - Money fails closed; no autonomous spend or paid API provisioning without explicit human approval.
   - In health and mind domains, model observations only; never diagnose or make clinical claims.

## Federated Repository Roster (7 repositories)

| Repository | Visibility | Primary Owner | Role |
| :--- | :--- | :--- | :--- |
| `blue-life-commons` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/blue-life-commons) |
| `dino-life-commons` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/dino-life-commons) |
| `ocean-intelligence` | `private` | `frankxai` | federated-mirror (SSOT: frankxai/ocean-intelligence) |
| `health-intelligence-system` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/health-intelligence-system) |
| `mind-intelligence-systems` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/mind-intelligence-systems) |
| `family-intelligence-os` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/family-intelligence-os) |
| `family-history-atlas` | `public` | `frankxai` | federated-mirror (SSOT: frankxai/family-history-atlas) |

Built on SIP
