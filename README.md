# Puxa

YouTube downloader nativo pra macOS, em SwiftUI, em cima do [yt-dlp](https://github.com/yt-dlp/yt-dlp). Este repositório só guarda as versões publicadas do app.

## Instalar

Precisa de **macOS 14 (Sonoma) ou mais novo** (no macOS 26 o app usa o visual Liquid Glass) e do [Homebrew](https://brew.sh). No Terminal:

```sh
brew install --cask deandevz/tap/puxa
```

O Homebrew instala junto o `yt-dlp`, o `ffmpeg` e o `deno`, e libera o app no macOS. Depois é só abrir o **Puxa** pela pasta Aplicativos ou pelo Spotlight.

## Atualizar

O próprio app procura versão nova todo dia e mostra um botão **Atualizar agora**. Dá pra procurar na hora em **Puxa › Procurar atualizações…** ou nos Ajustes (⌘,). O yt-dlp também se atualiza sozinho uma vez por semana.

## Desinstalar

```sh
brew uninstall --cask puxa
```
