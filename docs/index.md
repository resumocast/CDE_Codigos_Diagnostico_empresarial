
## Introdução

O Código de Diagnóstico Empresarial (CDE) é um sistema padronizado revolucionário para identificar, classificar e avaliar padrões nocivos em organizações. Inspirado no Código Internacional de Doenças (CID), o CDE aplica princípios médicos validados ao contexto empresarial, priorizando um diagnóstico preciso antes da intervenção.

## O CDE integra duas metodologias consolidadas para definir categorias de padrões nocivos:

1. [Balanced Scorecard (BSC)](https://pt.wikipedia.org/wiki/Balanced_scorecard): Uma das ferramentas de gestão estratégica mais conhecidas e validadas no mercado, o BSC alinha atividades empresariais à visão organizacional. Ele abrange quatro perspectivas principais: financeira, de clientes, de processos internos e de aprendizado e crescimento.

## Estrutura do Código

Cada código CDE segue o formato

# WW-XXX-YZ


### Componentes do Código

1. WW Categoria (letra + número) - Fixo, não pode ser modificado
2. XX Peso (001-100) - Fixo, pré-estabelecido para cada problema
3. Y Quantidade de critérios atendidos (1-9) - Determinado pelo advisor
4. Z Grau de gravidade (1-5) - Determinado pelo advisor


### Representação Visual

```
 F5 - 090 - 5 3
 │     │     │ │
 │     │     │ └─ (Z) Grau de gravidade (1-5, opinião do advisor)
 │     │     │
 │     │     └─── (Y) Critérios atendidos (1-9, opinião do advisor)
 │     │
 │     └──────── (XXX) Peso na categoria (001-100, fixo)
 │
 └──────────────  (WW) Categoria (letra + número, fixa)
```

{% include_relative codigos.md %}
