# Guia de Hospedagem Gratuita

Como o seu projeto é composto apenas por um arquivo HTML (que já inclui o CSS e o JavaScript), ele é considerado um **site estático**. Sites estáticos são os mais fáceis de hospedar na internet, e existem diversas opções excelentes e 100% gratuitas.

Abaixo, apresento as três melhores opções para você publicar o **Analisador de Razão Contábil**.

---

## Opção 1: GitHub Pages (Recomendado)

O GitHub Pages é a opção mais popular para projetos de código aberto e sites estáticos. É gratuito, rápido e muito confiável.

### Passo a passo:

1. **Crie uma conta no GitHub**
   - Acesse [github.com](https://github.com) e crie uma conta gratuita (se ainda não tiver uma).

2. **Crie um novo repositório**
   - Clique no botão `+` no canto superior direito e selecione **"New repository"**.
   - Dê um nome ao repositório (ex: `analisador-razao`).
   - Marque a opção **"Public"** (Público).
   - Clique em **"Create repository"**.

3. **Faça o upload dos arquivos**
   - Na tela do repositório, clique em **"uploading an existing file"** (enviar um arquivo existente).
   - Arraste e solte o arquivo `index.html` (e outros arquivos, se houver) para a área indicada.
   - Clique em **"Commit changes"** (Confirmar alterações) no final da página.

4. **Ative o GitHub Pages**
   - Vá na aba **"Settings"** (Configurações) do seu repositório.
   - No menu lateral esquerdo, clique em **"Pages"**.
   - Na seção "Build and deployment", em "Source", selecione **"Deploy from a branch"**.
   - Em "Branch", mude de `None` para `main` (ou `master`) e clique em **"Save"**.
   - Aguarde 1 a 2 minutos. Atualize a página e você verá uma mensagem verde com o link do seu site (algo como `https://seunome.github.io/analisador-razao/`).

---

## Opção 2: Netlify (Mais fácil de atualizar)

O Netlify é uma plataforma incrível para hospedagem de sites. O processo de "arrastar e soltar" deles é o mais simples do mercado.

### Passo a passo:

1. **Crie uma conta no Netlify**
   - Acesse [netlify.com](https://www.netlify.com) e clique em **"Sign Up"**.
   - Você pode usar seu e-mail ou conta do GitHub/Google.

2. **Faça o upload da pasta**
   - Após fazer login, vá para a aba **"Sites"** no menu lateral.
   - Role a página até o final, onde você verá uma área pontilhada com a mensagem **"Drag and drop your site output folder here"**.
   - **Importante:** Você precisa arrastar a **pasta inteira** (que contém o `index.html`), não apenas o arquivo solto.
   - Solte a pasta nessa área.

3. **Pronto!**
   - O Netlify vai publicar o site instantaneamente e fornecer um link (algo como `https://nome-aleatorio-12345.netlify.app`).

4. **Alterar o nome do link (Opcional)**
   - Clique em **"Site settings"**.
   - Clique em **"Change site name"**.
   - Escolha um nome melhor (ex: `analisador-razao-recofran`) e salve. O link ficará `https://analisador-razao-recofran.netlify.app`.

---

## Opção 3: Vercel (Excelente performance)

A Vercel é outra plataforma moderna e muito rápida, similar ao Netlify.

### Passo a passo:

1. **Crie uma conta na Vercel**
   - Acesse [vercel.com](https://vercel.com) e clique em **"Sign Up"**.

2. **Adicione o projeto**
   - No painel (Dashboard), clique no botão **"Add New..."** e selecione **"Project"**.
   - Você verá uma opção para importar do GitHub, mas também há uma opção para fazer upload direto.
   - Se preferir não usar GitHub, você precisará instalar o CLI (linha de comando) da Vercel, o que é um pouco mais técnico.
   - *Por isso, a Vercel funciona melhor se você já tiver feito o Passo 1 e 2 da opção GitHub.*

3. **Importar do GitHub**
   - Se você colocou seu código no GitHub, basta conectar sua conta do GitHub à Vercel.
   - Clique em **"Import"** ao lado do seu repositório `analisador-razao`.
   - Clique em **"Deploy"**.
   - Em poucos segundos seu site estará no ar!

---

## Resumo e Recomendação

Para o seu caso específico (uma ferramenta para outros usuários acessarem):

1. Se você quer a forma **mais rápida e fácil possível** agora mesmo: Use o **Netlify** (Opção 2) arrastando a pasta.
2. Se você quer algo mais **profissional e fácil de atualizar** no futuro: Use o **GitHub Pages** (Opção 1).

**Dica de Segurança:** Como o seu analisador processa tudo no navegador do usuário (usando a biblioteca PDF.js), nenhum dado financeiro ou contábil dos relatórios é enviado para servidores externos. O site é apenas a "casca" da ferramenta. Isso é excelente para a privacidade e segurança das informações dos seus usuários!
