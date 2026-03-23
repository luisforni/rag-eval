# rag-eval

Pipeline RAG con evaluación automática de calidad.

## Repos

| Submodulo | Descripcion |
|-----------|-------------|
| [rag-eval-api](https://github.com/luisforni/rag-eval-api) | Backend FastAPI (LangChain + Chroma + RAGAS) |
| [rag-eval-ui](https://github.com/luisforni/rag-eval-ui) | Frontend Next.js |

## Levantar el stack completo

```bash
# Clonar con submodulos
git clone --recurse-submodules https://github.com/luisforni/rag-eval

# Copiar y completar variables de entorno
cp .env.example rag-eval-api/.env

# Levantar
docker compose up --build
```

- API: http://localhost:8000
- Docs: http://localhost:8000/docs
- UI: http://localhost:3000

## Desarrollo

```bash
# Actualizar submodulos
git submodule update --remote --merge
```
