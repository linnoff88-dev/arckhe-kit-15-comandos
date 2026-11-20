# Kit 15 Comandos â€” o Claude mudou

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


**Menos instruÃ§Ã£o, menos tokens, mais prova.** Guia grÃ¡tis do INEMA.CLUB com 15 mudanÃ§as no jeito de trabalhar com o
Claude Code (e outros agentes), como implementar cada uma, cuidados, prÃ³ximos kits e o que a comunidade jÃ¡ tem.

- Guia: https://inematds.github.io/kit-15-comandos/guia/ ([EN](https://inematds.github.io/kit-15-comandos/guia/en/) Â· [ES](https://inematds.github.io/kit-15-comandos/guia/es/))
- Kit para baixar: [kit-15-comandos.zip](https://github.com/inematds/kit-15-comandos/releases/download/kit-v1.0.0/kit-15-comandos.zip) Â· pasta [`kit/`](kit/)

## As cinco camadas
1. **Skills** â€” skill menor (sÃ³ correÃ§Ãµes), avaliar com e sem, gravar a tarefa.
2. **Modelo e configuraÃ§Ãµes** â€” trocar de modelo custa cache, esforÃ§o Ã© a alavanca, advisor, padrÃµes melhoraram.
3. **Plano e prova** â€” plano Ã© para o humano, `/goal` com prova, hook de Stop que confere.
4. **Contexto e delegaÃ§Ã£o** â€” janela grande nÃ£o Ã© memÃ³ria, subagente ou fork, workflows de vÃ¡rios agentes.
5. **Rodando sem vocÃª** â€” rotinas por evento, sessÃµes na nuvem.

Comandos conferidos no Claude Code 2.1.303 (out/2026); os que podem variar estÃ£o marcados no guia.

## Estrutura
- `src/{pt,en,es}.json` â€” todo o texto Â· `src/build.py` â€” gera `guia/` Â· `kit/` â€” modelos do kit
- `video/` â€” scripts do explicativo e das imagens

LicenÃ§a MIT Â· [INEMA.CLUB](https://inema.club)

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>