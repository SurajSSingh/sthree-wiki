---
id: q06l9czrj5c8vzbvwe3thc9
title: SILT#00004
desc: 'Something I learned today for 2025, March 07'
updated: 1741417581711
created: 1741417130959
bluesky: 
mastadon: 
---

SILT#00004: Much like dividing by 0, if you set the CPU thread count to 0 for libraries like whisper.cpp, your app will say there is no need to work and crash. You may want 0 to have some special mean, but you have to specify it. Never forget the edge-cases, or risk the wrath of unintended behaviors
