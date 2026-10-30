# Convite — Douglas Nogueira 35 anos

Landing page estática do convite de aniversário (07/11, 15h30 às 20h, salão de festas — Rua dos Coqueiros, 709).

- `index.html`: página completa (HTML/CSS/JS, sem build). Música: player oficial do YouTube (Uptown Funk — Mark Ronson ft. Bruno Mars).
- `img/`: cartão e retrato.
- Confirmações: Supabase, projeto `aniversario-douglas-35` (tabela `confirmacoes`, só INSERT — imutável, uma confirmação por convite, prazo 01/11 23h59).
- Aviso no WhatsApp: botão wa.me para 11 97571-3735; campo `notifyWebhook` no CONFIG para ligar um webhook do n8n.

## Deploy na Vercel
Importar o repositório como projeto estático (Framework: Other, sem build command, output = raiz).

## Links pessoais
Abra o site com `?links=1` no final (ex.: `https://SEU-DOMINIO/?links=1`) para ver o link de cada família, com botões de copiar e enviar no WhatsApp.
Quem abre o próprio link (`?c=<id>`) já vê o nome no convite e o próprio cartão de confirmação no topo da lista.
