# JPlayer

Player de música offline (PWA) com IA.

## Publicar no GitHub Pages
1. Crie um repositório no GitHub (ex.: `jplayer`).
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Em **Settings → Pages**: Source = *Deploy from a branch*, Branch = `main` / `(root)` → Save.
4. Aguarde 1–2 min e abra `https://SEU-USUARIO.github.io/jplayer/` no Chrome do celular.
5. Menu ⋮ → **Instalar app** / **Adicionar à tela inicial**.

## Transformar em app Android (APK/AAB)
1. Com o site no ar, abra https://www.pwabuilder.com e cole a URL do GitHub Pages.
2. Clique em **Package for stores → Android** e baixe o pacote.
3. Instale o `.apk` no celular (ou use o `.aab` na Play Store).

## Atualizar
Ao mudar o app, aumente o número em `CACHE` no `service-worker.js` (ex.: `jplayer-v2`).
