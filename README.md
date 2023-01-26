# deno-topfen
Deno does not pass trace from error in dynamic import

```bash
$ deno run -A index.js 
SyntaxError: Unexpected reserved word
    at async file:///home/mre/work/deno-topfen/index.js:2:15
```
It misses the information that the error is on line 2 in test.js
