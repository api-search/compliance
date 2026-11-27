---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent CPA firm
    period: null
    report_access: nda
    scope: Security, Availability, and Confidentiality Trust Service Criteria
    text: The full report is available to customers and prospects under mutual NDA.
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: MontyCloud platform and privacy practices
    text: MontyCloud is GDPR compliant, aligned with the requirements set forth by the General Data Protection Regulation (EU) 2016/679.
    type: GDPR compliance
  trust_center:
    url: https://montycloud.com/trust-center/
frameworks:
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MontyCloud
provenance_date: '2026-11-10'
provider_name: MontyCloud
provider_slug: montycloud
slug: montycloud-compliance
source_date: '2026-11-10'
source_filename: montycloud-compliance.yml
source_heading: Compliance
source_page: https://montycloud.com/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MontyCloud\naid: montycloud\nurl: https://montycloud.com/trust-center/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/montycloud-trust-center.yml\ntrust_center:\n  url: https://montycloud.com/trust-center/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: Security, Availability, and Confidentiality Trust Service Criteria\n  period: null\n  issuer: independent CPA firm\n  report_access: nda\n  text: The full report is available to customers and prospects under mutual NDA.\n- framework: GDPR\n  type: GDPR compliance\n  scope: MontyCloud platform and privacy practices\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: MontyCloud is GDPR compliant, aligned with the requirements set forth by the General Data Protection Regulation\n    (EU) 2016/679.\n"
source_yaml_url: https://artifacts.apis.io/montycloud/compliance/montycloud-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from MontyCloud's own page on 2026-11-10.
synthetic: false
tags:
- Cloud
- Cloud Operations
- Amazon Web Services
- Managed Service Providers
- Governance
- Compliance
- Cost Management
- Artificial Intelligence
- Agents
- MCP
- Multi-Tenant
- Infrastructure
---
