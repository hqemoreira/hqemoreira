# Litrix — remove nonexistent brand domain `litrix.eu`

**Valid live URL only:** `https://litrixeu.vercel.app`  
**Never existed:** brand domain `litrix.eu` — remove everywhere.

## Paste into a Cloud Agent started INSIDE `hqemoreira/litrix`

```text
Remove nonexistent brand domain litrix.eu everywhere in hqemoreira/litrix.

Rules:
- Brand domain litrix.eu NEVER existed — delete "Brand domain: litrix.eu" and any similar lines from README and docs.
- The ONLY valid public URL is https://litrixeu.vercel.app (keep "Live: litrixeu.vercel.app").
- Replace every litrix.eu reference (links, canonical, sitemap locs, verify.html text, og:url, JSON-LD) with https://litrixeu.vercel.app or same-origin relative paths (e.g. /verify.html without litrix.eu label).
- Search the whole tree for: litrix.eu, Brand domain, brand domain
- Keep non-commercial learning framing.
- Branch: cursor/litrix-remove-brand-domain-2284
- Commit message: docs: remove nonexistent litrix.eu brand domain; keep litrixeu.vercel.app
- Push and open draft PR. Lint/build if applicable.

Known live-site hits to fix in source:
- Homepage text linking "litrix.eu/verify.html"
- verify.html canonical https://litrix.eu/verify.html
- sitemap.xml locs under https://litrix.eu/
```

## Status

- Portfolio already links `https://litrixeu.vercel.app` only (no brand-domain text).
- Profile agent cannot clone private `hqemoreira/litrix` (404) — must run the prompt above from inside that repo, then redeploy Vercel.
