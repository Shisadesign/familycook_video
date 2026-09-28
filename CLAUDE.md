# FamilyCook Video — memória do projeto

Este arquivo é a memória persistente do projeto: o Claude lê no início de cada sessão.
Atualize sempre que uma decisão for tomada.

## Contexto
- Projeto: vídeos da marca **FamilyCook** (família cozinhando junta).
- Dono: Shisa Design. Idioma de trabalho: **português (BR)**.
- Geração de mídia: conector **Artlist** (plano AI Suite 180K, renova todo dia 21).
- Branch de trabalho: `claude/creditos-100-uso-yvu5qz`.

## Decisões atuais (setup inicial — ajustar quando o cliente confirmar)
- Formato: vertical **9:16** (Reels/TikTok/Shorts), 1080p.
- Modelo padrão de vídeo: **Veo 3.1 Fast - T2V - Audio** (modelId 1040), cenas de 8s.
- Estilo: cozinha brasileira caseira, luz quente de fim de tarde, câmera na mão suave,
  cores quentes (terracota, verde-oliva, creme), clima afetivo e real — nada de "comercial plastificado".
- Sempre consultar custo (`get_generation_cost`) antes de gerar em lote.

## Estrutura
- `video/brief.md` — briefing e roteiro.
- `video/prompts/` — prompt final de cada cena (um arquivo por cena).
- `video/outputs/log.md` — registro das gerações (id, modelo, custo, link, status).

## Pendências
- Confirmar com o cliente: objetivo do vídeo, duração total, narração/locução, logo e paleta oficiais.
