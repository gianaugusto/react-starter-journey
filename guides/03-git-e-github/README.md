# Modulo 3 - Git e GitHub

## Objetivo

Versionar seu projeto localmente e publicar no GitHub.

## Passo a passo

1. Inicie o repositorio local:

```bash
git init
```

2. Configure nome e email (uma vez por maquina):

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```

3. Adicione arquivos e crie o primeiro commit:

```bash
git add .
git commit -m "Primeiro commit"
```

4. Crie um repositorio no GitHub.
5. Conecte o remoto e envie:

```bash
git remote add origin URL_DO_REPOSITORIO
git branch -M main
git push -u origin main
```

## Entregavel

Repositorio criado no GitHub com o primeiro commit publicado.

## Recursos gratuitos

- GitHub Docs: https://docs.github.com/pt
- Git Guide: https://rogerdudler.github.io/git-guide/index.pt_BR.html
- Video (YouTube): https://www.youtube.com/results?search_query=git+e+github+para+iniciantes
