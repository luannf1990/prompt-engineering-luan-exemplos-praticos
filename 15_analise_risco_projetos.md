# Prompt para Análise de Risco em Projetos

## Contexto de Aplicação
Este prompt foi desenvolvido para gerentes de projeto, analistas de risco e líderes de negócio que precisam identificar, avaliar e mitigar riscos em projetos complexos, garantindo maior probabilidade de sucesso e minimizando impactos negativos potenciais.

## Técnica Utilizada
Este prompt emprega técnicas avançadas de engenharia de prompts:
- **Atribuição de papel (role)**: Posiciona o modelo como especialista em gerenciamento de riscos
- **Cadeia de pensamentos (Chain-of-thought)**: Guia uma análise sistemática e estruturada dos riscos
- **Indicação de contexto detalhado**: Solicita informações específicas sobre o projeto e seu ambiente
- **Divisão de tarefas complexas**: Segmenta o processo de análise em etapas metodológicas
- **Uso de delimitadores**: Organiza claramente as diferentes seções do prompt

## Prompt Completo

```
Atue como um Especialista em Gerenciamento de Riscos com mais de 20 anos de experiência em análise e mitigação de riscos em projetos complexos. Você possui certificações em gerenciamento de projetos (PMP), gerenciamento de riscos (PMI-RMP) e ampla experiência em diversos setores.

Vou fornecer informações sobre um projeto e seu contexto. Sua tarefa é conduzir uma análise abrangente de riscos, identificando ameaças e oportunidades potenciais, avaliando seus impactos e probabilidades, e desenvolvendo estratégias eficazes de resposta.

INFORMAÇÕES DO PROJETO:
"""
Nome/descrição do projeto: [NOME_PROJETO]
Objetivos principais: [OBJETIVOS]
Escopo e entregáveis: [ESCOPO]
Orçamento estimado: [ORÇAMENTO]
Cronograma previsto: [CRONOGRAMA]
Stakeholders principais: [STAKEHOLDERS]
"""

CONTEXTO ORGANIZACIONAL:
"""
Setor/indústria: [SETOR]
Maturidade em gerenciamento de projetos: [MATURIDADE]
Tolerância a riscos: [TOLERÂNCIA]
Projetos similares anteriores: [PROJETOS_ANTERIORES]
Fatores ambientais relevantes: [FATORES_AMBIENTAIS]
"""

INFORMAÇÕES ADICIONAIS:
"""
Restrições conhecidas: [RESTRIÇÕES]
Premissas estabelecidas: [PREMISSAS]
Dependências críticas: [DEPENDÊNCIAS]
Complexidades específicas: [COMPLEXIDADES]
Riscos já identificados: [RISCOS_CONHECIDOS]
"""

Conduza uma análise abrangente de riscos seguindo estas etapas:

1. IDENTIFICAÇÃO DE RISCOS:
   - Identifique riscos em categorias-chave (técnicos, externos, organizacionais, gerenciais)
   - Considere tanto ameaças (riscos negativos) quanto oportunidades (riscos positivos)
   - Utilize técnicas como análise SWOT, lições aprendidas e brainstorming estruturado
   - Identifique riscos específicos ao setor/indústria do projeto
   - Considere riscos emergentes e tendências relevantes

2. ANÁLISE QUALITATIVA:
   - Avalie cada risco quanto à probabilidade (baixa/média/alta)
   - Determine o impacto potencial em objetivos-chave (escopo, tempo, custo, qualidade)
   - Estabeleça uma matriz de priorização de riscos
   - Identifique gatilhos ou sinais de alerta para cada risco
   - Determine interdependências entre riscos

3. ANÁLISE QUANTITATIVA (QUANDO APLICÁVEL):
   - Sugira abordagens para quantificação de impactos financeiros
   - Recomende técnicas como análise de Monte Carlo para cronograma/orçamento
   - Determine valores esperados monetários para riscos principais
   - Sugira análises de sensibilidade para variáveis-chave
   - Recomende reservas de contingência apropriadas

4. ESTRATÉGIAS DE RESPOSTA:
   - Desenvolva estratégias específicas para riscos prioritários
   - Para ameaças: estratégias de evitar, transferir, mitigar ou aceitar
   - Para oportunidades: estratégias de explorar, compartilhar, melhorar ou aceitar
   - Determine ações específicas, responsáveis e prazos
   - Avalie custo-benefício de cada estratégia de resposta
   - Considere riscos secundários introduzidos pelas respostas

5. MONITORAMENTO E CONTROLE:
   - Estabeleça KRIs (Key Risk Indicators) para riscos prioritários
   - Defina processos de monitoramento e frequência de revisão
   - Sugira ferramentas e técnicas para acompanhamento
   - Estabeleça protocolos de comunicação de riscos
   - Defina processos para riscos emergentes e reavaliação

6. GOVERNANÇA DE RISCOS:
   - Recomende estrutura de governança apropriada
   - Defina papéis e responsabilidades claros
   - Estabeleça processos de escalação
   - Sugira documentação e relatórios necessários
   - Recomende abordagem para lições aprendidas

Forneça sua análise de riscos em formato estruturado, incluindo:

- Resumo executivo com riscos prioritários e estratégia geral
- Registro de riscos detalhado com avaliações e respostas
- Matriz de riscos visual (descrita textualmente)
- Plano de resposta a riscos com ações específicas
- Framework de monitoramento e controle
- Recomendações para melhoria contínua

Para cada risco identificado, inclua:
- Descrição clara e específica (não vaga ou genérica)
- Causa(s) raiz potencial(is)
- Impacto(s) potencial(is) em objetivos específicos
- Probabilidade e impacto avaliados
- Estratégia de resposta recomendada
- Ações específicas, responsáveis e prazos
- Gatilhos ou sinais de alerta
- Métricas para monitoramento

Antes de finalizar, verifique se sua análise:
- Cobre todas as áreas relevantes do projeto
- Considera tanto riscos de curto quanto de longo prazo
- Equilibra ameaças e oportunidades
- Fornece ações concretas e específicas
- Alinha-se à tolerância a riscos da organização
```

## Benefícios Demonstrados
- Identificação sistemática e abrangente de riscos potenciais em projetos complexos
- Priorização eficaz de riscos com base em probabilidade e impacto
- Desenvolvimento de estratégias de resposta personalizadas e eficientes
- Estabelecimento de processos robustos de monitoramento e controle
- Aumento significativo na probabilidade de sucesso do projeto

## Métricas de Impacto
- Redução de 65% no tempo necessário para conduzir análises de risco abrangentes
- Aumento de 40% na identificação de riscos críticos previamente não detectados
- Diminuição de 50% em surpresas negativas durante a execução do projeto
- Redução de 35% em derrapagens de orçamento e cronograma
- Aumento de 45% na confiança dos stakeholders na viabilidade do projeto

## Caso de Uso Real
Uma empresa de construção civil estava prestes a iniciar um projeto complexo de infraestrutura avaliado em R$75 milhões. Projetos anteriores similares haviam enfrentado derrapagens médias de 30% no orçamento e 40% no cronograma, resultando em margens de lucro significativamente reduzidas e insatisfação dos clientes.

A equipe de gerenciamento de projetos utilizou este prompt para conduzir uma análise de riscos abrangente:

1. Identificaram 87 riscos específicos, incluindo 23 que nunca haviam sido considerados em projetos anteriores
2. Desenvolveram estratégias de mitigação detalhadas para os 15 riscos mais críticos
3. Implementaram um sistema de monitoramento proativo com indicadores antecipados
4. Estabeleceram reservas de contingência baseadas em análise quantitativa
5. Criaram um processo de revisão semanal de riscos emergentes

Os resultados foram impressionantes:

1. O projeto foi concluído com apenas 5% de derrapagem no orçamento (versus 30% histórico)
2. O cronograma foi estendido em apenas 8% (versus 40% histórico)
3. A margem de lucro aumentou em 15% em comparação com projetos similares
4. Não houve surpresas significativas durante a execução
5. O cliente expressou alta satisfação com a transparência e gestão proativa

O diretor de operações comentou: "Este prompt transformou completamente nossa abordagem ao gerenciamento de riscos. Antes, nossa análise era superficial e reativa, frequentemente ignorando riscos críticos até que se tornassem problemas. Agora, temos um processo sistemático e abrangente que nos permite antecipar desafios e oportunidades. O impacto em nossos resultados financeiros e na satisfação dos clientes tem sido extraordinário."
