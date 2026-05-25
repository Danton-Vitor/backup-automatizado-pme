# backup-automatizado-pme

# 🛡️ Projeto de Resiliência Digital: Backup Automatizado e Criptografado em Nuvem contra Ransomware

## 📝 Resumo do Projeto
Este projeto consiste na modelagem, especificação e implementação de um protótipo funcional de backup automatizado e criptografado em nuvem direcionado a Pequenas e Médias Empresas (PMEs). O objetivo principal é mitigar os impactos de ataques de Ransomware e falhas críticas de hardware, garantindo a confidencialidade dos dados através do algoritmo AES-256 e a continuidade do negócio por meio de um Plano de Recuperação de Desastres (DRP). A solução prioriza o uso de ferramentas open-source e armazenamento escalável para garantir viabilidade econômica e técnica.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

### ☁️ Infraestrutura e Armazenamento (Cloud)
*   **AWS S3 (Amazon Web Services) / Google Cloud Storage:** Provedores de nuvem utilizados para o armazenamento de objetos em buckets seguros, com políticas de retenção de dados e controle de acesso (IAM/ACL).

### 🔄 Software de Backup e Sincronização
*   **Duplicati / Rclone:** Ferramentas de código aberto (*Open Source*) utilizadas para mapear os diretórios locais, realizar a compactação, criptografia e automação do upload dos dados.

### 🔐 Segurança e Criptografia
*   **AES-256 (Advanced Encryption Standard):** Algoritmo de criptografia simétrica de nível militar utilizado para cifrar os arquivos localmente antes do tráfego de rede e armazenamento na nuvem.

### 🤖 Automação e Sistema Operacional
*   **Cron (Linux) / Agendador de Tarefas (Windows):** Serviços nativos do sistema operacional de origem utilizados para disparar as rotinas de backup sem intervenção humana.

### 📊 Modelagem e Engenharia de Software
*   **Ferramentas de Design (Draw.io / Lucidchart / Astah):** Utilizadas para a confecção dos diagramas UML (Casos de Uso, Atividades, Sequência, Classes) e processos (BPMN).
*   **Figma / Balsamiq:** Utilizados para a prototipagem das interfaces de gerenciamento e relatórios do sistema.

---

## 📁 Estrutura do Repositório (Organização dos Artefatos)

O repositório está organizado de forma a refletir o ciclo de vida de desenvolvimento do projeto, conforme os requisitos da disciplina de Engenharia de Software III:

*   📂 `01-missao-visao-valores/` -> Definição institucional do projeto.
*   📂 `02-elicitacao-requisitos/` -> Perguntas e respostas com os stakeholders.
*   📂 `03-matriz-swot/` -> Análise de forças, oportunidades, fraquezas e ameaças.
*   📂 `04-matriz-5w2h/` -> Planejamento tático do projeto.
*   📂 `05-bpmn/` -> Modelagem dos processos de negócio (atual e proposto).
*   📂 `06-documento-requisitos/` -> Requisitos Funcionais, Não-Funcionais e Regras de Negócio.
*   📂 `07-eap/` -> Estrutura Analítica do Projeto.
*   📂 `08-tap/` -> Termo de Abertura do Projeto.
*   📂 `09-casos-de-uso/` -> Diagrama e Documentação de Casos de Uso.
*   📂 `10-diagramas-comportamentais/` -> Diagramas de Atividades, Máquina de Estados e Sequência.
*   📂 `11-diagrama-classes/` -> Modelagem estrutural do sistema de gerenciamento.
*   📂 `12-prototipagem-telas/` -> Mockups das interfaces do sistema.
*   📂 `13-matriz-rastreabilidade/` -> Relação entre Requisitos, Regras e Casos de Uso.
*   📂 `14-portabilidade/` -> Documentação de portabilidade do sistema.
*   📂 `15-metricas-custo/` -> Estimativa de custos baseada na estrutura do projeto.
*   📂 `16-proposta-comercial/` -> Documento final de entrega comercial do projeto.
