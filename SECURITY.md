# Security policy

## Supported versions

Only the most recent published version is supported.

## Reporting a vulnerability

Please use GitHub's private vulnerability reporting for this repository rather
than opening a public issue. Include the application version, macOS version,
affected operation, and clear reproduction steps.

Do not attach administrator passwords, account tokens, private keys, complete
diagnostic archives, game package files, or personal data. Paths can contain a
macOS account name, so redact them when they are not required.

## Update integrity

Published application updates are intended to use Sparkle EdDSA signatures.
The corresponding private signing key must remain in the maintainer's macOS
Keychain or an encrypted offline backup and must never be committed here.

