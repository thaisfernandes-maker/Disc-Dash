# FORMA DISC · Deploy na Vercel

## Estrutura
```
forma-disc/
├── public/
│   ├── index.html   → Assessment (link para o time)
│   └── admin.html   → Painel admin (só para você)
└── vercel.json
```

## Deploy em 3 passos

### Opção A — Via GitHub (recomendado)
1. Crie um repositório no GitHub e suba essa pasta
2. Acesse vercel.com → "Add New Project" → conecte o repositório
3. Clique em Deploy — pronto

### Opção B — Via CLI
```bash
npm install -g vercel
cd forma-disc
vercel
```
Segue as instruções no terminal. Na primeira vez vai pedir login.

## URLs após o deploy
- Assessment: `https://seu-projeto.vercel.app/`
- Admin: `https://seu-projeto.vercel.app/admin`

## Compartilhamento
- Link do assessment → manda para os 15 líderes
- Link do admin → só para você
