# A current example: #

```javascript
var Demi = require("demi")

var fs = require("fs")
  , url = require("url")
  , exec = require("child_process").exec

var demi = new Demi("./docs")
  , indexHTML 

exec("docco `echo example/* lib/*`", function(err, stdout, stderr){
  console.log(stdout)
  fs.readFile("./docs/docs-example.html", function(err, data){
      indexHTML = data
  })
})

demi.route("^/$", "index.html")
    .on("GET", function(){
        return indexHTML
    })

// now run it.
demi.run(8769)
```

- First request is going to get an undefined
- Async in the callback body gets complicated.
- Server side events?

[moving forward](next_steps.md)




