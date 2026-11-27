# Security Policy

## Reporting
Do not disclose suspected vulnerabilities in public issues or pull requests. Use GitHub's private vulnerability reporting feature when available. Do not include live credentials in reports.

## Credential handling
Never commit API keys, access tokens, passwords, private keys, service-account files, or production environment files. If a credential is exposed, revoke or rotate it immediately; deleting it from the latest commit is not sufficient because Git history may retain it.

## Scope
Security fixes are applied to the default branch. Review workflow permissions, third-party actions, dependencies, and generated artifacts before release.
