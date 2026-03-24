# TechTalk AI - Backend

Backend de TechTalk AI usando FastAPI y Groq API.

## Setup Local

```bash
# Instalar dependencias
pip install -r requirements.txt

# Configurar API key
export GROQ_API_KEY="tu-api-key-aqui"

# Correr servidor
python main.py
```

Servidor corre en: http://localhost:8000

## Endpoints

- `GET /` - Health check
- `GET /api/question/{type}` - Obtiene pregunta aleatoria
- `POST /api/feedback` - Genera feedback sobre respuesta

## Deploy en Railway

1. Conectar repo de GitHub
2. Agregar variable de entorno: `GROQ_API_KEY`
3. Deploy automático
