# Security Policy

## Reporting a Vulnerability

Please do not report security vulnerabilities through public GitHub issues.

Instead, please report them responsibly by emailing security@abel.ai. We will acknowledge receipt of your vulnerability report within 48 hours and strive to send you regular updates about our progress. If you evaluate your report as a critical vulnerability, please mention this in the subject line.

## Where to Report Issues

Depending on what part of the CAP ecosystem your report concerns, please ensure the context is clear:

1. **Protocol/Spec Issues**: Vulnerabilities or logic flaws within the CAP specification itself that could lead to insecure implementations.
2. **SDK/Runtime Issues**: Vulnerabilities in the official `python-sdk` (e.g., insecure deserialization, improper error handling leaking data).
3. **Official Example Server Issues**: Vulnerabilities in the CAP organization's public `cap-example` repository or its published example server behavior.

## Supported Versions

We only provide security updates for the current major release of the CAP Python SDK and the active specification draft. Older implementations may not receive forward-ported security patches.
