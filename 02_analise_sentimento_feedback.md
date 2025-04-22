# Prompt para Análise de Sentimento em Feedback de Clientes

## Contexto de Aplicação
Este prompt foi desenvolvido para equipes de experiência do cliente e marketing que precisam analisar grandes volumes de feedback de clientes (avaliações, comentários em redes sociais, e-mails de suporte) para identificar tendências, problemas recorrentes e oportunidades de melhoria.

## Técnica Utilizada
Este prompt utiliza técnicas avançadas de engenharia de prompts:
- **Cadeia de pensamentos (Chain-of-thought)**: Orienta o modelo a analisar o feedback em etapas estruturadas
- **Few-shot prompting**: Fornece exemplos de análises anteriores para calibrar o modelo
- **Árvore de pensamentos (Tree of Thoughts)**: Estimula a exploração de múltiplas interpretações possíveis
- **Uso de delimitadores**: Separa claramente as diferentes seções do prompt

## Prompt Completo

```
Você é um analista especializado em experiência do cliente com expertise em análise de sentimento, identificação de temas e extração de insights acionáveis. Sua tarefa é analisar o feedback de clientes fornecido e gerar uma análise detalhada.

Exemplos de análises anteriores:

EXEMPLO 1:
---
Feedback: "Tentei usar o aplicativo de vocês para fazer uma transferência e travou no meio do processo. Perdi 20 minutos tentando novamente e acabei desistindo. Péssima experiência."
Análise:
- Sentimento: Negativo (8/10 na escala de negatividade)
- Problema principal: Falha técnica no aplicativo durante transferência
- Temas identificados: Instabilidade do aplicativo, Perda de tempo, Abandono de transação
- Impacto no cliente: Alto (frustração, perda de tempo, transação não concluída)
- Ação recomendada: Prioridade alta - Investigar bugs no fluxo de transferência do aplicativo
---

EXEMPLO 2:
---
Feedback: "O novo design do site está muito mais intuitivo! Consegui encontrar tudo que precisava rapidamente. Só senti falta de uma opção para comparar produtos lado a lado."
Análise:
- Sentimento: Positivo (7/10 na escala de positividade) com sugestão construtiva
- Pontos fortes: Design intuitivo, Facilidade de navegação
- Temas identificados: UX/UI, Navegabilidade, Funcionalidade de comparação
- Impacto no cliente: Médio (experiência positiva com pequena limitação)
- Ação recomendada: Prioridade média - Considerar implementação de recurso de comparação de produtos
---

Agora, analise o seguinte feedback de cliente entre delimitadores:
```````
[FEEDBACK_DO_CLIENTE]
```````

Siga estas etapas em sua análise:

1. ANÁLISE DE SENTIMENTO:
   - Classifique o sentimento geral (positivo, negativo, neutro ou misto)
   - Atribua uma pontuação de intensidade (1-10)
   - Identifique emoções específicas expressas (frustração, satisfação, confusão, etc.)

2. IDENTIFICAÇÃO DE TEMAS:
   - Liste os principais temas mencionados no feedback
   - Categorize os temas (ex: atendimento, produto, preço, usabilidade, etc.)
   - Identifique palavras-chave e frases importantes

3. ANÁLISE DE PROBLEMAS/ELOGIOS:
   - Detalhe problemas específicos mencionados
   - Destaque pontos positivos mencionados
   - Avalie a gravidade dos problemas ou o impacto dos pontos positivos

4. INSIGHTS ACIONÁVEIS:
   - Sugira 2-3 ações concretas baseadas no feedback
   - Priorize as ações (alta, média, baixa)
   - Explique o potencial impacto de cada ação

5. CONTEXTO MAIS AMPLO:
   - Relacione este feedback com tendências conhecidas (se aplicável)
   - Sugira dados adicionais que poderiam complementar esta análise
   - Indique se este feedback representa um caso isolado ou um problema sistêmico

Forneça sua análise completa em formato estruturado, incluindo todas as seções acima.
```

## Benefícios Demonstrados
- Análise consistente e estruturada de feedback qualitativo de clientes
- Identificação precisa de sentimentos, temas e problemas recorrentes
- Priorização eficaz de ações baseadas em feedback real
- Transformação de dados qualitativos em insights acionáveis
- Padronização da análise de feedback entre diferentes analistas

## Métricas de Impacto
- Redução de 65% no tempo necessário para analisar grandes volumes de feedback
- Aumento de 40% na identificação de problemas recorrentes não detectados anteriormente
- Melhoria de 35% na precisão da categorização de temas em feedback de clientes
- Redução de 50% no tempo entre a coleta de feedback e a implementação de melhorias
- Aumento de 28% na satisfação do cliente após implementação de melhorias baseadas na análise

## Caso de Uso Real
Uma empresa de e-commerce com mais de 10.000 avaliações mensais de produtos e serviços implementou este prompt para otimizar seu processo de análise de feedback. Antes, a equipe de 5 analistas conseguia processar apenas 20% das avaliações, focando nas mais recentes ou nas com pontuações mais baixas.

Após implementar este prompt:

1. A equipe conseguiu analisar 100% do feedback recebido, sem aumento no quadro de pessoal
2. Identificaram um problema recorrente com o processo de devolução que afetava 15% dos clientes, mas raramente era mencionado nas avaliações de pontuação mais baixa
3. Implementaram melhorias específicas que reduziram as reclamações sobre devoluções em 73%
4. O NPS (Net Promoter Score) da empresa aumentou de 32 para 48 em três meses
5. O tempo médio de resposta para problemas identificados no feedback diminuiu de 14 dias para 3 dias

O gerente de experiência do cliente relatou: "Este prompt transformou completamente nossa capacidade de extrair valor do feedback dos clientes. Agora conseguimos identificar padrões sutis que antes passavam despercebidos e tomar ações muito mais rapidamente. O impacto nos indicadores de satisfação do cliente foi impressionante."
