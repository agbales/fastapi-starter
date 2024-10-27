# FastAPI Starter

This python API starter repo gets you set up with FastAPI instantly.

Visit the [docs](https://fastapi.tiangolo.com/) for more.

Example:

[http://127.0.0.1:8000/items/5?q=hello](http://127.0.0.1:8000/items/5?q=hello)

`{ "item_id": 5, "q": "hello" }`

## Local Setup

#### Optional (recommended) [virtual environment](https://docs.python.org/3/library/venv.html)

`python3 -m venv myenv`
`source myenv/bin/activate`

#### Install dependencies
`pip install -r requirements.txt`

## Run

`fastapi dev main.py`