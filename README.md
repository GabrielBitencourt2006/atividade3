# Atividade 3 – Requisições GET e POST com Express

Servidor Node.js com Express que realiza as quatro operações matemáticas via POST.

## Como executar

npm install
node app.js

O servidor roda em http://localhost:3001

## Rotas

| Método | Rota | Descrição |
|---|---|---|
| GET | / | Retorna "Oi, mundo :-)" |
| POST | /soma | Soma `a` e `b` |
| POST | /subtracao | Subtrai `b` de `a` |
| POST | /multiplicacao | Multiplica `a` por `b` |
| POST | /divisao | Divide `a` por `b` (erro se `b` for 0) |

Exemplo de body: `{"a": 10, "b": 5}`

## Evidências

### GET /
<img width="1535" height="811" alt="image" src="https://github.com/user-attachments/assets/e5daa977-3514-4db4-90ad-702392a42166" />



### POST /soma

### POST /subtracao

### POST /multiplicacao

### POST /divisao
