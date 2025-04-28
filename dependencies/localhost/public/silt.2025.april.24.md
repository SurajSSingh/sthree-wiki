---
id: h8sa9iod68c2349lem0it7h
title: 'SILT#00040'
desc: 'Something I learned today for 2025, April 24'
updated: 1745884682825
created: 1745560198369
mastodon: https://mastodon.social/@surajssingh/114397070057938336
bluesky: https://bsky.app/profile/surajssingh.com/post/3lnmk6qfv7s2l
---

SILT#00040: Audio programming, like graphics programming, makes the wildest bugs. If you'd like to deep-fry your WAV audio, first make sure it is float encoded with bounds between -1 and 1. Take the samples and multiply by 32_767 (16-bit signed max), and re-encode it. This will produce that effect
