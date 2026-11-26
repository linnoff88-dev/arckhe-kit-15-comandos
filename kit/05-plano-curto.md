# Plano curto (10 linhas)

O modelo já planeja bem. O plano é para **você** aprovar objetivo, limites e o que conta como pronto.

```
OBJETIVO:   <uma frase: o que existe no fim que nêo existe agora>
PRONTO =    <comando ou verificaçêo objetiva: ./checa.sh passa; a página abre; 3 casos de teste>
NêO PODE:   <o que nêo mexer: banco de produçêo, templates/, e-mail para cliente>
PODE:       <o que pode fazer sozinho: criar arquivos em src/, rodar testes>
PERGUNTE:   <quando parar e perguntar: custo, apagar, publicar>
CONTEXTO:   <onde ler: docs/padrao.md, dados/>
LIMITE:     <tempo ou voltas máximas>
```

## Quando usar
- Cabe num parágrafo? Use só OBJETIVO, PRONTO e NêO PODE.
- Grande, confuso ou mexe em muitos arquivos? Peça: "me entreviste até ter este plano completo e grave em PLANO.md".
  Depois comece a construçêo numa sessêo nova lendo o PLANO.md.
- Quer travar edições até aprovar? Shift+Tab (modo de plano) ou `claude --permission-mode plan`.
