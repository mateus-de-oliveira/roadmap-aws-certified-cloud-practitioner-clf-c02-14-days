## Cronograma Intensivo de 2 Semanas (14 dias)

### Visão geral por domínio

- **Domínio 1 – Conceitos de nuvem (24%)** → **3 dias**  
- **Domínio 2 – Segurança e conformidade (30%)** → **4 dias**  
- **Domínio 3 – Tecnologia e serviços da nuvem (34%)** → **5 dias**  
- **Domínio 4 – Cobrança, preços e suporte (12%)** → **2 dias**  

---

### Dias 1–3: Domínio 1 – Conceitos de nuvem

| Dia | Tópico                                                                                               | Atividade                                                                              |
|-----|------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|
| 1   | **Valor da nuvem & Well‑Architected**<br>• Proposta de valor, agilidade, elasticidade<br>• Pilares do WA | Leitura AWS Cloud Value Proposition; vídeo Well‑Architected; flashcards dos pilares    |
| 2   | **Modelos de implantação & migração**<br>• Estratégias (rehost, refactor, rebuild)<br>• Economia de custos | Hands‑on IaC simples (CloudFormation/SAM); comparar TCO on‑prem vs. AWS Calculator     |
| 3   | **Infraestrutura global & revisão**<br>• Regiões, Zonas de Disponibilidade, locais de borda<br>• Quiz Domínio 1 | Mapear serviços distribuídos; simulado de 15 questões e revisão de erros               |

---

### Dias 4–7: Domínio 2 – Segurança e conformidade

| Dia | Tópico                                                                                       | Atividade                                                                                   |
|-----|----------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------|
| 4   | **Responsabilidade compartilhada & IAM**<br>• Modelo Shared Responsibility<br>• Usuário root, políticas, MFA | Whitepaper Shared Responsibility; hands‑on criar usuário IAM, grupos e MFA                 |
| 5   | **Governança & compliance**<br>• AWS Artifact, Config, CloudTrail, Security Hub             | Explorar Artifact; ativar AWS Config rules e CloudTrail                                    |
| 6   | **Recursos de segurança & detecção**<br>• Security Groups, NACLs, WAF, GuardDuty, Inspector | Laboratório: VPC com SG/NACL; ativar GuardDuty e analisar alertas                          |
| 7   | **Criptografia & revisão**<br>• KMS, ACM; em trânsito vs. em repouso<br>• Quiz Domínio 2     | Hands‑on KMS (criar key, criptografar S3); simulado de 20 questões e revisão de flashcards |

---

### Dias 8–12: Domínio 3 – Tecnologia e serviços da nuvem

| Dia | Tópico                                                                                              | Atividade                                                                           |
|-----|-----------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| 8   | **Acesso & IaC**<br>• Console, CLI, SDKs; CloudFormation                                            | Criar stack CF que provisiona EC2 + RDS                                            |
| 9   | **Compute & Contêineres**<br>• EC2, Lambda, Fargate<br>• ECS vs. EKS                                 | Função Lambda simples; deploy container no ECS com ECR                              |
| 10  | **Banco de dados & rede**<br>• RDS/Aurora, DynamoDB, DMS<br>• VPC, sub‑redes, Route 53, VPN        | Criar RDS; tabela DynamoDB; configurar VPC customizada e domínio no Route 53       |
| 11  | **Armazenamento & analytics/ML**<br>• S3 (ciclos), EBS, EFS; Athena, QuickSight, SageMaker          | Hands‑on ciclo de vida S3; explorar QuickSight; iniciar notebook no SageMaker       |
| 12  | **Integração & front‑end/mobile + revisão**<br>• SNS, SQS, EventBridge; Amplify, AppSync, Device Farm | Criar SNS+SQS+EventBridge; app Amplify com GraphQL; simulado de 25 questões Domínio 3 |

---

### Dias 13–14: Domínio 4 – Cobrança, preços e suporte

| Dia | Tópico                                                                                       | Atividade                                                                           |
|-----|----------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------|
| 13  | **Modelos de preços & custos de dados**<br>• Sob demanda, reservados, Spot, Savings Plans<br>• Transferência de dados, classes S3 | Exercício no Pricing Calculator; estimar custos de egress e ciclo de vida S3       |
| 14  | **Gestão de custos, suporte & revisão final**<br>• Budgets, Cost Explorer, Billing Conductor<br>• Planos de suporte, Trusted Advisor | Criar orçamento AWS Budgets; explorar Cost Explorer; simulado completo (50 questões) |

---

#### Dicas para 2‑semanas

- **Estude 3–4 h por dia**, intercalando hands‑on e flashcards.  
- Use **AWS Free Tier** para prática real.  
- Faça **anotações em Anki** para reforçar domínios e serviços.  
- Reserve o final de cada dia para **revisão rápida** do que aprendeu.  
