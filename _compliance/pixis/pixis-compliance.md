---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Our processes meet internationally recognized security and data management standards, ensuring the highest level of protection.
    type: ISO
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We adhere to rigorous security, availability, and confidentiality controls when it comes to handling sensitive data.
    type: SOC-2
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Pixis is fully compliant with GDPR regulations, ensuring personal data is handled with transparency, integrity, and user consent.
    type: compliance
  trust_center:
    url: https://pixis.ai/products/compliance/
frameworks:
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Pixis
provenance_date: '2026-11-10'
provider_name: Pixis
provider_slug: pixis
slug: pixis-compliance
source_date: '2026-11-10'
source_filename: pixis-compliance.yml
source_heading: Compliance
source_page: https://pixis.ai/products/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Pixis\naid: pixis\nurl: https://pixis.ai/products/compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/pixis-trust-center.yml\ntrust_center:\n  url: https://pixis.ai/products/compliance/\nattestations:\n- framework: other\n  type: ISO\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our processes meet internationally recognized security and data management standards, ensuring the highest\n    level of protection.\n- framework: SOC2\n  type: SOC-2\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We adhere to rigorous security,\
  \ availability, and confidentiality controls when it comes to handling sensitive\n    data.\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Pixis is fully compliant with GDPR regulations, ensuring personal data is handled with transparency, integrity,\n    and user consent.\n"
source_yaml_url: https://artifacts.apis.io/pixis/compliance/pixis-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Pixis's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise
- Advertising
- Marketing
- Artificial Intelligence
- Generative AI
- AdTech
- Marketing Automation
---
