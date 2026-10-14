# Awesome-Workplace-Safety-OSHA-Audit-Analyzers

## Top Workplace Safety (OSHA) Audit Analyzers Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Safety Compliance Auditing, Hazard Detection & Incident Analytics*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Workplace Safety (OSHA) Audit Analyzers**. These tools help organizations conduct safety audits, identify hazards, track incidents, and analyze compliance data to reduce workplace injuries and meet OSHA regulatory requirements.

**Examples** include VelocityEHS, Intelex, Cority, SafetyCulture (iAperture), Enablon, Gensuite (Benchmark ESG), Origami Risk, KPA Flex, Salus, and Quentic (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom audit workflows, and transparent safety data — ideal for safety managers, EHS professionals, and developers building workplace safety platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[VelocityEHS](https://www.velocityehs.com/)**  
  Comprehensive EHS and ESG software platform with audit management, incident tracking, chemical management, and compliance reporting.

- **[Intelex](https://www.intelex.com/)**  
  Enterprise EHS management software with audit workflows, corrective actions, and regulatory compliance tracking.

- **[Cority](https://www.cority.com/)**  
  EHS software platform with audit management, risk assessment, incident reporting, and occupational health modules.

- **[SafetyCulture (iAuditor)](https://safetyculture.com/)**  
  Mobile-first safety inspection and audit platform with customizable checklists, issue tracking, and analytics. Widely used for OSHA compliance inspections.

- **[Enablon](https://www.enablon.com/)**  
  Integrated risk and compliance software with audit management, incident investigation, and regulatory reporting.

- **[Gensuite (Benchmark ESG)](https://www.gensuite.com/)**  
  EHS and sustainability software with audit protocols, corrective action tracking, and compliance dashboards.

- **[Origami Risk](https://www.origamirisk.com/)**  
  Risk management platform with EHS modules for audits, incidents, and OSHA compliance reporting.

- **[KPA Flex](https://www.kpaflex.com/)**  
  EHS software with audit checklists, incident tracking, and OSHA recordkeeping for small to mid-size businesses.

- **[Salus](https://www.salus.com/)**  
  Safety management platform with mobile audits, hazard reporting, and compliance tracking.

- **[Quentic](https://www.quentic.com/)**  
  EHS and ESG software platform with mobile audit reporting, incident management, and compliance tools. The Quentic App enables HSE data collection with offline capability, drag-and-drop form builder, GPS location tagging, and electronic signatures [citation:4].

## Open-Source GitHub Projects

- **[OSHA Vision Auditor](https://github.com/AhmedMohammed4/osha-vision-auditor)**  
  AI-powered worksite safety compliance inspector. Upload construction site video and automatically detect OSHA PPE violations (missing hard hats, safety vests) using YOLOv8. Features risk scoring (0-100), AI-generated safety reports via OpenAI, interactive dashboard with clickable violation timestamps, and violation timeline visualization. Supabase backend for PostgreSQL and storage. Python 3.11+ backend with Next.js frontend [citation:1].

- **[SafeSight AI](https://github.com/chidubemOkafor/SafeSight.AI)**  
  AI-powered industrial safety inspection system for construction, warehouse, and industrial footage. Upload MP4 video, run YOLO-based PPE detector, browse detected violations with evidence frames, and ask natural-language questions about findings. Detects NO-Hardhat and NO-Safety Vest violations. FastAPI backend with Next.js 15 frontend, Docker Compose deployment, and HuggingFace LLM for Q&A [citation:5].

- **[Autonomous EHS Management](https://github.com/SafetyMP/Autonomous-EHS-Management)**  
  Self-hosted EHS console with incidents, CAPA, audits, and TRIR-style metrics in PostgreSQL. Optional AI suggests wording only — humans close records. Features turnkey local demo with Docker Postgres, realistic demo data, and comprehensive documentation for compliance and data governance [citation:10].

- **[Asgard EHS (Odin)](https://asgardehs.github.io/)**  
  Open-source, local-first compliance tools for EHS professionals. Single-binary Go applications that work standalone or integrated. Odin (in development) is a desktop compliance management application for manufacturing covering incidents, chemicals, training, and a schema builder for custom data. Built by an EHS professional with 15+ years in automotive manufacturing. GPL-3.0 licensed [citation:14].

- **[OiRA (Online interactive Risk Assessment)](https://github.com/EU-OSHA/oira.application.buildout)**  
  EU-OSHA's open-source risk assessment tool for small and micro enterprises. Built on Plone content management system, available on GitHub with full documentation. Provides sector-specific risk assessment tools across EU member states. Free and open-source software allowing modification and improvement [citation:6][citation:18].

- **[multimodal-compliance-monitor](https://github.com/rh-ai-quickstart/multimodal-compliance-monitor)**  
  Real-time safety and operational monitoring with multimodal AI. Features object tracking across frames, interactive chat for querying detection history, and video upload workflow. Uses YOLO for detection, BoxMOT for tracking, LLM chat via OpenAI-compatible API, and PostgreSQL for durable storage. Red Hat AI Quickstart project with Helm/Kubernetes deployment [citation:12].

- **[ppe-safety-detection-ai](https://github.com/prodbykosta/ppe-safety-detection-ai)**  
  AI-powered computer vision system for real-time workplace safety monitoring. Detects people and PPE compliance (helmets, vests) using YOLO models with intelligent tracking and MP4 output. Supports workplace safety monitoring, access control security systems, construction site oversight, and industrial facility monitoring. Python/OpenCV stack with optional Ultralytics YOLO models [citation:16].

- **[AI-PPE-Detection](https://github.com/darshan1654/AI-PPE-Detection)**  
  AI-powered CCTV surveillance system for real-time detection of PPE compliance including helmet and mask violations. Real-time detection of helmets, face masks, safety vests, and gloves. CCTV anomaly detection for restricted zone entry and unsafe movements. Streamlit dashboard with live status feed, violation logs, and compliance reports. Used in real industrial setup at Jyoti CNC Automation [citation:17].

- **[AegisVision](https://github.com/swadhinbiswas/AegisVision)**  
  Plug-and-play, multi-camera AI surveillance and behavioral-monitoring platform. Real-time face recognition with liveness anti-spoofing, occupancy analytics, spatial anti-theft memory, and Generative-AI copilot. FastAPI + ChromaDB + Elasticsearch + SQLite + React stack. GPL-3.0 licensed [citation:20].

- **[industrial-inspection](https://github.com/xbs0325/industrial-inspection)**  
  Seeed Studio's reference industrial safety monitoring demo for Jetson devices. YOLO handles person and PPE detection (missing helmet or vest), VLM analyzes behavior hazards (phone use, smoking, falls). Live WebRTC video with detection overlays and alert feed. Docker-based deployment on Jetson devices [citation:13].

### Additional Strong Open-Source Options

- **[Intel worker-safety-detection](https://huggingface.co/Intel/worker-safety-detection)** — Intel's OpenVINO-optimized object detection model for worker safety, detecting PPE compliance (helmets, safety jackets) at the edge. 19.4 MB model with DL Streamer integration [citation:9].
- **Vision-Based PPE Compliance Monitoring** — IEEE paper describing open-source deep learning system for real-time PPE compliance using YOLOv8 across multiple CCTV cameras. Detects helmets, vests, gloves, and masks with alerting and compliance trend dashboards [citation:3].
- **Nedo Vision Worker Core** — PyPI package for safety violation detection with PPE callbacks, area violation monitoring, and interval-based tracking. Python-based with callback registration for immediate and ongoing violation handling [citation:8].
- **KICS (Keeping Infrastructure as Code Secure)** — Open-source tool for detecting vulnerabilities, compliance issues, and misconfigurations. While infrastructure-focused, adaptable for safety compliance automation. Apache-2.0 licensed [citation:19].

**Frameworks for building custom systems**: Combine **OSHA Vision Auditor** or **SafeSight AI** for video-based PPE detection, **Autonomous EHS Management** or **Asgard EHS** for incident and audit tracking, **OiRA** for risk assessments, and **multimodal-compliance-monitor** for real-time behavioral analysis to build a complete self-hosted workplace safety audit stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Workplace safety tools must comply with OSHA regulations, data protection regulations (GDPR, CCPA), and worker privacy requirements.
- Self-hosted open-source solutions require proper security hardening, video data governance, and regulatory compliance verification.

---

**Made for safety managers, EHS professionals, compliance officers, and developers building workplace safety platforms.**  
Let's make workplace safety auditing more open, data-driven, and worker-protective.
