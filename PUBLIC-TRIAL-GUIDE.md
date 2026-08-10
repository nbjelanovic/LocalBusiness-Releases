# Seven-Day Public Trial Guide

## Download

Use the official
[0.3.0-preview.69 release](https://github.com/nbjelanovic/LocalBusiness-Releases/releases/tag/v0.3.0-preview.69-public-trial).

The release contains:

- `LocalBusiness-0.3.0-preview.69-win-x64-Setup.exe`
- `LocalBusiness-0.3.0-preview.69-win-x64-Setup.exe.sha256.txt`

No separate .NET installation is required.

## Verify the installer

Expected SHA-256:

`2F366D8B9DFBF74AD4E8C8F40107A5F02B893F0D7BB8C2389B9B4097D5753123`

In PowerShell, run:

```powershell
(Get-FileHash .\LocalBusiness-0.3.0-preview.69-win-x64-Setup.exe -Algorithm SHA256).Hash
```

The result must exactly match the expected value. Do not run a package whose
hash differs.

## Install

1. Close any existing Local Business window.
2. Run the downloaded `Setup.exe`.
3. Windows may display an unknown-publisher or protection warning because this
   preview is not digitally signed.
4. Complete first-run password and module/template setup.
5. Use fictional or safely copied test data and keep an independent backup.

The installer works for the current Windows user and creates normal Desktop
and Start Menu shortcuts plus an uninstall entry.

## Trial rules

- The trial lasts seven continuous days from the first successful launch of
  this exact version.
- Full application features are available during the active trial.
- Installing a newer version starts a new seven-day period for the newer
  version.
- Reinstalling or repairing this same version does not reset its trial.
- Uninstalling and reinstalling this same version does not reset its trial.
- Returning to an older version restores that older version's existing trial
  status rather than creating a new period.
- Moving the computer clock backward does not extend the trial.

## After expiration

Normal application workflows become unavailable. Business records are not
deleted. After signing in, an authorized user can still:

- Create a verified `.lbbackup` package
- Create a versioned open-data ZIP export

Keep those files in a safe location before changing computers or removing
local data manually.

## Upgrade and uninstall

A newer version preserves business data and receives its own seven-day trial.
Uninstall removes the installed application and shortcuts but preserves
business data and protected trial history under:

`%LOCALAPPDATA%\LocalBusinessPlatform`

Deleting that folder manually is outside normal uninstall behavior and can
destroy the only local copy of business records. Create and verify a backup
first.

## Feedback safety

Do not post customer, employee, supplier, payment, credential, database,
backup, private report, or sensitive screenshot content in public GitHub
pages. Describe the workflow and visible error without exposing business data.
