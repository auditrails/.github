<div align="center">
  <img src="https://raw.githubusercontent.com/auditrails/.github/main/profile/logo-icon-square.png" alt="AuditRails" width="96" height="96">

  # AuditRails

  Tamper-proof audit logging for compliance-ready applications.

  [Website](https://auditrails.io) · [Docs](https://docs.auditrails.io) · [Pricing](https://auditrails.io/en/pricing)
</div>

## What this is

AuditRails is a drop-in SDK and API for immutable, cryptographically verifiable audit logs. Every event is hash-chained (SHA-256 over the previous hash, the canonical payload, and a millisecond-precision timestamp), so any tampering, deletion, or reordering breaks the chain and is detectable immediately. Logs are written to S3 with Object Lock in compliance mode, once written, nobody can modify or delete them, not even an AuditRails administrator.

Built for teams that need to prove their audit trail is real, not just present. 18 compliance frameworks are supported out of the box, including EU AI Act, GDPR, DORA, NIS2, HIPAA, SOC 2, ISO 27001, and PCI DSS.

## SDKs

Official client libraries for sending events to AuditRails, built and tested. The Go SDK installs directly off its tagged repo; the other 4 are on their public repos now with registry publishing (npm, PyPI, Packagist, Maven Central) coming soon.

| Language | Package | Repo |
|----------|---------|------|
| Node.js | `@auditrails/node` | [auditrails/auditrails-node](https://github.com/auditrails/auditrails-node) |
| Python | `auditrails` | [auditrails/auditrails-python](https://github.com/auditrails/auditrails-python) |
| PHP | `auditrails/auditrails-php` | [auditrails/auditrails-php](https://github.com/auditrails/auditrails-php) |
| Go | `github.com/auditrails/auditrails-go` | [auditrails/auditrails-go](https://github.com/auditrails/auditrails-go) |
| Java | `io.auditrails:auditrails-java` | [auditrails/auditrails-java](https://github.com/auditrails/auditrails-java) |

## Links

- [Documentation](https://docs.auditrails.io)
- [API Reference](https://docs.auditrails.io/api-reference/overview)
- [Pricing](https://auditrails.io/en/pricing)
