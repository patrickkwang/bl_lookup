# Biolink Model lookup service

## deployment

### local

```bash
pip install -r requirements.txt
./main.py --port 8144
```

### Docker

```bash
docker build -t bl_lookup .
docker run -p 8144:8144 bl_lookup --port 8144
```
