# Security research and advisories

Vulnerability research, exploit development notes, and coordinated-disclosure
advisories by **Dilanka Kaushal Hewage (`r3vpwnx`)**.

Each advisory is written up with a root cause, a minimal reproduction, impact, an
honest CVSS, and a disclosure timeline. Everything here is published under
coordinated disclosure: nothing is posted before the affected vendor has been
notified and a fix or a reasonable disclosure window has passed.

- Site: https://r3vpwnx.space
- Contact: dilankakaushalhewage@gmail.com

## Advisories

Newest first.

| Date | Target | Class | CVE | Write-up |
|------|--------|-------|-----|----------|
| _(none published yet)_ | | | | |

Advisories are added here as coordinated-disclosure windows close.

## Research notes

Longer-form, class-level analysis that is not tied to a single advisory.

| Topic | Summary | Notes |
|-------|---------|-------|
| _(none published yet)_ | | |

## Layout

```
advisories/
  YYYY-<target>-<class>/
    README.md        the write-up (use templates/advisory-README.md)
    poc/             minimal proof-of-concept (no weaponized payloads)
research/
  <topic>/
    README.md
templates/
  advisory-README.md fixed section order for every advisory
```

Conventions:

- One directory per advisory, named `YYYY-<target>-<class>` (for example
  `2026-cacti-graph-template-rce`). Lowercase, hyphenated.
- Every advisory `README.md` follows [templates/advisory-README.md](templates/advisory-README.md)
  so they read consistently.
- Keep proof-of-concept code minimal and non-destructive. Default payloads should
  prove execution (a marker, `id`), not cause harm.
- Add the newest advisory to the top of the table above.

## Disclosure policy

Coordinated disclosure by default. Vendor first, a reasonable window, then public
write-up and (where applicable) a CVE via the CNA or MITRE. If a vendor disputes
or declines to fix, the write-up still represents their position fairly and links
any independent identifier (CVE) rather than editorializing.

## License

- Write-ups and prose: CC BY 4.0 (attribution).
- Code and proof-of-concept scripts: MIT.

See `LICENSE` (code) and the note above for prose. All content is for authorized
security testing and education only.
