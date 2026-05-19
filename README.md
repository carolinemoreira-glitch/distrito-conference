# Distrito Conference — 1º Semestre 2026

Página estática do Distrito Conference para deploy no Vercel.

## Deploy no Vercel (3 formas)

### Opção 1 — Arraste e solte (mais rápido)
1. Acesse [vercel.com](https://vercel.com) e faça login
2. Clique em **"Add New Project"**
3. Arraste a pasta `distrito-conference` direto para a tela
4. Clique em **Deploy** — pronto!

### Opção 2 — Via CLI
```bash
npm i -g vercel
cd distrito-conference
vercel
```

### Opção 3 — Via GitHub
1. Crie um repositório no GitHub e suba esta pasta
2. No Vercel, conecte o repositório
3. O deploy acontece automaticamente a cada push

## Estrutura
```
distrito-conference/
├── index.html      ← página completa (HTML + CSS + JS)
├── vercel.json     ← config do Vercel
└── README.md       ← este arquivo
```

## Atualizar conteúdo
Edite apenas o `index.html` e faça um novo deploy.  
Cada respondente está marcado com comentários `<!-- Card N: Nome -->` para facilitar a substituição.
