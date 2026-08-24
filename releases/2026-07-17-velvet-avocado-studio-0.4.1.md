# Velvet Avocado Studio 0.4.1

Released 17 July 2026

Version 0.4.1 adds structured prompt references and a provider-facing prompt editor, persists workbench layout choices, and makes generation inputs and job history easier to manage.

## Prompt references and expansion

- Prompts can reference project assets with `#` and attached media with `@`. Asset and attachment mentions retain stable IDs instead of relying on visible labels or filenames.
- Attached images, videos, and audio compile to provider tokens such as `@Image1`, `@Video1`, and `@Audio1`. Tokens follow the current model input order while continuing to resolve the same attached file after compatible moves or reordering.
- Asset mentions can select a specific turnaround or canonical reference image. The selected image is visibly attached to the first compatible model input, while the expanded prompt receives the asset name, type, live media token, and stored description.
- First-frame and last-frame roles are available for video models. Assigning a role adds the corresponding provider instruction, and changing the assigned image updates its media token without discarding edited surrounding text.
- Added an Expanded Prompt modal shared by Generate Media and the lower prompt panel. Prompt injections can be edited independently in auto-growing fields, while the Final prompt view shows the complete provider-facing text read-only.
- Expanded-prompt edits now merge with later structured prompt changes. Added text and references continue to compile live, removed sources remove their unneeded sections, and untouched generated sections keep updating.
- Added Prompt Syntax help beside the conditional Expanded Prompt button.

## Generation input workflow

- Attachment menus can move compatible media between model inputs and assign image roles where the selected video model supports them.
- Changing models carries compatible image, video, and audio inputs forward by media kind and input shape, including first- and last-frame semantics between video models.
- Attachment context menus now anchor to their originating chip, measure their actual size, and hide the hover preview while open.
- The destructive attachment action is labelled Remove. A menu containing only Remove no longer shows an unnecessary separator.

## Workbench and Generate Media layout

- Navigation width and collapsed state, inspector width, lower prompt-panel visibility and normal height, and Generate Media split-pane dimensions now persist in application preferences.
- Restored layout values are applied after navigation and application restart. Completed drags persist their constrained final size without writing every intermediate pointer movement.
- Generate Media remembers both the generation-setup pane width and the results history height.

## Queue and model browsing

- Generation jobs can now be archived and restored without deleting their execution status, outputs, prompt evidence, costs, or provider identifiers.
- Added an Archived queue filter. All, Running, Completed, and Failed exclude archived jobs, while Archived shows every hidden job regardless of status.
- Existing writable project databases migrate additively to schema version 8 for the separate archive marker.
- Model search now filters favourite models consistently alongside ordinary provider results.

## Reliability and polish

- Prompt compilation and cost estimation now use the same merged expanded prompt that is submitted to the provider.
- Removed stale expanded-prompt section overrides when their source reference no longer exists.
- Improved generation attachment, queue, provider-filter, layout-persistence, and prompt-compilation regression coverage.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
