---
id: s3z7wtc47c1blrhf3d4ua5c
title: SILT#00065
desc: 'Something I learned today for 2025, June 07'
updated: 1749361547513
created: 1749361142002
bluesky: https://bsky.app/profile/surajssingh.com/post/3lr35wjlu622f
---

SILT#00065: When using `document.querySelectorAll`, it returns a NodeList, which is almost like an array of Nodes, except it has none of the array function like `map` or `filter`. To get them, you have to do `Array.from`, which breaks the action preview in browser console, so debugging can be tricky
