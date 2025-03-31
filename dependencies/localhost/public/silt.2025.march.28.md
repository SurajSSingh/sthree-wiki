---
id: dnai5m258vxebs569b0r1en
title: 'SILT#00021'
desc: 'Something I learned today for 2025, March 28'
updated: 1743400794662
created: 1743228118683
mastodon: https://mastodon.social/@surajssingh/114244216129534904
bluesky: https://bsky.app/profile/surajssingh.com/post/3llinymhasc2k
---

SILT#00021: One issue you may come across when working with multi-pages is that building static pages does not guarantee that the path for the file will be correct. Instead, make sure you are using absolute paths. For SvelteKit, it's simply adding `paths: {relative: false}` to the Svelte config
