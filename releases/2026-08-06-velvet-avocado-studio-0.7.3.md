# Velvet Avocado Studio 0.7.3

Released 6 August 2026

Version 0.7.3 makes project chat and Studio Functions more capable for structured creative work. It improves tool-aware conversations, expands the local MCP surface, and lets screenplay analysis progress through bounded, recoverable stages while retaining results across conversations.

## Tool-aware project conversations

- Improved native tool calling for qualified Atlas Cloud, OpenRouter, and Ollama model combinations.
- Kept provider tool calls connected to the exact project action, approval decision, result, and continued response.
- Preserved approval boundaries for paid generation, destructive operations, external changes, and imported tools.
- Added stronger limits around long or repetitive tool-running conversations so a project assistant remains useful without allowing unbounded execution.

This gives supported chat models a clearer way to work with Velvet Avocado Studio capabilities. A model can request an eligible action, pause for review when required, receive the bounded result, and continue the same answer with the outcome rather than losing context between disconnected steps.

## Stronger screenplay and creative functions

- Expanded Studio Functions for visual style development, still-image prompts, moving-image prompts, Workflow authoring, and screenplay breakdown.
- Broke screenplay analysis into recoverable passes for scenes, characters, locations, props, costumes, and the final work summary.
- Retained completed screenplay-analysis stages so interrupted work could continue without discarding all previous progress.
- Preserved screenplay breakdown drafts across chats and normalised related scene and entity information into a consistent reviewable result.

## Expanded MCP project access

The local Velvet Avocado Studio MCP server gained additional bounded tools and resources for project assets, media metadata, documents, generation jobs, and managed media transfer. Studio Function templates also became available through MCP prompts. Imported third-party tools remained separate rather than being silently re-exported.

For creators, version 0.7.3 strengthens Velvet Avocado Studio as an AI production assistant: chat can understand more of the active project, propose structured work, respect explicit approvals, and retain complex screenplay-planning results for later review.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
