# 🚀 Azure Cloud & AI Solutions Architect Journey (.NET Edition)

Bu depo (repository), kıdemli bir **.NET Backend Developer** bakış açısıyla **Microsoft Azure** temellerinden başlayarak **AZ-104 (Azure Administrator)** ve **AZ-305 (Azure Solutions Architect Expert)** sertifikasyonlarına hazırlanma ve kurumsal sistemlere **Yapay Zeka (AI / RAG)** entegre etme yolculuğunun uygulamalı mühendislik portfolyosudur.

Her modül; gerçek dünya kurumsal senaryoları baz alınarak **Mimari Dokümanlar / Karar Kayıtları (ADR)**, **Infrastructure as Code (Bicep / Azure CLI)** ve **.NET 8** uygulamaları ile desteklenmektedir.

---

## 🏗️ Genel Yol Haritası ve İlerleme Tablosu (0'dan Zirveye)

| Modül | Odak Konu | Sertifika Kapsamı | Mimari Doküman (ADR) | Kod & Pratik Çıktısı | Durum |
| :--- | :--- | :---: | :---: | :---: | :---: |
| **Week 00** | **Azure Core Fundamentals & Cloud Concepts** | AZ-900 (Temel) | [ADR-000](./week-00-azure-fundamentals/README.md) | Portal + CLI + İlk .NET 8 API | 🟢 Sıradaki Adım |
| **Week 01** | **Governance, IAM & Cost Management** | AZ-104 / AZ-305 | [ADR-001](./week-01-governance-iam/README.md) | Bicep: RBAC, Policy & Budget | ⚪ Planlandı |
| **Week 02** | **Core Networking & Hub-Spoke Topology** | AZ-104 / AZ-305 | [ADR-002](./week-02-vnet-security/README.md) | Bicep: VNet Peering & NSG | ⚪ Planlandı |
| **Week 03** | **L7 Load Balancing & WAF Security** | AZ-104 / AZ-305 | [ADR-003](./week-03-load-balancing/README.md) | App Gateway + .NET Web API | ⚪ Planlandı |
| **Week 04** | **Storage Lifecycle & Secure SAS Access** | AZ-104 | [ADR-004](./week-04-storage-sas/README.md) | .NET Blob Storage & SAS API | ⚪ Planlandı |
| **Week 05** | **Serverless Containers & KEDA Scaling** | AZ-104 / AZ-305 | [ADR-005](./week-05-container-apps/README.md) | Azure Container Apps + Docker | ⚪ Planlandı |
| **Week 06** | **Hybrid Data Architecture (SQL, Cosmos, Redis)** | AZ-305 | [ADR-006](./week-06-data-architecture/README.md) | Multi-Model .NET Data Layer | ⚪ Planlandı |
| **Week 07** | **Business Continuity, HA & Disaster Recovery** | AZ-305 | [ADR-007](./week-07-ha-disaster-recovery/README.md) | Geo-Replication & Backup Vault | ⚪ Planlandı |
| **Week 08** | **Zero-Trust Security & Managed Identities** | AZ-104 / AZ-305 | [ADR-008](./week-08-zero-trust-security/README.md) | Key Vault + Passwordless .NET | ⚪ Planlandı |
| **Week 09** | **Observability, OpenTelemetry & KQL** | AZ-104 / AZ-305 | [ADR-009](./week-09-observability/README.md) | App Insights + KQL Alerts | ⚪ Planlandı |
| **Week 10** | **Event-Driven Microservices (Service Bus)** | AZ-305 | [ADR-010](./week-10-event-driven/README.md) | .NET Pub/Sub + DLQ Pattern | ⚪ Planlandı |
| **Week 11** | **Enterprise System Design Case Studies** | AZ-305 | [ADR-011](./week-11-system-design/README.md) | Kurumsal Mimari Şablonları | ⚪ Planlandı |
| **Week 12** | **Enterprise AI & RAG Capstone Project** | AI / Architect | [ADR-012](./week-12-enterprise-ai-rag/README.md) | .NET 8 + Semantic Kernel + OpenAI | ⚪ Planlandı |

---

## 📁 Depo Klasör Yapısı

```text
azure-architect-dotnet-journey/
├── README.md                        # Ana yol haritası ve ilerleme tablosu
├── week-00-azure-fundamentals/      # Temel bulut kavramları, Portal & CLI başlangıcı
├── week-01-governance-iam/          # Kurumsal yönetişim, RBAC ve FinOps bütçe kurulumu
├── week-02-vnet-security/           # Ağ topolojileri, VNet Peering ve güvenlik duvarları
├── ...
└── week-12-enterprise-ai-rag/       # Uçtan uca Production-Ready AI & .NET Mikroservis
```

---

## 🛠️ Teknoloji Yığını (Tech Stack)
* **Cloud Platform:** Microsoft Azure
* **Infrastructure as Code (IaC):** Azure Bicep, Azure CLI, PowerShell
* **Backend & AI:** .NET 8, C#, Semantic Kernel, Azure OpenAI Service, Azure AI Search
* **Veritabanı & Mesajlaşma:** Azure SQL, Cosmos DB, Redis Cache, Azure Service Bus
* **Konteyner & Orkestrasyon:** Docker, Azure Container Apps (ACA)

---

## 💰 FinOps ve Maliyet Kontrol Prensibi
Bu depodaki tüm laboratuvar çalışmaları **Azure Well-Architected Framework (Cost Optimization)** prensiplerine uygun olarak tasarlanmıştır. Her modül, fatura sürprizlerini önlemek amacıyla ücretsiz katman (Free Tier) alternatiflerini, otomatik bütçe alarmlarını ve tek komutla kaynak temizleme (`cleanup.sh`) adımlarını içerir.
