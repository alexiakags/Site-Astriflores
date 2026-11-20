# 🌱 Site Astriflores

Site institucional e plataforma de doações da **Astriflores** (Associação de Florestal - MG), desenvolvido com React, Vite e Materialize CSS.

---

## 🛠️ Tecnologias Utilizadas

- **React**
- **Vite**
- **JavaScript (ES6+)**
- **HTML5 & CSS3**
- **Materialize CSS**

---

## 📋 Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:
- [Node.js](https://nodejs.org/) (versão 18 ou superior recomendada)
- [Git](https://git-scm.com/)

---

## 🚀 Como rodar o projeto localmente

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/alexiakags/site-astriflores.git](https://github.com/alexiakags/site-astriflores.git)
   ```

2. **Acesse a pasta do projeto:**
   ```bash
   cd site-astriflores/site-astriflores
   ```

3. **Instale as dependências:**
   ```bash
   npm install
   ```

4. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   ```

5. **Acesse no navegador:**
   Abra o endereço exibido no terminal (geralmente `http://localhost:5173`).

---

## ⚠️ Solução de Problemas (Windows / PowerShell)

Caso apareça o erro *"a execução de scripts foi desabilitada neste sistema"* ao rodar comandos `npm` no PowerShell do Windows, você pode resolver de duas maneiras:

- **Opção 1 (Usar `npm.cmd`):**
  ```powershell
  npm.cmd install
  npm.cmd run dev
  ```

- **Opção 2 (Liberar execução de scripts no PowerShell):**
  ```powershell
  Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
  ```

---

## 📁 Estrutura de Pastas

```text
site-astriflores/
├── public/                 # Imagens, ícones e arquivos estáticos (logo, hero, luva)
├── src/                    # Código-fonte da aplicação
│   ├── App.jsx             # Componente principal e navegação
│   ├── main.jsx            # Ponto de entrada do React
│   ├── SiteHeader.jsx      # Barra de navegação superior
│   ├── SiteFooter.jsx      # Rodapé com informações de contato
│   ├── Doacoes.jsx         # Página de listagem de itens para doação
│   ├── CardDoacao.jsx      # Card individual de cada item
│   ├── DetalheDoacao.jsx   # Tela de detalhes do item selecionado
│   ├── PopupQRCode.jsx     # Modal de doação via PIX / QR Code
│   ├── PopupEmail.jsx      # Modal de contato/confirmação por e-mail
│   ├── itensDoacao.js      # Dados dos itens disponíveis para doação
│   └── *.css               # Folhas de estilo dos componentes e páginas
├── index.html              # Arquivo HTML base
└── package.json            # Dependências e scripts do projeto
```
