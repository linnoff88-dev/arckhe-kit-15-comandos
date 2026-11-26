# CLAUDE.md — só ponteiros

> Modelo. O CLAUDE.md nêo guarda o conhecimento: diz onde ele está. O agente lê o arquivo certo só quando precisa.

## Projeto
Loja Exemplo — vendas online e balcêo. Autor dos commits: <nome> <email>.

## Onde está cada coisa (leia só quando a tarefa pedir)
- Tom de voz e marca → `contexto/marca.md`
- Produtos, preços e exceções → `contexto/produtos.md`
- Processo de pedido e devoluçêo → `contexto/processos/pedidos.md`
- Clientes especiais → `contexto/clientes.md`
- Erros já cometidos e a correçêo → `LICOES.md` (uma linha por liçêo)

## Regras que nêo podem falhar
Viram hook, nêo frase aqui (ver `../07-stop-hook/`).

## Trabalho longo
Antes de limpar a conversa, grave `handoffs/ultimo.md` (modelo em `HANDOFF.md`) e retome lendo esse arquivo.
