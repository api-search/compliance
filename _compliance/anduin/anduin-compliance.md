---
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Anduin's security, availability, and confidentiality controls
    text: Annual independent audit evaluating the effectiveness of Anduin's security, availability, and confidentiality controls over time.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: privacy program mapped to GDPR
    text: Full compliance with EU data protection law. Anduin's privacy program is mapped to GDPR as the baseline global standard.
    type: GDPR compliance
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: cloud-specific security controls for SaaS platforms
    text: Cloud Security Alliance certification validating cloud-specific security controls and practices for SaaS platforms.
    type: CSA STAR certification
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: data access, deletion, and opt-out rights
    text: California consumer privacy rights are fully supported, including data access, deletion, and opt-out rights for all applicable users.
    type: CCPA / CPRA consumer privacy rights support
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: LP e-signatures across jurisdictions
    text: EU-recognized electronic signature framework covering both basic and advanced levels for legally valid LP e-signatures across jurisdictions.
    type: eIDAS Simple and Advanced electronic signatures
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Security, Availability & Confidentiality
    source: https://anduintransact.com/anduin-trust-center
    text: SOC2 Security, Availability & Confidentiality Type 1
    type: Type 1
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://anduintransact.com/anduin-trust-center
    text: EU General Data Protection Regulation (GDPR)
    type: null
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Basic and Advanced electronic signatures
    source: https://anduintransact.com/anduin-trust-center
    text: eIDAS No 910/2014 from the European Union (Basic and Advanced)
    type: eIDAS regulation
  trust_center:
    url: https://anduintransact.com/security
frameworks:
- CCPA
- CSA-STAR
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Anduin
provenance_date: '2026-11-09'
provider_name: Anduin
provider_slug: anduin
slug: anduin-compliance
source_date: '2026-11-09'
source_filename: anduin-compliance.yml
source_heading: Compliance
source_page: https://anduintransact.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Anduin\naid: anduin\nurl: https://anduintransact.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/anduin-trust-center.yml\n  sources:\n  - https://anduintransact.com/anduin-trust-center\n  - https://anduintransact.com/security\ntrust_center:\n  url: https://anduintransact.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Anduin's security, availability, and confidentiality controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Annual independent audit evaluating the effectiveness of Anduin's security, availability, and confidentiality\n\
  \    controls over time.\n- framework: GDPR\n  type: GDPR compliance\n  scope: privacy program mapped to GDPR\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Full compliance with EU data protection law. Anduin's privacy program is mapped to GDPR as the baseline\n    global standard.\n- framework: CSA-STAR\n  type: CSA STAR certification\n  scope: cloud-specific security controls for SaaS platforms\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Cloud Security Alliance certification validating cloud-specific security controls and practices for SaaS\n    platforms.\n- framework: CCPA\n  type: CCPA / CPRA consumer privacy rights support\n  scope: data access, deletion, and opt-out rights\n  period: null\n  issuer: null\n  report_access: unstated\n  text: California consumer privacy rights are fully supported, including data access, deletion, and opt-out rights\n    for all applicable users.\n- framework: other\n  type: eIDAS Simple and Advanced electronic\
  \ signatures\n  scope: LP e-signatures across jurisdictions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU-recognized electronic signature framework covering both basic and advanced levels for legally valid LP\n    e-signatures across jurisdictions.\n- framework: SOC2\n  type: Type 1\n  scope: Security, Availability & Confidentiality\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC2 Security, Availability & Confidentiality Type 1\n  source: https://anduintransact.com/anduin-trust-center\n- framework: GDPR\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: EU General Data Protection Regulation (GDPR)\n  source: https://anduintransact.com/anduin-trust-center\n- framework: other\n  type: eIDAS regulation\n  scope: Basic and Advanced electronic signatures\n  period: null\n  issuer: null\n  report_access: unstated\n  text: eIDAS No 910/2014 from the European Union (Basic and Advanced)\n  source: https://anduintransact.com/anduin-trust-center\n"
source_yaml_url: https://artifacts.apis.io/anduin/compliance/anduin-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Anduin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Private Markets
- Fund Administration
- Investor Onboarding
- Fund Subscription
- Venture Capital
- Private Equity
- E-Signature
- Fintech
---
