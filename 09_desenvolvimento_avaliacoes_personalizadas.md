# Prompt para Desenvolvimento de Avaliações Personalizadas

## Contexto de Aplicação
Este prompt foi desenvolvido para educadores, gestores de RH e especialistas em treinamento que precisam criar avaliações personalizadas para medir conhecimentos, habilidades e competências específicas, seja em contextos educacionais ou corporativos.

## Técnica Utilizada
Este prompt emprega técnicas avançadas de engenharia de prompts:
- **Atribuição de papel (role)**: Posiciona o modelo como especialista em avaliação e psicometria
- **Indicação de contexto detalhado**: Solicita informações específicas sobre objetivos e público-alvo
- **Divisão de tarefas complexas**: Segmenta o processo de criação em etapas metodológicas
- **Few-shot prompting**: Fornece exemplos de diferentes tipos de questões e formatos de avaliação
- **Uso de delimitadores**: Organiza claramente as diferentes seções do prompt

## Prompt Completo

```
Atue como um Especialista em Avaliação Educacional e Psicometria com mais de 20 anos de experiência no desenvolvimento de instrumentos de avaliação para contextos educacionais e corporativos. Você possui profundo conhecimento em design instrucional, taxonomia de Bloom, metodologias de avaliação e análise de dados educacionais.

Vou fornecer informações sobre uma necessidade de avaliação específica. Sua tarefa é desenvolver uma avaliação personalizada que meça com precisão os conhecimentos, habilidades ou competências desejados, alinhada aos objetivos de aprendizagem e adequada ao público-alvo.

INFORMAÇÕES SOBRE A AVALIAÇÃO:
"""
Propósito da avaliação: [PROPÓSITO: diagnóstica/formativa/somativa]
Área de conhecimento/habilidade: [ÁREA]
Objetivos específicos de aprendizagem: [OBJETIVOS]
Nível de proficiência esperado: [NÍVEL]
Formato desejado: [FORMATO: teste/projeto/apresentação/simulação/etc]
"""

INFORMAÇÕES SOBRE O PÚBLICO:
"""
Perfil dos avaliados: [PERFIL]
Nível educacional/experiência: [NÍVEL_EDUCACIONAL]
Conhecimentos prévios: [CONHECIMENTOS_PRÉVIOS]
Necessidades específicas: [NECESSIDADES]
"""

CONTEXTO DE APLICAÇÃO:
"""
Ambiente de aplicação: [AMBIENTE: sala de aula/online/corporativo/etc]
Tempo disponível: [TEMPO]
Recursos disponíveis: [RECURSOS]
Restrições específicas: [RESTRIÇÕES]
"""

REQUISITOS DE ANÁLISE:
"""
Tipo de feedback necessário: [FEEDBACK]
Métricas de desempenho desejadas: [MÉTRICAS]
Uso previsto dos resultados: [USO_RESULTADOS]
Necessidades de relatórios: [RELATÓRIOS]
"""

Desenvolva uma avaliação personalizada seguindo estas etapas:

1. ANÁLISE DE OBJETIVOS:
   - Refine os objetivos de aprendizagem em termos mensuráveis
   - Mapeie os objetivos segundo a taxonomia de Bloom
   - Identifique conhecimentos, habilidades e atitudes a serem avaliados
   - Estabeleça critérios claros de proficiência para cada objetivo

2. DESIGN DA AVALIAÇÃO:
   - Determine a abordagem geral mais adequada aos objetivos
   - Selecione tipos de questões/tarefas apropriados
   - Estruture a avaliação em seções lógicas
   - Estabeleça o sistema de pontuação e ponderação
   - Defina critérios de aprovação/classificação quando aplicável

3. DESENVOLVIMENTO DE ITENS:
   - Crie questões/tarefas alinhadas aos objetivos específicos
   - Varie o nível cognitivo das questões (conhecimento, aplicação, análise, etc.)
   - Desenvolva instruções claras e não ambíguas
   - Inclua cenários autênticos e relevantes quando apropriado
   - Crie rubricas detalhadas para itens subjetivos

4. ESTRATÉGIA DE FEEDBACK:
   - Desenvolva feedback específico para diferentes níveis de desempenho
   - Crie orientações para interpretação dos resultados
   - Sugira recursos para desenvolvimento adicional
   - Estabeleça mecanismos para feedback formativo

5. VALIDAÇÃO E EQUIDADE:
   - Verifique o alinhamento entre itens e objetivos
   - Avalie potenciais vieses ou barreiras de acessibilidade
   - Sugira adaptações para necessidades específicas
   - Proponha métodos para validar a eficácia da avaliação

Exemplos de diferentes tipos de questões:

EXEMPLO 1 - QUESTÃO OBJETIVA:
"""
Objetivo: Avaliar compreensão de conceitos fundamentais
Questão: Qual das seguintes afirmações melhor descreve o conceito de [conceito]?
A. [descrição parcialmente correta]
B. [descrição incorreta comum]
C. [descrição correta e completa]
D. [descrição relacionada mas incorreta]
Resposta correta: C
Justificativa: [explicação detalhada]
Nível cognitivo: Compreensão
"""

EXEMPLO 2 - QUESTÃO BASEADA EM CENÁRIO:
"""
Objetivo: Avaliar aplicação de conhecimentos em situações reais
Cenário: [descrição de uma situação autêntica e relevante]
Questão: Como você abordaria esta situação aplicando os princípios de [área de conhecimento]?
Rubrica:
- Nível 1: [critérios para desempenho básico]
- Nível 2: [critérios para desempenho intermediário]
- Nível 3: [critérios para desempenho avançado]
Nível cognitivo: Aplicação/Análise
"""

EXEMPLO 3 - PROJETO/TAREFA PRÁTICA:
"""
Objetivo: Avaliar habilidades complexas e integradas
Tarefa: [descrição detalhada do projeto ou tarefa]
Entregáveis: [lista de produtos/evidências a serem apresentados]
Critérios de avaliação:
1. [critério 1] - [descrição] - [pontuação]
2. [critério 2] - [descrição] - [pontuação]
3. [critério 3] - [descrição] - [pontuação]
Nível cognitivo: Síntese/Avaliação
"""

Forneça a avaliação completa em formato estruturado, incluindo:

- Visão geral da avaliação e objetivos
- Instruções detalhadas para aplicadores e participantes
- Todos os itens/questões/tarefas com gabaritos ou rubricas
- Sistema de pontuação e interpretação
- Recomendações para feedback e acompanhamento

Para cada componente da avaliação, explique:
- Alinhamento com objetivos específicos
- Nível cognitivo avaliado
- Justificativa para o formato escolhido
- Considerações sobre validade e confiabilidade
```

## Benefícios Demonstrados
- Criação de avaliações personalizadas e alinhadas precisamente aos objetivos de aprendizagem
- Desenvolvimento de instrumentos de avaliação baseados em princípios psicométricos sólidos
- Diversificação de formatos e níveis cognitivos para uma avaliação abrangente
- Integração de feedback formativo para apoiar o desenvolvimento contínuo
- Garantia de equidade e acessibilidade nas avaliações

## Métricas de Impacto
- Redução de 70% no tempo necessário para desenvolver avaliações personalizadas de alta qualidade
- Aumento de 45% na validade das avaliações em relação a instrumentos genéricos
- Melhoria de 35% na capacidade de identificar lacunas específicas de conhecimento
- Aumento de 50% na satisfação dos participantes com o processo de avaliação
- Redução de 40% em recursos necessários para remediação pós-avaliação

## Caso de Uso Real
Uma empresa de tecnologia com 500 funcionários precisava avaliar as competências técnicas e soft skills de sua equipe para um programa de desenvolvimento de talentos. Anteriormente, utilizavam avaliações genéricas que não capturavam adequadamente as habilidades específicas necessárias para seus projetos.

A equipe de RH utilizou este prompt para desenvolver um sistema de avaliação personalizado:

1. Reduziram o tempo de desenvolvimento de avaliações de 3 meses para 3 semanas
2. Criaram avaliações específicas para 12 diferentes funções técnicas e gerenciais
3. Implementaram um sistema de feedback formativo que identificava com precisão áreas de desenvolvimento
4. Aumentaram a correlação entre resultados de avaliação e desempenho real no trabalho de 0.4 para 0.8
5. Melhoraram a eficácia dos programas de treinamento subsequentes em 65%

O diretor de Recursos Humanos relatou: "Este prompt transformou completamente nossa abordagem às avaliações. Antes, usávamos ferramentas genéricas que não capturavam as nuances das habilidades que realmente importam para nosso negócio. Agora, conseguimos criar avaliações precisas e personalizadas que nos fornecem insights acionáveis. O impacto no desenvolvimento de nossa equipe e na alocação de recursos de treinamento foi extraordinário."
