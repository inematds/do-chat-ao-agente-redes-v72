# CLAUDE.md — do-chat-ao-agente-redes-v72

Curso no formato INEMA Learning v7.2 (skill `formato-curso-v72`): aprofundamento do degrau 4 (redes no automático) da formação Do chat ao agente. Visão geral: https://inematds.github.io/do-chat-ao-agente-v72/

- Conteúdo em `conteudo/pt/` (curso.json + aulas/*.json). Nunca editar o HTML gerado à mão.
- Portão: `python3 gerar.py && python3 validar.py --links` e `node ~/.claude/skills/formato-curso-v72/scripts/conferir-tela.cjs .` (HTTP local, 1366 e 390 px; nunca `file://`).
- Fonte do conteúdo: guias e repos reel7etapas, r7ex, promoavatar, promoavatar3, finviral, saudeviral, advviral e `jornada-agentes/exercicios/04-redes.md`. Não inventar fato, comando nem número além deles.
- Vídeos: só já publicados (release `video-v2.0.0` do jornada-agentes). Imagens: Codex image_gen pela assinatura, luz neutra.
- Autor dos commits: `inematds <inematds@gmail.com>`. Publicação = commit + push (GitHub Pages, raiz da main).
- Motor (`gerar.py`, `validar.py`, `assets/v71.*`, `assets/v72.*`) é cópia da skill; melhoria do formato vai para a skill, não fica só aqui.

## Self-learning

When I correct you, or you catch yourself making a mistake: before continuing, add the lesson as a one-line rule at the TOP of the Lessons section below.

## Lessons

- Marca-texto (anotação) dentro de elemento flex/grid vira item solto e abre espaço no meio da palavra: o texto anotável tem que estar num `span`/`p` próprio (ex.: `.nesta2 li > span`). Bloco anotável novo → conferir o `display` dele (18/10/2026).
- Rolagem guiada no desktop: o texto da etapa fica DENTRO do painel fixo (legenda que troca); cartões rolando por baixo do diagrama aparecem cortados e espiando no topo — o Nei viu na aula 1 (18/10/2026).
- Rolagem guiada: posição de destino calculada com o diagrama JÁ grudado no topo (top do sticky + altura), nunca pela posição atual; e a etapa só vira ativa quando o cartão está visível abaixo do diagrama (18/10/2026).
- Menu do topo de curso segue o padrão v2 (curso | INEMA.CLUB - PRO à esquerda; seções e Aa à direita); não inventar outro topo (18/10/2026).
- Simulação com falha proposital: amarrar a falha à primeira execução da tarefa, não à primeira rodada — senão interromper e retomar esconde a falha (18/10/2026).
- Validar por HTTP local, nunca `file://` (o progresso e os caminhos relativos se comportam diferente) (18/10/2026).
