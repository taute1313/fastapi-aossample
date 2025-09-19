# fastapi-aossample

Plantilla sencilla para crear APIs con FastAPI, inspirada en ejemplos como `aossample`. 
Incluye CRUD de `Item`, healthcheck, tests y Dockerfile.

## Instalación
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## Ejecución
```bash
uvicorn app.main:app --reload
# → http://127.0.0.1:8000/docs
```

## Tests
```bash
pytest -q
```
