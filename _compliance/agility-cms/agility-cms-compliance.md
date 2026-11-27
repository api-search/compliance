---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: on_request
    scope: Agility platform
    text: For access to our SOC 2 Type 2 report, security questionnaires, and detailed policy documentation, visit our Trust Center .
    type: SOC 2 Type 2 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Agility's Content Manager
    text: Agility's Content Manager is declared to be PCI Compliant.
    type: declared PCI compliant
  trust_center:
    url: https://agilitycms.com/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Agility CMS
provenance_date: '2026-11-09'
provider_name: Agility CMS
provider_slug: agility-cms
slug: agility-cms-compliance
source_date: '2026-11-09'
source_filename: agility-cms-compliance.yml
source_heading: Compliance
source_page: https://agilitycms.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Agility CMS\naid: agility-cms\nurl: https://agilitycms.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/agility-cms-trust-center.yml\ntrust_center:\n  url: https://agilitycms.com/security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 report\n  scope: Agility platform\n  period: null\n  issuer: independent auditor\n  report_access: on_request\n  text: For access to our SOC 2 Type 2 report, security questionnaires, and detailed policy documentation, visit\n    our Trust Center .\n- framework: PCI-DSS\n  type: declared PCI compliant\n  scope: Agility's Content Manager\n  period:\
  \ null\n  issuer: null\n  report_access: unstated\n  text: Agility's Content Manager is declared to be PCI Compliant.\n"
source_yaml_url: https://artifacts.apis.io/agility-cms/compliance/agility-cms-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Agility CMS's own page on 2026-11-09.
synthetic: false
tags:
- GraphQL
- Headless CMS
- Content Management
- REST
- Multi-Site
---
