# Velvet Avocado Studio 0.8.0

Released 31 August 2026

Velvet Avocado Studio 0.8.0 brings scene assembly, voice work, and AI model selection closer together in one local-first production workflow. Build a rough cut from the media already in a Project, return to it without losing your place, refine spoken material alongside the rest of the production, and spend less time navigating incomplete or stale model choices.

## Assemble scenes in the Editor

The built-in Editor now supports a more structured way to assemble a production. Use a scene-focused timeline when you want to work from the media already associated with one Scene, while still being able to bring in any other project media you need. For a broader cut, use a project-level timeline that can combine multiple scene assemblies with additional media. Both workflows live in the Editor rather than asking you to edit directly from a Scene's media area, and both keep their active timeline available as you move around the workbench.

The Editor also better connects assembly to generation. Images and video clips can be sent directly from the edit into a prompt as creative reference material, while captured frames, selected audio ranges, and rendered timeline ranges provide further ways to use an edit as source material for the next image, video, or audio generation. OpenTimelineIO and Final Cut Pro export now resolve compound clips and related timeline structure more completely, making it easier to carry a structured Velvet Avocado edit into professional post-production. Timeline behaviour, source and program monitoring, playback, audio mixing, skimming, media grouping, canvas settings, and retained visual effects have all received practical refinements for more dependable day-to-day editing.

Playback is smoother too. The Editor can generate lower-resolution all-intra proxy media, where every frame is independently encoded for quicker seeking. This gives demanding source clips a more responsive preview in the desktop editor, particularly when scrubbing frame by frame, working in slow motion, or navigating a busy timeline. Proxy handling, playback recovery, and effects processing have also been strengthened to make editing feel steadier and more dependable.

## More capable voice and model workflows

Recording Booth has improved controls for text-to-speech and voice work across supported providers. Provider-specific controls now stay aligned with the selected voice model, ElevenLabs voice previews and settings are more reliable, and Atlas speech previews are better supported. The panel also offers more complete voice filtering, helping you find an appropriate voice without losing the production context around a take.

Chatterbox is now available as a local text-to-speech and voice-cloning option, so you can create spoken material on your own supported computer instead of relying solely on an external voice provider. The Models experience distinguishes the multilingual and English Turbo options while keeping them part of the same local voice workflow. Longer Chatterbox synthesis is more reliable, and downloaded model data remains an explicit, user-controlled install rather than being bundled into the application download.

## Better provider discovery and dependable media handling

fal.ai is now available as a generation provider, bringing its image, video, audio, and media-processing model catalogue into the same project-centred workflow as Velvet Avocado's other providers. Provider catalogues now load and refresh more efficiently, with improved model detail, pricing coverage, and handling for large catalogues. This makes it easier to explore suitable generation options without turning catalogue refresh into a bottleneck. Generation cost reporting also handles missing or changing provider cost information more gracefully.

This release also improves the reliability of media work across platforms. Scene media and proxy handling, timeline playback and frame stepping, and Windows video probing have been refined so imported and generated assets behave more consistently as they move from library to scene assembly. Under the hood, the desktop workflow has received further stability work around its most frequently used production paths.

## Download Velvet Avocado Studio

Velvet Avocado is free to download and use.

[Download Velvet Avocado Studio for macOS or Windows](https://velvetavocado.com/download)
