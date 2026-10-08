---
name: videos-watchlist
description: See top performing videos from your watchlist
---
Show me the top performing videos from my watchlist. $ARGUMENTS

Use the `search_my_videos` tool. If the user provided a topic or filter context above, factor that into the search (pass the topic as a `query` and parse any natural-language filter words). Otherwise, use default settings.

Always present the results as an HTML artifact, never as a plain text reply. Make it beautiful, visual, and minimalist, styled in the Sandcastles theme: a white background, generous white space, clean sans-serif type, the primary blue #3B82F6 for accents, links, and highlights, and the Sandcastles logo (https://app.sandcastles.ai/logo-banner-light-mode.svg) in the header. Show each video as a card with its `thumbnail`, the creator's channel thumbnail as a round avatar, the creator's handle, the key metrics, and a link to its `sandcastles_url`. Lead with the insights, then the videos that support them.
