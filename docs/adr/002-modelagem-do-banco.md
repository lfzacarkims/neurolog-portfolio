# ADR 002 - Modelagem do Banco de Dados

## Status
Aceito

## Contexto
O sistema precisa armazenar:
- 
- 
- 

Foi necessário definir:
- Banco relacional ou não relacional
- Normalização vs simplicidade
- Estratégia de integridade dos dados

Alternativas consideradas:
- Banco relacional (ex: PostgreSQL, MySQL)
- Banco NoSQL (ex: MongoDB)

## Decisão
Foi adotado:
- Tipo de banco:
- Estratégia de modelagem:
- Padrões utilizados (ex: 3FN, soft delete, UUID, etc.)

## Justificativa
- 
- 
- 

## Consequências
Positivas:
- Consistência de dados
- Facilidade de consultas

Negativas:
- Complexidade em migrações
- Maior necessidade de planejamento inicial

## Impacto técnico
- Como isso afeta performance?
- Como afeta escalabilidade?
