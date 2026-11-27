---
api_specs:
- filename: nhsd-developers-portal.postman_collection.json
  format: json
  label: NHSD FHIR API
  slug: nhsd-fhir-api
  spec_type: Postman
  url: https://artifacts.apis.io/healthdirect/collections/nhsd-developers-portal.postman_collection.json
claim_count: 6
description: ''
doc:
  attestations:
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Healthcare provider directory data exchange
    text: Fast Healthcare Interoperability Resources (FHIR) standard for healthcare provider directory data exchange (FHIR AU-PD)
    type: Interoperability standard (FHIR AU-PD)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Health terminology
    text: An Australia-specific extension of the international SNOMED CT standard for health terminology.
    type: Health terminology standard (SNOMED CT-AU)
  - framework: other
    issuer: Geoscape Australia
    period: null
    report_access: unstated
    scope: Australian addresses and geographic coordinates
    text: The G-NAF is maintained by Geoscape Australia and is designed to provide a comprehensive dataset of Australian addresses and their geographic coordinates.
    type: Geocoding address standard (G-NAF)
  - framework: other
    issuer: Australian Signals Directorate
    period: null
    report_access: unstated
    scope: Information security in Australian government organisations
    text: A document produced by the Australian Signals Directorate.
    type: Cybersecurity guidance (Information Security Manual)
  - framework: other
    issuer: Australian Signals Directorate
    period: null
    report_access: unstated
    scope: Mitigation of cybersecurity incidents
    text: A set of strategies developed by the Australian Signals Directorate to mitigate cybersecurity incidents.
    type: Cybersecurity mitigation strategies (Essential Eight)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Third-party application access to user resources
    text: An open standard and a protocol that allows third-party applications to access the resources of a user without exposing the user's credentials.
    type: Authorization protocol (OAuth)
  trust_center:
    url: https://about.healthdirect.gov.au/what-we-do/portfolio/nhsd/integration-hub/standards
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Healthdirect Australia
provenance_date: '2026-11-09'
provider_name: Healthdirect Australia
provider_slug: healthdirect
slug: healthdirect-compliance
source_date: '2026-11-09'
source_filename: healthdirect-compliance.yml
source_heading: Compliance
source_page: https://about.healthdirect.gov.au/what-we-do/portfolio/nhsd/integration-hub/standards
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Healthdirect Australia\naid: healthdirect\nurl: https://about.healthdirect.gov.au/what-we-do/portfolio/nhsd/integration-hub/standards\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://about.healthdirect.gov.au/what-we-do/portfolio/nhsd/integration-hub/standards\nattestations:\n- framework: other\n  type: Interoperability standard (FHIR AU-PD)\n  scope: Healthcare provider directory data exchange\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Fast Healthcare Interoperability Resources (FHIR) standard for healthcare provider directory data exchange\n    (FHIR AU-PD)\n- framework: other\n\
  \  type: Health terminology standard (SNOMED CT-AU)\n  scope: Health terminology\n  period: null\n  issuer: null\n  report_access: unstated\n  text: An Australia-specific extension of the international SNOMED CT standard for health terminology.\n- framework: other\n  type: Geocoding address standard (G-NAF)\n  scope: Australian addresses and geographic coordinates\n  period: null\n  issuer: Geoscape Australia\n  report_access: unstated\n  text: The G-NAF is maintained by Geoscape Australia and is designed to provide a comprehensive dataset of Australian\n    addresses and their geographic coordinates.\n- framework: other\n  type: Cybersecurity guidance (Information Security Manual)\n  scope: Information security in Australian government organisations\n  period: null\n  issuer: Australian Signals Directorate\n  report_access: unstated\n  text: A document produced by the Australian Signals Directorate.\n- framework: other\n  type: Cybersecurity mitigation strategies (Essential Eight)\n \
  \ scope: Mitigation of cybersecurity incidents\n  period: null\n  issuer: Australian Signals Directorate\n  report_access: unstated\n  text: A set of strategies developed by the Australian Signals Directorate to mitigate cybersecurity incidents.\n- framework: other\n  type: Authorization protocol (OAuth)\n  scope: Third-party application access to user resources\n  period: null\n  issuer: null\n  report_access: unstated\n  text: An open standard and a protocol that allows third-party applications to access the resources of a user without\n    exposing the user's credentials.\n"
source_yaml_url: https://artifacts.apis.io/healthdirect/compliance/healthdirect-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from Healthdirect Australia's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Australia
- FHIR
- HL7
- Interoperability
- Provider Directory
- National Health System
- Health Services Directory
- Telehealth
- Digital Health
- Appointments
---
