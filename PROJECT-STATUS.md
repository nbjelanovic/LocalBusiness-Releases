# Project Status

Local Business Platform is in active pre-release development. This page is a
plain-language public summary; it is not the private engineering plan or a
production-readiness certification.

## Current public preview

Version `0.3.0-preview.69` is available as an unsigned, self-contained Windows
x64 seven-day public trial.

The preview includes:

- Selectable business templates and optional modules
- Local users, roles, permissions, inactivity locking, and activity history
- Customers, leads, catalog, inventory, suppliers, and purchase orders
- Quotes, estimates, invoices, payments, expenses, point of sale, jobs, work
  orders, appointments, employee time, fleet, and dispatch workflows
- Business documents and dashboards, including PDF output and a protected
  custom-reporting foundation
- Customer CSV/XLSX import with mapping and review before committing records
- Verified backup, restore, local data export, and privacy-conscious support
  diagnostics
- Twelve interface languages

The exact preview.68-to-preview.69 lifecycle passed install, forced
interruption rollback, `PublicTrial` identity verification, application launch,
protected trial-state creation, uninstall, and business-data preservation. The
full Release build completed with zero warnings and errors; localization,
architecture, functional, and Windows trial checks passed.

## Trial boundary

- The trial lasts seven continuous days from first launch for each exact
  version.
- A newer version receives a new seven-day period.
- Reinstalling the same version does not reset that version's period.
- Trial history and business data survive upgrade and uninstall.
- After expiration, signed-in authorized users retain verified backup and
  open-data export access; normal application workflows are unavailable.

## Important current boundaries

- The installer is unsigned, so Windows can identify it as coming from an
  unknown publisher.
- The preview is not approved for production business records or regulated
  workflows.
- Independent clean-machine and real-business acceptance are still required.
- Interactive visual acceptance of the trial screens remains pending because
  the release workstation's UI-automation runtime was unavailable; installed
  process launch and protected trial-state creation passed.
- Cloud synchronization, centralized multi-computer operation, Active
  Directory authentication, and external service integrations are future
  capabilities rather than current production claims.
- Licensing and final commercial terms remain under review.

## What must happen before a production release

- Complete independent tester acceptance on supported Windows environments
- Finish usability and accessibility review with realistic populated data
- Complete code signing and publisher-identity setup
- Finalize licensing, support, update, privacy, and commercial policies
- Complete legal and regulated-industry review for any claimed specialized
  business use
- Complete final production acceptance

## Public release policy

A source-code change is not automatically a public release. A version appears
on this repository's Releases page only after the exact package is built,
validated, reviewed for public distribution, and accompanied by its checksum
and release notes.
