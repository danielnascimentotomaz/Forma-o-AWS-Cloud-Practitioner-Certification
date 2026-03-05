# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 04/03/2026\
**Empresa:** Abstergo Industries\
**Responsável:** Daniel Nascimento

------------------------------------------------------------------------

## Introdução

Este relatório apresenta o processo de implementação de serviços da AWS
na empresa Abstergo Industries, com foco estratégico na redução imediata
de custos operacionais em infraestrutura de TI, melhoria de eficiência e
aumento da escalabilidade do ambiente tecnológico.

O projeto teve como objetivo selecionar e implementar 3 serviços AWS com
impacto direto na otimização financeira, priorizando redução de
desperdícios, modelo pay-as-you-go e melhor aproveitamento de recursos
computacionais.

------------------------------------------------------------------------

## Descrição do Projeto

A implementação foi dividida em três etapas estratégicas:

------------------------------------------------------------------------

## Etapa 1 -- Amazon EC2 + AWS Compute Savings Plans

### Foco

Otimização de custos com instâncias computacionais.

### Estratégia Aplicada

-   Mapeamento das instâncias em execução.
-   Identificação de workloads previsíveis.
-   Adoção de Savings Plans com compromisso de uso por 1 ano.
-   Rightsizing de instâncias superdimensionadas.

### Caso de Uso

A empresa mantinha servidores ativos 24/7 em modelo On-Demand.\
Com a migração para Savings Plans, foi possível reduzir entre 30% e 50%
dos custos computacionais recorrentes.

------------------------------------------------------------------------

## Etapa 2 -- Amazon S3

### Foco

Redução de custos com armazenamento.

### Estratégia Aplicada

-   Classificação de dados por frequência de acesso.
-   Implementação de Lifecycle Policies.
-   Migração para camadas mais baratas como:
    -   S3 Standard-IA\
    -   S3 Glacier

### Caso de Uso

Arquivos históricos e backups antigos estavam armazenados na camada
padrão (mais cara).\
Com a política de ciclo de vida, os dados passaram automaticamente para
camadas de menor custo.

Redução estimada de até 60% a 80% nos custos de armazenamento de longo
prazo.

------------------------------------------------------------------------

## Etapa 3 -- AWS Auto Scaling

### Foco

Eliminação de desperdício de recursos ociosos.

### Estratégia Aplicada

-   Implementação de grupos de Auto Scaling.
-   Integração com métricas do CloudWatch.
-   Escalabilidade automática baseada em CPU e tráfego.

### Caso de Uso

A aplicação apresentava picos de acesso em horários específicos.\
Antes, os servidores ficavam superdimensionados continuamente.\
Com Auto Scaling: - Recursos aumentam apenas quando necessário. -
Reduzem automaticamente em períodos de baixa demanda.

------------------------------------------------------------------------

## Conclusão

A implementação dos serviços AWS na Abstergo Industries proporcionou:

-   Redução imediata de custos com computação\
-   Otimização inteligente de armazenamento\
-   Eliminação de desperdícios com escalabilidade automática\
-   Maior previsibilidade financeira\
-   Ambiente mais moderno e escalável

Recomenda-se a continuidade da estratégia de FinOps, monitoramento
contínuo via AWS Cost Explorer e revisões periódicas de arquitetura para
manter a eficiência financeira.

------------------------------------------------------------------------

## Anexos

-   Planilha de comparação de custos (Antes x Depois)\
-   Relatório do AWS Cost Explorer\
-   Documentação de arquitetura implementada\
-   Políticas de Lifecycle configuradas

------------------------------------------------------------------------

**Assinatura do Responsável pelo Projeto:**

Daniel Nascimento\
Cloud & Back-End Developer \| AWS Cloud
