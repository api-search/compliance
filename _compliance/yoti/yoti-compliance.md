---
api_specs:
- filename: yoti-accounts-api-openapi.yml
  format: yaml
  label: Yoti Accounts API
  slug: yoti-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-accounts-api-openapi.yml
- filename: yoti-ai-api-openapi.yml
  format: yaml
  label: Yoti AI API
  slug: yoti-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-ai-api-openapi.yml
- filename: yoti-oauth-api-openapi.yml
  format: yaml
  label: Yoti OAuth API
  slug: yoti-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-oauth-api-openapi.yml
- filename: yoti-path-api-openapi.yml
  format: yaml
  label: Yoti Path API
  slug: yoti-path-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-path-api-openapi.yml
- filename: yoti-poa-api-openapi.yml
  format: yaml
  label: Yoti Poa API
  slug: yoti-poa-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-poa-api-openapi.yml
- filename: yoti-sessions-api-openapi.yml
  format: yaml
  label: Yoti Sessions API
  slug: yoti-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/yoti/openapi/yoti-sessions-api-openapi.yml
claim_count: 8
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: one of the big four accounting firms
    period: annual
    report_access: unstated
    scope: Yoti business
    text: We undergo an annual SOC2 Type II security assessment by one of the big four accounting firms.
    type: SOC 2 Type II security assessment
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Our provision of ID Verification Services
    text: Our provision of ID Verification Services is certified as compliant with the ISO/IEC 27001:2022 international standard for Information Security.
    type: certification
  - framework: ISO9001
    issuer: null
    period: '2023'
    report_access: unstated
    scope: quality management system
    text: In 2023 we attained ISO 9001 certification for our quality management system .
    type: certification
  - framework: other
    issuer: British Standards Institution
    period: null
    report_access: unstated
    scope: age-check services
    text: our age-check services were validated as being in compliance with the British Standards Institution’s PAS 1296:2018 code of practice.
    type: PAS 1296:2018 compliance validation
  - framework: other
    issuer: UK government
    period: null
    report_access: unstated
    scope: identity checking low and medium levels of assurance
    text: We help clients meet low and medium levels of assurance when checking identity in accordance with the UK government’s Good Practice Guide 45.
    type: GPG 45 assurance support
  - framework: other
    issuer: German Association for Voluntary Self-Regulation of Digital Media service providers
    period: null
    report_access: on_request
    scope: age verification methods
    text: The German Association for Voluntary Self-Regulation of Digital Media service providers has approved our age verification methods to safely regulate access content for minors.
    type: age verification approval
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: products, services and operations built and run under GDPR / UK Data Protection Act 2018
    text: Yoti products, services and operations are built and run in a jurisdiction subject to the GDPR / UK Data Protection Act 2018
    type: compliance statement
  - framework: other
    issuer: B Lab
    period: since 2015
    report_access: unstated
    scope: social, environmental performance
    text: We have been a certified B Corp since 2015
    type: B Corp certification
  trust_center:
    url: https://www.yoti.com/security/
frameworks:
- GDPR
- ISO27001
- ISO9001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Yoti
provenance_date: '2026-11-10'
provider_name: Yoti
provider_slug: yoti
slug: yoti-compliance
source_date: '2026-11-10'
source_filename: yoti-compliance.yml
source_heading: Compliance
source_page: https://www.yoti.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Yoti\naid: yoti\nurl: https://www.yoti.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.yoti.com/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II security assessment\n  scope: Yoti business\n  period: annual\n  issuer: one of the big four accounting firms\n  report_access: unstated\n  text: We undergo an annual SOC2 Type II security assessment by one of the big four accounting firms.\n- framework: ISO27001\n  type: certification\n  scope: Our provision of ID Verification Services\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our provision of ID\
  \ Verification Services is certified as compliant with the ISO/IEC 27001:2022 international\n    standard for Information Security.\n- framework: ISO9001\n  type: certification\n  scope: quality management system\n  period: '2023'\n  issuer: null\n  report_access: unstated\n  text: In 2023 we attained ISO 9001 certification for our quality management system .\n- framework: other\n  type: PAS 1296:2018 compliance validation\n  scope: age-check services\n  period: null\n  issuer: British Standards Institution\n  report_access: unstated\n  text: our age-check services were validated as being in compliance with the British Standards Institution’s PAS\n    1296:2018 code of practice.\n- framework: other\n  type: GPG 45 assurance support\n  scope: identity checking low and medium levels of assurance\n  period: null\n  issuer: UK government\n  report_access: unstated\n  text: We help clients meet low and medium levels of assurance when checking identity in accordance with the UK\n    government’s\
  \ Good Practice Guide 45.\n- framework: other\n  type: age verification approval\n  scope: age verification methods\n  period: null\n  issuer: German Association for Voluntary Self-Regulation of Digital Media service providers\n  report_access: on_request\n  text: The German Association for Voluntary Self-Regulation of Digital Media service providers has approved our\n    age verification methods to safely regulate access content for minors.\n- framework: GDPR\n  type: compliance statement\n  scope: products, services and operations built and run under GDPR / UK Data Protection Act 2018\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yoti products, services and operations are built and run in a jurisdiction subject to the GDPR / UK Data\n    Protection Act 2018\n- framework: other\n  type: B Corp certification\n  scope: social, environmental performance\n  period: since 2015\n  issuer: B Lab\n  report_access: unstated\n  text: We have been a certified B Corp since 2015\n"
source_yaml_url: https://artifacts.apis.io/yoti/compliance/yoti-compliance.yml
stated_fields:
- attestations
summary_line: 8 quoted statements, read from Yoti's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Identity
- Verification
- DigitalID
- SDK
---
