# wordle solution

bookmarklet to show you current solution

how to use:

1) create a new bookmark
2) set bookmarlet name to anything you want
3) copy + paste into URL:
```js
javascript:(function()%7Bwindow.alert(%60today's word is%3A%5Cn%5Cn%24%7BJSON.parse(window.localStorage%5B"nyt-wordle-state"%5D)%5B"solution"%5D.toUpperCase()%7D%60)%7D)()
```
4) go to wordle
5) click on bookmarklet
6) enjoy not having to guess the word yourself :KEKW:

