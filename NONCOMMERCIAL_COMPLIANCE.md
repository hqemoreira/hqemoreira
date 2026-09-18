# Non-commercial / reskilling compliance (before making any repo public)

Owner status: Finnish unemployment fund — **not an entrepreneur**. All public work must read as **personal reskilling / learning**, never as a business.

## Required line (README first screen + site footer/disclaimer + GitHub About)

```text
Personal reskilling project · Non-commercial · Not a product for sale · No accounts / no billing
```

## Ban / avoid on public surfaces

Buy · pricing · customers · free trial · SaaS · launch · get compliant for your company · start free · subscribe · waitlist · for sale · billing

## Prefer

research prototype · skill demonstration · learning project · illustrative demo · educational · non-commercial · Open prototype

## Per-repo checklist before flipping to public

- [ ] README opens with the required line
- [ ] Live site hero or footer carries the same line
- [ ] GitHub About/description updated
- [ ] No commercial CTAs in UI
- [ ] Litrix / compliance prototypes framed as **educational / illustrative**, not a service
- [ ] FORGE stays private forever
- [ ] No secrets in tree or history

## Prompt for each product repo (Cloud Agent inside that repo)

```text
Enforce non-commercial reskilling posture before any public visibility change.

REQUIRED DISCLAIMER (README first lines + site footer/hero + GitHub About description):
"Personal reskilling project · Non-commercial · Not a product for sale · No accounts / no billing."

Rules:
- Owner is not an entrepreneur; all work is personal learning / skill demonstration under Finnish unemployment-fund reskilling — not a company and not for sale.
- Remove or rewrite commercial language: Buy, pricing, customers, free trial, SaaS, launch, get compliant for your company, start free, subscribe, waitlist, billing.
- Prefer: research prototype, skill demonstration, learning project, illustrative demo, educational.
- CTAs: Open prototype only.
- Soften any compliance-product copy (especially Litrix) to educational/illustrative.
- Do NOT change GitHub visibility yourself; leave a PR note “ready for public after owner review”.
- FORGE: if this is FORGE, stop — keep private forever.
- Branch: cursor/<repo>-noncommercial-compliance-2284
- Commit, push, draft PR. Lint/build must pass if applicable.
```

## Status from profile agent (2026-09-18)

| Repo | Framing update |
|------|----------------|
| `hqemoreira` (profile) | Updated in PR |
| `portfolio` | Updated on branch `cursor/portfolio-noncommercial-framing-2284` (push may need in-repo agent) |
| `gryps`, `litrix`, others | Run the prompt above inside each repo — not writable from this profile-only agent |
| FORGE | Skip |
