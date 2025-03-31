---
id: pdqwkbc4btsbr0fekftr5fk
title: 'SILT#00022'
desc: 'Something I learned today for 2025, March 29'
updated: 1743400803493
created: 1743316544059
mastodon: https://mastodon.social/@surajssingh/114250016147411742
bluesky: https://bsky.app/profile/surajssingh.com/post/3lllag5dkns2m
---

SILT#00022: In Cargo, if you want to specify the same crate multiple times, you can basically create an alias to the library with the `package` option (i.e., `aliased_name = {package="crate-name", version="*"}`). However, this is only allowed when they are separated by SemVer major versions
