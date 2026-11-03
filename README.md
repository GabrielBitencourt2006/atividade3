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
<img width="1535" height="783" alt="image" src="https://github.com/user-attachments/assets/3786ca8a-3628-4bfe-a05c-eedb7980342b" />


### POST /subtracao
<img width="1535" height="797" alt="image" src="https://github.com/user-attachments/assets/b63009e3-f523-4eb7-9b39-290734fe42ca" />



### POST /multiplicacao
<img width="1535" height="802" alt="image" src="https://github.com/user-attachments/assets/7327a5da-9788-4870-83b3-8d21b66b417a" />


### POST /divisao
<img width="1535" height="862" alt="image" src="https://github.com/user-attachments/assets/2f9f548e-a69d-4034-9309-7902e95c7070" />

