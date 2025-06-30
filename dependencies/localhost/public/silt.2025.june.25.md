---
id: 3acj1ogkwtecinpzhn5lx90
title: SILT#00076
desc: 'Something I learned today for 2025, June 25'
updated: 1751005449408
created: 1750881366419
bluesky: https://bsky.app/profile/surajssingh.com/post/3lsiiynz65k2n
---

SILT#00076: If you've wanted a simple way to compare floating point-like numbers (discounting the `NaN`s), consider an augmented version of Radix sort. The idea is to do bit manipulation to create an ordering without direct comparisons. How that that happens is some forbidden magic (aka math)

## Additional Context

- Found the main article (["Radix Tricks" by Michael Herf](http://stereopsis.com/radix.html)) from: [Rust float Ord crate](https://github.com/notriddle/rust-float-ord)
- The article referenced another [titled "Radix Sort Revisited" by Pierre Terdiman](https://codercorner.com/RadixSortRevisited.htm)
