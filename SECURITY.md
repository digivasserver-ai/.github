# Security policy

## Reporting a vulnerability

Email **divivas.server@gmail.com** with `SECURITY` in the subject line.

Please do **not** open a public issue, and do not include exploit details in a pull request description.

Useful in a report:

- the repository and version or commit,
- what an attacker gains,
- the smallest reproduction you have,
- whether the issue is already public anywhere.

## What to expect

- **Acknowledgement within 7 days.**
- An assessment and a rough timeline after that.
- Credit in the release notes if you want it. Say so in the report; anonymous reports are fine too.

## Scope

In scope: anything in a repository under this account that processes untrusted input — parsers, scanners, probes, CI workflows, and anything that handles credentials.

Out of scope: findings that require a compromised device or an already-rooted host, missing hardening headers with no demonstrated impact, and reports produced solely by an automated scanner without a reproduction.

## Supported versions

Repositories with tagged releases support the latest tag. Older tags get fixes only when the issue is severe and the fix is small.
