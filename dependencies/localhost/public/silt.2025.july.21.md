---
id: rdo04rttmtw2pp2z2or8ho7
title: SILT#00091
desc: 'Something I learned today for 2025, July 21'
updated: 1753160288891
created: 1753159292376
bluesky: https://bsky.app/profile/surajssingh.com/post/3lujprsmmas2e
---

SILT#00091: There are many ways to load JS and CSS code using HTML, including using `defer` and `async` attributes (among other items like `type='module'` for JS). All of them boil down to when downloading and execution occurs in the HTML parsing phase (blocking, alongside, or at the end)

## Additional Notes

Links to additional reading

- <https://gist.github.com/jakub-g/385ee6b41085303a53ad92c7c8afd7a6>
- <https://v8.dev/features/modules#module-vs-script>
- <https://stackoverflow.com/questions/63420821/do-modules-prevent-the-need-to-use-the-domcontentloaded-listener>
- <https://flaviocopes.com/javascript-async-defer/#the-position-matters>
- <https://stackoverflow.com/questions/10808109/script-tag-async-defer>
- <https://peter.sh/experiments/asynchronous-and-deferred-javascript-execution-explained/>
