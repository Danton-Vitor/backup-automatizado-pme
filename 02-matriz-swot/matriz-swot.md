# 📊 Matriz SWOT - Projeto Backup Automatizado

A análise da Matriz SWOT permite avaliar o posicionamento estratégico do Projeto CyberVault, mapeando o ambiente interno (Forças e Fraquezas) e o ambiente externo (Oportunidades e Ameaças) no cenário de implantação de segurança para PMEs.

---

### 🗺️ Matriz de Análise Estratégica

| | **Fatores Positivos** | **Fatores Negativos** |
|---|---|---|
| **Ambiente Interno** (Contornável) | **💪 Forças (Forças)**<br>• Uso de criptografia de nível militar (AES-256).<br>• Solução de baixo custo utilizando ferramentas *Open Source*.<br>• Automação total das rotinas (elimina a falha humana).<br>• Armazenamento isolado da rede local (*offsite*). | **⚠️ Fraquezas (Fraquezas)**<br>• Dependência total de conexão estável com a internet.<br>• Tempo elevado para a execução do primeiro backup (carga inicial).<br>• Ausência de uma interface centralizada própria (uso de softwares terceiros). |
| **Ambiente Externo** (Incontrolável) | **🚀 Oportunidades**<br>• Crescimento exponencial de ataques *Ransomware* a pequenas empresas.<br>• Exigências legais de proteção de dados trazidas pela LGPD.<br>• Mercado de PMEs carente de soluções de segurança acessíveis.<br>• Possibilidade de ofertar o projeto como modelo de serviço (SaaS). | **💀 Ameaças**<br>• Mudanças nas políticas de preços e limites de armazenamento dos provedores de nuvem.<br>• Novas variantes de vírus capazes de burlar ou desativar agentes de backup locais.<br>• Resistência cultural dos proprietários em investir em segurança digital. |

---

### 📈 Estratégias de Cruzamento

* **Forças x Oportunidades:** Utilização do baixo custo do software livre combinado com a alta segurança do AES-256 para transportar PMEs que precisam se adequar à LGPD com orçamento limitado.
* **Fraquezas x Ameaças:** Criar políticas de agendamento de backup para a madrugada, minimizando os impactos de oscilações da internet e garantindo que o servidor esteja isolado nos horários de maior pico de ataques externos.
