# Caso fictício - secador de cabelo

## Problema
Secador de cabelo que começou a falhar e, depois, pegou fogo quando a consumidora foi usá-lo, danificando o banheiro. A embalagem não identifica fabricante nem importador, e a loja diz que a responsabilidade é só da marca. A consumidora pede uma orientação inicial.

## Como navegar
- entrada/ preserva o relato original (nunca vai para a IA);
- apoio/ contém o caso sanitizado e as únicas fontes permitidas na consulta;
- docs/ define as regras, a especificação e os prompts;
- evidencias/ registra a resposta da IA, a verificação, a auditoria e a revisão humana;
- entrega/ contém a orientação final.

## Ordem do fluxo
1. docs/limites_e_sigilo.md
2. apoio/caso_sanitizado.md, apoio/fonte_1.md (nota fiscal, embalagem e atendimento), apoio/fonte_2.md (CDC, arts. 12, 13 e 27)
3. docs/especificacao.md
4. docs/prompts/consulta_rag.md → evidencias/resposta_inicial.md
5. evidencias/verificacao.md
6. docs/prompts/auditoria.md (em nova conversa) → evidencias/auditoria.md
7. evidencias/revisao_humana.md
8. entrega/orientacao_inicial.md

## Repositório
https://github.com/brunagattei/caso-ficticio.git

## Como executar
Ler docs/prompts/consulta_rag.md e enviar para a IA somente os arquivos de apoio/.