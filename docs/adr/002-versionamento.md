# ADR 002: Política de versionamento

**Status:** aceita

## Decisão
Adotar versionamento semântico (MAIOR.MENOR.CORREÇÃO).

## O que é mudança maior neste projeto
- Renomear ou remover campo retornado pela API
- Alterar o formato dos arquivos CSV exportados
- Mudar o significado de um parâmetro de endpoint

## Consequências
Quem consome a API sabe, pelo número, se precisa alterar o próprio código.
