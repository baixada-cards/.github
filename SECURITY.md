# Security policy

## Supported code

Security fixes are made against the latest default branch and any release
explicitly identified as supported by its repository. Old snapshots,
experiments, and unmaintained releases may not receive fixes.

## Report a vulnerability privately

Use GitHub private vulnerability reporting in the affected repository:

1. Open the repository's **Security** tab.
2. Select **Advisories**.
3. Select **Report a vulnerability**.

Include the affected version or commit, the conditions needed to reproduce the
problem, its likely impact, and a minimal proof of concept when one is safe to
share. Remove credentials, personal data, production data, and unrelated
secrets.

Do not disclose a suspected vulnerability in a public issue, discussion, pull
request, or social post. Do not test against systems or accounts you do not own
or have permission to use.

Repositories that ship executable code are expected to enable GitHub private
vulnerability reporting. If the reporting button is unavailable, open a
content-free issue in the organization's `.github` repository stating only
which repository needs private reporting enabled. Wait for the private channel
before sharing details.

## What to expect

A maintainer will acknowledge the report when project capacity permits, assess
its scope, and keep material updates in the private advisory. There is no
guaranteed response or remediation time for this volunteer project.

When a fix is ready, maintainers will coordinate disclosure through the
advisory and credit the reporter unless they prefer to remain unnamed. Safe,
good-faith research that follows this policy will not be treated as hostile.
