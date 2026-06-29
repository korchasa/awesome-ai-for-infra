# Awesome AI for Infra

> **Note:** This repository contains an automatically compiled list of frameworks, tools, and resources that use AI/ML to operate ordinary IT infrastructure — AIOps for DevOps, SRE and Platform Engineering (observability, incident management, automation/self-healing, SecOps, and cloud/Kubernetes operations).

A curated list of awesome "AI for *Ops" software: using AI to run IT operations,
DevOps, SRE and platform engineering — intelligent observability and monitoring,
incident detection and root-cause analysis, automation and self-healing, AI for
security operations, and AI for cloud and Kubernetes infrastructure.


Table of Contents:
- [AIOps Platforms & Frameworks](#aiops-platforms-&-frameworks)
    - [Full-Stack AIOps Platforms](#full-stack-aiops-platforms) (6)
    - [Predictive Analytics for Operations](#predictive-analytics-for-operations) (1)
    - [Incident Management & Response](#incident-management-&-response) (4)
- [Observability & Monitoring with AI](#observability-&-monitoring-with-ai)
    - [Log Analysis & Intelligence](#log-analysis-&-intelligence) (5)
    - [Infrastructure Monitoring](#infrastructure-monitoring) (1)
    - [Root Cause Analysis](#root-cause-analysis) (9)
    - [Anomaly Detection](#anomaly-detection) (13)
- [Automation & Self-Healing](#automation-&-self-healing)
    - [AI-Powered Automation](#ai-powered-automation) (5)
    - [ChatOps & AI Assistants for Ops](#chatops-&-ai-assistants-for-ops) (3)
- [AI for Security Operations (SecOps)](#ai-for-security-operations-(secops))
    - [Threat Intelligence](#threat-intelligence) (2)
    - [Security Monitoring](#security-monitoring) (2)
    - [Compliance Automation](#compliance-automation) (1)
- [AI for Cloud & Infrastructure](#ai-for-cloud-&-infrastructure)
    - [Cloud Cost Optimization](#cloud-cost-optimization) (3)
    - [Container & Kubernetes Intelligence](#container-&-kubernetes-intelligence) (1)



## AIOps Platforms & Frameworks

### Full-Stack AIOps Platforms

- [alibaba/SREWorks](https://github.com/alibaba/SREWorks) (1988 Java) - SREWorks is Alibaba Cloud's cloud-native AIOps and DataOps platform designed to enhance IT operation and maintenance through AI and big data.
- [alibaba/UnifiedModel](https://github.com/alibaba/UnifiedModel) (203 Python) - UModel is a vendor-neutral semantic runtime that provides a unified object graph for enterprise AI agents, enabling them to understand and process fragmented IT operational data, services, and busi...
- [databufflabs/databuff](https://github.com/databufflabs/databuff) (170 Vue) - Databuff is an open-source, AI-native OpenTelemetry APM and SREAgent tool providing a platform for AI-driven application performance monitoring and root cause analysis.
- [HoloInsight/holoinsight](https://github.com/HoloInsight/holoinsight) (351 Java) - HoloInsight is a cloud-native observability platform that emphasizes real-time log analysis and integrates AI for enhanced monitoring and insights.
- [keephq/keep](https://github.com/keephq/keep) (11986 Python) - Keep is an open-source AIOps and alert management platform that centralizes alerts, deduplicates, enriches, filters them, and correlates incidents using AI-powered automation and various backend in...
- [nudgebee/nudgebee](https://github.com/nudgebee/nudgebee) (372 Go) - Nudgebee is an open-source SRE copilot leveraging AI for observability, FinOps, runbook automation, and incident response across Kubernetes and multi-cloud environments.

### Predictive Analytics for Operations

- [aqstack/sentinel](https://github.com/aqstack/sentinel) (364 Go) - Sentinel is a self-healing edge computing agent for Kubernetes, providing predictive failure detection and partition-resilient orchestration for edge nodes using lightweight statistical models.

### Incident Management & Response

- [Arvo-AI/aurora](https://github.com/Arvo-AI/aurora) (345 Python) - Aurora is an open-source, AI-powered incident management platform that uses AI agents to autonomously investigate incidents, perform root cause analysis, and suggest remediations across multi-cloud...
- [ongridio/ongrid](https://github.com/ongridio/ongrid) (332 Go) - Ongrid is an AI-powered ops agent that autonomously investigates alerts, performs root-cause analysis, and orchestrates fixes for IT infrastructure issues, interacting via chat platforms.
- [papadopouloskyriakos/agentic-chatops](https://github.com/papadopouloskyriakos/agentic-chatops) (106 Python) - This project implements a multi-agent ChatOps system that uses AI/ML to autonomously triage, investigate, and propose fixes for infrastructure alerts, including self-improving prompts and a causal ...
- [Tommy-yw/RunbookHermes](https://github.com/Tommy-yw/RunbookHermes) (530 Python) - RunbookHermes is an AIOps agent built on the Hermes Agent framework, designed for evidence-driven incident response, approval-gated remediation, and self-evolving runbook learning.

## Observability & Monitoring with AI

### Log Analysis & Intelligence

- [logpai/Drain3](https://github.com/logpai/Drain3) (829 Python) - Drain3 is an online log template miner that extracts structured templates from raw log messages for enhanced observability and anomaly detection.
- [logpai/Log3C](https://github.com/logpai/Log3C) (175 Python) - Log3C is a framework that identifies impactful service system problems by analyzing system logs and KPI metrics through a process of log parsing, sequence vectorization, cascading clustering, and c...
- [logpai/loglizer](https://github.com/logpai/loglizer) (1418 Jupyter Notebook) - Loglizer is an open-source machine learning toolkit designed for automated anomaly detection in system logs, supporting various supervised and unsupervised models.
- [logpai/logparser](https://github.com/logpai/logparser) (1982 Python) - Logparser is a machine learning toolkit that provides automated log parsing and benchmarks for structured log analytics via event template extraction.
- [salesforce/logai](https://github.com/salesforce/logai) (814 Python) - LogAI is an open-source library that provides a comprehensive platform for log analytics and intelligence, including summarization, clustering, and anomaly detection.

### Infrastructure Monitoring

- [linkedin/cruise-control](https://github.com/linkedin/cruise-control) (3035 Java) - Cruise Control is a self-healing and workload rebalancing tool for Apache Kafka clusters, optimizing resource utilization and detecting anomalies to simplify large-scale operations.

### Root Cause Analysis

- [cuebook/CueObserve](https://github.com/cuebook/CueObserve) (235 Python) - CueObserve is an open-source platform for time-series anomaly detection and root cause analysis directly on data warehouses, designed to monitor key metrics and identify causative factors.
- [derisk-ai/OpenDerisk](https://github.com/derisk-ai/OpenDerisk) (949 Python) - OpenDeRisk is an AI-native risk intelligence system providing 24/7 comprehensive protection for application systems through multi-agent collaboration for deep root cause analysis.
- [HolmesGPT/holmesgpt](https://github.com/HolmesGPT/holmesgpt) (2749 Python) - HolmesGPT is an open-source AI agent for SRE that investigates production incidents, finds root causes, and can automatically identify and fix problems 24/7.
- [kubeshark/kubeshark](https://github.com/kubeshark/kubeshark) (11976 Go) - Kubeshark provides eBPF-powered network observability for Kubernetes, indexing L4/L7 traffic with full K8s context and decrypting TLS, queryable by AI agents and humans.
- [openrca/orca](https://github.com/openrca/orca) (107 Python) - OpenRCA provides automated root cause analysis for Kubernetes clusters by constructing a real-time topology graph enriched with telemetry data from various sources.
- [scitix/siclaw](https://github.com/scitix/siclaw) (216 TypeScript) - Siclaw is an open-source AI agent designed for DevOps and SRE teams to perform read-only infrastructure diagnostics and root-cause analysis through deep investigation workflows.
- [shaido987/riskloc](https://github.com/shaido987/riskloc) (137 Python) - RiskLoc is an AI-powered method for localizing multi-dimensional root causes in time-series data, identifying the specific dimensions and values contributing to anomalies.
- [tangpan360/MicroRCA-Agent](https://github.com/tangpan360/MicroRCA-Agent) (251 Python) - MicroRCA-Agent is an LLM-agent-based solution for microservice root cause localization and fault analysis, processing multi-modal Log, Trace, and Metric data.
- [Tracer-Cloud/opensre](https://github.com/Tracer-Cloud/opensre) (7699 Python) - OpenSRE is an open-source framework for building, training, and evaluating AI SRE agents specifically designed for incident investigation and response, running on your own infrastructure.

### Anomaly Detection

- [activecm/rita](https://github.com/activecm/rita) (593 Go) - RITA (Real Intelligence Threat Analytics) is an open-source framework that detects command and control (C2) communication by analyzing network traffic, identifying beaconing, long connections, DNS ...
- [d0ng1ee/logdeep](https://github.com/d0ng1ee/logdeep) (458 Python) - LogDeep is an open-source deep learning-based toolkit for automated log anomaly detection, implementing state-of-the-art models like DeepLog, LogAnomaly, and RobustLog.
- [datamllab/tods](https://github.com/datamllab/tods) (1660 Python) - TODS is a comprehensive automated machine learning system for multivariate time-series outlier detection, providing modules for preprocessing, feature extraction, and a wide array of detection algo...
- [earthgecko/skyline](https://github.com/earthgecko/skyline) (586 Python) - Skyline is a real-time anomaly detection and time series analysis system designed for passive monitoring of numerous high-resolution metrics without pre-configured models or thresholds.
- [jixinpu/aiopstools](https://github.com/jixinpu/aiopstools) (400 Python) - AIopstools is a Python toolkit offering fundamental AI-driven functionalities for IT operations, including anomaly detection, alarm convergence, time series forecasting, and alarm association analy...
- [khundman/telemanom](https://github.com/khundman/telemanom) (1176 Jupyter Notebook) - Telemanom is a framework using LSTMs and automatic thresholding for unsupervised anomaly detection in multivariate time series data, originally developed for spacecraft telemetry.
- [kLabUM/rrcf](https://github.com/kLabUM/rrcf) (523 Python) - rrcf provides a Python implementation of the Robust Random Cut Forest algorithm for anomaly detection on streaming data, designed for high-dimensional datasets.
- [MentatInnovations/datastream.io](https://github.com/MentatInnovations/datastream.io) (915 Python) - datastream.io is an open-source framework for real-time anomaly detection in streaming data using Python, Elasticsearch, and Kibana.
- [sintel-dev/Orion](https://github.com/sintel-dev/Orion) (1358 Python) - Orion is an open-source machine learning library from MIT's Data to AI Lab, focused on unsupervised time series anomaly detection using various AI-driven pipelines.
- [Stream-AD/MIDAS](https://github.com/Stream-AD/MIDAS) (776 C++) - MIDAS is a C++ implementation for real-time anomaly detection in dynamic, time-evolving graphs, designed to identify intrusions, fraud, and fake rating anomalies with high accuracy and speed.
- [xuhongzuo/DeepOD](https://github.com/xuhongzuo/DeepOD) (579 Python) - DeepOD is an open-source Python library providing a unified API for 27 deep learning-based outlier and anomaly detection algorithms for tabular and time-series data.
- [yzhao062/pyod](https://github.com/yzhao062/pyod) (9890 Python) - PyOD is a comprehensive Python library for multi-modal anomaly detection, offering 60+ detectors and an agentic workflow for AI agents to drive investigations across various data types.
- [zillow/luminaire](https://github.com/zillow/luminaire) (806 Python) - Luminaire is a Python package from Zillow that provides ML-driven solutions for monitoring time series data through automated anomaly detection and forecasting.

## Automation & Self-Healing

### AI-Powered Automation

- [bgdnvk/clanker](https://github.com/bgdnvk/clanker) (369 Go) - Clanker is an AI-powered CLI agent designed for autonomous systems engineering across various cloud environments, enabling intelligent infrastructure operations and agent-human collaboration.
- [bolivian-peru/os-moda](https://github.com/bolivian-peru/os-moda) (106 Rust) - osModa is an AI-native operating system based on NixOS, allowing AI agents to manage server operations through typed, auditable tool access and atomic rollbacks.
- [getsavvyinc/savvy-cli](https://github.com/getsavvyinc/savvy-cli) (459 Go) - Savvy is a CLI tool that uses AI to create, share, and run command-line workflows, leveraging natural language for automation and explanation of commands and error messages.
- [mezmo/aura](https://github.com/mezmo/aura) (143 Rust) - AURA is an agentic harness that enables Large Language Models (LLMs) to perform SRE work autonomously by providing critical guardrails, API servers, state management, and tool integrations for prod...
- [microsoft/AIOpsLab](https://github.com/microsoft/AIOpsLab) (904 Python) - AIOpsLab is a comprehensive framework for designing, developing, and evaluating autonomous AIOps agents, providing reproducible and scalable benchmarks for AIOps solutions.

### ChatOps & AI Assistants for Ops

- [BUAADreamer/EasyRAG](https://github.com/BUAADreamer/EasyRAG) (635 Python) - EasyRAG is an efficient Retrieval-Augmented Generation (RAG) framework designed for automated network operations, achieving top results in the CCF AIOps International Challenge 2024.
- [Higangssh/homebutler](https://github.com/Higangssh/homebutler) (162 Go) - HomeButler is a homelab management tool that uses AI agents and structured interfaces to monitor, diagnose, and automate operations for self-hosted applications and services.
- [WeOps-Lab/OpsPilot](https://github.com/WeOps-Lab/OpsPilot) (192 TypeScript) - OpsPilot is an open-source intelligent operation and maintenance assistant that uses deep learning and LLM technology to link various O&M systems for enhanced capabilities.

## AI for Security Operations (SecOps)

### Threat Intelligence

- [taranis-ai/taranis-ai](https://github.com/taranis-ai/taranis-ai) (1167 Python) - Taranis AI is an open-source intelligence (OSINT) tool that leverages AI and NLP to gather, analyze, and structure information from diverse sources for situational analysis and threat intelligence.
- [thalesgroup-cert/Watcher](https://github.com/thalesgroup-cert/Watcher) (1311 JavaScript) - Watcher is an AI-powered open-source platform for cybersecurity threat intelligence and hunting, designed to discover and monitor emerging cyber threats.

### Security Monitoring

- [backbay-labs/clawdstrike](https://github.com/backbay-labs/clawdstrike) (284 TypeScript) - Clawdstrike is an AI-powered Endpoint Detection and Response (EDR) system providing policy enforcement, a signed audit chain, and threat detection for developer workstations and autonomous agent fl...
- [beenuar/AiSOC](https://github.com/beenuar/AiSOC) (1453 Python) - AiSOC is an open-source, self-hostable AI-powered Security Operations Center that ingests, correlates, and investigates security events using AI, providing a transparent investigation ledger.

### Compliance Automation

- [valqore/valqore](https://github.com/valqore/valqore) (920 Python) - Valqore is an infrastructure governance engine that scans Kubernetes manifests, Terraform, and cloud resources to provide scores and verdicts for security, cost, GreenOps, AI governance, and compli...

## AI for Cloud & Infrastructure

### Cloud Cost Optimization

- [infracost/infracost](https://github.com/infracost/infracost) (12385 Go) - Infracost provides cloud cost estimates and FinOps best practices for Infrastructure as Code (IaC) by integrating with CI/CD pipelines, IDEs, and AI coding agents to enable cost-aware development.
- [openops-cloud/openops](https://github.com/openops-cloud/openops) (1039 TypeScript) - OpenOps is a no-code FinOps automation platform that uses AI to optimize cloud costs and streamline financial operations through customizable workflows and integrations.
- [realopslabs/kubeledger](https://github.com/realopslabs/kubeledger) (482 Python) - KubeLedger is a Kubernetes cost accounting system that tracks CPU, memory, and GPU usage per namespace, making hidden non-allocatable overhead visible for precise financial analysis and optimization.

### Container & Kubernetes Intelligence

- [aliyun/alibabacloud-ack-mcp-server](https://github.com/aliyun/alibabacloud-ack-mcp-server) (113 Python) - ACK MCP Server by Alibaba Cloud unifies container operations for AI assistants, enabling natural language interaction to manage Kubernetes resources, observability, and diagnostic tasks, facilitati...


## License

[<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg">](https://creativecommons.org/publicdomain/zero/1.0/)
