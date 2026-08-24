# Velvet Avocado Studio 0.7.5

Released 15 August 2026

Version 0.7.5 improves generation-provider consistency, Atlas Cloud cost reporting, generation review, and asset-management workflows. It also strengthens the desktop release path for macOS while keeping that engineering complexity outside the creative workspace.

## More consistent provider integrations

Velvet Avocado Studio's bundled media providers moved onto a clearer shared integration contract. Provider-specific adapters still translate each service's models, inputs, parameters, uploads, status responses, costs, and outputs, while the application receives a consistent description of the creative capabilities available to the selected model.

For creators, this makes the generation workspace more predictable when moving between providers. Model controls, attachments, cost estimates, queued work, completed outputs, and error handling can follow the same project workflow even when the underlying services use different APIs and response formats.

## Improved Atlas Cloud costs

- Expanded Atlas Cloud estimate handling for model-specific prices and configurable request parameters.
- Improved final billing resolution for completed Atlas Cloud jobs.
- Preserved estimated and final cost information with the generation record so project history can distinguish what was expected from what the provider ultimately reported.
- Improved generation job details so prompts, settings, outputs, and cost information are easier to inspect together.

## Generation confirmation and asset workflows

- Moved generation confirmation into a stable workspace-level surface so it remains usable regardless of the prompt dock's layout.
- Refined asset-management workflows and their supporting interface.
- Improved generation review without disconnecting the submitted prompt, selected model, destination, or project media from the resulting job.

## More reliable macOS delivery

The release process gained a more resilient path for signing, notarising, finalising, and publishing macOS downloads. This does not change how a creator works inside a project, but it supports clearer operating-system trust checks and more dependable delivery of finished desktop installers.

Version 0.7.5 continues the product's core direction: one local-first AI video production workspace where provider choice, project assets, prompt history, generation costs, and completed media remain connected.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
