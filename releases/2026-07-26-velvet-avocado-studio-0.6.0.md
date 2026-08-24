# Velvet Avocado Studio 0.6.0

Released 26 July 2026

Version 0.6.0 turns project chat into a more capable production assistant, adding local Codex and Claude Code runtimes, project document ingestion, approval-gated tools and MCP connections, and the first Workflow library and guided run experience.

## Local agent chat

- Added Codex CLI and Claude Code as local chat runtimes. Velvet Avocado uses supported installations already available on your computer without asking you to copy their credentials into the app.
- Available models are discovered from the installed runtime, with reasoning effort controls shown when the selected runtime supports them.
- Each conversation remembers its latest provider, model, and reasoning effort so returning to a project restores the intended chat setup.
- Tool-enabled responses now show a live action checklist and keep ordinary answers streaming naturally.
- Improved cancellation, interrupted-response recovery, long-conversation handling, and protection against duplicate actions.

## Project documents

- Added a dedicated Documents section with file picker and drag-and-drop import.
- Supported formats include PDF, DOCX, ODT, RTF, HTML, XML, Fountain, Markdown, CSV, TSV, JSON, YAML, and plain text.
- Imported originals remain visible project media while extracted text is kept with the project for chat, Workflow, and search use.
- The inspector now shows extraction status, document format, page count, word count, and character count where available.
- Documents can be attached directly to a conversation. Later turns can return to precise excerpts without repeatedly loading the entire document.

## Tools and MCP

- Codex and Claude Code chats can now plan and run Velvet Avocado project actions through an application-controlled tool system.
- Action plans are shown before and during execution, with durable approval cards for paid generation, destructive operations, external changes, and imported tools.
- Added per-conversation approval modes. Safe native project actions can be approved automatically, while sensitive actions always stop for an explicit decision.
- Added MCP settings for registering local stdio or Streamable HTTP servers, enabling them per project, reviewing discovery errors, and managing tool approvals.
- Added an opt-in local Velvet Avocado MCP server so approved external tools can search the active project, create placeholder assets, inspect generations, estimate costs, and submit generation jobs.

## Workflows

- Added a Workflows destination with a searchable, filterable library of bundled, user, and project workflows.
- Workflow details now show their purpose, tool steps, parameters, local availability, and run history.
- Added schema-driven Workflow run forms for selecting project inputs and configuring parameters.
- Workflow runs use a two-step flow: create a no-side-effect preview, review the prospective actions and approval boundary, then explicitly confirm the exact preview.
- Included starter workflows for creating placeholder assets and rendering project-aware prompts.

## Updates and reliability

- Packaged builds now check once at launch for a newer supported release. When one is available, Velvet Avocado can open the exact installer download for the current platform in your browser.
- Offline use, current versions, unsupported packages, and invalid update information remain silent.
- Improved project chat streaming, tool approval recovery, document safety, Workflow run recovery, and release notice consistency across supported platforms.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
