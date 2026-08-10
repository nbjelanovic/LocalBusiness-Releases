# Public Changelog

This file records public-facing Local Business Platform milestones. Detailed
private engineering history and source-code changes remain in the private
development repository.

## Unreleased

No public-facing changes are currently queued.

## 0.3.0-preview.69 - 2026-08-10

### Added

- Published the first downloadable Windows x64 public preview.
- Added a Windows-user-protected, version-scoped seven-day trial.
- Added localized first-launch disclosure and remaining-time status across all
  12 interface languages.
- Added Leads follow-up attention on the Dashboard with overdue and
  next-seven-day counts and direct filtered navigation.

### Trial behavior

- The seven continuous days begin on first launch of the exact version.
- Installing a newer version starts a new seven-day trial.
- Reinstalling, repairing, or returning to the same version does not reset that
  version's trial.
- Clock rollback or damaged protected trial state fails closed.
- Trial expiration does not delete business data. Signed-in authorized users
  can still create a verified backup or open-data export.

### Validation

- Release build completed with zero warnings and zero errors.
- Localization coverage passed for 12 languages and architecture checks passed
  for 23 projects.
- Full functional and Windows suites passed, including exact expiry,
  same-version persistence, upgrade reset, clock rollback, and tamper handling.
- The preview.68-to-preview.69 installer lifecycle passed interrupted rollback,
  `PublicTrial` identity, installed launch, protected trial-state creation,
  uninstall, and data preservation.
- Installer SHA-256:
  `2F366D8B9DFBF74AD4E8C8F40107A5F02B893F0D7BB8C2389B9B4097D5753123`.

### Known limitations

- Unsigned pre-release software; Windows can show an unknown-publisher warning.
- Not approved for production or regulated workflows.
- Independent clean-machine, real-business, signing, licensing, legal, and
  final production acceptance remain open.
- Interactive visual acceptance of the trial screens remains pending because
  UI automation was unavailable on the release workstation; installed launch
  and protected state creation passed.

## Repository opened - 2026-08-10

- Opened the official public information and release repository without source
  code or private development history.
