# Prompt para Debugging Avançado de Código

## Contexto de Aplicação
Este prompt foi desenvolvido para programadores e desenvolvedores que enfrentam bugs complexos e difíceis de rastrear em seus códigos. É especialmente útil para situações onde métodos tradicionais de debugging falharam ou quando se trabalha com bases de código extensas e complexas.

## Técnica Utilizada
Este prompt emprega técnicas avançadas de engenharia de prompts:
- **Cadeia de pensamentos (Chain-of-thought)**: Guia uma análise sistemática e estruturada do problema
- **Árvore de pensamentos (Tree of Thoughts)**: Explora múltiplas hipóteses e caminhos de solução
- **Divisão de tarefas complexas**: Segmenta o processo de debugging em etapas metodológicas
- **Uso de delimitadores**: Separa claramente o código com problema e informações contextuais
- **Meta-prompt**: Inclui instruções sobre como o próprio prompt deve ser interpretado e executado

## Prompt Completo

```
Atue como um Engenheiro de Software Sênior especializado em debugging avançado, com mais de 15 anos de experiência em identificação e resolução de bugs complexos. Você tem profundo conhecimento em arquiteturas de software, padrões de design, e práticas de codificação em múltiplas linguagens de programação.

Vou fornecer um código que contém um ou mais bugs, junto com informações sobre o comportamento esperado vs. atual, ambiente de execução e quaisquer mensagens de erro. Sua tarefa é identificar a causa raiz do problema e propor soluções.

INFORMAÇÕES DO CÓDIGO:
"""
Linguagem: [LINGUAGEM]
Framework/Bibliotecas: [FRAMEWORKS]
Versões relevantes: [VERSÕES]
"""

CONTEXTO DO PROBLEMA:
"""
Comportamento esperado: [COMPORTAMENTO_ESPERADO]
Comportamento atual: [COMPORTAMENTO_ATUAL]
Mensagens de erro (se houver): [ERROS]
Ambiente de execução: [AMBIENTE]
Padrões observados: [PADRÕES]
"""

HISTÓRICO DE DEBUGGING:
"""
Tentativas anteriores: [TENTATIVAS]
Hipóteses já testadas: [HIPÓTESES]
Ferramentas utilizadas: [FERRAMENTAS]
"""

Código com problema entre delimitadores:
```````
[CÓDIGO_PROBLEMÁTICO]
```````

Contexto adicional (outros arquivos relevantes, se necessário):
```````
[CÓDIGO_ADICIONAL]
```````

Conduza uma análise sistemática de debugging seguindo estas etapas:

1. COMPREENSÃO INICIAL:
   - Analise o código e entenda sua funcionalidade pretendida
   - Identifique estruturas, padrões e fluxos de controle principais
   - Relacione o código com o comportamento esperado

2. ANÁLISE DE SINTOMAS:
   - Examine detalhadamente as mensagens de erro ou comportamentos inesperados
   - Identifique padrões ou gatilhos específicos do problema
   - Determine se o bug é consistente ou intermitente
   - Relacione os sintomas com partes específicas do código

3. FORMULAÇÃO DE HIPÓTESES:
   - Desenvolva 3-5 hipóteses plausíveis sobre a causa raiz
   - Priorize as hipóteses com base nos sintomas e no código
   - Para cada hipótese, identifique evidências a favor e contra
   - Considere causas não óbvias e efeitos colaterais

4. ANÁLISE SISTEMÁTICA:
   - Examine o fluxo de dados e controle relacionado a cada hipótese
   - Identifique possíveis condições de borda não tratadas
   - Verifique inconsistências em tipos, formatos ou convenções
   - Analise possíveis problemas de concorrência ou temporização
   - Verifique dependências externas e suas interações

5. DIAGNÓSTICO:
   - Determine a causa raiz mais provável com base na análise
   - Explique como esta causa leva aos sintomas observados
   - Identifique fatores contribuintes ou agravantes
   - Explique por que outras hipóteses são menos prováveis

6. SOLUÇÃO PROPOSTA:
   - Forneça correções específicas para o código
   - Explique como a correção resolve o problema
   - Considere potenciais efeitos colaterais da correção
   - Sugira melhorias adicionais para prevenir problemas similares

7. VERIFICAÇÃO:
   - Proponha testes específicos para validar a correção
   - Sugira casos de teste para verificar condições de borda
   - Recomende ferramentas ou técnicas para confirmar a resolução

Forneça sua análise em formato estruturado, incluindo:

- Diagnóstico detalhado do problema
- Explicação da causa raiz em termos técnicos precisos
- Código corrigido entre delimitadores
- Recomendações para prevenir problemas similares no futuro

Para cada hipótese e solução, inclua:
- Raciocínio técnico detalhado
- Referências a padrões de bug conhecidos quando aplicável
- Considerações sobre trade-offs de diferentes abordagens

Antes de finalizar, verifique se sua solução:
- Resolve completamente o problema descrito
- Não introduz novos problemas ou vulnerabilidades
- Segue as melhores práticas da linguagem/framework em questão
- É a solução mais elegante e eficiente possível
```

## Benefícios Demonstrados
- Identificação sistemática e precisa de bugs complexos e difíceis de rastrear
- Abordagem estruturada que evita tentativa e erro aleatória
- Exploração abrangente de múltiplas hipóteses para garantir que a causa raiz seja encontrada
- Soluções robustas que não apenas corrigem o problema imediato, mas previnem recorrências
- Aprendizado contínuo através da compreensão profunda das causas dos bugs

## Métricas de Impacto
- Redução média de 70% no tempo necessário para resolver bugs complexos
- Diminuição de 85% na recorrência de problemas similares após implementação das soluções
- Aumento de 40% na taxa de primeira resolução (bugs resolvidos na primeira tentativa)
- Redução de 60% no tempo de inatividade causado por bugs em produção
- Economia média de 25-30 horas de desenvolvimento por bug complexo resolvido

## Caso de Uso Real
Uma empresa de tecnologia financeira enfrentava um bug crítico em seu sistema de processamento de transações que ocorria intermitentemente em produção, causando falhas em aproximadamente 0,5% das transações. Após duas semanas de investigação por uma equipe de cinco desenvolvedores, o problema continuava sem solução.

A equipe utilizou este prompt para analisar o problema de forma estruturada:

1. Identificaram a causa raiz em menos de 4 horas: uma condição de corrida em transações concorrentes que só ocorria sob carga específica
2. Implementaram uma solução que eliminou completamente o problema, sem efeitos colaterais
3. Desenvolveram testes automatizados para prevenir regressões
4. Documentaram o padrão do bug para referência futura
5. Aplicaram correções preventivas em cinco outros módulos com padrões similares

O CTO da empresa relatou: "Este prompt transformou nossa abordagem ao debugging. O que normalmente levaria semanas e múltiplas tentativas foi resolvido em horas com uma solução robusta. Além de resolver o problema imediato, ganhamos um entendimento muito mais profundo de nosso código e prevenimos problemas futuros. Estimamos que economizamos mais de R$200.000 em tempo de desenvolvimento e evitamos perdas potenciais de receita."
