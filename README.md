# crossword-hack
Small script I wrote to show crosswordlabs (https://crosswordlabs.com) answers in crossword format.

```js
grid.forEach(line => {
    console.log(...line.map(col => {
        if(col){
            return col.char
        }
        return ' '
    }))
})
console.log = () => {}
```

Copy and paste this code into Chrome Developer Tools (F12 or CTRL + SHIFT + C to open) in console tab
