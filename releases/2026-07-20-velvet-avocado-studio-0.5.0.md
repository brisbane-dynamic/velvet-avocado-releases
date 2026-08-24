# Velvet Avocado Studio 0.5.0

Released 20 July 2026

Version 0.5.0 improves first-run provider setup, generation review and prompt workflows, project search, provider media handling, and desktop release polish. The installed application is now published as **Velvet Avocado**, with the version shown separately in the native About experience.

## Provider setup and integrations

- Added provider-first onboarding that lets new projects choose media and chat capabilities without forcing a provider connection before local work begins.
- Added offline setup guidance and clearer capability-aware provider cards for hosted and local connections.
- Higgsfield generation can now upload and reuse supported reference media through a project-owned provider media cache.
- ComfyUI generation now supports compatible audio and video media inputs in addition to images.
- Provider credentials now use an application-owned vault key, with explicit macOS access approval and recovery behavior.
- Provider catalogues and queued responses are normalized more defensively so malformed or delayed provider data cannot destabilize later requests.

## Generation and prompt workflow

- Added prompt-reference previews and hover details while keeping stored prompt provenance intact when generation jobs are reloaded.
- Added configurable prompt text sizing and confirmation before submitting a duplicate generation request.
- Improved generation queue selection, row double-click behavior, and video output previews.
- Workbench prompt and panel transitions now avoid animating during restored layout changes.

## Search, media, and projects

- Rebuilt project search as a media-first browser with field-aware matching, asset type context, and cover previews.
- Added a focused media viewer and improved media-grid navigation and review.
- Project Settings now save more reliably, and switching between recent projects preserves the intended workspace route and state.
- The project switcher and prompt reference surfaces provide clearer nearby context without exposing absolute project media paths.

## Desktop release polish

- The installed and published application name is now **Velvet Avocado** rather than a version-suffixed product name. Release artifacts continue to carry the version in their filenames for traceability.
- Windows now includes **Help → About Velvet Avocado**, showing the running application version in a native dialog, matching the version visibility already available on macOS.
- Native dropdown option text remains legible in dark mode while light-mode behavior stays unchanged.
- Packaging, compliance, and platform checks cover the updated product identity and current bundled resources.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
