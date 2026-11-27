---
claim_count: 13
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Judi platform
    text: Judi® platform has achieved Ready status under the Federal Risk and Authorization Management Program (FedRAMP®) and is now listed in the FedRAMP Marketplace
    type: FedRAMP Ready status
  - framework: SOC2
    issuer: null
    period: 12/1/2024-11/30/2025
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 (12/1/2024-11/30/2025)
    type: SOC 2 Type 2
  - framework: SOC2
    issuer: null
    period: 12/1/2025-6/30/2026
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 (12/1/2025-6/30/2026)
    type: SOC 2 Type 2
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 Type 2
    type: SOC 1 Type 2
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 3
    type: SOC 3
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HITRUST
    type: certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: HIPAA
    type: compliance
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Judi Health platform
    source: https://www.judi.health/security
    text: Judi Health is FedRAMP Ready, which means protecting your data at the same level trusted by federal defense and intelligence agencies.
    type: FedRAMP Ready
  - framework: HITRUST
    issuer: null
    period: null
    report_access: unstated
    scope: Judi Health
    source: https://www.judi.health/security
    text: HITRUST certification combines HIPAA, NIST, and other frameworks into one comprehensive, healthcare-specific standard.
    type: certification
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: Judi Health systems handling benefit and claims data
    source: https://www.judi.health/security
    text: A SOC 1 report validates the controls that affect financial reporting.
    type: report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Judi Health
    source: https://www.judi.health/security
    text: A SOC 2 report evaluates controls around security, availability, and confidentiality.
    type: report
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: Judi Health platform
    source: https://www.judi.health/security
    text: SOC 1/2/3, HITRUST, NIST, FISMA, and FedRAMP.
    type: certification
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: Judi Health security program
    source: https://www.judi.health/security
    text: Our security program is built on the NIST 800–53 and FISMA frameworks
    type: framework
  trust_center:
    url: https://trust.judi.health/
frameworks:
- FedRAMP
- HIPAA
- HITRUST
- NIST-800-53
- SOC1
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Judi Health
provenance_date: '2026-11-09'
provider_name: Judi Health
provider_slug: judi-health
slug: judi-health-compliance
source_date: '2026-11-09'
source_filename: judi-health-compliance.yml
source_heading: Compliance
source_page: https://trust.judi.health/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Judi Health\naid: judi-health\nurl: https://trust.judi.health/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/judi-health-trust-center.yml\n  sources:\n  - https://trust.judi.health/\n  - https://www.judi.health/security\ntrust_center:\n  url: https://trust.judi.health/\nattestations:\n- framework: FedRAMP\n  type: FedRAMP Ready status\n  scope: Judi platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Judi® platform has achieved Ready status under the Federal Risk and Authorization Management Program (FedRAMP®)\n    and is now listed in the FedRAMP Marketplace\n- framework:\
  \ SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: 12/1/2024-11/30/2025\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 (12/1/2024-11/30/2025)\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: null\n  period: 12/1/2025-6/30/2026\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 (12/1/2025-6/30/2026)\n- framework: SOC1\n  type: SOC 1 Type 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type 2\n- framework: SOC3\n  type: SOC 3\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 3\n- framework: HITRUST\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HITRUST\n- framework: HIPAA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HIPAA\n- framework: FedRAMP\n  type: FedRAMP Ready\n  scope: Judi Health platform\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: Judi Health is FedRAMP Ready, which means protecting your data at the same level trusted by federal defense\n    and intelligence agencies.\n  source: https://www.judi.health/security\n- framework: HITRUST\n  type: certification\n  scope: Judi Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: HITRUST certification combines HIPAA, NIST, and other frameworks into one comprehensive, healthcare-specific\n    standard.\n  source: https://www.judi.health/security\n- framework: SOC1\n  type: report\n  scope: Judi Health systems handling benefit and claims data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: A SOC 1 report validates the controls that affect financial reporting.\n  source: https://www.judi.health/security\n- framework: SOC2\n  type: report\n  scope: Judi Health\n  period: null\n  issuer: null\n  report_access: unstated\n  text: A SOC 2 report evaluates controls around security, availability, and confidentiality.\n  source: https://www.judi.health/security\n\
  - framework: SOC3\n  type: certification\n  scope: Judi Health platform\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1/2/3, HITRUST, NIST, FISMA, and FedRAMP.\n  source: https://www.judi.health/security\n- framework: NIST-800-53\n  type: framework\n  scope: Judi Health security program\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our security program is built on the NIST 800–53 and FISMA frameworks\n  source: https://www.judi.health/security\n"
source_yaml_url: https://artifacts.apis.io/judi-health/compliance/judi-health-compliance.yml
stated_fields:
- attestations
summary_line: 13 quoted statements, read from Judi Health's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Pharmacy Benefits
- PBM
- Health Benefits
- Benefits Administration
- Health Tech
- Medicare
- Insurance
---
