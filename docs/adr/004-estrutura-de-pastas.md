# ADR 004 - Estrutura de Pastas

## Status
Aceito

## Contexto
O projeto precisava:
- Facilitar manutenção
- Separar responsabilidades
- Permitir escalabilidade futura

Alternativas consideradas:
- Estrutura por tipo (controllers, services, models)
- Estrutura por domínio/feature
- Estrutura híbrida

## Decisão
Foi adotada a estrutura:
- Descrever padrão escolhido

Exemplo simplificado:

src/
  modules/
  shared/
  config/

## Justificativa
- 
- 
- 

## Consequências
Positivas:
- Código mais organizado
- Facilidade para novos desenvolvedores

Negativas:
- Curva de adaptação inicial
