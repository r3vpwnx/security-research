# <CVE-ID or PENDING> - <Target product> <version>: <one-line title>

<!--
Advisory template. Copy this file to advisories/YYYY-<target>-<class>/README.md
and fill every section. Keep it factual, keep an honest CVSS, keep the vendor's
position fair. Delete these comments and any section that genuinely does not
apply (say why if you drop one).
-->

- Reporter: Dilanka Kaushal Hewage (r3vpwnx) <dilankakaushalhewage@gmail.com>
- Status: <reported | acknowledged | fixed | published | disputed>
- CVE: <CVE-ID or "PENDING (MITRE/CNA request filed)" or "none">

## Summary

<Two or three sentences: what the component is, what the flaw is, and what an
attacker gets. No hype.>

## Affected versions

<Exact versions you confirmed. State what you tested. Do not list a range you did
not verify.>

## Root cause

<The mechanism. Name the sink (function/file/parameter) and why the input reaches
it. One or two short paragraphs, or a small annotated code excerpt.>

## Reproduction

<Exact, replayable steps. Commands and the real flags. Reference the PoC in
`poc/`. Keep payloads minimal and non-destructive.>

```
<command(s)>
```

Expected result:

```
<the observed evidence: marker file, id output, HTTP status differential, etc.>
```

## Impact

<What the flaw allows, measured not hyped. Preconditions (auth required?
default config? network reachable?) stated plainly.>

## Severity

`CVSS:3.1/...` (score)

<One line justifying the vector honestly, including any downgrade for
preconditions. Attacker-needed privileges = PR; victim action = UI:R.>

CWE-<id> (<name>).

## Control / differential

<Why this is a real defect and not expected behavior: the baseline that behaves
correctly (a gated sibling returning 401/403, an unaffected version, a control
request) versus the affected path.>

## Remediation

<The fix, specific. What the vendor should change. Any workaround for operators.>

## Disclosure timeline

- YYYY-MM-DD: reported to vendor (<channel>)
- YYYY-MM-DD: acknowledged
- YYYY-MM-DD: fixed / patched version <x>
- YYYY-MM-DD: public write-up / CVE assigned

## References

- NVD / advisory: <link>
- Vendor advisory / commit: <link>

## Disclaimer

For authorized security testing and education only. Tested in an isolated
environment against software obtained legitimately; no third-party or production
system was accessed. Use only against systems you own or are explicitly
authorized to test.
