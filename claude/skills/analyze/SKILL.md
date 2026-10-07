---
name: analyze
description: Analyze a single video
argument-hint: [video URL or UUID]
---
Analyze this video: $ARGUMENTS

Use the `analyze_video` tool. Pass `$ARGUMENTS` as the URL (TikTok, Instagram, or YouTube Shorts) or as a `video_uuid` if it looks like a UUID. The tool queues the analysis and never returns it, so call `get_video_details` about 30 seconds later, then every 30 seconds until the analysis is complete, and summarize it covering the hook, format, narrative structure, topic, and any other key components. If `$ARGUMENTS` is empty, ask the user which video they want analyzed.
