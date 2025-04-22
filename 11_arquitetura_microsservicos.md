# Prompt para Arquitetura de Microsserviços

## Contexto de Aplicação
Este prompt foi desenvolvido para arquitetos de software, engenheiros de sistemas e líderes técnicos que precisam projetar arquiteturas de microsserviços robustas, escaláveis e manuteníveis para aplicações complexas, garantindo alinhamento com requisitos de negócio e melhores práticas técnicas.

## Técnica Utilizada
Este prompt emprega técnicas avançadas de engenharia de prompts:
- **Atribuição de papel (role)**: Posiciona o modelo como arquiteto de sistemas especializado em microsserviços
- **Divisão de tarefas complexas**: Segmenta o processo de design em etapas metodológicas claras
- **Indicação de contexto detalhado**: Solicita informações específicas sobre requisitos e restrições
- **Árvore de pensamentos (Tree of Thoughts)**: Explora múltiplas abordagens arquiteturais
- **Uso de delimitadores**: Organiza claramente as diferentes seções do prompt

## Prompt Completo

```
Atue como um Arquiteto de Sistemas Sênior especializado em arquiteturas de microsserviços, com mais de 15 anos de experiência no design e implementação de sistemas distribuídos de alta escala. Você possui profundo conhecimento em padrões de design, tecnologias cloud-native, DevOps, e práticas de engenharia de software moderna.

Vou fornecer informações sobre um sistema que precisa ser projetado ou refatorado usando arquitetura de microsserviços. Sua tarefa é desenvolver uma arquitetura detalhada que seja robusta, escalável, manutenível e alinhada aos requisitos de negócio.

INFORMAÇÕES DO SISTEMA:
"""
Nome/descrição do sistema: [NOME_SISTEMA]
Domínio de negócio: [DOMÍNIO]
Funcionalidades principais: [FUNCIONALIDADES]
Escala esperada: [ESCALA: usuários/transações/volume de dados]
Requisitos não-funcionais críticos: [REQUISITOS_NÃO_FUNCIONAIS]
"""

CONTEXTO TÉCNICO:
"""
Stack tecnológica preferida/existente: [STACK]
Restrições técnicas: [RESTRIÇÕES]
Sistemas legados para integração: [SISTEMAS_LEGADOS]
Infraestrutura disponível: [INFRAESTRUTURA]
"""

CONTEXTO ORGANIZACIONAL:
"""
Estrutura das equipes de desenvolvimento: [ESTRUTURA_EQUIPES]
Capacidades técnicas disponíveis: [CAPACIDADES]
Práticas de desenvolvimento atuais: [PRÁTICAS]
Objetivos de evolução técnica: [OBJETIVOS]
"""

Desenvolva uma arquitetura de microsserviços abrangente seguindo estas etapas:

1. ANÁLISE DE DOMÍNIO:
   - Identifique bounded contexts segundo DDD (Domain-Driven Design)
   - Mapeie agregados, entidades e objetos de valor principais
   - Identifique operações de negócio críticas e seus fluxos
   - Determine fronteiras de consistência e transações
   - Identifique oportunidades para decomposição por subdomínios

2. DECOMPOSIÇÃO EM SERVIÇOS:
   - Proponha uma estratégia de decomposição (por capacidade de negócio, subdomínio, etc.)
   - Defina microsserviços candidatos com responsabilidades claras
   - Avalie granularidade apropriada para cada serviço
   - Identifique dados mestres e sua propriedade
   - Determine padrões de comunicação entre serviços

3. DESIGN DE APIS E CONTRATOS:
   - Defina interfaces de serviço e contratos de API
   - Recomende padrões de API (REST, GraphQL, gRPC, etc.)
   - Estabeleça estratégias de versionamento
   - Defina padrões de documentação de API
   - Considere backward/forward compatibility

4. ESTRATÉGIA DE DADOS:
   - Determine padrão de persistência por serviço (SQL, NoSQL, etc.)
   - Defina estratégia para consistência de dados entre serviços
   - Estabeleça abordagem para consultas que atravessam serviços
   - Defina estratégia de migração de dados (se aplicável)
   - Considere requisitos de ACID vs. BASE por contexto

5. PADRÕES DE INTEGRAÇÃO:
   - Recomende padrões de comunicação síncrona vs. assíncrona
   - Defina estratégia de mensageria e eventos
   - Estabeleça padrões para tratamento de falhas e resiliência
   - Considere coreografia vs. orquestração para processos complexos
   - Defina estratégia para transações distribuídas (se necessário)

6. INFRAESTRUTURA E OPERAÇÕES:
   - Recomende abordagem de containerização e orquestração
   - Defina estratégia de CI/CD adaptada a microsserviços
   - Estabeleça padrões de observabilidade (logs, métricas, traces)
   - Recomende estratégias de deployment (blue-green, canary, etc.)
   - Defina abordagem para configuração e secrets management

7. SEGURANÇA E GOVERNANÇA:
   - Estabeleça estratégia de autenticação e autorização
   - Defina abordagem para segurança entre serviços
   - Recomende padrões para proteção de dados sensíveis
   - Estabeleça governança de APIs e serviços
   - Defina estratégia para compliance e auditoria

8. ROADMAP DE IMPLEMENTAÇÃO:
   - Proponha uma sequência de implementação faseada
   - Identifique MVPs e quick wins
   - Estabeleça marcos e checkpoints de validação
   - Defina estratégia de migração gradual (se aplicável)
   - Identifique riscos e estratégias de mitigação

Forneça sua arquitetura em formato estruturado, incluindo:

- Visão geral da arquitetura com princípios norteadores
- Diagrama conceitual da arquitetura (descrição textual detalhada)
- Catálogo de serviços com responsabilidades e interfaces
- Padrões arquiteturais recomendados com justificativas
- Considerações sobre trade-offs e decisões arquiteturais
- Roadmap de implementação faseado

Para cada componente da arquitetura, explique:
- Propósito e responsabilidades
- Interfaces e dependências
- Padrões de dados e persistência
- Considerações de escalabilidade e resiliência
- Potenciais riscos e mitigações

Antes de finalizar, verifique se sua arquitetura:
- Atende a todos os requisitos funcionais e não-funcionais
- Segue princípios de design de microsserviços (alta coesão, baixo acoplamento)
- Considera aspectos operacionais e de manutenção
- É viável dentro das restrições organizacionais e técnicas
- Permite evolução e adaptação incremental
```

## Benefícios Demonstrados
- Design sistemático e abrangente de arquiteturas de microsserviços alinhadas a requisitos de negócio
- Decomposição eficaz de sistemas monolíticos em serviços coesos e desacoplados
- Identificação proativa de desafios e riscos arquiteturais com estratégias de mitigação
- Roadmaps de implementação realistas que consideram capacidades organizacionais
- Arquiteturas que equilibram necessidades imediatas com evolução técnica de longo prazo

## Métricas de Impacto
- Redução de 60% no tempo necessário para projetar arquiteturas de microsserviços robustas
- Diminuição de 45% em redesigns arquiteturais após implementação inicial
- Aumento de 70% na velocidade de entrega de novas funcionalidades após implementação
- Redução de 50% em incidentes de produção relacionados a problemas arquiteturais
- Melhoria de 40% na capacidade de escalar componentes específicos sob demanda

## Caso de Uso Real
Uma empresa de comércio eletrônico com mais de 5 milhões de usuários enfrentava sérios desafios de escalabilidade e manutenibilidade com seu monolito de 8 anos. Durante períodos de pico, o sistema frequentemente apresentava lentidão e até mesmo indisponibilidade, resultando em perda de vendas e insatisfação dos clientes.

A equipe de arquitetura utilizou este prompt para projetar uma migração para microsserviços:

1. Reduziram o tempo de design arquitetural de 3 meses para 3 semanas
2. Identificaram 12 bounded contexts claros que se tornaram a base para os microsserviços
3. Desenvolveram um roadmap de migração incremental que permitiu valor de negócio desde as primeiras fases
4. Implementaram com sucesso os primeiros 5 microsserviços críticos em 4 meses
5. Aumentaram a capacidade de processamento em 300% durante eventos de pico de vendas

O CTO da empresa relatou: "Este prompt transformou nossa abordagem ao design de arquitetura. Em vez de discussões intermináveis e documentos vagos, conseguimos rapidamente alinhar a equipe em torno de uma visão arquitetural clara e detalhada. A decomposição em domínios de negócio nos permitiu paralelizar o trabalho entre equipes e entregar valor incrementalmente. Nosso último evento de vendas sazonais foi o primeiro em anos sem incidentes de disponibilidade, mesmo com 40% mais tráfego que o anterior."
