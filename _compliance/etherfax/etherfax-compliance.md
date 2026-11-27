---
api_specs:
- filename: etherfax-accounts-api-openapi.yml
  format: yaml
  label: etherFAX Accounts API
  slug: etherfax-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-accounts-api-openapi.yml
- filename: etherfax-devices-api-openapi.yml
  format: yaml
  label: etherFAX Devices API
  slug: etherfax-devices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-devices-api-openapi.yml
- filename: etherfax-inbox-api-openapi.yml
  format: yaml
  label: etherFAX Inbox API
  slug: etherfax-inbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-inbox-api-openapi.yml
- filename: etherfax-outbox-api-openapi.yml
  format: yaml
  label: etherFAX Outbox API
  slug: etherfax-outbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-outbox-api-openapi.yml
- filename: etherfax-routes-api-openapi.yml
  format: yaml
  label: etherFAX Routes API
  slug: etherfax-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-routes-api-openapi.yml
- filename: etherfax-status-api-openapi.yml
  format: yaml
  label: etherFAX Status API
  slug: etherfax-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/etherfax/openapi/etherfax-status-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: U.S. government services (ETHERFAX GovCloud)
    text: In 2025, ETHERFAX achieved FedRAMP ® High authorization to deliver cloud services for government agencies.
    type: FedRAMP High authorization
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: commercial document exchange solutions
    text: ETHERFAX’s commercial document exchange solutions operate in an environment that complies with HIPAA and SOC 2 ® standards
    type: compliance with HIPAA
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: commercial document exchange solutions
    text: ETHERFAX’s commercial document exchange solutions operate in an environment that complies with HIPAA and SOC 2 ® standards
    type: compliance with SOC 2 standards
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: commercial document exchange solutions
    text: is certified to meet HITRUST CSF, ® R2, PCI DSS 4.01 Level 1, and NIST v1.1 cybersecurity requirements.
    type: HITRUST CSF R2 certification
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: commercial document exchange solutions
    text: is certified to meet HITRUST CSF, ® R2, PCI DSS 4.01 Level 1, and NIST v1.1 cybersecurity requirements.
    type: PCI DSS 4.01 Level 1 certification
  - framework: NIST-CSF
    issuer: null
    period: null
    report_access: unstated
    scope: commercial document exchange solutions
    text: is certified to meet HITRUST CSF, ® R2, PCI DSS 4.01 Level 1, and NIST v1.1 cybersecurity requirements.
    type: NIST v1.1 cybersecurity requirements
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: U.S. government services operating within AWS GovCloud High environment
    text: including Department of Defense (DoD) CC SRG Impact Level 5 (IL5) cybersecurity controls, operating within AWS’ GovCloud High environment.
    type: DoD CC SRG Impact Level 5 (IL5) cybersecurity controls
  trust_center:
    url: https://www.etherfax.net/security/
frameworks:
- FedRAMP
- HIPAA
- NIST-CSF
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: etherFAX
provenance_date: '2026-11-09'
provider_name: etherFAX
provider_slug: etherfax
slug: etherfax-compliance
source_date: '2026-11-09'
source_filename: etherfax-compliance.yml
source_heading: Compliance
source_page: https://www.etherfax.net/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: etherFAX\naid: etherfax\nurl: https://www.etherfax.net/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.etherfax.net/security/\nattestations:\n- framework: FedRAMP\n  type: FedRAMP High authorization\n  scope: U.S. government services (ETHERFAX GovCloud)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: In 2025, ETHERFAX achieved FedRAMP ® High authorization to deliver cloud services for government agencies.\n- framework: HIPAA\n  type: compliance with HIPAA\n  scope: commercial document exchange solutions\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ ETHERFAX’s commercial document exchange solutions operate in an environment that complies with HIPAA and\n    SOC 2 ® standards\n- framework: SOC2\n  type: compliance with SOC 2 standards\n  scope: commercial document exchange solutions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ETHERFAX’s commercial document exchange solutions operate in an environment that complies with HIPAA and\n    SOC 2 ® standards\n- framework: other\n  type: HITRUST CSF R2 certification\n  scope: commercial document exchange solutions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: is certified to meet HITRUST CSF, ® R2, PCI DSS 4.01 Level 1, and NIST v1.1 cybersecurity requirements.\n- framework: PCI-DSS\n  type: PCI DSS 4.01 Level 1 certification\n  scope: commercial document exchange solutions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: is certified to meet HITRUST CSF, ® R2, PCI DSS 4.01 Level 1, and NIST v1.1 cybersecurity requirements.\n\
  - framework: NIST-CSF\n  type: NIST v1.1 cybersecurity requirements\n  scope: commercial document exchange solutions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: is certified to meet HITRUST CSF, ® R2, PCI DSS 4.01 Level 1, and NIST v1.1 cybersecurity requirements.\n- framework: other\n  type: DoD CC SRG Impact Level 5 (IL5) cybersecurity controls\n  scope: U.S. government services operating within AWS GovCloud High environment\n  period: null\n  issuer: null\n  report_access: unstated\n  text: including Department of Defense (DoD) CC SRG Impact Level 5 (IL5) cybersecurity controls, operating within\n    AWS’ GovCloud High environment.\n"
source_yaml_url: https://artifacts.apis.io/etherfax/compliance/etherfax-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from etherFAX's own page on 2026-11-09.
synthetic: false
tags:
- Fax
- Cloud
- Artificial Intelligence
- Secure
- Document Automation
---
