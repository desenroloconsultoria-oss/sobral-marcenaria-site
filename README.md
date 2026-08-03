# Sobral Marcenaria — Landing Page

Site estático pronto para publicar. Sem build, sem dependências de servidor.

## Estrutura
```
deploy/
├── index.html        página principal
├── support.js        runtime
├── image-slot.js     runtime das imagens
├── .nojekyll         (mantém pastas iniciadas com _ no GitHub Pages)
└── images/           todas as fotos, otimizadas para web (.webp)
```

## Publicar no GitHub Pages
1. Crie um repositório e suba **o conteúdo desta pasta `deploy/`** na raiz do repo
   (o `index.html` precisa ficar na raiz da branch publicada).
2. Em **Settings → Pages**, selecione a branch (ex.: `main`) e a pasta `/ (root)`.
3. O site fica disponível em `https://SEU-USUARIO.github.io/SEU-REPO/`.

Para domínio próprio, adicione um arquivo `CNAME` com o domínio e configure o DNS.

## Imagens
Todas as fotos estão em `images/` no formato **WebP** (bom para web: leve e nítido).
Para trocar uma foto, substitua o arquivo correspondente mantendo o mesmo nome.
