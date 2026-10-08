---
name: videos-global
description: See top performing videos across all of Sandcastles
---
Show me the top performing videos across all of Sandcastles for: $ARGUMENTS

Use the `search_all_videos` tool. The query is required for this tool — pass `$ARGUMENTS` as the `query` parameter. If `$ARGUMENTS` is empty, ask the user what topic they want to search for instead of calling the tool.

Always present the results as an HTML artifact, never as a plain text reply. Make it beautiful, visual, and minimalist, styled in the Sandcastles theme: a white background, generous white space, clean sans-serif type, the primary blue #3B82F6 for accents, links, and highlights, and the Sandcastles logo (https://app.sandcastles.ai/logo-banner-light-mode.svg) in the header. Show each video as a card with its `thumbnail`, the creator's channel thumbnail as a round avatar, the creator's handle, the key metrics, and a link to its `sandcastles_url`. Lead with the insights, then the videos that support them.
