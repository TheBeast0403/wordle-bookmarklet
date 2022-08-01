# wordle bookmarklet

bookmarklet to show you current solution

how to use:

1) create a new bookmark
2) set bookmarlet name to anything you want
3) copy + paste into URL:
```js
javascript:(function(){window.alert(`today's word is:\n\n${JSON.parse(window.localStorage["nyt-wordle-state"])["solution"].toUpperCase()}`)})()
```
4) go to wordle
5) click on bookmarklet
6) enjoy not having to guess the word yourself :KEKW:

