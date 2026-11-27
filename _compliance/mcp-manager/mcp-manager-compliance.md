---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: '2025'
    report_access: on_request
    scope: null
    text: SOC 2 Type 2 + HIPAA report (2025)
    type: Type 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: As a HIPAA-compliant platform, MCP Manager signs Business Associate Agreements (BAAs)
    type: null
  - framework: ISO27001
    issuer: null
    period: '2022'
    report_access: unstated
    scope: null
    text: ISO 27001:2022 & ISO 27701:2019 certificates
    type: certificate
  - framework: ISO27701
    issuer: null
    period: '2019'
    report_access: unstated
    scope: null
    text: ISO 27001:2022 & ISO 27701:2019 certificates
    type: certificate
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: Level 3
    text: TISAX Level 3 assessment result
    type: assessment result
  trust_center:
    url: https://docs.mcpmanager.ai/enterprise/security-and-compliance.md
frameworks:
- HIPAA
- ISO27001
- ISO27701
- SOC2
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MCP Manager
provenance_date: '2026-11-10'
provider_name: MCP Manager
provider_slug: mcp-manager
slug: mcp-manager-compliance
source_date: '2026-11-10'
source_filename: mcp-manager-compliance.yml
source_heading: Compliance
source_page: https://docs.mcpmanager.ai/enterprise/security-and-compliance.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MCP Manager\naid: mcp-manager\nurl: https://docs.mcpmanager.ai/enterprise/security-and-compliance.md\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mcp-manager-trust-center.yml\ntrust_center:\n  url: https://docs.mcpmanager.ai/enterprise/security-and-compliance.md\nattestations:\n- framework: SOC2\n  type: Type 2\n  scope: null\n  period: '2025'\n  issuer: null\n  report_access: on_request\n  text: SOC 2 Type 2 + HIPAA report (2025)\n- framework: HIPAA\n  type: null\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: As a HIPAA-compliant platform, MCP Manager signs Business\
  \ Associate Agreements (BAAs)\n- framework: ISO27001\n  type: certificate\n  scope: null\n  period: '2022'\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 & ISO 27701:2019 certificates\n- framework: ISO27701\n  type: certificate\n  scope: null\n  period: '2019'\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2022 & ISO 27701:2019 certificates\n- framework: TISAX\n  type: assessment result\n  scope: Level 3\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TISAX Level 3 assessment result\n"
source_yaml_url: https://artifacts.apis.io/mcp-manager/compliance/mcp-manager-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from MCP Manager's own page on 2026-11-10.
synthetic: false
tags:
- Company
- MCP
- AI Governance
- API Gateway
- Security
- Observability
- DLP
- Identity
- RBAC
- Enterprise
---
