# FALHAS

| data | o que quebrou | menor correção | prompt \| infra |
|---|---|---|---|
| 2026-10-19 | tradução ES (Codex) trocou nomes de arquivo no texto (canales.md, reglas.md, canales.json, mis-3-videos.md, plan.md; EN plan.md) e o EN adaptou a regra "tu/teu/tua" para "thou" | corrigido no cache `i18n/<lang>.json` + retradução só do cache; conferir nomes de arquivo PT × EN × ES por contagem antes de publicar | prompt |
