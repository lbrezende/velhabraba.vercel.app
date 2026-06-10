# VELHA BRABA 💣👻🧱

Jogo da velha neo-brutalista em pt-BR. Um arquivo HTML, zero dependências, 100% braba.

**Jogar:** [velhabraba.vercel.app](https://velhabraba.vercel.app)

## Modos

- **CLÁSSICO** — vs CPU em 3 dificuldades (MOLEZA, CASCA-GROSSA e IMPOSSÍVEL S.A. com minimax imbatível) ou 2 jogadores local
- **BATATA QUENTE 💣** — os dois jogam X e quem fechar a trinca PERDE (Notakto). Empate impossível. Tem um segredo de teoria dos jogos pra quem descobrir.
- **AMNÉSIA 👻** — só 3 marcas vivas por jogador; a mais antiga some a cada jogada. Nunca dá velha.
- **TIJOLADA 🧱** — gravidade em grade 4x4: escolha a coluna e a peça despenca. Inclui A TORRE, um boss rush de 3 andares.

## Por dentro

- Arquivo único ([velha.html](velha.html)): HTML + CSS + JS vanilla, única dependência externa é o Google Fonts
- Placar, streaks e recordes persistidos em localStorage
- Sons sintetizados via WebAudio, vibração no celular, confete em canvas
- Acessível: botões nativos, aria-live, jogável 100% pelo teclado (1–9), `prefers-reduced-motion`
- Responsivo de 320px a desktop, com suporte a Safari iOS (safe-area, dvh com fallback)

## Rodar localmente

Abra o `velha.html` no navegador. Só isso.
