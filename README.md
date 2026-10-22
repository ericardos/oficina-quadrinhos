# Oficina de Quadrinhos

Aplicativo para criar histórias em quadrinhos no navegador, feito para aulas. Tem quadros prontos, balões, desenho, figurinhas, formas, imagens, várias páginas e exportação em PNG e PDF. Não precisa de conta nem de servidor.

## Usar online (GitHub Pages)
1. Crie um repositório e envie os arquivos desta pasta (`index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`).
2. No repositório: **Settings → Pages → Build and deployment → Deploy from a branch**, escolha `main` e a pasta `/ (root)`.
3. Em alguns minutos o app abre em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## Usar offline
- **Mais simples:** baixe o arquivo `index.html` e abra no Chrome (duplo clique). Funciona sem internet.
- **Como aplicativo (Chromebook, Windows, Mac):** abra o endereço do GitHub Pages uma vez com internet e use o ícone de instalar na barra de endereços do Chrome (ou menu ⋮ → *Instalar*). Depois abre offline, como um app.

## Observações
- O trabalho é salvo automaticamente **no navegador do aparelho**. Para guardar ou levar para outro computador, use **Salvar projeto** (arquivo `.json`) e **Abrir projeto**.
- As fontes dos balões (Inter, Comic Neue, Bangers, Patrick Hand, Permanent Marker) vêm do Google Fonts. Offline, o app usa fontes do sistema no lugar; no modo instalado elas ficam guardadas depois da primeira visita online.
- Os emojis usam a fonte de emojis do próprio sistema, então a aparência varia entre aparelhos.
- As bibliotecas de imagens (OpenClipart, Openverse, Pixabay, Wikimedia) são links externos: baixe a imagem e use **Inserir imagem** (ou copie e cole com Ctrl+V). Confira a licença de cada imagem.
- Ao atualizar o app depois de publicado, troque o texto `oficina-v1` em `sw.js` (por exemplo para `oficina-v2`) para que quem já instalou receba a nova versão.

## Licença
Escolha uma licença para o repositório (por exemplo MIT) e adicione um arquivo `LICENSE`.
