# l
because typing `console.log` is too long!

l is a handy shorthand function
```JavaScript
/**
 * because fuck `console.log`.
 * `l` is a shorthand for `console.log`.
 */
function l() {
    if (arguments.length) console.log.apply(console, arguments)
}
```

