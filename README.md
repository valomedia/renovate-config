# renovate-config

Shared Renovate presets for valo.media repositories.

## Usage

Add  to a repository:



This repository is public because public repositories using the hosted Renovate GitHub App cannot reliably extend presets from private repositories.

## Default policy

- Use Renovate recommended defaults.
- Show the Dependency Dashboard.
- Use semantic commit messages for Renovate branches.
- Run weekly lockfile maintenance before 06:00 Europe/Berlin on Mondays.
- Require dashboard approval for major updates and pre-1.0 packages.
- Automerge lockfile-only maintenance and stable patch updates only after required status checks pass.
- Group GitHub Actions updates and npm development dependency updates.
