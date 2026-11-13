# ciencio-web

Site de apresentação do **ciênc.io**, app para iPhone com curiosidades científicas em português.

É um site estático (HTML e CSS, sem build), publicado pelo GitHub Pages.

## Publicar

1. No GitHub: **Settings → Pages**.
2. Em *Build and deployment*, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
3. Em um ou dois minutos o site fica em `https://dmrangel.github.io/ciencio-web/`.

## Ver localmente

Abra o `index.html` no navegador, ou rode um servidor simples na pasta:

```bash
python3 -m http.server 8000
```

e acesse `http://localhost:8000`.

## Páginas para a App Store

A App Store pede dois links, que o app também abre na tela de Ajustes:

- `privacidade.html`: política de privacidade (o app não coleta dados; tudo fica no aparelho).
- `suporte.html`: perguntas frequentes e contato com o desenvolvedor.

As duas usam o estilo de `documento.css`. Se a política mudar, atualize a data no topo da página.
