---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Givecloud's payment partners
    text: Givecloud's payment partners are PCI DSS compliant, ensuring that all financial transactions are safe and secure.
    type: compliance of payment partners
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: Givecloud cybersecurity program
    text: Givecloud's cybersecurity program is aligned with the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF).
    type: aligned cybersecurity program
  trust_center:
    url: https://help.givecloud.com/en/articles/6045181-security
frameworks:
- NIST-CSF
- PCI-DSS
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Givecloud
provenance_date: '2026-11-09'
provider_name: Givecloud
provider_slug: givecloud
slug: givecloud-compliance
source_date: '2026-11-09'
source_filename: givecloud-compliance.yml
source_heading: Compliance
source_page: https://help.givecloud.com/en/articles/6045181-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Givecloud\naid: givecloud\nurl: https://help.givecloud.com/en/articles/6045181-security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://help.givecloud.com/en/articles/6045181-security\nattestations:\n- framework: PCI-DSS\n  type: compliance of payment partners\n  scope: Givecloud's payment partners\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Givecloud's payment partners are PCI DSS compliant, ensuring that all financial transactions are safe and\n    secure.\n- framework: NIST-CSF\n  type: aligned cybersecurity program\n  scope: Givecloud cybersecurity program\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: Givecloud's cybersecurity program is aligned with the National Institute of Standards and Technology (NIST)\n    Cybersecurity Framework (CSF).\n"
source_yaml_url: https://artifacts.apis.io/givecloud/compliance/givecloud-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Givecloud's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fundraising
- Non-Profit
- Software-as-a-Service
- Platform
---
