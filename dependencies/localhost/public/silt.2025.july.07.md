---
id: iskooayfjvqxa6ql0l88ca3
title: SILT#00082
desc: 'Something I learned today for 2025, July 07'
updated: 1751956165000
created: 1751955738644
bluesky: https://bsky.app/profile/surajssingh.com/post/3ltgodyniuc22
---

SILT#00082: Seeing how the `array_combinations` function works in Rust's itertools crate made me realize that const generics can be inferred just like regular type generics. This means, providing the shape of the array (which has a compile time length) allows the compiler to infer the returned array
