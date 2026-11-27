---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: ISO9001
    issuer: null
    period: null
    report_access: public
    scope: quality management system
    text: EcoVadis has developed a quality management system (QMS) which is certified ISO 9001
    type: certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: information security management system
    text: EcoVadis has established an Information Security management system (ISMS) which undergoes regular independent third-party audits for ISO/IEC 27001 compliance
    type: certification
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: personal data protection
    text: We use the complementary ISO 27701 framework to meet GDPR and data protection requirements.
    type: framework
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data of EU citizens
    text: Ecovadis is committed to comply with GDPR
    type: compliance commitment
  trust_center:
    url: https://ecovadis.com/trust-center/
frameworks:
- GDPR
- ISO27001
- ISO27701
- ISO9001
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ecovadis
provenance_date: '2026-11-09'
provider_name: Ecovadis
provider_slug: ecovadis
slug: ecovadis-compliance
source_date: '2026-11-09'
source_filename: ecovadis-compliance.yml
source_heading: Compliance
source_page: https://ecovadis.com/trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ecovadis\naid: ecovadis\nurl: https://ecovadis.com/trust-center/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ecovadis-trust-center.yml\ntrust_center:\n  url: https://ecovadis.com/trust-center/\nattestations:\n- framework: ISO9001\n  type: certification\n  scope: quality management system\n  period: null\n  issuer: null\n  report_access: public\n  text: EcoVadis has developed a quality management system (QMS) which is certified ISO 9001\n- framework: ISO27001\n  type: certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: public\n  text:\
  \ EcoVadis has established an Information Security management system (ISMS) which undergoes regular independent\n    third-party audits for ISO/IEC 27001 compliance\n- framework: ISO27701\n  type: framework\n  scope: personal data protection\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We use the complementary ISO 27701 framework to meet GDPR and data protection requirements.\n- framework: GDPR\n  type: compliance commitment\n  scope: personal data of EU citizens\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Ecovadis is committed to comply with GDPR\n"
source_yaml_url: https://artifacts.apis.io/ecovadis/compliance/ecovadis-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from Ecovadis's own page on 2026-11-09.
synthetic: false
tags:
- Business
- Environment
- Ratings
- Sustainability
---
