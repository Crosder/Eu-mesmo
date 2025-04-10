# Escola Dashboard Backend

## Rotas disponíveis:
- POST `/login` - autenticação com `username` e `password`
- GET `/alunos` - retorna nome, desempenho, faltas e nota para gráficos

Configure `.env` com os dados do MySQL e rode com:
```bash
npm install
npm start
```