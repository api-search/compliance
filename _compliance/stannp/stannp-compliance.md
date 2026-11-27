---
api_specs:
- filename: stannp-account-api-openapi.yml
  format: yaml
  label: Stannp Account API
  slug: stannp-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-account-api-openapi.yml
- filename: stannp-campaigns-api-openapi.yml
  format: yaml
  label: Stannp Campaigns API
  slug: stannp-campaigns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-campaigns-api-openapi.yml
- filename: stannp-events-api-openapi.yml
  format: yaml
  label: Stannp Events API
  slug: stannp-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-events-api-openapi.yml
- filename: stannp-groups-api-openapi.yml
  format: yaml
  label: Stannp Groups API
  slug: stannp-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-groups-api-openapi.yml
- filename: stannp-letters-api-openapi.yml
  format: yaml
  label: Stannp Letters API
  slug: stannp-letters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-letters-api-openapi.yml
- filename: stannp-postcards-api-openapi.yml
  format: yaml
  label: Stannp Postcards API
  slug: stannp-postcards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-postcards-api-openapi.yml
- filename: stannp-recipients-api-openapi.yml
  format: yaml
  label: Stannp Recipients API
  slug: stannp-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stannp/openapi/stannp-recipients-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: processing of patient information / protected health information
    text: we are HIPAA compliant, offering assurances to our clients that we comply to and follow strict physical, network and process security measures when handling protected health information (PHI)
    type: HIPAA compliance statement
  - framework: other
    issuer: USPS (The United States Postal Service)
    period: null
    report_access: unstated
    scope: US address data formatting and handling
    text: Stannp.com is CASS certified by USPS (The United States Postal Service).
    type: USPS CASS certification
  - framework: other
    issuer: Royal Mail
    period: null
    report_access: unstated
    scope: UK address data verification via Postal Address File
    text: Stannp.com is accredited by Royal Mail as a Postal Address File (PAF) partner.
    type: Royal Mail PAF accreditation
  - framework: other
    issuer: Royal Mail
    period: null
    report_access: unstated
    scope: mail campaign delivery
    text: Stannp.com is accredited by Royal Mail as a Mail Made Easy partner.
    type: Royal Mail Mail Made Easy partner accreditation
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Stannp role as Business Associate and safeguards for Protected Health Information
    source: https://www.stannp.com/us/trust
    text: Explore our proactive approach to HIPAA compliance, including our role as a Business Associate, safeguards for Protected Health Information
    type: HIPAA compliance approach
  trust_center:
    url: https://www.stannp.com/us/accreditations
frameworks:
- HIPAA
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Stannp
provenance_date: '2026-11-10'
provider_name: Stannp
provider_slug: stannp
slug: stannp-compliance
source_date: '2026-11-10'
source_filename: stannp-compliance.yml
source_heading: Compliance
source_page: https://www.stannp.com/us/accreditations
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Stannp\naid: stannp\nurl: https://www.stannp.com/us/accreditations\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://www.stannp.com/us/accreditations\n  - https://www.stannp.com/us/trust\ntrust_center:\n  url: https://www.stannp.com/us/accreditations\nattestations:\n- framework: HIPAA\n  type: HIPAA compliance statement\n  scope: processing of patient information / protected health information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: we are HIPAA compliant, offering assurances to our clients that we comply to and follow strict physical,\n    network and process security measures when\
  \ handling protected health information (PHI)\n- framework: other\n  type: USPS CASS certification\n  scope: US address data formatting and handling\n  period: null\n  issuer: USPS (The United States Postal Service)\n  report_access: unstated\n  text: Stannp.com is CASS certified by USPS (The United States Postal Service).\n- framework: other\n  type: Royal Mail PAF accreditation\n  scope: UK address data verification via Postal Address File\n  period: null\n  issuer: Royal Mail\n  report_access: unstated\n  text: Stannp.com is accredited by Royal Mail as a Postal Address File (PAF) partner.\n- framework: other\n  type: Royal Mail Mail Made Easy partner accreditation\n  scope: mail campaign delivery\n  period: null\n  issuer: Royal Mail\n  report_access: unstated\n  text: Stannp.com is accredited by Royal Mail as a Mail Made Easy partner.\n- framework: HIPAA\n  type: HIPAA compliance approach\n  scope: Stannp role as Business Associate and safeguards for Protected Health Information\n\
  \  period: null\n  issuer: null\n  report_access: unstated\n  text: Explore our proactive approach to HIPAA compliance, including our role as a Business Associate, safeguards\n    for Protected Health Information\n  source: https://www.stannp.com/us/trust\n"
source_yaml_url: https://artifacts.apis.io/stannp/compliance/stannp-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Stannp's own page on 2026-11-10.
synthetic: false
tags:
- Direct Mail
- Postcards
- Letters
- Print
- Physical Mail
- Marketing Automation
- Campaigns
- Address Verification
- SMS
- Webhook
- Mailing Lists
- Fulfillment
---
