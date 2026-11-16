# Andrielly Carrijo — site pessoal

Site estático (HTML, CSS e JS puros), sem dependências e sem etapa de build.

## Estrutura

| Arquivo        | Função                                         |
| -------------- | ---------------------------------------------- |
| `index.html`   | Página principal                               |
| `404.html`     | Página de erro (a Vercel usa automaticamente)  |
| `styles.css`   | Estilos, temas claro/escuro e responsividade   |
| `script.js`    | Botão de tema e animações de rolagem           |
| `favicon.svg`  | Ícone da aba                                   |
| `robots.txt`   | Permite indexação por buscadores               |
| `vercel.json`  | URLs limpas e cabeçalhos de segurança          |

## Ver localmente

Basta abrir `index.html` no navegador.

## Publicar na Vercel

1. Envie estes arquivos para o repositório no GitHub
   (pelo site: **Add file → Upload files**, ou via `git push`).
2. Acesse <https://vercel.com/new> e importe o repositório.
3. Configurações:
   - **Framework Preset:** `Other`
   - **Build Command:** deixe vazio
   - **Output Directory:** deixe vazio (raiz do projeto)
4. Clique em **Deploy**.

A cada novo commit no GitHub, a Vercel republica o site automaticamente.

## Antes de publicar

Procure por `TODO` em `index.html` para adicionar LinkedIn, Lattes e e-mail.
