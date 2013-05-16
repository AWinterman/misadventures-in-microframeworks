```javascript
demi.route("/")
  .on("GET", function(req, resp){
      resp.write("Hello World!")
   // resp.end() ?
  })
```
I'm not sure exactly how the api should look moving forward.

[lesson's learned](lessons_learned.md)
