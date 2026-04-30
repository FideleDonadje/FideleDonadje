<div align="center">

<!-- Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a3a5c,100:00b4d8&height=200&section=header&text=Fidele%20Donadje&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=AWS%20Cloud%20Security%20Engineer&descAlignY=60&descSize=20&animation=fadeIn" width="100%"/>

<!-- Typing animation -->
<a href="https://github.com/FideleDonadje">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&pause=1000&color=00B4D8&center=true&vCenter=true&width=650&lines=Building+AI-powered+security+tooling+on+AWS;Bedrock+%7C+CDK+%7C+Lambda+%7C+Security+Hub;From+findings+to+full+RMF+compliance+packages;Design-first.+Infrastructure-as-code-always." alt="Typing SVG" />
</a>

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=FideleDonadje&color=00b4d8&style=flat-square&label=Profile+Views)
[![GitHub followers](https://img.shields.io/github/followers/FideleDonadje?label=Followers&style=flat-square&color=00b4d8)](https://github.com/FideleDonadje?tab=followers)

</div>

---

## 👋 About Me

I'm a cloud security engineer building production-grade tooling on AWS. My focus is the intersection of **cloud security**, **AI automation**, and **compliance engineering** — turning noisy security findings into structured, actionable outputs including full RMF compliance packages.

- 🚀 Shipped a 3-feature AWS security platform: AI SOC Triage, ATO Assist Mode, and a full NIST RMF Workspace with live artifact generation
- 📋 The RMF Workspace walks through all 7 NIST RMF steps and auto-generates the SSP, SAR, Risk Assessment, POA&M, and FIPS 199 categorization from live Security Hub findings
- ⚡ Everything I build is infrastructure-as-code first (AWS CDK), no manual console changes
- 🧠 Design-first workflow: architecture is thought through before a line of code is written, and I own every decision

---

## 🛠️ Tech Stack

**Cloud & Security**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)
![AWS CDK](https://img.shields.io/badge/CDK-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)
![AWS Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![Security Hub](https://img.shields.io/badge/Security%20Hub-DD344C?style=flat-square&logo=amazonaws&logoColor=white)
![Bedrock](https://img.shields.io/badge/Bedrock-4A154B?style=flat-square&logo=amazonaws&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![Cognito](https://img.shields.io/badge/Cognito-DD344C?style=flat-square&logo=amazonaws&logoColor=white)
![IAM](https://img.shields.io/badge/IAM-232F3E?style=flat-square&logo=amazonaws&logoColor=FF9900)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)

**Languages & Frameworks**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PowerShell](https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)

**DevSecOps**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Checkov](https://img.shields.io/badge/Checkov-5C4EE5?style=flat-square)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)

**Compliance**

![NIST 800-53](https://img.shields.io/badge/NIST%20800--53-1a3a5c?style=flat-square)
![NIST RMF](https://img.shields.io/badge/NIST%20RMF-00b4d8?style=flat-square)
![ATO](https://img.shields.io/badge/ATO%20%2F%20POA%26M-1a3a5c?style=flat-square)
![SSP](https://img.shields.io/badge/SSP%20%2F%20SAR-00b4d8?style=flat-square)
![FIPS 199](https://img.shields.io/badge/FIPS%20199-1a3a5c?style=flat-square)

---

## 🔐 Portfolio Projects

### ✅ [security-triage-agent](https://github.com/FideleDonadje/security-triage-agent)
> AI-powered AWS security platform — Triage, ATO Assist, and NIST RMF Workspace

A fully deployed, 3-feature security platform built on AWS:

**SOC Triage Agent** — ingests Security Hub findings, routes them through an AI triage workflow using Bedrock AgentCore, and executes approved Tier 1 remediation actions with human-in-the-loop approval via a React/Cognito frontend.

**ATO Assist Mode** — pulls NIST 800-53 findings from Security Hub grouped by control family, uses Bedrock to draft control implementation statements, and auto-generates POA&M entries from failed findings.

**NIST RMF Workspace** — a full 7-step RMF workflow dashboard. Covers system categorization (FIPS 199), control selection, implementation tracking, security assessment, authorization package generation, and continuous monitoring. Auto-generates the SSP, Security Assessment Report, and Risk Assessment from live Security Hub data. Every artifact has a Regenerate button so documents always reflect current environment state.

`AWS Bedrock AgentCore` `CDK` `Lambda` `DynamoDB Streams` `Security Hub` `React/Vite` `TypeScript` `Cognito` `S3`

---

### ✅ [security-control-coverage-analyzer](https://github.com/FideleDonadje/security-control-coverage-analyzer)
> Account-level AWS security control coverage auditing

Produces auditable JSON and Markdown reports showing exactly which AWS security controls are active vs. missing. Designed for compliance engineers who need clean evidence artifacts with no dashboard noise.

`Python` `AWS Security Hub` `NIST 800-53` `Markdown Reports`

---

## 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=FideleDonadje&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&icon_color=00b4d8&text_color=c9d1d9&count_private=true" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=FideleDonadje&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&text_color=c9d1d9&langs_count=6" />

</div>

---

## 🗺️ What's Next

| Status | Project | Description |
|--------|---------|-------------|
| 🔨 In Progress | CI/CD Security Gate | Pre-deploy IaC scanning with Checkov/tfsec in GitHub Actions |
| 📋 Planned | Greenfield AWS Setup Guide | Blog post on secure account bootstrapping from scratch |
| 📋 Planned | IAM Policy Analyzer | Detect overpermissioned policies before they reach production |
| 📋 Planned | Infrastructure Drift Detector | Alert on live AWS config deviating from CDK-defined state |

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,100:0d1117&height=100&section=footer" width="100%"/>

</div>
