#### flask

```python
from flask import Flask, escape, request, render_template
import random

app = Flask(__name__)


@app.route('/welcome') 
def welcome():
    return '반갑습니다.'
```

