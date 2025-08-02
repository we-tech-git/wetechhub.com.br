# Guia Rápido para Clonar e Rodar o Repositório

Link do repositório:  
https://github.com/we-tech-git/wetechhub.com.br.git

---

## 1. Pré-requisitos

- **Git** instalado  
  ```bash
  git --version
  ```

- **Node.js** instalado  
  ```bash
  node --version
  ```

- **Yarn** instalado  
  ```bash
  yarn --version
  ```


Acesso ao repositório

Público (HTTPS): não exige chave SSH

2. Clonar o repositório
Via HTTPS
```bash
git clone https://github.com/we-tech-git/wetechhub.com.br.git
```

Via SSH
```bash
git clone git@github.com:we-tech-git/wetechhub.com.br.git
```

3. Entrar na pasta e instalar dependências
```bash
cd wetechhub.com.br
yarn install
```
## 4. Inspecionar o README
Abra o arquivo README.md na raiz do projeto e confira:

Variáveis de ambiente em .env.example

Scripts disponíveis em "scripts" do package.json

Requisitos adicionais (Docker, versão do Node, etc.)

## 5. Rodar em modo desenvolvimento
```bash
yarn dev
```

6. Fluxo de trabalho
Criar branch para cada tarefa:

```bash
git checkout -b feature/minha-nova-tarefa
```
Fazer commits pequenos e claros:

```bash
git add .
git commit -m "feat: adiciona componente de cartão"
```
Enviar para o remoto e abrir Pull Request no GitHub:

```bash
git push origin feature/minha-nova-tarefa
```

7. Dicas Finais
Use Node LTS (recomendo nvm para gerenciar versões).

Em caso de erro de dependências:

```bash
rm -rf node_modules yarn.lock
yarn install
```
Consulte sempre o README e as Issues do projeto para detalhes específicos.

# Vue 3 + TypeScript + Vite

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

Learn more about the recommended Project Setup and IDE Support in the [Vue Docs TypeScript Guide](https://vuejs.org/guide/typescript/overview.html#project-setup).
