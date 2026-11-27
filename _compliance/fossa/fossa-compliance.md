---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: unstated
    period: null
    report_access: unstated
    scope: unstated
    text: SOC 2 Compliance
    type: unstated
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://fossa.com/trust/
    text: SOC 2 Compliance
    type: SOC 2 compliance
  trust_center:
    url: https://fossa.com/trust/
frameworks:
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Fossa
provenance_date: '2026-11-09'
provider_name: Fossa
provider_slug: fossa
slug: fossa-compliance
source_date: '2026-11-09'
source_filename: fossa-compliance.yml
source_heading: Compliance
source_page: https://fossa.com/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Fossa\naid: fossa\nurl: https://fossa.com/trust/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/fossa-trust-center.yml\n  sources:\n  - https://fossa.com/trust/\ntrust_center:\n  url: https://fossa.com/trust/\nattestations:\n- framework: SOC2\n  type: unstated\n  scope: unstated\n  period: null\n  issuer: unstated\n  report_access: unstated\n  text: SOC 2 Compliance\n- framework: SOC2\n  type: SOC 2 compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Compliance\n  source: https://fossa.com/trust/\n"
source_yaml_url: https://artifacts.apis.io/fossa/compliance/fossa-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Fossa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Security
- Software Supply Chain
- Open Source
- License Compliance
- Vulnerability Management
- SBOM
- Software Composition Analysis
- DevSecOps
---
