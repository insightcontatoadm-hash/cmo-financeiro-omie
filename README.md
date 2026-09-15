# CMO Financeiro

Dashboard público modular da CMO, publicado em modo somente leitura.

## Organização

- **Estratégico:** visão geral, liquidez, concentração e riscos;
- **Tático:** DRE gerencial/proxy de caixa, contas a pagar, contas a receber e vencimentos;
- **Operacional:** escopo publicado, classificações agregadas e qualidade;
- **Metodologia:** regras, fórmulas, fontes e limitações.

## Filtros globais

Empresa, natureza, situação e período ficam em uma única janela de **Filtros globais**. O estado em rascunho é separado do estado aplicado; `Aplicar filtros` recalcula todas as visões, enquanto `Descartar`, `ESC` e `X` preservam o recorte atual.

Na versão pública, o período de vencimento é aplicado em granularidade mensal para manter a publicação agregada. O dashboard local protegido permite precisão diária.

## Escopo público

Esta edição apresenta somente agregações por empresa, natureza, situação, mês de vencimento e classificações não identificáveis, derivadas de um snapshot real da API Omie. Não são publicados títulos individuais, nomes de clientes ou fornecedores, documentos, IDs, observações, dados brutos, credenciais ou dados de acesso.

A visão tática de DRE é explicitamente um **proxy gerencial de caixa** baseado em liquidações; não substitui uma DRE contábil por competência.

O painel é um snapshot e não realiza atualização automática em tempo real. O detalhamento operacional permanece no ambiente local protegido.
