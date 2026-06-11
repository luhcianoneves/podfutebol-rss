# Config do GitHub Pages — 48 do Segundo

Execute uma vez para criar o repositório e ativar o Pages.

## 1. Criar repositório no GitHub
Acesse https://github.com/new
- Nome: `podfutebol-rss`
- Público
- Não iniciar com README

## 2. Rodar setup
Execute o script abaixo no terminal (pasta raiz do projeto):
```powershell
& ".\scripts\pages-setup.ps1"
```

## 3. Ativar GitHub Pages
- Acesse Settings > Pages do repositório
- Source: Deploy from a branch
- Branch: `main`, pasta `/ (root)`
- Salvar

Pronto! O RSS estará em:
https://luhcianoneves.github.io/podfutebol-rss/rss.xml

## 4. Configurar no Spotify for Podcasters
- Dashboard → Settings → Distribution
- Em "Import a podcast", cole a URL do RSS acima
- Pronto — toda vez que o RSS atualizar (push automático), o Spotify publica o novo episódio
