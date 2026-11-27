---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Knox Cloud at FedRAMP Moderate and High
    text: Knox currently supports FedRAMP Moderate, FedRAMP High, and DoD IL4.
    type: Authorization to Operate (ATO)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Knox Cloud
    text: Deployed on AWS, Azure, and GCP at FedRAMP Moderate, High, and DISA IL4, with 15 ATOs.
    type: DoD IL4 authorization
  trust_center:
    url: https://knoxsystems.com/platform
frameworks:
- FedRAMP
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Knox Systems
provenance_date: '2026-11-09'
provider_name: Knox Systems
provider_slug: knoxsystems
slug: knoxsystems-compliance
source_date: '2026-11-09'
source_filename: knoxsystems-compliance.yml
source_heading: Compliance
source_page: https://knoxsystems.com/platform
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Knox Systems\naid: knoxsystems\nurl: https://knoxsystems.com/platform\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://knoxsystems.com/platform\nattestations:\n- framework: FedRAMP\n  type: Authorization to Operate (ATO)\n  scope: Knox Cloud at FedRAMP Moderate and High\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Knox currently supports FedRAMP Moderate, FedRAMP High, and DoD IL4.\n- framework: other\n  type: DoD IL4 authorization\n  scope: Knox Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Deployed on AWS, Azure, and GCP at FedRAMP Moderate, High, and\
  \ DISA IL4, with 15 ATOs.\n"
source_yaml_url: https://artifacts.apis.io/knoxsystems/compliance/knoxsystems-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Knox Systems's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Compliance
- Security
- Government
- FedRAMP
- Cloud
- Artificial Intelligence
- Public Sector
- Governance
- Managed Service
---
