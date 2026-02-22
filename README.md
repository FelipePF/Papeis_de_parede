# 🖼️ Wallpapers Collection (JPEG XL)

Este repositório contém minha coleção pessoal de **wallpapers em alta qualidade** no formato **JPEG XL (JXL)**, garantindo compressão eficiente sem perdas de qualidade.

---

## 📂 Conteúdo
- Wallpapers em **diferentes resoluções** e **categorias**.
- Diversos temas como Animes, Linux, Games e mais.
- Formatos 16:9, 21:9, Icon, 4:3 e Mobile.
- Todos os arquivos estão no formato **.jxl** (Lossless JPEG XL). 
- Algumas imagens originalmente tem muito blur, serrilhado ou resolução extremamente baixa (pinterest quem o diga), que seriam complicadas de serem usadas (acho que nenhuma pessoa curte usar wallpaper assim) neste caso, foi usado IA generativa para aumentar a resolução e melhorar a qualidade da imagem, as imagens que foram usadas Upscaler por IA tem "upscaler" escrito no nome.

---

## ❓ Por que JPEG XL?
- 📉 **Melhor compressão** que JPEG comum.  
- 🖼️ **Qualidade sem perdas** (lossless), pode ser convertida para .png e utilizada para qualquer fim.  
- ⚡ **Mais rápido e eficiente** para decodificação.  
- 🌍 **Formato moderno e aberto**, com suporte crescente em navegadores e softwares.  

---

## 🛠️ Como abrir arquivos `.jxl`
O ideal é poder ser aberto como uma imagem qualquer, ou seja, com "2 cliques", mas dependendo do seu sistema operacional ou método de instalação, pode ser necessário instalar suporte extra:

### Linux
```bash
# Debian/Ubuntu
sudo apt install libjxl-tools
```
```bash
# Arch/Manjaro
sudo pacman -S libjxl
```

### MacOS
Suporte nativo limitado. Para abrir ou converter arquivos .jxl, você pode usar o Homebrew:
```bash
brew install jpeg-xl
```
Isso instala ferramentas de linha de comando como cjxl (compressão) e djxl (decodificação).

### BSD
Suporte depende da distribuição. No FreeBSD, por exemplo, você pode instalar via pkg:
```bash
pkg install jpeg-xl
```

### Windows
Suporte nativo limitado, MAS o windows 11 oferece um pacote para adicionar o suporte de forma oficial, quando for abrir uma imagem jxl, ele vai deixar um link que leva direto para o pacote na microsoft store. Caso contrario, para abrir ou converter .jxl, use aplicativos como:

XnView MP (visualizador de imagens)

IrfanView com plugin JPEG XL

JPEG XL reference binaries: https://gitlab.com/wg1/jpeg-xl/-/releases

### Android
O Android não possui suporte nativo para .jxl, mas você pode usar aplicativos de terceiros para converter:  

Termux:

Baixe o Termux e coloque pelo explorador de arquivos a pasta com os wallpapers dentro, converta, e os novamente pelo explorador de arquivos, coloque de volta na pasta desejada as versões .png:

```bash
# Instala o suporte a .jxl
pkg install jpeg-xl
```
```bash
# converte uma imagem específica para .png
djxl imagem.jxl imagem.png
```

JPEG XL & JXL Image Viewer: https://play.google.com/store/apps/details?id=jpeg.xl.jxl.image.viewer&hl=en-us

Assim Converter as imagens para .JPG e utilizar normalmente.