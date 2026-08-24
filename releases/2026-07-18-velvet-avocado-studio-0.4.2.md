# Velvet Avocado Studio 0.4.2

Released 18 July 2026

Version 0.4.2 makes provider catalogues and cost estimates more resilient, adds live hosted Higgsfield model discovery and credit preflights, and improves generation controls and popover behaviour across the workbench.

## Provider catalogue reliability

- Startup refreshes now target only enabled providers whose catalogue is missing, failed, or more than six hours old. Fresh cached catalogues remain immediately available without an unnecessary provider request.
- Provider catalogue refreshes run concurrently and fail independently. One offline provider no longer prevents other catalogues from loading, and cached or bundled models remain available as a fallback.
- Plugin Settings shows connection errors on the provider that produced them and clears the error after a successful refresh.
- Enabling a provider or saving its settings updates the interface immediately and scopes any required background refresh to that provider.
- Concurrent refresh requests for the same project and provider are coalesced, reducing duplicate discovery work.
- Incomplete dynamic catalogue parameters are normalized before they reach the renderer, preventing malformed or legacy provider data from crashing model selection.

## Higgsfield hosted MCP integration

- Higgsfield now discovers current image, video, and audio models from the hosted MCP catalogue instead of relying on a fixed list. Paginated media catalogues are fetched in parallel and normalized into Velvet Avocado processes, inputs, parameters, and credit metadata.
- Added a read-only Higgsfield `get_cost` preflight. The generation interface can show the configured job's credit cost without submitting a generation or inventing a dollar conversion.
- Improved OAuth sign-in completion and error presentation with a dedicated local callback page.
- The hosted MCP provider is now the active Higgsfield integration. The unverified CLI evaluation remains hidden, and the superseded REST plugin has been removed from packaged resources.

## Generation and workbench improvements

- ComfyUI workflows now turn live sampler and scheduler choices from `/object_info` into dropdowns. Custom nodes without usable choice metadata retain the workflow value as a locked field.
- Prompt Template, Prompt Syntax, dock, and media popovers now share viewport-aware placement that avoids clipping near window edges and responds to layout changes.
- Scrollbars across workbench surfaces now use consistent theme-aware styling.
- Windows image imports now use native raster decoding with a bounded Shell-provider fallback for JPEG thumbnails.
- Added recoverable error surfaces for Plugin Settings and the application shell so an unexpected renderer failure can be dismissed or retried instead of leaving an empty window.

## Error handling and packaging

- Provider cost-estimate failures now return `Cost unavailable` without blocking submission, terminating the plugin worker, or affecting later estimates.
- Electron IPC now preserves structured Node application errors through the preload bridge, giving feature clients consistent command failure details.
- Package staging and integrity checks now exclude superseded provider resources and verify the current provider set.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
