# Python_Flask_Django
## What is Flask?
* ### Flask is a micro web framework that is written in Python. 
* #### fFask provides you with tools, libraries and technologies that allow you to build a web application. Flask provides support for APIs which are nicely shaped and coherent. Flask is very easy to learn, and also its implementation is straightforward. In just a few lines of code, you can get started with this.
* #### A minimal Flask application looks something like this:
```
from flask import Flask

app = Flask(__name__)

@app.route("/")
def hello_world():
    return "<p>Hello, World!</p>"
@app.route("/<name>")
def user(name):
    return f"Hell {name}!"
    
if __name__=="__main__":
     app.run()
```
    
