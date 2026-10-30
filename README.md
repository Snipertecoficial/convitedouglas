# Convite — Douglas Nogueira 35 anos

Landing page estática do convite de aniversário (07/11, 15h30 às 20h, salão de festas — Rua dos Coqueiros, 709).

- `index.html`: página completa (HTML/CSS/JS, sem build). Trilha instrumental gerada no navegador via Web Audio.
- `img/`: fotos.
- Confirmações: Supabase, projeto `aniversario-douglas-35` (tabela `confirmacoes`, só INSERT — imutável, uma confirmação por convite, prazo 01/11 23h59).
- Aviso no WhatsApp: botão wa.me para 11 97571-3735; campo `notifyWebhook` no CONFIG para ligar um webhook do n8n.

## Deploy na Vercel
Importar o repositório como projeto estático (Framework: Other, sem build command, output = raiz).
