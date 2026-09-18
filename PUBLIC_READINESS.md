# Public readiness — Henrique Moreira repos

Policy confirmed by owner (2026-09-18).

| Product | GitHub | Visibility intent | Status from this agent |
|---------|--------|-------------------|------------------------|
| **Portfolio** | `hqemoreira/portfolio` | **PUBLIC** | Cleanup ready locally; push blocked (env token scoped to profile only) |
| **GRYPS** | `hqemoreira/gryps` (private; screenshot) | Curate → then decide public | Not reachable from this agent run |
| **FORGE** | private | **PRIVATE forever** | Skip |
| **Profile README** | `hqemoreira/hqemoreira` | **PUBLIC** | PR open; env setup proposed for Save |
| **Archived prototypes** | `litrix`, `disclai`, … (private) | Curate while private → decide | Not reachable from this agent run |

## Why access still fails on this run

GitHub App repository access was updated (user confirmed Save). This Cloud Agent environment still lists only:

`github.com/hqemoreira/hqemoreira`

The run token therefore still reports `/installation/repositories` total=1. Expanding the App does not re-scope a mid-flight agent. New agents must be started **from each product repo**, or the environment must include those repos and a **new** agent started.

## How to finish curation

Open Cursor Desktop → open each repo → Cloud Agent → paste the curation prompt for that product. Skip FORGE.
