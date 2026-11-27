---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: AITIRE CLOUD infrastructure (hosting provider)
    text: 'AITIRE CLOUD has certification for compliance with: ISO/IEC 27001:2013 - Information security management systems — Requirements.'
    type: certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: AITIRE CLOUD infrastructure (hosting provider), Spanish National Security Scheme
    text: Esquema Nacional de Seguridad (ENS) .
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: INTERXION MAD3 datacenter (hosting subprocessor)
    text: 'INTERXION MAD3 datacenter has certification for compliance with: PCI-DSS ISO 9001 ISO 14001 ISO 20001 ISO 22301 ISO 27001 ISO 50001 ENS SOC1 SOC2'
    type: certification
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: INTERXION MAD3 datacenter (hosting subprocessor)
    text: 'INTERXION MAD3 datacenter has certification for compliance with: PCI-DSS ISO 9001 ISO 14001 ISO 20001 ISO 22301 ISO 27001 ISO 50001 ENS SOC1 SOC2'
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: INTERXION MAD3 datacenter (hosting subprocessor)
    text: 'INTERXION MAD3 datacenter has certification for compliance with: PCI-DSS ISO 9001 ISO 14001 ISO 20001 ISO 22301 ISO 27001 ISO 50001 ENS SOC1 SOC2'
    type: certification
  trust_center:
    url: https://taiga.io/security/
frameworks:
- ISO27001
- PCI-DSS
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Taiga
provenance_date: '2026-11-10'
provider_name: Taiga
provider_slug: taiga
slug: taiga-compliance
source_date: '2026-11-10'
source_filename: taiga-compliance.yml
source_heading: Compliance
source_page: https://taiga.io/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Taiga\naid: taiga\nurl: https://taiga.io/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/taiga-trust-center.yml\ntrust_center:\n  url: https://taiga.io/security/\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: AITIRE CLOUD infrastructure (hosting provider)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'AITIRE CLOUD has certification for compliance with: ISO/IEC 27001:2013 - Information security management\n    systems — Requirements.'\n- framework: other\n  type: certification\n  scope: AITIRE CLOUD infrastructure (hosting provider), Spanish National\
  \ Security Scheme\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Esquema Nacional de Seguridad (ENS) .\n- framework: PCI-DSS\n  type: certification\n  scope: INTERXION MAD3 datacenter (hosting subprocessor)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'INTERXION MAD3 datacenter has certification for compliance with: PCI-DSS ISO 9001 ISO 14001 ISO 20001 ISO\n    22301 ISO 27001 ISO 50001 ENS SOC1 SOC2'\n- framework: SOC1\n  type: certification\n  scope: INTERXION MAD3 datacenter (hosting subprocessor)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'INTERXION MAD3 datacenter has certification for compliance with: PCI-DSS ISO 9001 ISO 14001 ISO 20001 ISO\n    22301 ISO 27001 ISO 50001 ENS SOC1 SOC2'\n- framework: SOC2\n  type: certification\n  scope: INTERXION MAD3 datacenter (hosting subprocessor)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'INTERXION MAD3 datacenter has certification for compliance\
  \ with: PCI-DSS ISO 9001 ISO 14001 ISO 20001 ISO\n    22301 ISO 27001 ISO 50001 ENS SOC1 SOC2'\n"
source_yaml_url: https://artifacts.apis.io/taiga/compliance/taiga-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Taiga's own page on 2026-11-10.
synthetic: false
tags:
- Agile
- Project Management
- Scrum
- Kanban
- Issue Tracking
- Open Source
- Sprints
- User Stories
- Epic
- Task
---
