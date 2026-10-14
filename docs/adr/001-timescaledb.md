# ADR 001: Uso do TimescaleDB para leituras dos sensores

**Status:** aceita

## Contexto
O sistema grava milhares de leituras por minuto e consulta por intervalo de tempo.

## Decisão
Armazenar as leituras no TimescaleDB, mantendo o PostgreSQL para os demais dados.

## Consequências
- Consultas por período rápidas e compressão dos dados antigos
- Um único motor SQL (PostgreSQL) para toda a aplicação
- Necessidade de configurar políticas de retenção
