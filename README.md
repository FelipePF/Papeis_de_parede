# 🖼️ Wallpapers Collection (JPEG XL)

Este repositório contém minha coleção pessoal de **wallpapers em alta qualidade** no formato **JPEG XL (JXL)**, garantindo compressão eficiente sem perdas de qualidade.

---

## 📂 Conteúdo
- Wallpapers em **diferentes resoluções** e **categorias**.
- Diversos temas como Animes, Linux, Games.
- Formatos 16:9, 21:9, Icon e Mobile.
- Todos os arquivos estão no formato **.jxl** (Lossless JPEG XL).  

---

## ❓ Por que JPEG XL?
- 📉 **Melhor compressão** que JPEG comum.  
- 🖼️ **Qualidade sem perdas** (lossless).  
- ⚡ **Mais rápido e eficiente** para decodificação.  
- 🌍 **Formato moderno e aberto**, com suporte crescente em navegadores e softwares.  

---

## 🛠️ Como abrir arquivos `.jxl`
O ideal é poder ser aberto como uma imagem qualquer, ou seja, com "2 cliques", mas dependendo do seu sistema operacional ou médoto de instalação, pode ser necessário instalar suporte extra:

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
Suporte nativo limitado. Para abrir ou converter .jxl, use aplicativos como:

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