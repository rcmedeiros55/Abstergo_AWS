# 💊 Abstergo Industries – Implementação de Serviços AWS

## 📌 Sobre o Projeto

Este repositório apresenta um projeto de **implementação estratégica de serviços Amazon Web Services (AWS)** para a empresa farmacêutica fictícia **Abstergo Industries**, com foco em **modernização da infraestrutura de TI**, **redução de custos operacionais**, **segurança da informação**, **compliance regulatório** e **automação de processos corporativos**.

O projeto foi desenvolvido em formato de **relatório técnico-acadêmico/profissional**, simulando um cenário real de transformação digital no setor farmacêutico.

---

## 🎯 Objetivo do Projeto

O principal objetivo desta implementação é demonstrar como serviços AWS podem ser utilizados para:

* Reduzir custos com infraestrutura física;
* Melhorar disponibilidade dos sistemas corporativos;
* Garantir armazenamento seguro de dados regulatórios;
* Automatizar processos operacionais;
* Aprimorar monitoramento e governança de TI;
* Fortalecer conformidade com regulamentações do setor farmacêutico.

---

## 🏢 Empresa do Estudo de Caso

**Abstergo Industries** é uma empresa fictícia do setor farmacêutico especializada em:

* Pesquisa clínica;
* Desenvolvimento de medicamentos;
* Produção farmacêutica;
* Distribuição e logística de produtos hospitalares.

Devido ao elevado volume de dados sensíveis e requisitos regulatórios rigorosos, a empresa necessita de uma infraestrutura segura, escalável e economicamente eficiente.

---

## ☁️ Serviços AWS Implementados

### 1. Amazon EC2 (Elastic Compute Cloud)

**Objetivo:** Infraestrutura computacional escalável.

**Caso de uso na empresa:**
Hospedagem de aplicações corporativas críticas:

* ERP farmacêutico;
* Sistema LIMS laboratorial;
* Gestão da cadeia de suprimentos;
* Rastreamento de medicamentos.

**Benefícios:**
✅ Escalabilidade sob demanda
✅ Redução de custos com servidores físicos
✅ Alta disponibilidade operacional

---

### 2. Amazon S3 + Amazon S3 Glacier

**Objetivo:** Armazenamento seguro e retenção de longo prazo.

**Caso de uso na empresa:**

Armazenamento de:

* Dados clínicos;
* Pesquisas laboratoriais;
* Documentação regulatória;
* Certificados de qualidade;
* Backups corporativos.

**Benefícios:**
✅ Baixo custo operacional
✅ Alta durabilidade dos dados
✅ Segurança e rastreabilidade documental

---

### 3. AWS Lambda + Amazon CloudWatch

**Objetivo:** Automação e monitoramento inteligente.

**Caso de uso na empresa:**

* Alertas automáticos;
* Monitoramento de aplicações;
* Backup automatizado;
* Controle de temperatura de medicamentos sensíveis;
* Logs operacionais.

**Benefícios:**
✅ Menor intervenção manual
✅ Redução de falhas humanas
✅ Monitoramento proativo

---

## 🏗️ Arquitetura da Solução

```text
Usuários Internos
        │
        ▼
 Load Balancer (ELB)
        │
        ▼
 Amazon EC2
 (ERP / LIMS)
        │
 ┌──────┴────────┐
 ▼               ▼
Amazon S3     CloudWatch
(Documentos)   (Monitoramento)
        │
        ▼
S3 Glacier
(Arquivamento)
        │
        ▼
AWS Lambda
(Automação)
```

---

## 📑 Documentação do Projeto

O projeto contém documentação técnica complementar:

### 📘 Relatório de Implementação AWS

Documento principal contendo objetivos, justificativas, metodologia e análise da implementação.

### 📗 Manual Operacional AWS

Procedimentos operacionais para administração dos serviços implementados.

### 📙 Documento de Arquitetura da Solução

Descrição técnica da infraestrutura proposta.

### 📕 Plano de Continuidade de Negócios

Estratégias de backup, recuperação e contingência.

### 📊 Planilhas Técnicas

* Estimativa de custos AWS;
* Checklist de compliance e LGPD;
* Inventário de recursos;
* Cronograma de implantação.

---

## 🔒 Segurança e Compliance

O projeto considera práticas de governança e conformidade:

* **LGPD (Lei Geral de Proteção de Dados)**;
* Criptografia de dados em repouso e trânsito;
* Controle de acesso baseado em privilégios mínimos;
* Multi-Factor Authentication (MFA);
* Monitoramento contínuo via CloudWatch;
* Políticas de backup e retenção.

---

## 📈 Benefícios Esperados

| Indicador         | Resultado Esperado             |
| ----------------- | ------------------------------ |
| Redução de custos | Infraestrutura mais econômica  |
| Disponibilidade   | Menor indisponibilidade        |
| Segurança         | Proteção de dados críticos     |
| Escalabilidade    | Crescimento sob demanda        |
| Compliance        | Maior conformidade regulatória |
| Automação         | Redução de tarefas manuais     |

---

## 🚀 Tecnologias Utilizadas

* Amazon EC2
* Amazon S3
* Amazon S3 Glacier
* AWS Lambda
* Amazon CloudWatch
* GitHub
* Markdown

---

## 👨‍💻 Autor

**Rodrigo Carvalho Medeiros**

Projeto desenvolvido para fins **acadêmicos, profissionais e de portfólio**, simulando um cenário real de implementação de infraestrutura cloud em ambiente farmacêutico.

---

## 📄 Licença

Este projeto possui finalidade **educacional e demonstrativa**, podendo ser reutilizado para estudos e aperfeiçoamento profissional.
