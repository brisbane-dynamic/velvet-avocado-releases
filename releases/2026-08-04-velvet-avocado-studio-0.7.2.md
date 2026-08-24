# Velvet Avocado Studio 0.7.2

Released 4 August 2026

Version 0.7.2 is a focused workflow and recovery update for project navigation, the Recording Booth, local voice tools, and the integrated editor. It reduces repeated model checks, restores access to projects affected by completed recording migrations, and makes the main project navigation easier to organise.

## More dependable Recording Booth projects

- Fixed completed recording migrations being re-evaluated against later, legitimate Recording Booth changes.
- Allowed a project with a completed but not yet published migration result to recover its current project index on the next open.
- Preserved strict recovery checks while a migration was genuinely incomplete.
- Prevented new dialogue takes or media changes made after a successful migration from making an otherwise healthy project appear unrecoverable.

This matters for active voice production because a completed migration should become part of project history, not a permanent comparison against a frozen earlier state. Creators can continue recording, editing, cleaning, and organising takes after the migration without those normal changes blocking the project.

## Faster local voice readiness

- Treated a successfully installed and verified Chatterbox runtime as ready during routine status checks.
- Stopped ordinary navigation back to the Models screen from repeatedly rechecking the entire local runtime and launching another health probe.
- Retained full verification for explicit installation and recovery operations.

The result is quicker Settings navigation and fewer false reports that a previously working local voice installation needs to be removed or downloaded again.

## Clearer navigation and editor controls

- Made labelled project-navigation sections independently collapsible when the navigation rail is expanded.
- Kept every destination accessible in compact mode, with clearer dividers and immediate icon labels.
- Allowed the navigation resize handle to move naturally between compact and expanded layouts.
- Hid integrated-editor AI, transcript, scene-detection, local-model, and frame-interpolation controls that were not supported by the Velvet Avocado Studio release.

Version 0.7.2 keeps the visible interface aligned with working production capabilities while improving recovery for established projects.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
