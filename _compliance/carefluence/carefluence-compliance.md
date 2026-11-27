---
api_specs:
- filename: postman.yaml
  format: yaml
  label: Carefluence Open API R4
  slug: openapi-r4
  spec_type: Postman
  url: https://api.carefluence.com/
claim_count: 1
description: ''
doc:
  attestations:
  - framework: other
    issuer: Drummond Group (ONC-ACB)
    period: Certified on June 29, 2022
    report_access: unstated
    scope: Carefluence Open API R4
    text: Carefluence’s Open API R4 has been certified on June 29, 2022, under the unique certification number 15.04.04.2657.Care.R4.01.0.220629.
    type: ONC Health IT certification (170.315 criteria)
  trust_center:
    url: https://www.carefluence.com/onc-certification/
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Carefluence
provenance_date: '2026-11-09'
provider_name: Carefluence
provider_slug: carefluence
slug: carefluence-compliance
source_date: '2026-11-09'
source_filename: carefluence-compliance.yml
source_heading: Compliance
source_page: https://www.carefluence.com/onc-certification/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Carefluence\naid: carefluence\nurl: https://www.carefluence.com/onc-certification/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.carefluence.com/onc-certification/\nattestations:\n- framework: other\n  type: ONC Health IT certification (170.315 criteria)\n  scope: Carefluence Open API R4\n  period: Certified on June 29, 2022\n  issuer: Drummond Group (ONC-ACB)\n  report_access: unstated\n  text: Carefluence’s Open API R4 has been certified on June 29, 2022, under the unique certification number 15.04.04.2657.Care.R4.01.0.220629.\n"
source_yaml_url: https://artifacts.apis.io/carefluence/compliance/carefluence-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Carefluence's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Interoperability
- FHIR
- HL7
- SMART on FHIR
- Electronic Health Records
- Clinical Data
- Health IT
- ONC Certified
- USCDI
- OAuth
- Telehealth
- Health Information Exchange
- Authentication
---
