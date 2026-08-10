# Local Business Platform — Public Releases

This repository is the official public information and download location for
**Local Business Platform**, a local-first Windows application for small
businesses.

> **Pre-release status:** The application is under active development and is
> not approved for production business use. Use fictional or safely copied test
> data and keep an independent backup.

## Start here

- **[Download the seven-day public trial](https://github.com/nbjelanovic/LocalBusiness-Releases/releases/tag/v0.3.0-preview.69-public-trial)**
- **[Public Trial Guide](PUBLIC-TRIAL-GUIDE.md)** — installation, checksum, trial, upgrade, expiration, and uninstall guidance
- **[Project Status](PROJECT-STATUS.md)** — current capabilities and remaining production gates
- **[Public Changelog](CHANGELOG.md)** — public-facing release history
- **[Testing Partners](TESTING-PARTNERS.md)** — safe feedback boundaries

## Current seven-day public trial

Version 0.3.0-preview.69 is an unsigned, self-contained Windows x64 installer.
No separate .NET installation is required.

- The seven continuous days begin when this exact version launches for the
  first time.
- The application provides full feature access during the active trial.
- Installing a newer application version starts a new seven-day trial for that
  newer version.
- Repairing, reinstalling, uninstalling and reinstalling, or returning to this
  same version does not reset this version's trial.
- Trial history and business data remain preserved through upgrade and
  uninstall.
- After expiration, normal application workflows are unavailable, but a
  signed-in authorized user can still create a verified backup or open-data
  export.
- Nothing is uploaded automatically.

Windows may show an unknown-publisher or protection warning because this
preview is not digitally signed.

### Verify the download

Installer SHA-256:

`2F366D8B9DFBF74AD4E8C8F40107A5F02B893F0D7BB8C2389B9B4097D5753123`

Download only from this repository's
[Releases](https://github.com/nbjelanovic/LocalBusiness-Releases/releases)
page and compare the installer to its published `.sha256.txt` sidecar.

## What the application is for

Local Business Platform brings common daily workflows into one modular desktop
application. A business can begin with only the modules it needs and enable
additional modules later without deleting existing records.

Current areas include:

- Customers and leads
- Products, services, inventory, suppliers, and purchase orders
- Quotes, estimates, invoices, payments, and expenses
- Point of sale and cash-session workflows
- Appointments, jobs, work orders, and employee time
- Fleet and dispatch workflows for local and cross-country operations
- Business reports, dashboards, PDF documents, and custom reporting
- Local users, permissions, activity history, backup, recovery, and open-data
  export

Business templates help configure a practical starting set of modules for
retail, online merchandise, food service, contractors, trucking, professional
services, and other small-business types.

## Product principles

- Core business records remain available locally without an internet
  connection.
- The business owns its data and can create open-data exports.
- Modules can be enabled as needed while retained data remains intact.
- Financial, inventory, and audit history use traceable corrections instead
  of silent destructive edits.
- Backup, recovery, permissions, diagnostics, and accessibility are treated as
  product features.
- Future multi-computer, directory authentication, central-database, and
  integration options are being designed without making them requirements for
  local use.

## Languages

The application includes English, Chinese, Czech, French, German, Hungarian,
Italian, Romanian, Russian, Serbian (Latin), Spanish, and Ukrainian interfaces.
Localization remains part of ongoing preview validation.

## Privacy and safety

Use fictional records or a separately copied and sanitized dataset. Do not
post customer information, employee records, credentials, payment data,
databases, backups, reports, or sensitive screenshots in public GitHub pages.
Review every export before sharing it.

For security reporting guidance, see [Security](SECURITY.md).

## Source code and ownership

This is an **information and binary-release repository only**. It does not
contain application source code, private development history, internal
architecture documents, private test data, signing material, or the build
system.

Local Business Platform is proprietary software. No open-source license is
granted by this repository. Copyright © 2026. All rights reserved.
