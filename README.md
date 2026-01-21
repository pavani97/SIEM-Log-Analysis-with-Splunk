# 🔍 Splunk SIEM Log Analysis Project

A comprehensive, hands-on cybersecurity project that demonstrates how to use **Splunk** as a **SIEM (Security Information and Event Management)** platform for real-world log analysis and threat detection.

This project walks through installing and configuring Splunk, ingesting multiple log sources (DNS, SSH, and HTTP), and using SPL queries to uncover suspicious behavior and unauthorized access attempts.

It is well-suited for **SOC Analysts**, **Cybersecurity Students**, and **beginners** who want practical experience with Splunk-based security monitoring.

---

## 📘 Table of Contents
- [Project Overview](#project-overview)
- [Learning Objectives](#learning-objectives)
- [Tools & Setup](#tools--setup)
- [Project Workflow](#project-workflow)
- [Step 1 — Install and Configure Splunk](#step-1--install-and-configure-splunk)
- [Step 2 — DNS Log Analysis](#step-2--dns-log-analysis)
- [Step 3 — SSH Log Analysis](#step-3--ssh-log-analysis)
- [Step 4 — HTTP Log Analysis](#step-4--http-log-analysis)
- [Step 5 — Investigating Unauthorized Access](#step-5--investigating-unauthorized-access)
- [Results and Screenshots]

---

## 🧠 Project Overview

This project focuses on creating a functional SIEM lab using Splunk to perform structured security monitoring and log analysis. You will learn how to collect logs from different sources, search and filter events using SPL, and identify indicators of malicious or abnormal activity.

The lab simulates the daily responsibilities of a SOC analyst by emphasizing investigation, correlation, and incident analysis rather than theory alone.

---

## 🎯 Learning Objectives

By completing this project, you will be able to:

- Install and configure Splunk Enterprise on Ubuntu Linux
- Ingest and analyze DNS, SSH, and HTTP log data
- Identify anomalies such as brute-force attempts, suspicious domains, and abnormal web activity
- Perform basic incident investigation using log correlation
- Build confidence using SPL for real-world security use cases

---

## 🧰 Tools & Setup

| Component | Description |
|---------|-------------|
| Operating System | Ubuntu 20.04 / 22.04 (Server or Desktop) |
| SIEM Tool | Splunk Enterprise (Free local license) |
| Access Method | Splunk Web Interface (Port 8000) |
| Log Sources | Zeek-formatted DNS, SSH, and HTTP logs (JSON) |

---

## 🌐 Project Background

In modern security operations, logs are a primary source of truth for detecting and investigating threats. Every system, application, and network device continuously produces logs that record activity across the environment.

Manually reviewing these logs is inefficient and error-prone. SIEM platforms like Splunk solve this problem by centralizing, parsing, and correlating large volumes of log data in real time.

Using Splunk, security teams can:

- Aggregate logs from multiple sources into a single platform
- Normalize and structure raw data for consistent analysis
- Correlate events across systems to uncover hidden threats
- Detect malicious behavior through patterns and anomalies
- Visualize findings using dashboards and reports

Mastering Splunk helps develop a **SOC analyst mindset**, enabling you to convert raw telemetry into actionable security intelligence.

---

## 🧩 Project Workflow

| Step | Focus Area | Description |
|-----|-----------|-------------|
| Step 1 | Splunk Installation & Configuration | Deploy Splunk on Ubuntu and prepare it for log ingestion |
| Step 2 | DNS Log Analysis | Analyze DNS queries to identify suspicious domains and unusual request patterns |
| Step 3 | SSH Log Analysis | Detect failed logins, brute-force attempts, and unauthorized SSH access |
| Step 4 | HTTP Log Analysis | Examine web traffic for anomalies, server errors, and potential attacks |
| Step 5 | Investigation & Correlation | Correlate multiple log sources to investigate unauthorized access and potential compromise |

---

## 🚀 What’s Next?

With the project scope and workflow defined, the next section begins with **Step 1: Install and Configure Splunk**. This step will guide you through deploying Splunk Enterprise on Ubuntu and preparing the environment for ingesting security logs.

Subsequent sections will dive deeper into log analysis, detection techniques, and SOC-style investigations.

---

📌 *This project can be expanded further by adding dashboards, alerts, and additional log sources to enhance SIEM capabilities.*
