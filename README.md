# FastAPI mit PIP

## Projekt einrichten

### 1. Virtual Environment erstellen

```bash
python -m venv .venv
```

### 2. Virtual Environment aktivieren

```bash
source .venv/bin/activate
```

### 3. FastAPI installieren

```bash
pip install "fastapi[standard]"
```

### 4. Requirements-Datei erstellen

```bash
pip freeze > requirements.txt
```

### 5. Server starten

```bash
fastapi dev main.py
```

Der Server läuft dann unter http://127.0.0.1:8000

### 6. API testen

- Browser: http://127.0.0.1:8000
- Swagger UI: http://127.0.0.1:8000/docs

## Dateien

- `requirements.txt` - Liste der Abhängigkeiten
- `main.py` - FastAPI Anwendung
- `.venv/` - Virtual Environment (nicht committen)
