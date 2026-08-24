# Velvet Avocado Studio 0.3.0

Released 17 July 2026

Version 0.3.0 rebuilt the desktop foundation behind Velvet Avocado Studio while preserving the project-first creative workflow. The release concentrated on application reliability, secure local project access, packaged desktop behaviour, restart recovery, and consistent ownership of project files, media, generation jobs, provider connections, and conversations.

## Stronger desktop project handling

- Improved project creation, opening, recent-project activation, settings, search, close behaviour, and operating-system file activation.
- Added clearer recovery boundaries for interrupted project operations and recording sessions.
- Kept project media access scoped to the active project instead of exposing unrestricted native file paths to the interface.
- Improved native file dragging, media previews, project-relative media locations, and compatibility with portable project records.
- Strengthened local indexing so assets, media, prompts, generation history, and conversations could be rebuilt from the project's durable records.

These changes made ordinary production work more resilient when the application restarted, a project moved, an indexing operation was interrupted, or media needed to be reopened through the packaged desktop app.

## Connected project services

The release brought the main project workflows behind one trusted desktop service boundary. Asset metadata, media assignments, Trash and restore operations, recording metadata, prompt templates, imports, conversation records, provider settings, generation submission, polling, retrieval, and completed-output placement all continued to support the same visible Velvet Avocado Studio workspaces while gaining more consistent lifecycle and recovery behaviour.

For creators, that meant the application could keep a generation job running independently of the currently visible screen, restore its state later, place completed media into the intended project destination, and retain the prompt and provider evidence needed for production history.

## Desktop packaging and reliability

- Added a packaged macOS release for version 0.3.0.
- Improved application startup, native menus, window lifecycle, media authorisation, developer tools in development builds, and packaged smoke behaviour.
- Added stricter package checks for the desktop runtime, legal files, native media service, provider resources, and supported application workflows.
- Preserved the existing local-first project format while strengthening the desktop application's handling of SQLite data, portable records, media processing, and plugin execution.

Version 0.3.0 was therefore a foundation release rather than a visual redesign. Its purpose was to make the growing set of AI video production features—project assets, media management, generation, prompts, chat, and voice work—operate through a more dependable desktop application without separating creators from their existing projects.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
