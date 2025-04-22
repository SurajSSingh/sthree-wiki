---
id: grz5ceu9miptofo07xqa6c3
title: 'SILT#00030'
desc: 'Something I learned today for 2025, April 9'
updated: 1745303618403
created: 1744265072527
mastodon: https://mastodon.social/@surajssingh/114312202291591709
bluesky: https://bsky.app/profile/surajssingh.com/post/3lmgu4py6ec2g
---

SILT#00030: My brief attempt explaining Tauri channels: They stream large data between the JS and Rust via callback object. To use, in Rust, add the `Channel<T>` param to your command; in JS, create a `Channel<T>` class and set the `onmessage` field your callback. `T` is the serializable payload

## Additional Details

- <https://v2.tauri.app/develop/calling-frontend/#channels>
