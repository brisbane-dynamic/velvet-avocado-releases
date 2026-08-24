# Velvet Avocado Studio 0.7.6

Released 16 August 2026

Version 0.7.6 is a focused generation and release-reliability update. It keeps generation submission responsive while cost estimates are refreshing and strengthens recovery around verified desktop downloads.

## Responsive generation submission

- Kept the generation submit action available while a background cost estimate was still in progress.
- Prevented an estimate refresh from unnecessarily blocking a creator who was otherwise ready to submit the configured request.
- Retained the existing submission safeguards and current prompt capture at the point the generation is created.
- Covered the different generation entry points so the Generate Media workspace and shared prompt surfaces follow the same rule.

Cost estimates remain useful planning information, especially for video models, multiple results, and providers with configuration-dependent pricing. They should not make the creative interface feel frozen, however. Version 0.7.6 separates the temporary state of an estimate request from the creator's ability to proceed, while preserving the generation record, selected model, attachments, destination, and available cost evidence.

## More resilient release delivery

This maintenance release also improved how completed desktop builds recover and move through final publication. Verified release channels could be restored without replacing valid immutable files, transient download-storage failures were retried more safely, and the final macOS release record retained its notarisation and corresponding-source evidence.

These changes are mostly invisible inside the application, but they support an important part of the Velvet Avocado Studio experience: a download advertised as the current release should resolve to the intended, verified package and its associated release information. Recovery work should not silently move a channel to different bytes or discard the evidence belonging to a completed build.

Version 0.7.6 therefore combines a small but practical generation-interface fix with stronger release continuity. Creators can submit work without waiting unnecessarily for estimate refreshes, while the surrounding distribution process is better prepared to recover from temporary publication failures.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
