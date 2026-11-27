---
api_specs:
- filename: github-copilot-copilot-api-openapi.yml
  format: yaml
  label: GitHub Copilot Copilot API
  slug: github-copilot-copilot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-copilot-api-openapi.yml
- filename: github-copilot-copilot-spaces-api-openapi.yml
  format: yaml
  label: GitHub Copilot Copilot Spaces API
  slug: github-copilot-copilot-spaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-copilot-spaces-api-openapi.yml
- filename: github-copilot-merge-queue-api-openapi.yml
  format: yaml
  label: GitHub Copilot Merge Queue API
  slug: github-copilot-merge-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-merge-queue-api-openapi.yml
- filename: github-copilot-pulls-api-openapi.yml
  format: yaml
  label: GitHub Copilot Pulls API
  slug: github-copilot-pulls-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/github-copilot/openapi/github-copilot-pulls-api-openapi.yml
claim_count: 15
description: ''
doc:
  attestations:
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 1 Type 2 Report
    type: SOC 1 Type 2 Report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type 2 Report
    type: SOC 2 Type 2 Report
  - framework: SOC3
    issuer: null
    period: April - September 2025
    report_access: unstated
    scope: null
    text: GitHub SOC 3 Report April - September 2025
    type: SOC 3 Report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ISO 27001:2013
    type: ISO 27001:2013
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: CSA STAR Level 2
    type: CSA STAR Level 2
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: TISAX
    type: TISAX
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: GitHub Copilot portfolio
    text: GitHub achieves ISO/IEC 42001 Certification
    type: ISO/IEC 42001:2023 certification
  - framework: PCI-DSS
    issuer: null
    period: '2026'
    report_access: unstated
    scope: null
    text: 2026 GitHub PCI DSS v4.0.1 Shared Responsibility Matrix.xlsx
    type: PCI DSS v4.0.1 shared responsibility matrix
  - framework: SOC1
    issuer: null
    period: null
    report_access: unstated
    scope: GitHub Copilot
    source: https://copilot.github.trust.page/
    text: SOC 1 Type 2 Report
    type: SOC 1 Type 2 Report
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: GitHub Copilot
    source: https://copilot.github.trust.page/
    text: SOC 2 Type 2 Report
    type: SOC 2 Type 2 Report
  - framework: SOC3
    issuer: null
    period: April - September 2025
    report_access: unstated
    scope: GitHub Copilot
    source: https://copilot.github.trust.page/
    text: GitHub SOC 3 Report April - September 2025
    type: SOC 3 Report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://copilot.github.trust.page/
    text: ISO 27001:2013
    type: ISO 27001:2013 certification
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://copilot.github.trust.page/
    text: CSA STAR Level 2
    type: CSA STAR Level 2
  - framework: TISAX
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://copilot.github.trust.page/
    text: TISAX
    type: TISAX
  - framework: ISO42001
    issuer: null
    period: null
    report_access: unstated
    scope: GitHub Copilot portfolio
    source: https://copilot.github.trust.page/
    text: GitHub is extending ISO/IEC 42001:2023 certification across the GitHub Copilot portfolio
    type: ISO/IEC 42001:2023 certification
  trust_center:
    url: https://copilot.github.trust.page/
frameworks:
- CSA-STAR
- ISO27001
- ISO42001
- PCI-DSS
- SOC1
- SOC2
- SOC3
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: GitHub Copilot
provenance_date: '2026-11-09'
provider_name: GitHub Copilot
provider_slug: github-copilot
slug: github-copilot-compliance
source_date: '2026-11-09'
source_filename: github-copilot-compliance.yml
source_heading: Compliance
source_page: https://copilot.github.trust.page/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: GitHub Copilot\naid: github-copilot\nurl: https://copilot.github.trust.page/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/github-copilot-trust-center.yml\n  sources:\n  - https://copilot.github.trust.page/\ntrust_center:\n  url: https://copilot.github.trust.page/\nattestations:\n- framework: SOC1\n  type: SOC 1 Type 2 Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type 2 Report\n- framework: SOC2\n  type: SOC 2 Type 2 Report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Report\n- framework: SOC3\n\
  \  type: SOC 3 Report\n  scope: null\n  period: April - September 2025\n  issuer: null\n  report_access: unstated\n  text: GitHub SOC 3 Report April - September 2025\n- framework: ISO27001\n  type: ISO 27001:2013\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2013\n- framework: CSA-STAR\n  type: CSA STAR Level 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR Level 2\n- framework: TISAX\n  type: TISAX\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TISAX\n- framework: ISO42001\n  type: ISO/IEC 42001:2023 certification\n  scope: GitHub Copilot portfolio\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GitHub achieves ISO/IEC 42001 Certification\n- framework: PCI-DSS\n  type: PCI DSS v4.0.1 shared responsibility matrix\n  scope: null\n  period: '2026'\n  issuer: null\n  report_access: unstated\n  text: 2026 GitHub PCI DSS v4.0.1 Shared Responsibility\
  \ Matrix.xlsx\n- framework: SOC1\n  type: SOC 1 Type 2 Report\n  scope: GitHub Copilot\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 1 Type 2 Report\n  source: https://copilot.github.trust.page/\n- framework: SOC2\n  type: SOC 2 Type 2 Report\n  scope: GitHub Copilot\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type 2 Report\n  source: https://copilot.github.trust.page/\n- framework: SOC3\n  type: SOC 3 Report\n  scope: GitHub Copilot\n  period: April - September 2025\n  issuer: null\n  report_access: unstated\n  text: GitHub SOC 3 Report April - September 2025\n  source: https://copilot.github.trust.page/\n- framework: ISO27001\n  type: ISO 27001:2013 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001:2013\n  source: https://copilot.github.trust.page/\n- framework: CSA-STAR\n  type: CSA STAR Level 2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n \
  \ text: CSA STAR Level 2\n  source: https://copilot.github.trust.page/\n- framework: TISAX\n  type: TISAX\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: TISAX\n  source: https://copilot.github.trust.page/\n- framework: ISO42001\n  type: ISO/IEC 42001:2023 certification\n  scope: GitHub Copilot portfolio\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GitHub is extending ISO/IEC 42001:2023 certification across the GitHub Copilot portfolio\n  source: https://copilot.github.trust.page/\n"
source_yaml_url: https://artifacts.apis.io/github-copilot/compliance/github-copilot-compliance.yml
stated_fields:
- attestations
summary_line: 15 quoted statements, read from GitHub Copilot's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- Artificial Intelligence
- Code Generation
- Code Review
- Coding Agents
- Custom Instructions
- Developer Tools
- Extensions
- IDE
- Machine Learning
- MCP
- Metrics
- Productivity
---
