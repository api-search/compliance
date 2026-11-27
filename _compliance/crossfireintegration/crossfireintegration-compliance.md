---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: null
    text: Check the certificate on the JAS-ANZ register
    type: certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Personal data belonging to EU and EEA citizens
    text: GDPR compliant.
    type: compliance statement
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: eInvoicing service
    text: Certified PEPPOL Access Point.
    type: PEPPOL Access Point certification
  trust_center:
    url: https://crossfireintegration.com/security
frameworks:
- GDPR
- ISO27001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Sandfield
provenance_date: '2026-11-09'
provider_name: Sandfield
provider_slug: crossfireintegration
slug: crossfireintegration-compliance
source_date: '2026-11-09'
source_filename: crossfireintegration-compliance.yml
source_heading: Compliance
source_page: https://crossfireintegration.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Sandfield\naid: crossfireintegration\nurl: https://crossfireintegration.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://crossfireintegration.com/security\nattestations:\n- framework: ISO27001\n  type: certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: public\n  text: Check the certificate on the JAS-ANZ register\n- framework: GDPR\n  type: compliance statement\n  scope: Personal data belonging to EU and EEA citizens\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR compliant.\n- framework: other\n  type: PEPPOL Access Point certification\n\
  \  scope: eInvoicing service\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Certified PEPPOL Access Point.\n"
source_yaml_url: https://artifacts.apis.io/crossfireintegration/compliance/crossfireintegration-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Sandfield's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Integration
- EDI
- Supply Chain
---
