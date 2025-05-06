# Projeto Memory Pessoal

## Visão Geral

Este projeto implementa um sistema de Memory personalizado utilizando uma estrutura de Knowledge Graph para armazenar, relacionar e recuperar informações pessoais críticas. O sistema é especialmente otimizado para complementar meu perfil cognitivo com TDAH, facilitando a organização, o foco em prioridades e a execução de ações alinhadas com meus objetivos financeiros e profissionais.

## Objetivos

1. **Compensar Desafios do TDAH** - Criar um sistema de "memória externa" que minimize os efeitos de desorganização, esquecimento e paralisia por análise
2. **Acelerar Objetivos Financeiros** - Estruturar informações e ações prioritárias para atingir metas de R$15k em 30 dias, escalando para R$300k mensais
3. **Organizar Oportunidades** - Mapear e priorizar caminhos de geração de renda através de marketing de resposta direta e advocacia especializada
4. **Potencializar Rede de Contatos** - Gerenciar relacionamentos profissionais de forma estratégica
5. **Implementar Sistema de Execução** - Estabelecer rotinas de revisão e acompanhamento de progresso

## Metodologia

O projeto utiliza o framework do Knowledge Graph Memory Server para criar:

1. **Entidades** - Representações de pessoas, organizações, habilidades, objetivos, etc.
2. **Relações** - Conexões entre as entidades (ex: "Gustavo" → "tem" → "TDAH")
3. **Observações** - Fatos específicos sobre cada entidade

O sistema é concebido para ser utilizado através de:

- **Consultas Diárias** - Revisão matinal das prioridades (período de maior clareza mental)
- **Entradas Contínuas** - Adição de novos insights, contatos e oportunidades
- **Análise Periódica** - Revisão semanal e mensal de progresso e ajustes de estratégia

## Estrutura do Projeto

```
/memory-pessoal/
  ├── README.md                 # Este documento
  ├── perfil-inicial.md         # Dados iniciais estruturados
  ├── scripts/                  # Scripts para manipulação do Knowledge Graph
  │   ├── criar-entidades.js    # Script para inicializar entidades
  │   ├── criar-relacoes.js     # Script para estabelecer relações
  │   └── consultas.js          # Consultas comuns ao Knowledge Graph
  ├── atualizacoes/             # Registros de atualizações periódicas
  │   ├── diarias/              # Revisões diárias
  │   ├── semanais/             # Análises semanais
  │   └── mensais/              # Avaliações mensais
  └── oportunidades/            # Análises de oportunidades específicas
      ├── marketing-afiliado/   # Documentação sobre marketing de afiliados
      └── advocacia-nicho/      # Documentação sobre nichos jurídicos
```

## Como Utilizar

### Inicialização

1. Revisar e atualizar o arquivo `perfil-inicial.md` com informações atuais
2. Executar o script `criar-entidades.js` para popular o Knowledge Graph
3. Executar o script `criar-relacoes.js` para estabelecer as conexões iniciais

### Uso Diário

1. Manhã: Consultar o sistema para as 3 prioridades do dia usando o prompt de memory
2. Final do dia: Registrar progresso e novos insights
3. Utilizar as consultas pré-configuradas para diferentes contextos:
   - "Quais são as próximas ações para [objetivo específico]?"
   - "Quem na minha rede pode me ajudar com [desafio atual]?"
   - "Quais oportunidades se alinham melhor com minhas habilidades?"

### Revisões Periódicas

- **Diárias**: 5-10 minutos de revisão matinal
- **Semanais**: 30 minutos de análise de progresso (domingos)
- **Mensais**: 1-2 horas de revisão completa e ajustes de estratégia

## Adaptações para TDAH

Este sistema foi especificamente projetado considerando meu perfil de TDAH:

1. **Visual e Estruturado** - Informações organizadas de forma visual e clara
2. **Redução de Sobrecarga Cognitiva** - Armazenamento externo de informações para liberar recursos mentais
3. **Gatilhos de Ação** - Técnicas para superar a inércia inicial e a procrastinação
4. **Hiperfoco Direcionado** - Canalização do hiperfoco para tarefas de alto impacto
5. **Gestão de Transições** - Suporte para períodos de transição entre tarefas
6. **Lembretes Contextuais** - Alertas baseados em contexto, não apenas em tempo

## Métricas de Sucesso

- **Financeiras**: Progresso em direção às metas de R$15k (30 dias) e R$300k (8 meses)
- **Comportamentais**: Redução em tempo perdido com atividades não prioritárias
- **Organizacionais**: Melhoria na execução de tarefas planejadas
- **Relacionais**: Fortalecimento e expansão estratégica da rede profissional

## Próximos Passos

1. Finalizar coleta inicial de dados
2. Implementar scripts de consulta e atualização
3. Estabelecer rotina diária de revisão
4. Documentar detalhadamente duas oportunidades prioritárias
5. Criar dashboards visuais de acompanhamento

## Recursos e Referências

- [Documentação do Knowledge Graph Memory Server](link-para-documentação)
- [Frameworks de Produtividade para TDAH](links-para-recursos)
- [Técnicas de Marketing de Resposta Direta](links-para-recursos)
- [Metodologias de Análise de Oportunidades](links-para-recursos)
