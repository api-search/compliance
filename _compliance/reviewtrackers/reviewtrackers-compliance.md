---
claim_count: 4
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Yes. Upon request, ReviewTrackers will execute a BAA to meet your compliance requirements
    type: Business Associate Agreement
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: credit card data processed via Stripe
    text: All credit card data is stored securely with our credit card processor Stripe, who is a PCI Service Provider Level 1.
    type: compliance answer
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Are you part of the EU-US Privacy Shield and GDPR compliant? Yes.
    type: compliance answer
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: ReviewTrackers is a EU-U.S. Privacy Shield participant
    type: EU-U.S. Privacy Shield participant
  trust_center:
    url: https://www.reviewtrackers.com/terms-service/security/
frameworks:
- GDPR
- HIPAA
- PCI-DSS
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ReviewTrackers
provenance_date: '2026-11-10'
provider_name: ReviewTrackers
provider_slug: reviewtrackers
slug: reviewtrackers-compliance
source_date: '2026-11-10'
source_filename: reviewtrackers-compliance.yml
source_heading: Compliance
source_page: https://www.reviewtrackers.com/terms-service/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ReviewTrackers\naid: reviewtrackers\nurl: https://www.reviewtrackers.com/terms-service/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.reviewtrackers.com/terms-service/security/\nattestations:\n- framework: HIPAA\n  type: Business Associate Agreement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Yes. Upon request, ReviewTrackers will execute a BAA to meet your compliance requirements\n- framework: PCI-DSS\n  type: compliance answer\n  scope: credit card data processed via Stripe\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All\
  \ credit card data is stored securely with our credit card processor Stripe, who is a PCI Service Provider\n    Level 1.\n- framework: GDPR\n  type: compliance answer\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Are you part of the EU-US Privacy Shield and GDPR compliant? Yes.\n- framework: other\n  type: EU-U.S. Privacy Shield participant\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ReviewTrackers is a EU-U.S. Privacy Shield participant\n"
source_yaml_url: https://artifacts.apis.io/reviewtrackers/compliance/reviewtrackers-compliance.yml
stated_fields:
- attestations
summary_line: 4 quoted statements, read from ReviewTrackers's own page on 2026-11-10.
synthetic: false
tags:
- Reputation Management
- Review Monitoring
- Customer Feedback
- Sentiment Analytics
- Local SEO
- Online Reviews
- Multi-Location
- Customer Experience
- Review Response
- Local Listings
---
