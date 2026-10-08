# The Sims 2: Pack Installer

An unofficial, noncommercial macOS utility for installing and removing
macOS compatibility conversions for **The Sims 2: Super
Collection**.

> This project is not endorsed by or affiliated with EA or its licensors.

## Download

Download the application ZIP directly from [Download for macOS][direct-download],
or view the [latest GitHub Release][latest-release]. Do not download copies from
re-upload sites.

## Requirements

- macOS 13 Ventura or later
- The Sims 2: Super Collection for macOS
- The game installed directly in `/Applications`
- Free disk space for the application, staging data, and recoverable backups

This installer does not include The Sims 2: Super Collection itself and cannot
be used as a replacement for the game.

## Available conversions

- Mansion and Garden Stuff Pack
- H&M Fashion Stuff Pack
- Teen Style Stuff Pack
- Kitchen and Bath Stuff Pack
- IKEA Stuff Pack
- Celebration! Stuff Pack

Apartment Life Expansion Pack and FreeTime Expansion Pack are displayed as
coming later and cannot currently be installed.

## Installation

1. Download the application archive from the latest release.
2. Extract it and move **The Sims 2 Pack Installer.app** to `Applications`.
3. Open the application. Because the current build is not notarized, macOS may
   require you to approve the first launch in **System Settings → Privacy &
   Security**.
4. Select a pack. On first use, allow the installer to control Finder under
   **Privacy & Security → Automation**.
5. Approve Finder's protected file operation when macOS asks. The installer
   never receives or stores your administrator password.

Each pack is handled as one complete set. Protected changes are verified,
backed up, and rolled back if an operation fails. The original shared sound
files and backed-up fonts are restored only after the final installed pack is
removed. Protected changes are grouped by destination folder, so macOS can ask
for more than one administrator confirmation.

## Additional features

The installer includes an experimental HDR toggle, a persistent game-language
selector, and shared Central European text-input compatibility. Installing a
pack or enabling a shared runtime feature can update the game's executable.
The original executable is restored when all packs and HDR are off and Language
is set to System Default.

## Reporting a problem

Open a [bug report][bug-report] and include the diagnostic code shown by the
application. Never post passwords, account tokens, game package files, or other
copyrighted payloads. Review paths in diagnostic text before posting because a
path can contain your macOS account name.

## Updates

The application checks a signed Sparkle update feed hosted by this repository.
When a new version is found, it offers to download and install it without
visiting GitHub. Automatic checks are normally scheduled once every 24 hours;
use **Check for Updates…** to check immediately. The private update-signing key
is never stored in this repository.

Updating the installer does not silently update files in the game. Afterward,
update any packs marked **Needs update** using their toggles, with the game closed.

## Legal notice

This is an unofficial fan project. See [LEGAL.md](LEGAL.md) before downloading
or redistributing it.

[latest-release]: https://github.com/dtergent/the-sims-2-pack-installer/releases/latest
[direct-download]: https://github.com/dtergent/the-sims-2-pack-installer/releases/latest/download/The.Sims.2.Pack.Installer.zip
[bug-report]: https://github.com/dtergent/the-sims-2-pack-installer/issues/new?template=bug-report.yml
