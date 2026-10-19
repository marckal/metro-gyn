# Metrô Goiânia · Mapa ao vivo (projeto de design especulativo)

Simulação interativa de um painel em tempo real para o metrô imaginado por Marck Al
([Neuralbrand, 2017](https://neuralbrand.medium.com/metr%C3%B4-de-goi%C3%A2nia-5af7bfac647c)).
Este metrô não existe: trens, horários e avisos são dados simulados.

É um único arquivo (`index.html`), sem dependências nem build.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub (por exemplo `metro-goiania`).
2. Envie estes arquivos para a branch `main`.
3. Em **Settings → Pages → Build and deployment**, escolha **Source: GitHub Actions**.
   O workflow em `.github/workflows/pages.yml` publica a cada push na `main`.
4. O site ficará em `https://SEU-USUARIO.github.io/metro-goiania/`.

Alternativa sem Actions: em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
