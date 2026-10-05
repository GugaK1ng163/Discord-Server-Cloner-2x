# Painel: Sensação de Segurança em SP

292 respostas (formulário 3MMD07). Site estático de um arquivo só (`index.html`), sem build e sem dependências: as bibliotecas de gráficos já estão dentro do arquivo.

## Publicar

- **Netlify (mais rápido):** abra https://app.netlify.com/drop e arraste esta pasta (ou o `painel-seguranca-sp.zip`).
- **Vercel:** em https://vercel.com/new, importe o repositório e defina *Root Directory* = `painel-seguranca-sp` (Framework: Other, sem build command). Ou, com a CLI: `cd painel-seguranca-sp && npx vercel --prod`.
- **GitHub Pages / qualquer hospedagem:** envie o `index.html`.

## Uso

Setas do teclado, scroll ou deslizar o dedo trocam de cena. O botão "Números" mostra a tabela de cada cena.

A fonte (Archivo) vem do Google Fonts; sem internet, o painel usa uma fonte condensada do sistema e continua funcionando.
