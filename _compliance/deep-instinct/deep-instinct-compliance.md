---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AICPA
    period: null
    report_access: on_request
    scope: null
    text: Deep Instinct is certified as SOC 2 Type II in accordance with the AICPA framework.
    type: Type II
  - framework: PCI-DSS
    issuer: Coalfire Systems, Inc.
    period: null
    report_access: unstated
    scope: Deep Instinct Endpoint Protection
    text: Deep Instinct Endpoint Protection was validated by Coalfire Systems , Inc.
    type: validation
  - framework: GDPR
    issuer: Coalfire Systems, Inc.
    period: null
    report_access: unstated
    scope: zero-time threat prevention platform
    text: Deep Instinct’s zero-time threat prevention platform was validated as suitable to meet t he General Data Protection Regulation (GDPR) requirements for protection of personal data.
    type: validation
  trust_center:
    url: https://www.deepinstinct.com/compliance-certification-evaluation
frameworks:
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Deep Instinct
provenance_date: '2026-11-09'
provider_name: Deep Instinct
provider_slug: deep-instinct
slug: deep-instinct-compliance
source_date: '2026-11-09'
source_filename: deep-instinct-compliance.yml
source_heading: Compliance
source_page: https://www.deepinstinct.com/compliance-certification-evaluation
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Deep Instinct\naid: deep-instinct\nurl: https://www.deepinstinct.com/compliance-certification-evaluation\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.deepinstinct.com/compliance-certification-evaluation\nattestations:\n- framework: SOC2\n  type: Type II\n  scope: null\n  period: null\n  issuer: AICPA\n  report_access: on_request\n  text: Deep Instinct is certified as SOC 2 Type II in accordance with the AICPA framework.\n- framework: PCI-DSS\n  type: validation\n  scope: Deep Instinct Endpoint Protection\n  period: null\n  issuer: Coalfire Systems, Inc.\n  report_access: unstated\n  text: Deep\
  \ Instinct Endpoint Protection was validated by Coalfire Systems , Inc.\n- framework: GDPR\n  type: validation\n  scope: zero-time threat prevention platform\n  period: null\n  issuer: Coalfire Systems, Inc.\n  report_access: unstated\n  text: Deep Instinct’s zero-time threat prevention platform was validated as suitable to meet t he General Data\n    Protection Regulation (GDPR) requirements for protection of personal data.\n"
source_yaml_url: https://artifacts.apis.io/deep-instinct/compliance/deep-instinct-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Deep Instinct's own page on 2026-11-09.
synthetic: false
tags:
- Cybersecurity
- Endpoint Security
- malware-prevention
- Ransomware
- Deep Learning
- Threat Prevention
- Data Security
- Endpoint Detection and Response
- SOC Automation
- MCP
---
