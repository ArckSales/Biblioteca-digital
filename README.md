## Como executar o projeto (FastAPI)

Siga os passos abaixo para rodar o projeto localmente:
Instale o FastAPI e o Uvicorn:

```bash
pip install fastapi uvicorn
```
Entre na pasta onde está o arquivo `main.py`:

```bash
cd Biblioteca digital
```
Inicie a aplicação com o comando:

```bash
uvicorn main:app --reload
```
Após rodar o servidor, abra:

* API: http://127.0.0.1:8000
* Documentação (Swagger): http://127.0.0.1:8000/docs
* Documentação alternativa: http://127.0.0.1:8000/redoc
