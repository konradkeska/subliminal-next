# Subliminal Next

[![installs](https://vsmarketplacebadge.apphb.com/installs/konradkeska.subliminal-next.svg)](https://marketplace.visualstudio.com/items?itemName=konradkeska.subliminal-next)
[![rating](https://vsmarketplacebadge.apphb.com/rating/konradkeska.subliminal-next.svg)](https://marketplace.visualstudio.com/items?itemName=konradkeska.subliminal-next)

![Preview](https://user-images.githubusercontent.com/29062983/102016616-1d253880-3d62-11eb-926f-4894ce8b046d.png)

## About

First of, this theme was supposed to be only for my personal use, but later (after coming to the conclusion that some people might find it useful) I've decided to share it. It has helped me increase my productivity a lot, hope it will do for you too.

It is basically a subjectively revamped version of awesome [Subliminal](https://github.com/gaearon/subliminal) theme made by [Dan Abramov](https://github.com/gaearon).

After using Subliminal for a while I have began adding consecutive adjustments and finally came out with a basically new theme.

Major changes:

- base color and contrast
- new UI look
- small syntax modifications
- support for other languages

I've decided to make this theme because I really liked the idea behind Subliminal, but wanted slightly more electrifying look and more diverse functionality related to my needs (not only JavaScript focused).

## Basic concept

We want to highlight only what is important and therefore increase our productivity by making our brain automatically recognize some patterns:

- Red - function/class declarations, returns, comparison
- Yellow - function calls, assignment, logic
- Blue - literals (numbers, booleans), types
- Green - strings

## Font

The font I use in the theme samples section is **Dank Mono** which is available to purchase - [here](https://dank.sh/).

## Syntax support (What I've tested so far)

- **JS / JSX**
- **TS / TSX**
- **CSS, SCSS, SASS, LESS, CSS-in-JS**
- **JSON**
- **MD**

## Settings I use

```js
{
  "editor.folding": false,
  "breadcrumbs.enabled": false,
  "editor.colorDecorators": false,
  "editor.cursorBlinking": "solid",
  "editor.cursorStyle": "line",
  "editor.fontSize": 18,
  "editor.letterSpacing": 0.5,
  "editor.lineHeight": 26,
  "editor.lineNumbers": "off",
  "editor.minimap.enabled": true,
  "editor.minimap.enabled": true,
  "editor.overviewRulerBorder": false,
  "editor.renderLineHighlight": "none",
  "editor.renderWhitespace": "none",
  "editor.scrollbar.vertical": "hidden",
  "editor.scrollbar.verticalScrollbarSize": 5,
  "editor.snippetSuggestions": "top",
  "explorer.openEditors.visible": 0,
  "workbench.activityBar.visible": false,
  "workbench.editor.tabCloseButton": "off",
  "workbench.editor.tabSizing": "shrink",
  "workbench.sideBar.location": "left",
  "workbench.statusBar.visible": true,
}
```

## Extensions I use - theme wise

- [Quill Icons](https://marketplace.visualstudio.com/items?itemName=cdonohue.quill-icons)
- [Sublte Match Brackets](https://marketplace.visualstudio.com/items?itemName=rafamel.subtle-brackets)
- [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2)
- [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
