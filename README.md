# Portfólio - Diogo Borges de Moura

Este é o meu portfólio profissional, focado em Análise de Dados e Desenvolvimento de Software.

## 🚀 Como hospedar no Render

Para colocar este site no ar gratuitamente usando o Render, siga estes passos:

1. **GitHub:**
   - Crie um novo repositório no seu GitHub.
   - Faça o upload de todos os arquivos desta pasta para o repositório.
   - Comandos sugeridos:
     ```bash
     git init
     git add .
     git commit -m "Initial commit"
     git branch -M main
     git remote add origin https://github.com/SEU_USUARIO/NOME_DO_REPO.git
     git push -u origin main
     ```

2. **Render:**
   - Acesse [Render.com](https://render.com) e conecte sua conta do GitHub.
   - Clique em **"New +"** > **"Web Service"**.
   - Selecione o repositório deste projeto.
   - **Settings:**
     - **Runtime:** `Node`
     - **Build Command:** `npm install`
     - **Start Command:** `npm start`
   - Clique em **"Deploy Web Service"**.

O Render criará uma URL pública (ex: `meu-site.onrender.com`) e toda vez que você fizer um `git push`, ele atualizará o site automaticamente!
