---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: own custody facility for storage of user assets
    text: We maintain our own PCI DSS / SOC 2 compliant facility for the storage of your assets.
    type: compliance claim
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: custody storage of user assets
    text: PCI DSS & SOC 2 Compliant Custody
    type: compliance claim
  trust_center:
    url: https://www.blocpal.com/security
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: BlocPal
provenance_date: '2026-11-09'
provider_name: BlocPal
provider_slug: blocpal
slug: blocpal-compliance
source_date: '2026-11-09'
source_filename: blocpal-compliance.yml
source_heading: Compliance
source_page: https://www.blocpal.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: BlocPal\naid: blocpal\nurl: https://www.blocpal.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.blocpal.com/security\nattestations:\n- framework: PCI-DSS\n  type: compliance claim\n  scope: own custody facility for storage of user assets\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We maintain our own PCI DSS / SOC 2 compliant facility for the storage of your assets.\n- framework: SOC2\n  type: compliance claim\n  scope: custody storage of user assets\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS & SOC 2 Compliant Custody\n"
source_yaml_url: https://artifacts.apis.io/blocpal/compliance/blocpal-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from BlocPal's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Digital Banking
- Wealth Management
- Blockchain
---
