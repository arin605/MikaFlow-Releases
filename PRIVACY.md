# MikaFlow Privacy and Data Notes

MikaFlow is a local-first desktop application. The core Studio, Prompts, Archive, and Utility sections do not require a MikaFlow account, analytics service, or remote API.

## Local data

- Studio and Archive content is stored in the content location selected during setup.
- Prompts, Notes, indexes, caches, and non-secret application settings are stored in the current Windows user's MikaFlow folders.
- Uninstalling or deleting the application does not automatically delete these user-data folders.
- Local content is not encrypted by MikaFlow. Windows account and disk security remain responsible for protecting it.

## Credentials

Optional service credentials are stored in Windows Credential Manager. MikaFlow release packages do not contain the developer's tokens, passwords, service-account files, or private content.

## Optional network features

- Mobile Flow starts a local HTTP server only when the user starts it. It is intended for a trusted private network and requires initial device pairing.
- Notes can request link metadata or load embedded media when those blocks are used.
- Pixiv Stats, Assistant, and Shop connect only to services configured by the user after those sections are enabled.

MikaFlow does not add product analytics or telemetry to the core application.

## Before sharing diagnostics

Review screenshots, logs, settings, and exported files before sharing them. They can contain local paths, prompts, image metadata, account identifiers, or service error details.

