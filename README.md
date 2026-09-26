# Awesome-AI-Risk-Management-Platform

# Top AI Risk Management Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Model Risk Management, AI System Inventory, Fairness & Bias Controls, Policy Enforcement & Continuous AI Risk Oversight*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Risk Management**. These systems help organizations inventory AI models and agents, assess risk (bias, performance, security, regulatory), enforce policies, and maintain audit-ready evidence across the AI lifecycle.

**Examples** include Holistic AI, Credo AI, ModelOp, FairNow, Monitaur, IBM watsonx.governance, Trustible, CalypsoAI, TruEra, and Protect AI (the category leaders).

**Open-source emphasis**: Full enterprise AI risk platforms are mostly commercial. Open building blocks include **model cards**, **AegisAI**-style GRC tools, **ModelScan**, **guardrails**, **Evidently**, and NIST AI RMF-aligned checklists. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Holistic AI](https://www.holisticai.com/)**  
  AI risk and governance platform covering bias, robustness, efficacy, and policy workflows for enterprise AI systems.

- **[Credo AI](https://www.credo.ai/)**  
  AI governance platform for risk assessment, policy management, and continuous compliance across the AI portfolio.

- **[ModelOp, Monitaur, FairNow, Trustible](https://www.modelop.com/)**  
  Model risk management and AI governance tools focused on inventory, monitoring, fairness, and operational controls.

- **[IBM watsonx.governance](https://www.ibm.com/watsonx/governance)**  
  Enterprise AI governance module for risk, lifecycle, and regulatory alignment within the IBM AI stack.

- **[CalypsoAI, Protect AI, TruEra](https://www.calypsoai.com/)**  
  Platforms spanning AI security, model risk, evaluation, and runtime controls that feed into broader risk programs.

- **[Other commercial AI risk management platforms](https://www.holisticai.com/)**  
  Additional solutions for model inventory, impact assessment, and board-level AI risk reporting.

## Open-Source GitHub Projects

- **[AegisAI](https://github.com/SdSarthak/AegisAI)**  
  Open-source AI-GRC platform oriented to EU AI Act and risk workflows—system registration, risk classification, documentation, and related controls.

- **[AiExponent / RiskForge-style tools](https://github.com/aiexponenthq)**  
  Open utilities for AI risk screening, risk management files, and compliance artefacts mapped to regulatory obligations.

- **[ModelScan (Protect AI)](https://github.com/protectai/modelscan)**  
  Open-source scanner for unsafe model serialization (Pickle, H5, SavedModel)—foundational supply-chain risk control.

- **[Model cards & documentation toolkits](https://github.com/huggingface/model-card-toolkit)**  
  Open standards and tools for documenting intended use, metrics, and risks—core evidence for model risk programs.

- **[Evidently](https://github.com/evidentlyai/evidently)**  
  Open ML/LLM monitoring for drift, performance, and data quality—operational risk signals for deployed models.

- **[NeMo Guardrails, LLM Guard](https://github.com/NVIDIA/NeMo-Guardrails)**  
  Open runtime controls whose configuration and logs serve as technical risk mitigations.

- **[NIST AI RMF playbooks & open checklists](https://github.com/search?q=NIST+AI+RMF+OR+AI+risk+management+framework)**  
  Community implementations and templates aligned to NIST AI Risk Management Framework and similar standards.

- **[Fairness & bias open toolkits](https://github.com/search?q=fairness+toolkit+OR+bias+detection+machine+learning)**  
  Libraries such as Fairlearn and AIF360 for measuring and mitigating bias as part of model risk assessment.

### Additional Strong Open-Source Options

- **Inventory & classification**: Lightweight registries + AegisAI-style risk tiers.
- **Supply-chain risk**: ModelScan before loading third-party models.
- **Operational risk**: Evidently for drift and performance monitoring.
- **Documentation**: Model cards as minimum risk documentation.
- **Composable stacks**: Inventory → risk score → model card → monitoring → guardrails → audit log.
- Commercial platforms still lead in multi-framework policy engines, workflow, and enterprise reporting.

**Frameworks for building custom systems**:  
Open **model cards**, **ModelScan**, **Evidently**, **fairness toolkits**, and **guardrails** form a practical open risk toolkit.  
**AegisAI**-class projects aim at fuller AI-GRC workflows.  
Commercial platforms (Holistic AI, Credo AI, ModelOp, Monitaur, IBM watsonx.governance, etc.) deliver process, scale, and audit support.  
Many organizations pair commercial risk platforms with open technical controls. Fully open risk programs work for smaller estates with strong process ownership; regulated enterprises typically need commercial depth.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AI risk management is domain- and jurisdiction-specific. Software does not replace legal advice, independent validation, or required regulatory processes. High-risk systems may need formal audits or notified-body involvement.
- Open-source tools help structure controls and evidence but do not guarantee regulatory acceptance. Commercial platforms shift process and support burden to the vendor. Always involve risk, legal, and compliance stakeholders.

---

**Made for AI risk officers, model risk teams, and organizations governing AI responsibly.**  
Let's expand open AI risk tooling while recognizing the process maturity and scale that leading commercial AI risk management platforms deliver.
