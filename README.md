English | [简体中文](README.zh-CN.md)

# ZyBooks Auto

A Tampermonkey userscript that automates ZyBooks interactive activities. It answers multiple-choice questions, handles drag-and-drop exercises, plays through animations at 2x speed, and moves to the next page when everything's done.

## What It Does

- **Multiple choice** — clicks through options until it finds the correct one, then skips already-completed questions.
- **Drag and drop** — matches draggable items to their targets by trial and error.
- **Animations & slideshows** — hits Play, sets 2x speed, and waits for them to finish.
- **Short answer** — uses the "Show Answer" button when available, fills in the text, and checks it.
- **Auto-advance** — moves to the next page once all participation activities are complete.

## Install

1. Install [Tampermonkey](https://www.tampermonkey.net/) in your browser.
2. Install [Stylus](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) (optional, for custom styles).
3. Go to the [Greasy Fork page](https://greasyfork.org/en/scripts/488644-zybooks-auto) and click Install.

Or copy `ZyBooks_auto.js` directly into a new Tampermonkey script.

## Usage

Open any ZyBooks chapter. The script starts running automatically and works through the activities on the page. Check the browser console (F12) for logs.

## Notes

- Challenge activities are skipped — the script only handles participation exercises.
- It won't get every drag-and-drop question right on the first try; it uses trial and error.
- Keep the browser tab open and visible. Some activities don't load properly in background tabs.

## License

[MIT](LICENSE)
