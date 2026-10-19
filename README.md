# Redes no automático, com fonte na tela — curso (INEMA Learning v7.2)

Curso completo do **degrau 4** da formação [Do chat ao agente](https://inematds.github.io/do-chat-ao-agente-v72/): desenhar o canal do seu nicho com regras, base com fonte, roteiro conferido, agenda e portão antes de publicar.

**Abrir o curso:** https://inematds.github.io/do-chat-ao-agente-redes-v72/

**Other languages / Otros idiomas:** [English](https://inematds.github.io/do-chat-ao-agente-redes-v72/en/) · [Español](https://inematds.github.io/do-chat-ao-agente-redes-v72/es/)

## As 8 aulas

1. A esteira de um canal com fonte na tela
2. O reel em 7 etapas: plano antes da fala (r7e / r7ex)
3. Os 5 do seu nicho e as regras que nunca se quebram
4. A base com fonte: cada número com o trecho literal
5. Roteiro de 60 s com fonte na tela
6. Um assunto, vários públicos: promoavatar e promoavatar3
7. Agenda com portão: o canal roda sozinho, você decide
8. O seu canal, na ordem certa (plano com datas)

Cada aula: objetivo em uma linha, diagrama clicável, texto curto, modelos com botão copiar, prática com "pronto quando" e teste comentado. A prática segue os exercícios de [jornada-agentes/exercicios/04-redes.md](https://github.com/inematds/jornada-agentes/blob/main/exercicios/04-redes.md).

Fontes: [reel7etapas](https://inematds.github.io/reel7etapas/guia/), [r7ex](https://inematds.github.io/r7ex/guia/), [promoavatar](https://inematds.github.io/promoavatar/guia/), [promoavatar3](https://inematds.github.io/promoavatar3/guia/), [finviral](https://inematds.github.io/finviral/guia/), [saudeviral](https://inematds.github.io/saudeviral/guia/) e [advviral](https://inematds.github.io/advviral/guia/).

## Como funciona

| Arquivo | O que é |
|---|---|
| `conteudo/pt/curso.json` | nome, vídeos, página inicial e textos da interface |
| `conteudo/pt/aulas/*.json` | uma aula por arquivo |
| `gerar.py` | monta `index.html` e `aulas/<slug>/index.html` |
| `validar.py` | portão de qualidade (`--links` confere os links externos) |
| `assets/` | CSS, JS, imagens e legendas |

```bash
python3 gerar.py && python3 validar.py --links
```

HTML estático, sem build e sem backend. O progresso fica só no navegador de quem estuda. Vídeos da série *Do chat ao agente* ([jornada-agentes](https://github.com/inematds/jornada-agentes), release `video-v2.0.0`).

Conteúdo aberto e gratuito · [INEMA.CLUB](https://inema.club)

## Mais no INEMA.CLUB

- [Ficha completa deste curso](https://www.inema.club/cursos/327-do-chat-ao-agente-degrau-4-redes-no-automatico-com-fonte-na-tela/)
- [Guia: como aprender inteligência artificial](https://www.inema.club/aprender-inteligencia-artificial/)
- [Todos os cursos](https://www.inema.club/cursos/)
