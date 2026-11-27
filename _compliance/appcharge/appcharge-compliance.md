---
api_specs:
- filename: appcharge-assets-api-openapi.yml
  format: yaml
  label: Appcharge Assets API
  slug: appcharge-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-assets-api-openapi.yml
- filename: appcharge-authentication-api-openapi.yml
  format: yaml
  label: Appcharge Authentication API
  slug: appcharge-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-authentication-api-openapi.yml
- filename: appcharge-badges-api-openapi.yml
  format: yaml
  label: Appcharge Badges API
  slug: appcharge-badges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-badges-api-openapi.yml
- filename: appcharge-coupons-api-openapi.yml
  format: yaml
  label: Appcharge Coupons API
  slug: appcharge-coupons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-coupons-api-openapi.yml
- filename: appcharge-general-api-openapi.yml
  format: yaml
  label: Appcharge General API
  slug: appcharge-general-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-general-api-openapi.yml
- filename: appcharge-localization-api-openapi.yml
  format: yaml
  label: Appcharge Localization API
  slug: appcharge-localization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-localization-api-openapi.yml
- filename: appcharge-offer-designs-api-openapi.yml
  format: yaml
  label: Appcharge Offer Designs API
  slug: appcharge-offer-designs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-offer-designs-api-openapi.yml
- filename: appcharge-offers-api-openapi.yml
  format: yaml
  label: Appcharge Offers API
  slug: appcharge-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-offers-api-openapi.yml
- filename: appcharge-orders-api-openapi.yml
  format: yaml
  label: Appcharge Orders API
  slug: appcharge-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-orders-api-openapi.yml
- filename: appcharge-personalization-api-openapi.yml
  format: yaml
  label: Appcharge Personalization API
  slug: appcharge-personalization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-personalization-api-openapi.yml
- filename: appcharge-popups-api-openapi.yml
  format: yaml
  label: Appcharge Popups API
  slug: appcharge-popups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-popups-api-openapi.yml
- filename: appcharge-portal-content-api-openapi.yml
  format: yaml
  label: Appcharge Portal Content API
  slug: appcharge-portal-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-portal-content-api-openapi.yml
- filename: appcharge-products-api-openapi.yml
  format: yaml
  label: Appcharge Products API
  slug: appcharge-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-products-api-openapi.yml
- filename: appcharge-promo-codes-api-openapi.yml
  format: yaml
  label: Appcharge Promo Codes API
  slug: appcharge-promo-codes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-promo-codes-api-openapi.yml
- filename: appcharge-rolling-offers-api-openapi.yml
  format: yaml
  label: Appcharge Rolling Offers API
  slug: appcharge-rolling-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-rolling-offers-api-openapi.yml
- filename: appcharge-store-refresh-popups-api-openapi.yml
  format: yaml
  label: Appcharge Store Refresh Popups API
  slug: appcharge-store-refresh-popups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-store-refresh-popups-api-openapi.yml
- filename: appcharge-triggered-popups-api-openapi.yml
  format: yaml
  label: Appcharge Triggered Popups API
  slug: appcharge-triggered-popups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appcharge/openapi/appcharge-triggered-popups-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: PCI-DSS
    issuer: independent Qualified Security Assessors
    period: null
    report_access: unstated
    scope: platform handling payment transactions
    text: Appcharge is fully compliant with the Payment Card Industry Data Security Standard (PCI-DSS) at Level 1 – the highest level of certification.
    type: certification (Level 1)
  - framework: SOC2
    issuer: independent auditors
    period: null
    report_access: nda
    scope: security, availability, and confidentiality principles under AICPA Trust Services Criteria
    text: we can furnish our latest SOC 2 Type II report under NDA upon request.
    type: SOC 2 Type II audit
  trust_center:
    url: https://docs.appcharge.com/merchant-of-record/security/about-security-at-appcharge
frameworks:
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Appcharge
provenance_date: '2026-11-09'
provider_name: Appcharge
provider_slug: appcharge
slug: appcharge-compliance
source_date: '2026-11-09'
source_filename: appcharge-compliance.yml
source_heading: Compliance
source_page: https://docs.appcharge.com/merchant-of-record/security/about-security-at-appcharge
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Appcharge\naid: appcharge\nurl: https://docs.appcharge.com/merchant-of-record/security/about-security-at-appcharge\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://docs.appcharge.com/merchant-of-record/security/about-security-at-appcharge\nattestations:\n- framework: PCI-DSS\n  type: certification (Level 1)\n  scope: platform handling payment transactions\n  period: null\n  issuer: independent Qualified Security Assessors\n  report_access: unstated\n  text: Appcharge is fully compliant with the Payment Card Industry Data Security Standard (PCI-DSS) at Level 1\n    – the highest level of certification.\n\
  - framework: SOC2\n  type: SOC 2 Type II audit\n  scope: security, availability, and confidentiality principles under AICPA Trust Services Criteria\n  period: null\n  issuer: independent auditors\n  report_access: nda\n  text: we can furnish our latest SOC 2 Type II report under NDA upon request.\n"
source_yaml_url: https://artifacts.apis.io/appcharge/compliance/appcharge-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Appcharge's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Monetization
- Merchant of Record
- Mobile Games
- Gaming
- Checkout
- In-Game Purchases
- Web Store
- E-Commerce
---
