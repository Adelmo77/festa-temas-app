# PartyThemes Pro

Sistema web simples e pronto para ser publicado no GitHub Pages para empresas de decoração de festas.

## Estrutura do projeto

```text
festa-temas-app/
├── index.html
├── admin.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       ├── data.js
│       ├── app.js
│       └── admin.js
└── .nojekyll
```

## O que já vem pronto

- Catálogo público de temas
- Busca por nome, tags e público
- Filtros por categoria e audiência
- Painel administrativo local
- Cadastro, edição e exclusão de temas
- Exportação e importação de catálogo em JSON
- Botão para WhatsApp
- Layout responsivo

## Como abrir no computador

1. Baixe a pasta do projeto.
2. Extraia o arquivo ZIP.
3. Abra a pasta no VS Code.
4. Clique duas vezes em `index.html` para testar rapidamente.
5. Para trabalhar melhor, instale a extensão **Live Server** no VS Code.
6. Clique com o botão direito em `index.html` e escolha **Open with Live Server**.

## Como publicar no GitHub Pages

1. Crie uma conta no GitHub.
2. Clique em **New repository**.
3. Dê um nome como `partythemes-pro`.
4. Envie todos os arquivos desta pasta para o repositório.
5. No GitHub, vá em **Settings > Pages**.
6. Em **Build and deployment**, escolha **Deploy from a branch**.
7. Em **Branch**, escolha `main` e `/root`.
8. Salve.
9. Aguarde a publicação do site.
10. O link ficará em formato parecido com:

```text
https://seu-usuario.github.io/partythemes-pro/
```

## Como personalizar para vender

- Troque o nome `PartyThemes Pro` pela sua marca.
- Altere as cores em `assets/css/styles.css`.
- Substitua o WhatsApp padrão no `data.js`.
- Cadastre os temas reais pela página `admin.html`.
- Exporte o JSON e mantenha backups.
- Para cada cliente, você pode clonar esse projeto e mudar logo, cores e catálogo.

## O que precisa para virar produto mais forte

Esse projeto é um MVP estático. Para virar SaaS completo para várias empresas, o próximo nível é adicionar:

- Login por usuário
- Banco de dados online
- Upload real de imagens
- Painel multiempresa
- Planos e pagamentos
- Domínio próprio
- LGPD, termos e política de privacidade

## Sugestão de evolução

Fase 1: vender como catálogo profissional personalizado.
Fase 2: integrar Firebase ou Supabase.
Fase 3: criar assinatura mensal para decoradoras.
