# CMO Financeiro

Dashboard público modular da CMO, publicado em modo somente leitura.

## Organização

- **Estratégico:** visão geral, liquidez, concentração e riscos;
- **Tático:** contas a pagar, contas a receber, vencimentos, categorias, grupos e ranking de custo por departamento;
- **DRE:** aba dedicada com DRE macro, por departamento, por grupos/categorias e resultado final;
- **Análises prontas:** prioridades, onde está o dinheiro, gaps/gargalos e direção sugerida;
- **Operacional:** escopo publicado, classificações agregadas e qualidade;
- **Metodologia:** regras, fórmulas, fontes e limitações.

## Filtros globais

Empresa, natureza, situação e período ficam em uma única janela de **Filtros globais**. O estado em rascunho é separado do estado aplicado; `Aplicar filtros` recalcula todas as visões, enquanto `Descartar`, `ESC` e `X` preservam o recorte atual.

Na versão pública, o período de vencimento é aplicado em granularidade mensal para manter a publicação agregada. O dashboard local protegido permite precisão diária e filtros adicionais de categoria, grupo, departamento, projeto e conta corrente.

## Escopo público

Esta edição apresenta somente agregações por empresa, natureza, situação, mês de vencimento, categorias/grupos oficiais, projetos e departamentos. Os rótulos são derivados dos cadastros oficiais retornados pelo Omie; quando não há vínculo, o painel sinaliza a ausência.

Não são publicados títulos individuais, nomes de clientes ou fornecedores, documentos, IDs, observações, dados brutos, credenciais ou dados de acesso. Contas correntes não são publicadas por serem identificadores internos.

A DRE é explicitamente um **proxy gerencial de caixa** baseado em liquidações; não substitui uma DRE contábil por competência. As análises prontas distinguem fatos observados de sugestões e não afirmam causas que o snapshot não permite observar.

O painel é um snapshot e não realiza atualização automática em tempo real. O detalhamento operacional permanece no ambiente local protegido.
