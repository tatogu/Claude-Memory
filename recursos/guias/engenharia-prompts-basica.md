# Guia Básico de Engenharia de Prompts para Claude

**Tipo**: Guia
**Data**: 2025-05-06
**Autor**: Gustavo

## Objetivo

Este guia fornece uma introdução às técnicas básicas de engenharia de prompts para obter respostas mais precisas e úteis do Claude.

## Princípios Fundamentais

### 1. Seja Claro e Específico

Quanto mais específico for seu prompt, melhores serão os resultados. Compare:

**Vago**: "Fale sobre marketing"
**Específico**: "Explique 3 estratégias de marketing digital para uma pequena loja de roupas com orçamento limitado, focando em mídia social e e-mail marketing"

### 2. Forneça Contexto Adequado

O contexto ajuda o Claude a entender o que você precisa. Inclua:
- Seu objetivo
- Público-alvo (se aplicável)
- Nível de detalhe desejado
- Conhecimento prévio que você assume

**Exemplo**:
"Estou preparando uma apresentação para advogados não familiarizados com IA. Preciso explicar como os LLMs funcionam em termos simples, sem jargão técnico excessivo, em uma apresentação de 5 minutos."

### 3. Defina o Formato Desejado

Especifique como você quer que a resposta seja estruturada:

**Exemplo**:
"Responda no formato de uma tabela comparativa com três colunas: 'Estratégia', 'Vantagens' e 'Desvantagens'."

### 4. Use Técnicas Avançadas

#### Chain-of-Thought (Encadeamento de Pensamento)
Peça ao Claude para "pensar passo a passo" em problemas complexos:

"Resolva este problema de probabilidade, pensando passo a passo e explicando seu raciocínio em cada etapa."

#### Role Prompting (Definição de Papéis)
Peça ao Claude para assumir um papel específico:

"Como um especialista em direito marítimo, explique as implicações legais do Artigo X da Convenção Internacional Y."

#### Few-Shot Learning (Aprendizado com Poucos Exemplos)
Forneça exemplos do tipo de resposta que você deseja:

"Traduza estas frases para o francês:
Exemplo 1: 'Hello' → 'Bonjour'
Exemplo 2: 'How are you?' → 'Comment allez-vous?'
Agora traduza: 'I would like to order dinner'"

## Exemplos Práticos

### Para Respostas Criativas:
```
Atue como um romancista especializado em suspense. Crie uma abertura impactante para uma história curta sobre um advogado que descobre um documento secreto em um caso aparentemente simples. 
Use linguagem atmosférica e evite clichês. O texto deve ter aproximadamente 200 palavras.
```

### Para Análise Técnica:
```
Analise os prós e contras de utilizar AWS Lambda versus containers tradicionais para uma aplicação web com tráfego variável. 
Estruture sua resposta em: 
1. Visão geral das tecnologias
2. Comparação de custos
3. Escalabilidade
4. Manutenção
5. Casos de uso ideais
```

## Aplicações

Estas técnicas podem ser aplicadas em diversos contextos:
- Redação de documentos legais
- Criação de conteúdo de marketing
- Análise de problemas técnicos
- Brainstorming de ideias
- Pesquisa e síntese de informações

## Recursos Adicionais

- [Documentação oficial da Anthropic sobre prompts](https://docs.anthropic.com/claude/docs/introduction-to-prompting)
- [Exemplos de prompts eficazes na pasta exemplos](../exemplos/)
- [Guia avançado de engenharia de prompts](./engenharia-prompts-avancada.md) (em desenvolvimento)
