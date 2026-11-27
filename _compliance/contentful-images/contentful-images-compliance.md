---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: accredited third-party certification body
    period: null
    report_access: on_request
    scope: Security program governed by ISMS
    text: Our security program is governed by an Information Security Management System (ISMS) certified to ISO/IEC 27001:2022.
    type: ISO/IEC 27001:2022 certification of ISMS
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: controls relating to security, availability, and confidentiality
    text: Contentful maintains an independent SOC 2 Type 2 examination, providing assurance over the design and operating effectiveness of controls relating to security, availability, and confidentiality.
    type: SOC 2 Type 2 examination
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 3
    type: SOC 3 report
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: PCI DSS SAQ A
    type: PCI DSS SAQ A
  - framework: TISAX
    issuer: TÜV Rheinland
    period: null
    report_access: unstated
    scope: Contentful GmbH
    text: TISAX assessment results are not publicly available.
    type: TISAX assessment
  trust_center:
    url: https://www.contentful.com/security/
frameworks:
- ISO27001
- PCI-DSS
- SOC2
- SOC3
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Contentful Images
provenance_date: '2026-11-09'
provider_name: Contentful Images
provider_slug: contentful-images
slug: contentful-images-compliance
source_date: '2026-11-09'
source_filename: contentful-images-compliance.yml
source_heading: Compliance
source_page: https://www.contentful.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Contentful Images\naid: contentful-images\nurl: https://www.contentful.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/contentful-images-trust-center.yml\ntrust_center:\n  url: https://www.contentful.com/security/\nattestations:\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification of ISMS\n  scope: Security program governed by ISMS\n  period: null\n  issuer: accredited third-party certification body\n  report_access: on_request\n  text: Our security program is governed by an Information Security Management System (ISMS) certified to ISO/IEC\n    27001:2022.\n- framework: SOC2\n\
  \  type: SOC 2 Type 2 examination\n  scope: controls relating to security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Contentful maintains an independent SOC 2 Type 2 examination, providing assurance over the design and operating\n    effectiveness of controls relating to security, availability, and confidentiality.\n- framework: SOC3\n  type: SOC 3 report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 3\n- framework: PCI-DSS\n  type: PCI DSS SAQ A\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: PCI DSS SAQ A\n- framework: TISAX\n  type: TISAX assessment\n  scope: Contentful GmbH\n  period: null\n  issuer: TÜV Rheinland\n  report_access: unstated\n  text: TISAX assessment results are not publicly available.\n"
source_yaml_url: https://artifacts.apis.io/contentful-images/compliance/contentful-images-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Contentful Images's own page on 2026-11-09.
synthetic: false
tags:
- Development
- Public APIs
---
