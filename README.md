# FastApi-101
Firts steps learning Fast Api

## Preconditions:

- Python 3

## Run locally

### Install dependencies

```
pip install -r requirements.txt
```

### Run server

```
uvicorn app.main:app --reload
```

If uvicorn is not in your path, use

```
python -m uvicorn main:app --reload
```

### Navigate to OpenApi documentation

http://127.0.0.1:8000/redoc