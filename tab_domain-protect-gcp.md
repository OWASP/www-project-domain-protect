---
title: Domain Protect GCP
layout:  null
tab: true
order: 1
tags: domain-protect-gcp
---

## Domain Protect GCP

[!OWASP state](https://img.shields.io/badge/owasp-Incubator%20Project-green.svg)
[![Release version](https://img.shields.io/github/release/OWASP/domain-protect-gcp)](https://github.com/domain-protect/domain-protect-gcp/releases)
[![Domain Protect Github Stars](https://img.shields.io/github/stars/domain-protect/domain-protect?label=domain-protect&style=social)](https://github.com/domain-protect/domain-protect-gcp)
[![Python 3.x](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

Attackers can take over an organisation's subdomains, and use them for reputational damage, malware hosting and credential harvesting.
Subdomain takeover is particularly common for organisations hosting their applications and infrastructure in the cloud.

Domain Protect GCP helps to prevent subdomain takeover, using serverless functions in GCP to continually scan an organisation's DNS records.
When vulnerable subdomains are found, it sends alerts via Slack or email, and optionally creates cloud resources to take over subdomains before attackers or bug bounty researchers.