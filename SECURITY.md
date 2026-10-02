# Security

## Reporting a vulnerability

Please report security issues **privately**, not in a public issue. Use this repository's **Security → Report a vulnerability** option, or contact whoever sent your beta invite.

Include what you found, how to reproduce it, and the ONYX version (shown in **Settings → About**). You'll get a reply as soon as possible.

## How ONYX handles your data

- **Seller data is local.** Inventory, templates, deals, and notes are stored in a database on your PC. ONYX never uploads them.
- **No marketplace access.** ONYX doesn't ask for, store, or use marketplace credentials, and doesn't connect to any marketplace.
- **Licensing is the only network use.** Activation sends your license key and a random installation ID. Occasional check-ins send only your signed license. There's no telemetry or analytics.
- **Signed licenses.** ONYX accepts only licenses signed by the ONYX license server, verified on your PC. The license file is encrypted with Windows' built-in data protection for your Windows account, and the full license key is never stored.
- **Not encrypted:** the local database. Anyone with access to your Windows account can read it, so don't store passwords or account logins in notes.

## Supported versions

During the beta, only the latest version receives fixes.
