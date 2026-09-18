# Public readiness — Henrique Moreira repos

Decision matrix based on live deployments + GitHub visibility from Cloud Agent (2026-09-18).

| Product | Live URL | GitHub (from this agent) | Recommendation | Why |
|---------|----------|--------------------------|----------------|-----|
| **Portfolio** | https://henriquemoreira.eu | `hqemoreira/portfolio` (public, push denied to agent) | **Keep PUBLIC** | Indexed hub; already public; cleanup prepared |
| **GRYPS** | https://gryps.vercel.app | Not visible under `hqemoreira/*` | **Make / keep PUBLIC** after scrub | Non-commercial R&D demo already on the open web; skill-demo posture |
| **FORGE** | https://forge.henriquemoreira.eu | Not visible under `hqemoreira/*` | **Keep PRIVATE** | Auth.js login wall; personal ops dashboard; deployment/session history |
| **Profile README** | GitHub profile | `hqemoreira/hqemoreira` | **Keep PUBLIC** | Profile front door; PR open |
| Earlier prototypes (LitrixEU, Velu, Grantemia, Lycaon, DisclAI, Iraun) | various `*.vercel.app` / domains | No separate repos visible | **Prefer private or archived**; if public, noindex + hub `nofollow` | Shelved context only; portfolio already links nofollow |

## Blockers for this agent

1. Write access only to `hqemoreira/hqemoreira`
2. `hqemoreira/portfolio` readable but **push 403**
3. GRYPS and FORGE GitHub URLs unknown / private — not resolvable as `hqemoreira/gryps` or `hqemoreira/forge`

## What you should do next

1. Reply with exact GitHub URLs for GRYPS and FORGE, **or** open Cloud Agents from inside those repos.
2. Re-run / grant write on **portfolio** so the cleanup PR can land.
3. For GRYPS public release checklist: README + LICENSE + SECURITY, no secrets in history, no Forge-private coupling, env example scrubbed, Dependabot/CI green.
4. For FORGE: leave private; ensure repo visibility=private; no public Vercel preview without auth; confirm `.env` / Neon / Auth secrets never committed.
