# pipelineLucas

Aplicação web simples em Flask com uma rota de status e uma API para buscar alunos.

## Requisitos

- Python 3.10 ou superior

## Instalação e execução

No PowerShell, na pasta do projeto:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
python app.py
```

O servidor estará disponível em `http://127.0.0.1:5000`.

## Endpoints

- `GET /` retorna uma mensagem informando que a aplicação está funcionando.
- `GET /alunos` retorna todos os alunos em JSON.
- `GET /alunos?nome=ana` filtra os alunos por nome, sem diferenciar maiúsculas de minúsculas.

## Testes

```powershell
python -m pytest -q
```
