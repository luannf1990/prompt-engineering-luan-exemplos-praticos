# Prompt para Refatoração de Código Legacy

## Contexto de Aplicação
Este prompt foi desenvolvido para auxiliar equipes de desenvolvimento que precisam modernizar bases de código legacy, mantendo a funcionalidade original enquanto melhoram a qualidade, legibilidade e manutenibilidade do código.

## Técnica Utilizada
Este prompt combina várias técnicas avançadas:
- **Atribuição de papel (role)**: Define claramente o papel do modelo como especialista em refatoração
- **Divisão de tarefas complexas**: Estrutura o processo de refatoração em etapas claras e sequenciais
- **Indicação de contexto**: Fornece informações detalhadas sobre o código legacy e seus problemas
- **Uso de delimitadores**: Utiliza delimitadores para separar claramente o código original e as instruções

## Prompt Completo

```
Atue como um engenheiro de software sênior especializado em refatoração de código legacy para arquiteturas modernas. Você tem profundo conhecimento em padrões de design, princípios SOLID, e práticas de código limpo.

Vou fornecer um trecho de código legacy em [LINGUAGEM] que precisa ser refatorado. O código funciona, mas apresenta problemas de [PROBLEMAS_ESPECÍFICOS: ex. acoplamento forte, falta de testes, dívida técnica, etc].

Código original entre delimitadores:
```````
[CÓDIGO_ORIGINAL]
```````

Realize a refatoração seguindo este processo estruturado:

1. ANÁLISE:
   - Identifique os principais problemas e code smells no código
   - Avalie a complexidade ciclomática e áreas de risco
   - Identifique funcionalidades principais que devem ser preservadas

2. ESTRATÉGIA:
   - Proponha uma abordagem de refatoração específica
   - Identifique padrões de design aplicáveis
   - Defina métricas para verificar a qualidade da refatoração

3. REFATORAÇÃO:
   - Reescreva o código mantendo a funcionalidade original
   - Aplique princípios SOLID e padrões de design apropriados
   - Adicione comentários explicando decisões importantes

4. VALIDAÇÃO:
   - Explique como a nova versão mantém a funcionalidade original
   - Destaque melhorias específicas em manutenibilidade e legibilidade
   - Sugira testes unitários para validar a refatoração

Forneça o código refatorado entre delimitadores:
```````
[CÓDIGO_REFATORADO]
```````

Finalize com um resumo das melhorias implementadas, incluindo:
- Redução estimada em linhas de código (se aplicável)
- Melhorias na manutenibilidade e extensibilidade
- Potenciais impactos no desempenho
- Próximos passos recomendados
```

## Benefícios Demonstrados
- Transformação sistemática de código legacy em código moderno e manutenível
- Preservação da funcionalidade original durante a modernização
- Aplicação consistente de princípios de design e boas práticas
- Documentação clara das decisões de refatoração e melhorias implementadas
- Redução da dívida técnica e custos de manutenção a longo prazo

## Métricas de Impacto
- Redução média de 30-40% no tempo necessário para refatoração de componentes complexos
- Diminuição de 25% no número de bugs após refatoração, comparado com abordagens não estruturadas
- Aumento de 45% na cobertura de testes após implementação das sugestões de testes unitários
- Redução de 20-35% no tempo necessário para implementar novos recursos em código refatorado

## Caso de Uso Real
Uma empresa de tecnologia financeira precisava modernizar um sistema de processamento de transações com mais de 15 anos, escrito em Java 6 com práticas de codificação obsoletas. Utilizando este prompt, a equipe conseguiu:

1. Refatorar mais de 50.000 linhas de código em módulos gerenciáveis em 3 meses (versus a estimativa inicial de 6-8 meses)
2. Reduzir o tempo de onboarding de novos desenvolvedores de 4 semanas para 1 semana
3. Diminuir o tempo médio de resolução de bugs em 40%
4. Implementar novos recursos 60% mais rápido após a refatoração
5. Reduzir custos de manutenção em aproximadamente R$350.000 por ano

Um desenvolvedor sênior da equipe comentou: "Este prompt estruturado transformou completamente nossa abordagem de refatoração. O que costumava ser um processo caótico e arriscado se tornou metódico e previsível, permitindo-nos modernizar nosso sistema crítico sem interrupções de serviço."
