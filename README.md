# API Restaurantes (Python)

Exercícios de consumo de API e criação de endpoints com FastAPI, feitos durante meus estudos de back-end.

## O que tem aqui

- `app.py`: lê restaurantes de uma API pública e salva um arquivo JSON por restaurante.
- `main.py`: API FastAPI com os endpoints `/api/hello` e `/api/restaurante/`.

## Como rodar

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload
```

Depois, abra http://127.0.0.1:8000/docs para testar os endpoints.

Para gerar os arquivos JSON, rode `python3 app.py`. Eles não ficam no repositório porque são criados a cada execução.

## Fonte dos dados

API pública usada no curso: https://guilhermeonrails.github.io/api-restaurantes/restaurantes.json

## Tecnologias

Python, FastAPI, Requests