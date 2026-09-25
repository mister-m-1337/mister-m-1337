<div align="center">

# Michael Mendes Mendonça
### Infrastructure Architect · Senior DevSecOps & Cloud Security · Critical Systems Resilience

*Engenharia de infraestrutura, automação de esteiras seguras e garantia de disponibilidade determinística para ambientes de missão crítica.*

[![GitHub](https://img.shields.io/badge/GitHub-mister--m--1337-24292e?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mister-m-1337)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/michael-mendes-ot-security)
[![Email](https://img.shields.io/badge/Email-michaelmmendonca%40gmail.com-24292e?style=for-the-badge&logo=maildotru&logoColor=white)](mailto:michaelmmendonca@gmail.com)
[![Localização](https://img.shields.io/badge/Localiza%C3%A7%C3%A3o-An%C3%A1polis%2FGO%20%C2%B7%20Remoto%20Global-24292e?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## 🏛️ Visão Arquitetural

> **"Protejo o que não pode parar."**  
> *Linhas de produção farmacêutica, saneamento básico e plantas industriais: ambientes onde indisponibilidade ou violação de integridade não geram apenas perdas financeiras, mas impacto operacional severo e risco físico real.*

Atuo na convergência entre **Cibersegurança Industrial (OT/ICS), Engenharia de Infraestrutura/DevSecOps e Validação de Sistemas Computadorizados (CSV/GxP)**. Minha carreira é dedicada à blindagem, resiliência e conformidade de ecossistemas de missão crítica — desde a sustentação e auditoria em ambientes farmacêuticos industriais contínuos até a liderança tática de operações de SOC multicliente de alta complexidade.

Sobre a base determinística do chão de fábrica e data centers, integro arquiteturas modernas de nuvem (AWS/Azure), infraestrutura declarativa (Terraform/OpenTofu) e esteiras CI/CD seguras (Shift-Left), tornando segurança e conformidade atributos verificáveis no código.

---

### Eixos Estratégicos de Especialidade

* **Segurança OT/ICS & SCADA:** Arquitetura de segmentação e zonas/conduítes orientada por **ISA/IEC 62443**, NIST CSF e Purdue Model. Hardening de camadas de controle e PLCs, análise de integridade em protocolos industriais (Modbus, DNP3) e eliminação de superfícies de ataque em linhas de produção.
* **Validação Farmacêutica (CSV / GxP):** Ciclo completo de qualificação de infraestruturas e validação de sistemas computadorizados (QI, QO, QP) em estrita conformidade com **ANVISA (RDC 658/301), GAMP 5 e FDA 21 CFR Part 11**, conectando garantia da qualidade, engenharia e TI.
* **DevSecOps & Resiliência em Nuvem:** Implementação de controles nativos em esteiras de entrega contínua (SAST, SCA, Secret Scanning), governança de identidades e automação de infraestrutura imutável (IaC via Terraform/Ansible) em ambientes híbridos e multi-cloud.
* **Operações de SOC & Resposta a Incidentes:** Operação e governança de centros de defesa cibernética 24/7, mapeamento e correlação de ameaças via **MITRE ATT&CK**, redução contínua de MTTD/MTTR e reporte executivo com foco em risco de negócio.

---

| Princípio | Aplicação Prática |
| :--- | :--- |
| **Zero-Trust** | Nenhum segmento é confiável por padrão; identidade, microsegmentação e overlay cifrado (WireGuard/NetBird) substituem perímetros planos. Serviços administrativos expostos apenas em loopback atrás de proxy reverso autenticado. |
| **Imutabilidade** | Infraestrutura como código versionada, artefatos reprodutíveis e camadas de observabilidade em modo somente-leitura. Mudanças são sempre um novo estado declarado, nunca uma intervenção in-place não rastreada. |
| **Observabilidade Aplicada** | Métricas, telemetria de logs e trilhas de auditoria desacoplados do plano de escrita. A infraestrutura de observabilidade sobrevive à eventual falha do sistema que monitora. |
| **Tolerância a Falhas** | Durabilidade transacional explícita, rotinas de *self-healing* idempotentes e runbooks determinísticos de recuperação contra desastres. |
| **Governança & Risco** | Conformidade tratada como requisito de código (ISA/IEC 62443, GAMP 5, MITRE ATT&CK), com evidências e testes gerados pela própria esteira automatizada. |

---

### 🎯 Atuação & Posicionamento Profissional

Aberto a desafios técnicos e estratégicos em posições de **Arquiteto de Soluções / Infraestrutura, Especialista Sênior em DevSecOps / Cloud Security ou Liderança Técnica de Segurança** em organizações que operam infraestruturas críticas, plataformas digitais de alta escala ou manufatura regulada.

* **Modalidades:** Prestação de Serviços (PJ) ou Posições Corporativas Estratégicas (CLT).
* **Regime:** 100% Remoto ou Híbrido.
* **Contato Direto:** Mensagem direta via LinkedIn ou pelos canais informados no cabeçalho.

---

## 🗺️ Ecossistema de Atuação

```mermaid
graph TD
    subgraph OT_ICS ["Indústria & Infraestruturas Críticas"]
        Purdue["Purdue Model & Purdue Levels"]
        Zonas["ISA/IEC 62443 (Zonas & Conduítes)"]
        CSV["GAMP 5 / Validação Farmacêutica"]
    end

    subgraph Infra_Plataforma ["Infraestrutura & Data Center"]
        Borda["Borda L1/L2/L3 (pfSense, VLANs, Switches)"]
        Virt["Virtualização Bare-Metal (Proxmox VE)"]
        Resiliencia["Disaster Recovery & Backup Determinístico"]
    end

    subgraph Cloud_DevOps ["Cloud & DevSecOps Platform"]
        IaC["Terraform / OpenTofu & Ansible"]
        K8s["Kubernetes & Containers Docker"]
        CICD["CI/CD Hardening (SAST, SCA, Secret Scanning)"]
    end

    subgraph Cyber_Defesa ["Segurança Contínua & Defesa"]
        ZeroTrust["Zero-Trust Mesh (WireGuard / NetBird)"]
        SOC["Engenharia de Detecção & MITRE ATT&CK"]
        Telemetria["Observabilidade (Prometheus, Grafana, KQL)"]
    end

    OT_ICS --> Borda
    Borda --> Infra_Plataforma
    Infra_Plataforma --> Cloud_DevOps
    Cloud_DevOps --> Cyber_Defesa
```

---

## 🛠️ Stack Tecnológica & Domínios

**Cloud & Containers**<br>
![AWS](https://img.shields.io/badge/AWS-1e293b?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-1e293b?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-1e293b?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-1e293b?style=for-the-badge&logo=docker&logoColor=white)

**IaC & Automação**<br>
![Terraform](https://img.shields.io/badge/Terraform-1e293b?style=for-the-badge&logo=terraform&logoColor=white)
![OpenTofu](https://img.shields.io/badge/OpenTofu-1e293b?style=for-the-badge&logo=opentofu&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-1e293b?style=for-the-badge&logo=ansible&logoColor=white)
![Python](https://img.shields.io/badge/Python-1e293b?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-1e293b?style=for-the-badge&logo=gnubash&logoColor=white)

**Redes & Borda**<br>
![pfSense](https://img.shields.io/badge/pfSense-24292e?style=for-the-badge&logo=pfsense&logoColor=white)
![Fortinet](https://img.shields.io/badge/Fortinet-24292e?style=for-the-badge&logo=fortinet&logoColor=white)
![WireGuard](https://img.shields.io/badge/WireGuard-24292e?style=for-the-badge&logo=wireguard&logoColor=white)
![NetBird](https://img.shields.io/badge/NetBird-24292e?style=for-the-badge)
![VLANs](https://img.shields.io/badge/L2%2FL3%20%C2%B7%20VLANs%20802.1Q-24292e?style=for-the-badge)

**Cibersegurança & SOC**<br>
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-1e293b?style=for-the-badge)
![SIEM/SOAR](https://img.shields.io/badge/SIEM%20%2F%20SOAR-1e293b?style=for-the-badge)
![Burp Suite](https://img.shields.io/badge/Burp%20Suite-1e293b?style=for-the-badge&logo=burpsuite&logoColor=white)
![Nessus](https://img.shields.io/badge/Nessus-1e293b?style=for-the-badge)
![SAST/SCA](https://img.shields.io/badge/SAST%20%2F%20SCA-1e293b?style=for-the-badge)

**OT / ICS Crítico**<br>
![ISA/IEC 62443](https://img.shields.io/badge/ISA%2FIEC%2062443-24292e?style=for-the-badge)
![Modbus](https://img.shields.io/badge/Modbus-24292e?style=for-the-badge)
![DNP3](https://img.shields.io/badge/DNP3-24292e?style=for-the-badge)
![SCADA](https://img.shields.io/badge/SCADA-24292e?style=for-the-badge)
![GAMP 5](https://img.shields.io/badge/GAMP%205-24292e?style=for-the-badge)

**Virtualização & Métricas**<br>
![Proxmox](https://img.shields.io/badge/Proxmox%20VE-1e293b?style=for-the-badge&logo=proxmox&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-1e293b?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-1e293b?style=for-the-badge&logo=grafana&logoColor=white)
![KQL](https://img.shields.io/badge/KQL%20%2F%20Azure%20Monitor-1e293b?style=for-the-badge&logo=microsoftazure&logoColor=white)

| Domínio | Ferramentas & Tecnologias | Escopo de Atuação |
| :--- | :--- | :--- |
| **Cloud & Containers** | `AWS` `Azure` `Kubernetes` `Docker` | Landing zones, governança IAM (least privilege), policies de admissão e orquestração de containers distribuídos. |
| **IaC & Automação** | `Terraform` `OpenTofu` `Ansible` `Python` `Bash` | Módulos reutilizáveis, state remoto centralizado com lock, prevenção de drift e runbooks automatizados. |
| **Redes & Borda** | `pfSense` `Fortinet` `WireGuard` `NetBird` `VLANs` | Topologias L2/L3 corporativas, segmentação 802.1Q, firewalls NGFW, Outbound NAT e redes mesh criptografadas. |
| **Cibersegurança & SOC** | `MITRE ATT&CK` `SIEM/SOAR` `Burp Suite` `Nessus` | Threat intelligence, caça a ameaças (threat hunting), engenharia de detecção e contenção de incidentes. |
| **OT / ICS Crítico** | `ISA/IEC 62443` `Modbus` `DNP3` `SCADA` `GAMP 5` | Hardening de ativos operacionais, mitigação de protocolos industriais e qualificação de sistemas críticos (CSV). |
| **Virtualização & Métricas** | `Proxmox VE` `Prometheus` `Grafana` `KQL` | Clusters bare-metal, storage redundante, painéis de camada 7 e telemetria avançada de logs. |

---

## 🚀 Projetos Arquiteturais em Destaque

### 1. BACKUP-CENTRAL — Resiliência & Disaster Recovery para Proxmox
*Ecossistema autônomo de proteção e backup determinístico de máquinas virtuais e containers, desenhado para tolerar falhas de processo e manter integridade absoluta do catálogo de auditoria.*

* **Hardening Transacional em SQLite:** Implementação do motor de dados sob `PRAGMA journal_mode=WAL` e `PRAGMA synchronous=FULL`, prevenindo lockings concorrentes e corrupção em cenários de corte abrupto de energia.
* **Autonomia e Self-Healing:** Rotina de startup que identifica artefatos `.partial`, descarta os arquivos inconsistentes e reprocessa de forma idempotente apenas os jobs interrompidos, sem reexecutar o ciclo completo.
* **Observabilidade Desacoplada e Imutável:** Interface Datasette configurada com a diretiva `--immutable` apontando para snapshots somente-leitura, eliminando bloqueios contra o writer primário do sistema.
* **Segurança de Borda em Loopback:** Painel administrativo isolado na interface local `127.0.0.1`, publicado por proxy reverso Nginx com autenticação e headers defensivos (`Content-Security-Policy`, `X-Frame-Options`, `X-Content-Type-Options`).
* **Telemetria de SLOs:** Exportação de métricas para Prometheus e Grafana para acompanhamento em tempo real de RPO, tempos de execução e volume de dados.

```mermaid
sequenceDiagram
    autonumber
    participant PVE as Proxmox (vzdump)
    participant Core as BACKUP-CENTRAL Engine
    participant DB as SQLite (WAL + FULL)
    participant Storage as Storage de Backup
    participant Nginx as Nginx (Reverse Proxy)
    participant Obs as Datasette (--immutable)

    Core->>PVE: Dispara rotina de backup por job
    PVE->>Storage: Streaming de dados do dump
    Core->>DB: Registro transacional do job
    Note over Core,Storage: Falha de I/O ou processo interrompido
    Core->>Storage: Identifica e descarta artefatos .partial
    Core->>PVE: Reprocessa apenas os jobs interrompidos (idempotente)
    Nginx->>Obs: Acesso via Loopback 127.0.0.1 + Basic Auth
    Obs-->>DB: Leitura desacoplada (Read-Only)
```

---

### 2. Auditoria de Borda & Otimização L1/L2 — Enterprise Network Infrastructure
*Diagnóstico determinístico e reengenharia arquitetural na borda corporativa, eliminando saturação de tráfego, tempestades de broadcast e anomalias de Camada 2.*

```text
  CENÁRIO ANTES (Saturação L2)                  CENÁRIO DEPOIS (Arquitetural Correto)
  ─────────────────────────────                 ─────────────────────────────────────
  [Link WAN]                                    [Link WAN]
       │                                             │
  [Firewall Appliance]                          [Firewall Appliance]
  └── bridge0 (Software Bridge)                      ├── Interface Trunk (802.1Q)
       ├── Porta igb1 ──[Switch A]                   │     ├── VLAN 10 (Gestão & Borda)
       ├── Porta igb2 ──[Switch B]                   │     ├── VLAN 20 (Servidores & BD)
       └── Porta igb3 ──[Switch C]                   │     └── VLAN 30 (Estações de Trabalho)
             ↑ Loop L2 / MAC Flapping                │
             ↑ CPU em 100% (Interrupt Storms)   [Switch Core L2/L3 Dedicado]
             ↑ Autonegociação em 100baseTX           ├── 1000baseT Full-Duplex Verificado
             ↑ NAT Automático sem Governança         └── Outbound NAT Determinístico
```

* **Desconstrução de Software Bridge:** Remoção da carga de comutação L2 da CPU do firewall, delegando a camada de broadcast e forwarding para hardware dedicado (Switches Core), sanando eventos severos de *MAC flapping*.
* **Saneamento L1/L2:** Correção determinística de auto-negociações degradadas (forçando e validando enlaces a **1000baseT Full-Duplex** sem descarte de quadros).
* **Estabilização de Estados:** Governança das tabelas de estado (State Tables) e substituição de NAT automático por regras explícitas de Outbound NAT por segmento.

---

### 3. Pipeline Hardening & Software Supply Chain Defense
*Arquitetura de esteira CI/CD segura orientada a mitigar vetores complexos de evasão de código e comprometimento de estações de trabalho de engenharia.*

```mermaid
flowchart LR
    Dev[Desenvolvedor / DevContainer] -->|Git Commit| Repo[Repositório Git]

    subgraph CI_Pipeline ["Esteira Segura (CI/CD Gates)"]
        Repo --> SAST[SAST Code Scanner]
        Repo --> SCA[SCA Dependency Audit]
        SAST & SCA --> Gate{Security Gate}
        Gate -- Falha Bloqueante --> Alert[Triagem & Alerta SOC]
        Gate -- Aprovado --> Build[Build Imutável de Artefato]
    end

    subgraph Target ["Ambiente Protegido"]
        Build --> K8s[Deploy em Produção / Zero Trust]
    end
```

* **Defesa contra APTs & Supply Chain:** Mitigação de ataques em dependências de segundo nível, identificando código malicioso em pacotes aparentemente benignos — com base em campanhas atribuídas a agentes norte-coreanos na esteira de supply chain e engenharia social (ex.: malware OTTERCOOKIE / campanha *Contagious Interview*).
* **Isolamento de Runtime:** Padronização de desenvolvimento em ambientes isolados (DevContainers), impedindo execução de scripts arbitrários diretamente no host da estação de trabalho.
* **Gates Bloqueantes:** Inclusão de scanners SAST/SCA e Secret Scanning como critérios de reprovação automática na esteira de integração contínua.

---

### 4. Cloud Identity & CI/CD Platform Architecture — Azure & Keycloak
*Engenharia de identidade corporativa, automação de esteiras CI/CD seguras e sustentação de microsserviços em produção no ecossistema Microsoft Azure.*

* **Sustentação de Identidade & Contêineres:** Diagnóstico e resolução de falhas críticas de startup no **Azure Container Apps** hospedando o Keycloak. Mapeamento de regras de rede e firewall (`pg_hba.conf` / "Permitir serviços do Azure") no **Azure Database for PostgreSQL**, sincronização determinística de segredos em runtime (`KC_DB_PASSWORD`) e estabilização de revisões de contêiner.
* **Refatoração de CI/CD com Least Privilege (GitHub Actions):** Pivotagem pragmática de runners locais instáveis para autenticação desacoplada via Service Principal corporativo (`az ad sp create-for-rbac`). Aplicação estrita de RBAC delimitada exclusivamente ao escopo do Resource Group de produção e injeção segura de credenciais via GitHub Secrets em esteiras separadas de backend e frontend.
* **Administração de Identity Provider via Terminal (kcadm):** Mitigação de indisponibilidade da interface gráfica através de injeção direta de comandos no runtime do contêiner (`az containerapp exec`), governança de contexto de assinatura (`az account set`) e provisionamento automatizado de roles administrativas (`manage-users`) para Service Accounts de backend.

```mermaid
flowchart LR
    Dev[Push / Pull Request] --> GH[GitHub Actions CI/CD]

    subgraph Azure_Cloud ["Microsoft Azure (Resource Group de Produção)"]
        SP[Service Principal / RBAC Restrito]
        ACA[Azure Container Apps / Keycloak]
        PG[(Azure Database for PostgreSQL)]

        GH -->|Auth Segura via Secrets| SP
        SP -->|Deploy Automatizado| ACA
        ACA -->|pg_hba & KC_DB_PASSWORD| PG
    end

    subgraph CLI_Hardening ["Governança & Automação Terminal"]
        CLI[Azure CLI / az containerapp exec] -->|kcadm.sh| ACA
        CLI -.->|manage-users Role| BackendClient[Service Account Backend]
    end
```

---

### 5. Hybrid Observability Platform & FinOps Architecture — Azure, Prometheus & Zero-Trust
*Arquitetura de observabilidade híbrida para telemetria de alta densidade em nuvem (App Service Plans multitenant), mitigando custos de ingestão e eliminando taxas de transferência (egress).*

* **Estratégia FinOps & Otimização de Tráfego:** Eliminação de faturas exponenciais de ingestão/retenção no Azure Monitor / Log Analytics através de coleta desacoplada para armazenamento próprio. Tráfego encapsulado via túnel Zero-Trust (NetBird/WireGuard), neutralizando *egress fees* públicas e sobrecarga de agentes na nuvem.
* **Diagnóstico de Confiabilidade & Migração Arquitetural (Push vs. Pull):** Descontinuação de modelo frágil baseado em scripts Bash/Cron e InfluxDB (que gerava falsos positivos e métricas congeladas por `last()` em caso de falha de coleta). Migração para o padrão de mercado **Prometheus (Pull Pattern)**, garantindo detecção instantânea de alvos inoperantes (estado `DOWN`).
* **Tratamento de Latência de API & Métricas Contínuas:** Resolução de retornos nulos causados pela janela de consolidação da Azure Monitor API (offset de 2 minutos). Implantação de coletor especializado em container via registro seguro (Quay.io) e autenticação não-humana (Service Principal RBAC com privilégio de `Reader`).
* **Telemetria Centralizada & Consultas PromQL:** Integração de sondagem direta via endpoint `/probe/metrics/resource` no Prometheus Server on-premises, com consultas dinâmicas no Grafana refletindo a utilização real de CPU e memória sob alta carga.

```mermaid
flowchart LR
    subgraph Azure_Cloud ["Microsoft Azure (Produção)"]
        ASP[App Service Plan / 60+ Apps]
        API[Azure Monitor Metrics API]
        VM_Proxy["Proxy VM (Ubuntu ARM64)"]
        Exporter["Azure Metrics Exporter (Quay.io)"]
        SP[Service Principal / Reader RBAC]

        ASP -->|Métricas Brutas| API
        SP -->|Auth Headless| API
        API -->|Scrape de Métricas| Exporter
        Exporter -.->|Container Runtime| VM_Proxy
    end

    subgraph Overlay_Security ["Malha Cifrada Zero-Trust"]
        Tunnel["NetBird / WireGuard Encrypted Mesh"]
    end

    subgraph Core_Infra ["Data Center On-Premises"]
        Prometheus["Prometheus Server (Pull Mode / 1m)"]
        Grafana["Grafana Dashboards (PromQL)"]

        VM_Proxy --- Tunnel
        Tunnel --- Prometheus
        Prometheus --> Grafana
    end
```

---

## 🎤 Liderança Técnica & Palestras

* **Palestra: "FinOps: Quando seu Pipeline Deploya Dinheiro, Não Só Código"**  
  *Conferência PorteraTech / Hub Goiás*  
  Discussão executiva sobre o impacto financeiro de decisões técnicas em pipelines de entrega contínua. Métodos para introduzir governança de custos em arquiteturas de nuvem (*Policy-as-Code* e alocação via IaC) sem comprometer resiliência, tolerância a falhas ou segurança operacional.

---

<div align="center">

<sub>Arquitetura resiliente não é a ausência de falhas — é a previsibilidade do comportamento quando elas acontecem.</sub>

</div>
