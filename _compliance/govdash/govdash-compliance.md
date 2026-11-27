---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: FedRAMP-recognized Third Party Assessment Organization (3PAO)
    period: null
    report_access: on_request
    scope: Federal environment govdash.us
    text: GovDash has achieved FedRAMP Moderate Equivalency as defined by the Department of Defense's December 2023 memorandum from the DoD CIO.
    type: Moderate Equivalency
  - framework: FedRAMP
    issuer: 3PAO Readiness Assessment and FedRAMP PMO review
    period: null
    report_access: unstated
    scope: GovDash platform
    text: GovDash is also FedRAMP Ready and publicly listed on the FedRAMP Marketplace following a 3PAO Readiness Assessment and FedRAMP PMO review.
    type: Ready
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: CUI and CDI storage, processing and transmission
    text: DFARS 252.204-7012 Compliant
    type: DFARS 252.204-7012 compliance
  trust_center:
    url: https://www.govdash.com/security
frameworks:
- FedRAMP
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Govdash
provenance_date: '2026-11-09'
provider_name: Govdash
provider_slug: govdash
slug: govdash-compliance
source_date: '2026-11-09'
source_filename: govdash-compliance.yml
source_heading: Compliance
source_page: https://www.govdash.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Govdash\naid: govdash\nurl: https://www.govdash.com/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.govdash.com/security\nattestations:\n- framework: FedRAMP\n  type: Moderate Equivalency\n  scope: Federal environment govdash.us\n  period: null\n  issuer: FedRAMP-recognized Third Party Assessment Organization (3PAO)\n  report_access: on_request\n  text: GovDash has achieved FedRAMP Moderate Equivalency as defined by the Department of Defense's December 2023\n    memorandum from the DoD CIO.\n- framework: FedRAMP\n  type: Ready\n  scope: GovDash platform\n  period: null\n  issuer: 3PAO Readiness\
  \ Assessment and FedRAMP PMO review\n  report_access: unstated\n  text: GovDash is also FedRAMP Ready and publicly listed on the FedRAMP Marketplace following a 3PAO Readiness\n    Assessment and FedRAMP PMO review.\n- framework: other\n  type: DFARS 252.204-7012 compliance\n  scope: CUI and CDI storage, processing and transmission\n  period: null\n  issuer: null\n  report_access: unstated\n  text: DFARS 252.204-7012 Compliant\n"
source_yaml_url: https://artifacts.apis.io/govdash/compliance/govdash-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Govdash's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Government Contracting
- GovCon
- Artificial Intelligence
- Proposal Management
- Capture Management
- Public Sector
- Enterprise
---
