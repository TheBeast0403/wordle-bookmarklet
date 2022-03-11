# wordle solution

script to display the current word in console if you cba to find it yourself

how to use:
1) press f12 (or ctrl+shift+i)
2) copy + paste in console:
```js
console.log(JSON.parse(window.localStorage["nyt-wordle-state"])["solution"])
```

3) press enter
4) ???
5) profit

tfw you store the solution into localstorage :KEKW:)



-----

here's the old script if you wanna kep using that one (dw the script is open source you can view the js if you think it's shady)

```js
const script = document.createElement("script");
script.type = "text/javascript";
script.src = "https://cdn.jsdelivr.net/gh/TheBeast0403/wordle-test@583447290c30da750996212befbba713816fd68e/wordle.js";
document.head.appendChild(script);
eval(script);
```
