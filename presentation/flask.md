# [Flask is awesome](http://flask.pocoo.org/) #

```python
#import it
from flask import Flask
app = Flask(__name__)

#name it
@app.route("/")
def hello():
    return "Hello World!"

#do it
if __name__ == "__main__":
    app.run()
```

# but... #
[do we need another node framework?](node_frameworks.md)

