# ProduktPix × Zippy Landing

Projeto estático pronto para alojar na Vercel.

## Estrutura
- `index.html`
- `assets/`
- `vercel.json`
- `package.json`
- `.gitignore`

## Opção 1 — Deploy pela Vercel (dashboard)
1. Fazer upload desta pasta para um repositório GitHub
2. Importar o repositório na Vercel
3. Framework preset: `Other`
4. Build command: deixar vazio
5. Output directory: deixar vazio
6. Deploy

## Opção 2 — Deploy com Vercel CLI
```bash
npm i -g vercel
cd zippy-zippy-lp
vercel
vercel --prod
```

## Notas
- Como é uma landing estática, não precisas de Next.js.
- As imagens já são servidas a partir da pasta `assets/`.
- Se quiseres usar um domínio próprio depois, podes ligá-lo no dashboard da Vercel.
