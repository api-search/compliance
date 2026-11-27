---
api_specs:
- filename: keeper-security-bi-api-api-openapi.yml
  format: yaml
  label: Keeper Security Bi API
  slug: keeper-security-bi-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keeper-security/openapi/keeper-security-bi-api-api-openapi.yml
- filename: keeper-security-health-api-openapi.yml
  format: yaml
  label: Keeper Security Health API
  slug: keeper-security-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/keeper-security/openapi/keeper-security-health-api-openapi.yml
claim_count: 15
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 SOC 3 ISO 27001:2022 ISO 27017 ISO 27018 GDPR CCPA COMPLIANT CCPA
    type: SOC 2 report
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 3
    type: SOC 3 report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2022 Certificate
    type: ISO 27001:2022 certificate
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: FedRAMP High Rev. 5
    type: FedRAMP High Rev. 5 security assessment
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: IL-5 Security Assessment Report (SAR)
    type: IL-5 security assessment report
  - framework: StateRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: StateRAMP Authorized Status Award Letter
    type: StateRAMP authorized status
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS Attestation of Scan Compliance
    type: PCI DSS attestation of scan compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Digital Operational Resilience Act
    type: Digital Operational Resilience Act compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: NIS 2 Directive
    type: NIS 2 Directive compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GovRAMP
    type: GovRAMP compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TX-RAMP
    type: TX-RAMP compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR compliance
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Keeper processes and products for customers in the EU and worldwide
    source: https://www.keepersecurity.com/security.html
    text: Keeper is GDPR compliant and committed to ensuring our processes and products maintain GDPR compliance for our customers in the European Union and across the world.
    type: GDPR compliance statement
  - framework: other
    issuer: NIST Cryptographic Module Verification Program (CMVP)
    period: null
    report_access: unstated
    scope: Keeper cryptographic module
    source: https://www.keepersecurity.com/security.html
    text: Keeper is certified by the NIST Cryptographic Module Verification Program (CMVP) to meet the FIPS 140-3 standard.
    type: FIPS 140-3 validation (NIST CMVP)
  - framework: other
    issuer: U.S. Department of Commerce
    period: null
    report_access: unstated
    scope: Data privacy compliance
    source: https://www.keepersecurity.com/security.html
    text: We comply with the EU-U.S. Data Privacy Framework
    type: EU-U.S. Data Privacy Framework participation
  trust_center:
    url: https://trust.keeper.io/
frameworks:
- FedRAMP
- GDPR
- ISO27001
- PCI-DSS
- SOC2
- SOC3
- StateRAMP
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Keeper Security
provenance_date: '2026-11-09'
provider_name: Keeper Security
provider_slug: keeper-security
slug: keeper-security-compliance
source_date: '2026-11-09'
source_filename: keeper-security-compliance.yml
source_heading: Compliance
source_page: https://trust.keeper.io/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Keeper Security\naid: keeper-security\nurl: https://trust.keeper.io/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/keeper-security-trust-center.yml\n  sources:\n  - https://trust.keeper.io/\n  - https://www.keepersecurity.com/security.html\ntrust_center:\n  url: https://trust.keeper.io/\nattestations:\n- framework: SOC2\n  type: SOC 2 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 SOC 3 ISO 27001:2022 ISO 27017 ISO 27018 GDPR CCPA COMPLIANT CCPA\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: SOC 3\n- framework: ISO27001\n  type: ISO 27001:2022 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 Certificate\n- framework: FedRAMP\n  type: FedRAMP High Rev. 5 security assessment\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: FedRAMP High Rev. 5\n- framework: other\n  type: IL-5 security assessment report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: IL-5 Security Assessment Report (SAR)\n- framework: StateRAMP\n  type: StateRAMP authorized status\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: StateRAMP Authorized Status Award Letter\n- framework: PCI-DSS\n  type: PCI DSS attestation of scan compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS Attestation of Scan Compliance\n- framework: other\n  type: Digital Operational Resilience Act compliance\n\
  \  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Digital Operational Resilience Act\n- framework: other\n  type: NIS 2 Directive compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: NIS 2 Directive\n- framework: other\n  type: GovRAMP compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GovRAMP\n- framework: other\n  type: TX-RAMP compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TX-RAMP\n- framework: GDPR\n  type: GDPR compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: GDPR\n  type: GDPR compliance statement\n  scope: Keeper processes and products for customers in the EU and worldwide\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Keeper is GDPR compliant and committed to ensuring our processes and products maintain GDPR compliance for\n    our customers\
  \ in the European Union and across the world.\n  source: https://www.keepersecurity.com/security.html\n- framework: other\n  type: FIPS 140-3 validation (NIST CMVP)\n  scope: Keeper cryptographic module\n  period: null\n  issuer: NIST Cryptographic Module Verification Program (CMVP)\n  report_access: unstated\n  text: Keeper is certified by the NIST Cryptographic Module Verification Program (CMVP) to meet the FIPS 140-3\n    standard.\n  source: https://www.keepersecurity.com/security.html\n- framework: other\n  type: EU-U.S. Data Privacy Framework participation\n  scope: Data privacy compliance\n  period: null\n  issuer: U.S. Department of Commerce\n  report_access: unstated\n  text: We comply with the EU-U.S. Data Privacy Framework\n  source: https://www.keepersecurity.com/security.html\n"
source_yaml_url: https://artifacts.apis.io/keeper-security/compliance/keeper-security-compliance.yml
stated_fields:
- attestations
summary_line: 15 quoted statements, read from Keeper Security's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- Secrets Management
- Password Manager
- Privileged Access Management
- Zero Knowledge
- Security
- SDK
---
