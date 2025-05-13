---
id: pi53nk0uzsmck9l3aadyugf
title: SILT#00049
desc: 'Something I learned today for 2025, May 10'
updated: 1747028290207
created: 1746944940829
mastodon: https://mastodon.social/@surajssingh/114487798240652554
bluesky: https://bsky.app/profile/surajssingh.com/post/3loutj4yens2l
---

SILT#00049: Async Rust is an interesting beast to debug. A subtle item to watch out for in async function: when locking a mutex, make sure to understand when Rust unlocks the mutex via drop. Even when explicitly dropping, a (standard) mutex may still be locked, leading to deadlock issues
