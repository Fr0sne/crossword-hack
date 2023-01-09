# crossword-hack
Small script I wrote to show crosswordlabs answers in crossword format.

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
