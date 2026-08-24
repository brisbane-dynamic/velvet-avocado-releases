# Velvet Avocado Studio 0.7.4

Released 12 August 2026

Version 0.7.4 is a broad production-workflow update spanning batch generation, project chat, asset libraries, media organisation, Gallery review, folder management, production metadata, and responsive workbench behaviour.

## Batch generation and prompt actions

- Added batch size controls for requesting multiple image or video results from one configured prompt.
- Submitted each result as its own durable generation job so progress, retries, outputs, and costs remain individually traceable.
- Displayed the aggregate estimated cost for the full batch before submission.
- Added configurable confirmation for generations above a chosen estimated cost and an additional warning for multiple video generations.
- Added Copy and Replace Prompt actions to assistant responses, with confirmation before replacing a non-empty generation prompt.

## Better asset and media organisation

- Improved asset cards, selection, keyboard actions, context menus, cover images, descriptions, tags, and Scene numbers.
- Added portable Scene, Sequence, Take, and Shot production fields to media records.
- Added media-type grouping and filters across project browsers, generation pickers, and editor media selection.
- Added trusted creation and renaming of organisational folders, including whole-folder assignment to existing assets or Sound destinations.
- Improved ordering, filtering, responsive toolbar layout, audio preview controls, and folder navigation.

## Gallery and review improvements

- Added consistent media actions across grids, lists, Gallery views, keyboard shortcuts, and the Properties pane.
- Added Grid, List, and Viewer modes to shared media controls.
- Brought preview navigation, assignment, favourites, tags, roles, rename, export, reveal, and Trash actions into the Gallery workflow.
- Improved context-menu placement near window edges and the prompt dock.
- Kept user-facing property values, generated prompts, and chat replies selectable while preventing accidental text selection across application chrome.

## Project recovery and desktop polish

Project opening became more tolerant of recoverable record problems, surfacing non-blocking warnings instead of preventing every part of the project from loading. Media metadata edits became more resilient across selection changes, malformed saved conversations were isolated, and managed-Trash recovery handled more interrupted move states. The packaged editor was also made smaller by removing disabled runtime paths while retaining supported editing and enhancement capabilities.

Version 0.7.4 makes the local-first workspace faster to navigate and more consistent when a production contains many assets, takes, folders, generated alternatives, and saved conversations.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
