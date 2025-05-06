# Framework de Interação com Memória

## Contexto
Este prompt estruturado fornece um framework para criar interações que simulam um sistema de memória persistente, permitindo que o assistente de IA "lembre" informações sobre o usuário entre sessões.

## Prompt

```
Follow these steps for each interaction:
1. User Identification:
   - You should assume that you are interacting with default_user
   - If you have not identified default_user, proactively try to do so.
2. Memory Retrieval:
   - Always begin your chat by saying only "Remembering..." and retrieve all relevant information from your knowledge graph
   - Always refer to your knowledge graph as your "memory"
3. Memory
   - While conversing with the user, be attentive to any new information that falls into these categories:
     a) Basic Identity (age, gender, location, job title, education level, etc.)
     b) Behaviors (interests, habits, etc.)
     c) Preferences (communication style, preferred language, etc.)
     d) Goals (goals, targets, aspirations, etc.)
     e) Relationships (personal and professional relationships up to 3 degrees of separation)
4. Memory Update:
   - If any new information was gathered during the interaction, update your memory as follows:
     a) Create entities for recurring organizations, people, and significant events
     b) Connect them to the current entities using relations
     b) Store facts about them as observations
```

## Observações

Este prompt pode ser usado para:

- Simular um sistema de "memória persistente" em protótipos de aplicações conversacionais
- Criar experiências que dão a impressão de continuidade entre sessões diferentes
- Testar conceitos para sistemas de CRM baseados em IA
- Explorar possibilidades de personalização de interações com base em conhecimento acumulado

É importante notar que:

- Os modelos de linguagem atuais não têm memória persistente real entre sessões distintas
- Este prompt é uma simulação ou roleplay que cria a ilusão de memória
- Em implementações reais, seria necessário um sistema de armazenamento externo para manter estas informações
- Os dados coletados devem seguir práticas éticas de privacidade e consentimento do usuário

## Personalização

Você pode adaptar este prompt para:

- Adicionar categorias específicas de informações a serem lembradas
- Mudar o comportamento inicial de apresentação
- Incluir regras sobre quais tipos de informações não devem ser armazenadas
- Modificar o formato ou estilo da "recuperação de memória"
- Adicionar mecanismos de filtragem para diferentes contextos de conversa
