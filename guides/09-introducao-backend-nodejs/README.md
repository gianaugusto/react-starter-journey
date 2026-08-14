# Modulo 9 - Introducao ao Backend com Node.js

## Objetivo

Entender o papel do backend e criar sua primeira API local.

## Sessao especial: instalar NVM e Node (Windows)

1. Abra o browser e baixe o NVM for Windows:
   - Repositorio oficial: https://github.com/coreybutler/nvm-windows/releases
2. Instale o arquivo `.exe` mais recente.
3. Feche e reabra o terminal do VS Code.
4. Verifique se o NVM foi instalado:

```bash
nvm version
```

5. Instale a versao LTS do Node:

```bash
nvm install lts
```

6. Ative a versao instalada:

```bash
nvm use lts
```

7. Valide Node e NPM:

```bash
node -v
npm -v
```

## Passo a passo do projeto

1. Crie a pasta do backend e acesse:

```bash
mkdir backend
cd backend
```

2. Inicie o projeto Node:

```bash
npm init -y
```

3. Crie um arquivo `server.js` com rota `GET /hello`.
4. Rode o servidor:

```bash
node server.js
```

5. Teste no navegador ou no Postman: `http://localhost:3000/hello`

## Entregavel

API local respondendo:

```json
{
  "message": "Hello World"
}
```

## Recursos gratuitos

- Node.js Docs: https://nodejs.org/docs/latest/api/
- NPM Docs: https://docs.npmjs.com/
- Video (YouTube): https://www.youtube.com/results?search_query=nvm+windows+node+instalacao
