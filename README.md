# 📝 WasmMP3.PWA

![GitHub](https://img.shields.io/github/license/jtn-san/WasmMP3.PWA)
![GitHub last commit](https://img.shields.io/github/last-commit/jtn-san/WasmMP3.PWA)
![PWA Ready](https://img.shields.io/badge/PWA-Ready-success)

**WasmMP3.PWA** é um bloco de notas minimalista e de alta performance, projetado para funcionar totalmente no navegador. Combinando a velocidade do **WebAssembly** com a flexibilidade de uma **Progressive Web App**, ele oferece uma experiência de escrita fluida, segura e disponível offline.

> 🚀 **Demo:** [Insira o Link da Demo Aqui](https://jtn-san.github.io/WasmMP3.PWA)

## ✨ Funcionalidades

* **🔒 Privacidade em Primeiro Lugar:** Todo o processamento é feito localmente no seu dispositivo via WebAssembly. Seus textos não são enviados para a nuvem.
* **📱 PWA (Progressive Web App):**
    * Instale como um aplicativo nativo no Windows, Mac, Android e iOS.
    * Funciona **100% Offline** graças aos Service Workers.
* **💾 Gerenciamento de Arquivos:**
    * Abra e salve arquivos `.txt` (ou markdown) diretamente do seu dispositivo.
    * Persistência local automática (opcional, dependendo da implementação).
* **⚡ Performance Wasm:** O motor de texto/processamento é otimizado via WebAssembly para garantir rapidez mesmo com arquivos grandes.
* **🌑 Modo Escuro / Claro:** Interface limpa e livre de distrações.

## 🛠️ Tecnologias Utilizadas

Este projeto explora o poder da web moderna:

* **Core Logic:** [Rust / C++ / Go] compilado para **WebAssembly (.wasm)**.
* **Interface:** HTML5, CSS3, JavaScript.
* **Armazenamento:** LocalStorage / File System Access API.
* **PWA:** Manifest.json & Service Workers para cache e instalação.

## 🚀 Como Rodar Localmente

Siga os passos para ter seu próprio bloco de notas rodando:

### Pré-requisitos

* Navegador moderno (Chrome, Edge, Firefox, Safari).
* [Node.js](https://nodejs.org/) (apenas para rodar o servidor local de desenvolvimento).

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/jtn-san/WasmMP3.PWA.git](https://github.com/jtn-san/WasmMP3.PWA.git)
    cd WasmMP3.PWA
    ```

2.  **Instale dependências (se houver bundler como Vite/Webpack):**
    ```bash
    npm install
    ```

3.  **Execute o servidor:**
    ```bash
    npm run dev
    # ou use uma ferramenta simples de http server
    npx http-server .
    ```

4.  **Acesse:**
    Abra `http://localhost:8080` (ou a porta indicada) no navegador.

## 📸 Screenshots

| Desktop (Modo Escuro) | Mobile (Instalado) |
|:---:|:---:|
| ![Desktop Screenshot](./docs/desktop.png) | ![Mobile Screenshot](./docs/mobile.png) |
*(Adicione as imagens na pasta docs ou assets)*


## 📄 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

---

Desenvolvido por [Jonathan](https://github.com/jtn-san).
