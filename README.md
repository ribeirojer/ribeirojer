# Olá! 👋 Eu sou José Eduardo Ribeiro

**Desenvolvedor Full Stack | TypeScript · React · Next.js · Deno · PostgreSQL**

Bacharel em Ciência e Tecnologia (UNIFESP), moro em Joinville - SC.
Construo produtos de ponta a ponta: frontend, APIs, banco de dados, pagamentos, autenticação e entrega. Criador do **[Flashcards Pro](https://www.flashcardspro.com.br)** — plataforma de venda de decks para Anki com catálogo, checkout, autenticação e entrega digital.

## 🚀 O que construo

- 🧩 Aplicações web full stack (Next.js + TypeScript + Tailwind)
- 🔌 APIs REST e integrações entre serviços (Deno + Oak, Node.js, Elysia)
- 🤖 Aplicações com IA generativa
- 🎮 Jogos multiplayer realtime (engine pura + Supabase Realtime)
- 📊 Sistemas orientados a dados (PostgreSQL + Supabase)
- ⚙️ Arquiteturas com múltiplos serviços, jobs e testes E2E
- 📚 Produtos digitais com pagamento e entrega

## 🛠️ Tecnologias

**Frontend**
`TypeScript` `React` `Next.js` `Tailwind CSS`

**Backend**
`Deno` `Oak` `Node.js` `Elysia` `REST APIs` `Zod` `JWT`

**Banco de dados & realtime**
`PostgreSQL` `Supabase` `Supabase Realtime` `Deno KV`

**Infra & ferramentas**
`Git` `GitHub` `Docker` `Linux` `Deno Deploy` `Vercel`

> Poucos selos, mais prova: cada tecnologia acima tem um repositório abaixo comprovando o uso.

## ⭐ Projetos em destaque

### 🔹 Flashcards Pro — produto real em produção
**Site:** https://www.flashcardspro.com.br (repositório principal é privado)

Partes públicas do ecossistema:

| Repositório | O que demonstra |
|------|---------------|
| [fp-affiliates-service](https://github.com/ribeirojer/fp-affiliates-service) | API de afiliados em Deno + Oak + Supabase: JWT (HMAC-SHA512), validação Zod, cliques/comissões/saques (mín. R$30 PIX), 59 testes, logs estruturados |

> O restante do ecossistema (pedidos, catálogo, E2E) está em repositórios privados.

Arquitetura (simplificada):
```text
Next.js (web)
   ↓
APIs Deno (afiliados, pedidos, catálogo)
   ↓
PostgreSQL (Supabase + RLS)
   +
Mercado Pago (Pix) · Resend (e-mail) · Supabase Storage
```

### 🔹 [bomberman-mvp](https://github.com/ribeirojer/bomberman-mvp) — multiplayer realtime
Clone multiplayer de Bomberman em tempo real para demonstrar full-stack moderno: engine de jogo pura (sem React/DOM), rede host-authority e componentes limpos.
`Next.js 16` `React 19` `TypeScript` `Supabase Realtime` `Tailwind v4` — Demo: https://bomberman-mvp.vercel.app

### 🔹 [CollabAI](https://github.com/ribeirojer/CollabAI) — chat em grupo com IA
Aplicação de hackathon (Adapta): chat em grupo com participação de IA generativa.
`Next.js` `TypeScript` — Demo: https://collab-ai-theta.vercel.app

### 🔹 [Text2Sound](https://github.com/ribeirojer/Text2Sound) — SaaS texto ↔ áudio
SaaS de conversão de texto para áudio e áudio para texto, com integração entre serviços.
`Next.js` `TypeScript` — Demo: https://text2-sound.vercel.app

### 🔹 [analise-vagas-cepat-joinville](https://github.com/ribeirojer/analise-vagas-cepat-joinville) — dados
Código usado para gerar estatísticas a partir de dados públicos.
`TypeScript` `Bun`

## 🔭 Atualmente

- 🚀 Evoluindo o Flashcards Pro (pagamentos, afiliados, entrega)
- 🔌 Construindo APIs tipadas com Deno + Oak + Zod + OpenAPI
- 🗄️ Aprofundando PostgreSQL / Supabase (RLS, modelagem)
- 🧠 Explorando fluxos com IA e automação

## 📫 Contato

- 💼 [LinkedIn](https://www.linkedin.com/in/eduardojer/)
- 🌐 [Flashcards Pro](https://www.flashcardspro.com.br)
- 📧 [eduardojerbr@gmail.com](mailto:eduardojerbr@gmail.com)
- 📷 [Instagram](https://www.instagram.com/eduardojer7/)

<!--
Repo do perfil: ribeirojer/ribeirojer
Fixados sugeridos: fp-affiliates-service, bomberman-mvp, CollabAI, Text2Sound, analise-vagas-cepat-joinville (+ 1 livre — considere republicar binance-proxy)
Bio sugerida: Desenvolvedor Full Stack • TypeScript • React • Next.js • Deno • PostgreSQL
-->
