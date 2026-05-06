<div align="center">

<img src="cerberus-logo.png" alt="Cerberus" width="160">

# Cerberus

**Continuous Security Testing Platform**

AI-driven agents that autonomously pentest, review code, verify exploits,<br>
and auto-fix vulnerabilities.

[![.NET 10](https://img.shields.io/badge/.NET-10-512BD4?style=flat-square&logo=dotnet&logoColor=white)](https://dotnet.microsoft.com/)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-Orchestrated-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![AI Powered](https://img.shields.io/badge/AI-Powered-FF5300?style=flat-square&logo=openai&logoColor=white)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=flat-square)](#)

---

</div>

## What is Cerberus?

Cerberus is an **AI-powered security platform** built by Ledger Donjon that continuously tests your infrastructure and codebase for vulnerabilities. Instead of one-off manual pentests, Cerberus deploys autonomous AI agents that explore, analyze, verify, and remediate security issues — then report back with structured findings and evidence.

<br>

## Disclosed Vulnerabilities

A sample of security issues Cerberus has reported to upstream maintainers. We commit to responsible disclosure: when a finding is realistically exploitable, we report it privately through the project's security channel and follow their coordinated-disclosure process before any public mention. For lower-impact issues, we open a public issue or pull request directly so the conversation happens openly with maintainers.

| Project | Date | Vulnerability | Severity | Reference |
| --- | :---: | --- | :---: | --- |
| **Clawvisor** | 2026-04-24 | Cross-tenant adapter overwrite in generated adapter installation | Critical | [PR #302](https://github.com/clawvisor/clawvisor/pull/302) |
| **Yubico** *(libfido2, python-fido2, YubiKey Manager)* | 2026-04-15 | DLL search-path hijack on Windows | High (CVSS 7.0) | [CVE-2026-40947](https://www.yubico.com/support/security-advisories/ysa-2026-01/) |
| **KDE Kleopatra** | 2026-04-08 | Local privilege escalation on Windows via single-instance mechanism | High | [CVE-2026-41527](https://kde.org/info/security/advisory-20260408-1.txt) |
| **Nethermind** | 2026-04-03 | Duplicate-signature quorum bypass in XDC vote aggregation | Critical | [PR #11027](https://github.com/NethermindEth/nethermind/pull/11027) |
| **Wasabi Wallet** | 2026-03-16 | OS command injection in URL opener via crafted "Read More" link | High | [Issue #14410](https://github.com/WalletWasabi/WalletWasabi/issues/14410) |
| **BTCPay Server** | 2026-03-13 – 03-15 | 6 access-control & tampering issues — IDOR, cross-store/cross-tenant escalation, plan/price tampering | High–Critical | [Commits](https://github.com/btcpayserver/btcpayserver/commits?author=Donjon-Cerberus) |

<br>

## Tech Stack

[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)](https://www.rabbitmq.com/)
[![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)](https://redis.io/)
[![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=flat-square&logo=blazor&logoColor=white)](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)
[![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)](https://kubernetes.io/)
[![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)](https://helm.sh/)
[![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)](https://openai.com/)
[![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)](https://playwright.dev/)
[![GitHub Actions](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/features/actions)

<br>

---

<div align="center">

Built by Ledger Donjon — the security research team at [Ledger](https://www.ledger.com/)

</div>
