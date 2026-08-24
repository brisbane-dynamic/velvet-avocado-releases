# Velvet Avocado Studio 0.4.0

Released 17 July 2026

Version 0.4.0 brings together everything added since 0.1.0, with a major focus on faster prompting, a more capable Recording Booth, clearer generation costs, and smoother day-to-day media management.

## Prompting and generation

- The bottom prompt dock and Generate Media screen now share one live draft. Prompt text, model, settings, attachments, destination, and estimated cost stay in sync as you move around the project.
- Prompts can now reference project assets with `#`. Search Characters, Locations, Props, and Costumes without leaving the composer.
- Prompts can reference attached media with `@`. Images, videos, and audio are automatically numbered into clear provider-ready references such as `@Image1`, `@Video1`, and `@Audio1`.
- Assets with multiple visual references now offer a second picker so you can choose the exact turnaround or image to use in that mention.
- On video models, attached images can be marked as a general reference, first frame, or last frame. First- and last-frame instructions are added to the submitted prompt automatically. Reassigning either role updates its live media token even when the surrounding instruction has been edited.
- Asset references prepend name, type, live media token, and stored description definitions while retaining the asset name and token inline in the prompt.
- When compiled provider text differs from the raw prompt, both generation surfaces can open the same large editing modal. Its Expanded Prompt button stays hidden for equivalent text, but appears for asset expansion, first/last-frame instructions, and other real differences. The modal separates editable injected sections from a read-only view of the complete final prompt. Injected definitions and frame instructions retain edits independently while the main prompt body, added references, slot changes, and removals continue to compile live. Reset returns every section to generated text. A Prompt Syntax popover explains asset and attached-media references.
- Attachment menus can move media between compatible model inputs, change image roles, or remove an attachment.
- Changing models now carries compatible attachments into the new model's input slots where possible.
- Media can be sent straight to a compatible prompt input from its context menu. The `P` shortcut adds the selected media to the first compatible input.
- Generation inputs have been reordered and resized for a clearer setup flow, especially on narrower workspaces.
- Queue rows in the bottom dock can now open the full job details dialog. Dialogs are wider, media previews are larger, and generation status is easier to scan.

## Recording Booth

- Added a searchable voice browser for text-to-speech and voice conversion, including manual refresh and provider voice previews when available.
- Text-to-speech, voice conversion, and voice cleanup now show cost estimates before submission when the provider supplies pricing.
- Generated takes remain visible in their dialogue-line stack while they are queued or processing.
- Failed take retrievals can be retried directly from the take stack.
- Derived takes now show which original take they came from, making conversion, cleanup, and edit history easier to follow.
- Booth generation jobs retain their line, source, voice, and take context even if you navigate away before they complete.
- Interrupted recording sessions are cleaned up more safely when a project is reopened.

## Cost estimates and usage

- Added duration-aware estimates for models that charge according to the length of image, video, or audio inputs.
- Expanded WaveSpeed pricing support across the bundled model catalogue, including formula-based and time-based pricing.
- Improved OpenRouter image-model pricing discovery and estimate accuracy.
- Estimated cost is now captured when a generation is submitted, so the queue preserves what was shown at the time.
- Improved actual-cost reporting when a provider returns billing information after the generation has completed.

## Media and asset workflows

- Bulk imports now place originals first, then process metadata and thumbnails in the background. Large batches become visible sooner and are less likely to interrupt other work.
- Completing an import no longer replaces the media you already selected.
- Grid thumbnails and video posters now use quality-80 JPEG files, reducing project cache size. Older matching PNG derivatives are cleaned up automatically.
- Media selection now follows familiar desktop behaviour: Shift selects a range, while Command on macOS or Control on Windows and Linux toggles individual items.
- Multi-file drag-out to Finder and Explorer is more reliable, with safeguards against accidentally dropping files back into their original project folder.
- Smart ordering no longer changes simply because thumbnails or other derivatives were processed in the background.
- Media toolbars adapt earlier on narrow layouts, collapsing labels and wrapping filters before controls become cramped.
- Assigning media to an asset can now be undone.
- Creating a blank asset keeps you in its library, making it quicker to create several placeholders in a row.

## Workbench improvements

- Added standard desktop menu shortcuts for New, Open, and Close Project, Preferences, prompt visibility, full-screen prompting, and navigation.
- The bottom dock can collapse to a compact header while remaining easy to restore.
- The collapsed dock can be reopened normally or taken directly to full-screen height.
- The dock remembers its previous dragged height when hidden, restored, or temporarily expanded.
- Generation screens, queue rows, dialogs, and content surfaces received a visual polish pass for clearer hierarchy and more consistent spacing.
- The macOS title bar now follows the active app theme.

## Fixes

- Fixed bottom-of-window content being clipped after the macOS title-bar inset was applied.
- Fixed some portable or moved project media failing analysis or derivative generation.
- Fixed one rejected media preview from preventing other valid previews in the same view from loading.
- Fixed unreliable drag-out handoff and duplicate drag behaviour.
- Fixed chat-provider OAuth setup rejecting a valid provider identity.
- Improved installed macOS app startup reliability.
- Prevented development and installed copies of the app from incorrectly blocking one another.
- Fixed several generation layout, attachment-state, selection, and queue-detail edge cases.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
