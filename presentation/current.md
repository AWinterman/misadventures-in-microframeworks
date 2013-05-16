# The current way of doing things: #

It's on [github](https://github.com/AWinterman/demitasse.git).

```javascript

Demi = require("demi")
public = "path/to/public/files"

demi = new Demi(public)

demi.route("/").on("GET", hello_world)

function hello_world(){
  return "hello world"
}
```

[but life isn't this simple.](not_that_simple.md)
