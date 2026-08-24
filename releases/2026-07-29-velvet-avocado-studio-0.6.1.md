# Velvet Avocado Studio 0.6.1

Released 29 July 2026

Version 0.6.1 improves the connection between project files, generation history, asset management, and the workbench. Media added or reorganised outside Velvet Avocado Studio becomes available more reliably, while new inspector and side-panel tools make production assets easier to review and reuse.

## Live project media updates

- Added filesystem monitoring for media-bearing project folders so compatible files added outside the app can appear without waiting for a broad project rescan.
- Preserved media identity, metadata, and generated derivatives across external moves and renames when the original item could be recognised.
- Scoped background reconciliation to the affected folder instead of repeatedly reprocessing the entire project.
- Improved stable filenames for generated media and more useful cover images for nested folders and asset search results.

These changes support a genuinely local-first workflow. Creators can continue using Finder, Explorer, render tools, audio applications, or other production software around the same project while Velvet Avocado Studio keeps its searchable media records connected to the underlying files.

## Richer media inspection and generation history

- Split media properties into clearer Organisation and Technical views.
- Added a Generation view for AI-generated media, including the original prompt, provider, model, inputs, settings, cost information, destination, status, and lineage.
- Made it possible to reuse the historical prompt from a generated item while retaining the model and attachment context that still exists.
- Resolved historical attachments through stable media identities after project files were moved.

## Faster asset and workspace navigation

- Added a persistent, resizable side panel that remains available across standalone workspaces.
- Improved asset creation, editing, selection, covers, tags, descriptions, and related media workflows.
- Added a native full-screen media viewer for focused image, video, and audio review.
- Refined navigation labels, headings, prompt access, and responsive workbench behaviour.

Together, these improvements make Velvet Avocado Studio more useful as a production asset manager: project media can change on disk, retain its identity in the catalogue, and remain connected to the prompt and generation record that produced it.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
