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

| Date | Target | Class | CVE / GHSA | Write-up |
|------|--------|-------|-----|----------|
| 2026-11-25 | asar-py | Path traversal (archive extraction -> RCE) | [CVE-2026-136923](https://www.cve.org/CVERecord?id=CVE-2026-136923) | [Write-up](https://r3vpwnx.space/research/asar-py-extract-path-traversal/) |
| 2026-11-25 | PyBioNetGen | Eval injection (RCE) | [CVE-2026-136922](https://www.cve.org/CVERecord?id=CVE-2026-136922) | [Write-up](https://r3vpwnx.space/research/pybionetgen-bngxml-sympify-rce/) |
| 2026-11-24 | RedVector | Hard-coded credentials + command injection (RCE) | [CVE-2026-136168](https://www.cve.org/CVERecord?id=CVE-2026-136168) | [Write-up](https://r3vpwnx.space/research/redvector-default-token-command-rce/) |
| 2026-11-24 | vedo | Deserialization RCE | [CVE-2026-136167](https://www.cve.org/CVERecord?id=CVE-2026-136167) | [Write-up](https://r3vpwnx.space/research/vedo-npy-allow-pickle-rce/) |
| 2026-11-24 | OpenShot Video Editor | Deserialization RCE | [CVE-2026-134704](https://www.cve.org/CVERecord?id=CVE-2026-134704) | [Write-up](https://r3vpwnx.space/research/openshot-osp-pickle-rce/) |
| 2026-11-24 | Gammapy | Eval injection (RCE) | [CVE-2026-134694](https://www.cve.org/CVERecord?id=CVE-2026-134694) | [Write-up](https://r3vpwnx.space/research/gammapy-wcsshape-fits-eval-rce/) |
| 2026-11-23 | hickle | Deserialization RCE (safe=True bypass) | [CVE-2026-103926](https://www.cve.org/CVERecord?id=CVE-2026-103926), [GHSA-mwxj](https://github.com/telegraphic/hickle/security/advisories/GHSA-mwxj-5v28-gh2q) | [Write-up](https://r3vpwnx.space/research/hickle-safe-flag-pickle-rce/) |
| 2026-11-21 | diffpy.structure | Eval injection (RCE) | [CVE-2026-133708](https://www.cve.org/CVERecord?id=CVE-2026-133708) | [Write-up](https://r3vpwnx.space/research/diffpy-structure-cif-eval-rce/) |
| 2026-11-21 | targets (R, rOpenSci) | Code injection (RCE) | [CVE-2026-133707](https://www.cve.org/CVERecord?id=CVE-2026-133707) | [Write-up](https://r3vpwnx.space/research/targets-store-format-eval-rce/) |
| 2026-11-21 | yt | Eval injection (RCE) | [CVE-2026-132751](https://www.cve.org/CVERecord?id=CVE-2026-132751) | [Write-up](https://r3vpwnx.space/research/yt-ytdata-con-args-rce/) |
| 2026-11-14 | RedAmon | Missing authentication (root shell) + BOLA | [CVE-2026-129855](https://www.cve.org/CVERecord?id=CVE-2026-129855), [CVE-2026-129854](https://www.cve.org/CVERecord?id=CVE-2026-129854) | [Write-up](https://r3vpwnx.space/research/redamon-unauth-pty-and-session-bola/) |
| 2026-11-10 | Head Start TTADP (US HHS) | Broken access control (cross-region IDOR) | [GHSA-9r9x](https://github.com/HHS/Head-Start-TTADP/security/advisories/GHSA-9r9x-g862-525c), [GHSA-q859](https://github.com/HHS/Head-Start-TTADP/security/advisories/GHSA-q859-79hf-rpr3) | [Write-up](https://r3vpwnx.space/research/head-start-ttadp-cross-region-idor/) |
| 2026-11-09 | PyMoDAQ | Deserialization + eval RCE | [CVE-2026-120859](https://www.cve.org/CVERecord?id=CVE-2026-120859) | [Write-up](https://r3vpwnx.space/research/pymodaq-h5-deserialization-rce/) |
| 2026-11-09 | mpv | Playlist / CRLF injection | [CVE-2026-123095](https://www.cve.org/CVERecord?id=CVE-2026-123095) | [Write-up](https://r3vpwnx.space/research/mpv-ytdl-playlist-injection/) |
| 2026-11-09 | labbench (NIST) | Deserialization RCE | [CVE-2026-120833](https://www.cve.org/CVERecord?id=CVE-2026-120833) | [Write-up](https://r3vpwnx.space/research/labbench-read-pickle-rce/) |
| 2026-11-09 | h5io | Code injection (eval/import/unpickle) | [CVE-2026-120499](https://www.cve.org/CVERecord?id=CVE-2026-120499) | [Write-up](https://r3vpwnx.space/research/h5io-read-hdf5-code-injection/) |
| 2026-11-03 | QOwnNotes | Path traversal | [GHSA-fmqx](https://github.com/pbek/QOwnNotes/security/advisories/GHSA-fmqx-8x8h-gf76) | [Write-up](https://r3vpwnx.space/research/qownnotes-media-path-traversal/) |
| 2026-11-01 | imagecodecs | Memory-safety DoS | [CVE-2026-120251](https://www.cve.org/CVERecord?id=CVE-2026-120251), [CVE-2026-120252](https://www.cve.org/CVERecord?id=CVE-2026-120252) | [Write-up](https://r3vpwnx.space/research/imagecodecs-decoder-dos/) |
| 2026-11-01 | GSAS-II (DOE / Argonne) | Deserialization RCE | [GHSA-ppf5](https://github.com/AdvancedPhotonSource/GSAS-II/security/advisories/GHSA-ppf5-4gw2-37j9) | [Write-up](https://r3vpwnx.space/research/gsas-ii-gpx-pickle-rce/) |
| 2026-10-31 | VNote | OS command injection (RCE) | [CVE-2026-126042](https://www.cve.org/CVERecord?id=CVE-2026-126042) | [Write-up](https://r3vpwnx.space/research/vnote-tasks-cmdinjection/) |
| 2026-10-31 | CherryTree | OS command injection (RCE) | [CVE-2026-118692](https://www.cve.org/CVERecord?id=CVE-2026-118692) \* | [Write-up](https://r3vpwnx.space/research/cherrytree-weblink-cmdinjection/) |
| 2026-10-24 | QOwnNotes | OS command injection (RCE) | [GHSA-jp2h](https://github.com/pbek/QOwnNotes/security/advisories/GHSA-jp2h-69pm-p69c) | [Write-up](https://r3vpwnx.space/research/qownnotes-git-cmdinjection/) |

\* CherryTree: independent discovery; the CVE is credited to another researcher, and r3vpwnx is credited in the upstream fix.

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
