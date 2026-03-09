# ✟ Culto de Ensino da Palavra

**App PWA** para controle de presença no Culto de Ensino da Palavra — Imersão Escatológica 2026.

Funciona offline, é instalável no celular e no computador, e roda direto do navegador via GitHub Pages.

---

## 🚀 Como publicar no GitHub Pages

### 1. Crie um repositório no GitHub

1. Acesse [github.com](https://github.com) e faça login
2. Clique em **"New repository"**
3. Nomeie como `culto-ensino-palavra` (ou qualquer nome)
4. Deixe como **Public**
5. Clique em **"Create repository"**

### 2. Envie os arquivos

Faça upload de **todos os arquivos** desta pasta:

```
index.html
manifest.json
sw.js
favicon.ico
icons/
  ├── icon-72x72.png
  ├── icon-96x96.png
  ├── icon-128x128.png
  ├── icon-144x144.png
  ├── icon-152x152.png
  ├── icon-192x192.png
  ├── icon-384x384.png
  ├── icon-512x512.png
  ├── apple-touch-icon.png
  └── favicon-32x32.png
```

**Via interface do GitHub:**
- Clique em **"uploading an existing file"**
- Arraste todos os arquivos e a pasta `icons/`
- Clique **"Commit changes"**

### 3. Ative o GitHub Pages

1. Vá em **Settings** → **Pages**
2. Em *Source*, selecione **"Deploy from a branch"**
3. Branch: **main** | Folder: **/ (root)**
4. Clique **Save**

Aguarde ~1 minuto. Seu app estará disponível em:

```
https://SEU_USUARIO.github.io/culto-ensino-palavra/
```

---

## 📲 Instalação no celular / computador

Ao abrir o link no navegador, aparece automaticamente um banner para instalar o app:

- **Android (Chrome):** toque em **"⬇ Instalar"** no banner
- **iPhone/iPad (Safari):** toque em **Compartilhar ⬆** → **"Adicionar à Tela Inicial"**
- **Desktop (Chrome/Edge):** clique no ícone de instalação na barra de endereço, ou no banner

---

## ✨ Funcionalidades

- ⚙ **Configuração** — nome da igreja, congregação e pastor; seleção das sextas de 2026
- 👤 **Pessoas** — cadastro com nome, idade, cargo e controle de material didático
- 📋 **Presença** — bolinhas verde/vermelho por data, com percentual de frequência
- 📊 **Progresso** — anéis animados, ranking e estatísticas gerais
- 📤 **Exportar** — relatórios formatados para WhatsApp
- 🏆 **Certificado** — gera e baixa certificado PNG para quem atingiu ≥70% (tema Imersão Escatológica)

---

## 🔒 Dados

Todos os dados são salvos localmente no dispositivo (localStorage). Nenhuma informação é enviada para servidores externos.

---

*Desenvolvido para uso ministerial · 2026*
