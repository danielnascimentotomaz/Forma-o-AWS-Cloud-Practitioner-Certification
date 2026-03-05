# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

**Data:** 04/03/2026\
**Empresa:** Abstergo Industries\
**Responsável:** Daniel Nascimento

------------------------------------------------------------------------

## Introdução

Este relatório apresenta o processo de implementação de medidas de
segurança em serviços AWS na empresa Abstergo Industries.

O objetivo do projeto foi elencar 3 medidas estratégicas de segurança
utilizando serviços da AWS, com a finalidade de aumentar o nível de
proteção dos dados, reforçar controles de acesso e reduzir riscos
operacionais na infraestrutura em nuvem.

------------------------------------------------------------------------

## Descrição do Projeto

O projeto foi dividido em 3 etapas, cada uma com foco específico em
segurança da informação e governança na nuvem.

------------------------------------------------------------------------

## Etapa 1 -- AWS IAM

### Foco da ferramenta

Controle de acesso e gestão de permissões.

### Descrição de caso de uso

Foi realizada a revisão de usuários, grupos e permissões, aplicando o
princípio do menor privilégio (Least Privilege).

Medidas implementadas: - Criação de grupos com permissões específicas\
- Remoção de acessos administrativos desnecessários\
- Ativação de MFA (Autenticação Multifator)\
- Definição de política de senha forte

Resultado esperado: Redução de riscos de acessos indevidos e maior
controle sobre identidades.

------------------------------------------------------------------------

## Etapa 2 -- AWS CloudTrail

### Foco da ferramenta

Auditoria e rastreabilidade de ações na conta AWS.

### Descrição de caso de uso

Foi ativado o CloudTrail para registrar todas as ações realizadas na
conta, incluindo: - Criação e exclusão de recursos\
- Alterações em políticas\
- Tentativas de login

Os logs foram direcionados para armazenamento seguro no Amazon S3.

Resultado esperado: Maior visibilidade e capacidade de auditoria para
investigações e conformidade.

------------------------------------------------------------------------

## Etapa 3 -- AWS GuardDuty

### Foco da ferramenta

Monitoramento inteligente e detecção de ameaças.

### Descrição de caso de uso

O GuardDuty foi habilitado para identificar: - Atividades suspeitas\
- Tentativas de acesso não autorizado\
- Comunicação com IPs potencialmente maliciosos

A ferramenta utiliza análise comportamental e inteligência de ameaças da
AWS.

Resultado esperado: Identificação proativa de riscos e resposta mais
rápida a incidentes.

------------------------------------------------------------------------

## Conclusão

A implementação das medidas de segurança na Abstergo Industries
proporcionou:

-   Aumento do nível de proteção da conta AWS\
-   Maior controle sobre acessos e permissões\
-   Capacidade de auditoria das ações realizadas\
-   Monitoramento contínuo contra ameaças

Recomenda-se a continuidade do monitoramento, revisões periódicas de
permissões IAM e expansão das práticas de segurança para outros serviços
AWS.

------------------------------------------------------------------------

## Anexos

-   Relatório de usuários e permissões IAM\
-   Logs do CloudTrail\
-   Relatório de achados do GuardDuty\
-   Política de Segurança da Informação atualizada

------------------------------------------------------------------------

**Assinatura do Responsável pelo Projeto:**

Daniel Nascimento\
Cloud & Back-End Developer \| AWS Cloud
