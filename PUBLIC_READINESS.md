# Public readiness — Henrique Moreira repos

Policy confirmed 2026-09-18 by owner.

| Product | GitHub (expected) | Visibility intent | Recommendation |
|---------|-------------------|-------------------|----------------|
| **Portfolio** | `hqemoreira/portfolio` | **PUBLIC** | Keep public. Professional cleanup prepared; agent needs write access to land PR. |
| **GRYPS** | `hqemoreira/main` (renamed from gryps) | Decide after curation | Curate to public-ready (README, LICENSE, SECURITY, scrub secrets). Live demo already public at gryps.vercel.app. |
| **FORGE** | private internal OS | **PRIVATE forever** | Do not make public. Personal/internal infrastructure OS. |
| **Profile README** | `hqemoreira/hqemoreira` | **PUBLIC** | Keep public. |
| **Archived prototypes** (LitrixEU, Velu, Grantemia, DisclAI, Lycaon, Iraun, …) | private + archived | Curate first, then decide | Clean code + professional README while still private; unarchive/make public only after owner review. |

## Agent access status (this run)

| Repo | Readable | Writable |
|------|----------|----------|
| `hqemoreira/hqemoreira` | yes | yes |
| `hqemoreira/portfolio` | yes (public clone) | **no** (push 403) |
| `hqemoreira/main` (GRYPS) | **no** (404 to agent) | **no** |
| FORGE | **no** | **no** (intentionally private) |
| Archived prototypes | **no** | **no** |

Private repos are invisible to `cursor[bot]` until Cloud Agents are started **from inside those repositories** (or the GitHub App is granted access and they are added to the environment).

## Curation checklist (for each repo before public)

- [ ] Professional README (what it is, stack, how to run, license, contact)
- [ ] LICENSE + SECURITY.md
- [ ] No secrets in tree or git history (`.env`, API keys, tokens)
- [ ] `.env.example` with placeholders only
- [ ] Dead assets / scaffold leftovers removed
- [ ] Lint + build pass
- [ ] Accurate public posture (no storefront claims; prototypes labeled as such)
- [ ] FORGE: skip — remains private
