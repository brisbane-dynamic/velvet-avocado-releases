# Velvet Avocado Studio 0.2.0

Released 12 July 2026

Version 0.2.0 expanded the Recording Booth into a more dependable voice-production workspace. It improved voice selection, text-to-speech setup, provider cost visibility, generated-take tracking, and the connection between long-running generation jobs and the dialogue line they belong to.

## Searchable voice selection

- Added a shared searchable voice browser for supported text-to-speech and voice-conversion providers.
- Displayed provider voice previews when the connected voice directory supplied them.
- Refreshed available voices through the same Recording Booth workflow so newly created or changed voices could become available without rebuilding the project.
- Kept voice choice attached to the configured provider operation instead of presenting every voice as a separate generation model.

This made accounts with many available voices easier to navigate and gave creators a more direct way to audition a voice before using it for a line or transformation.

## Better text-to-speech and take tracking

- Added provider cost estimates to the text-to-speech setup where pricing information was available.
- Preserved dialogue-line, provider, job, and voice context with a submitted generation.
- Kept queued, processing, and failed generated takes visible in their line's take stack.
- Reconnected completed work to the correct line even when the creator navigated away from the Recording Booth before the provider finished.
- Rehydrated unfinished and failed booth jobs when returning to the project.

The update made generated speech behave more like production takes and less like disconnected provider output. A line could retain its recorded, generated, converted, cleaned, and edited alternatives together, including the source relationship needed to understand how a take was created.

## Voice transformation workflow

Version 0.2.0 also refined the controls used for voice conversion, cleanup, and text-to-speech. Supported ElevenLabs and local Voicebox capabilities remained available through the shared generation system, while the Recording Booth presented controls in the context of the selected line, take, source audio, and target voice.

For creators producing dialogue, narration, character voices, or alternate performances, the result was a clearer workflow from script line to voice selection, generation, review, and keeper choice—all inside the same local-first Velvet Avocado Studio project.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
