# Safari Issue: Background Image in Vertical Writing Mode

Safari doesn't show background images when a child element uses vertical writing mode. [Bug report](https://bugs.webkit.org/show_bug.cgi?id=303742).

**Demo:** [Live page](https://maxim-mazurok.github.io/safari-issue-background-image-vertical-writing-mode/) | [index.html](./index.html)

![Safari (missing background)](safari.png) ![Chrome (correct)](chrome.png)

**Workaround:** Move `writing-mode: vertical-rl;` from child to parent element. See [workaround.html](./workaround.html) or [live demo](https://maxim-mazurok.github.io/safari-issue-background-image-vertical-writing-mode/workaround.html).