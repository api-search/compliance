---
api_specs:
- filename: manifest-cyber-assets-api-openapi.yml
  format: yaml
  label: Manifest Cyber Assets API
  slug: manifest-cyber-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manifest-cyber/openapi/manifest-cyber-assets-api-openapi.yml
- filename: manifest-cyber-organizations-api-openapi.yml
  format: yaml
  label: Manifest Cyber Organizations API
  slug: manifest-cyber-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manifest-cyber/openapi/manifest-cyber-organizations-api-openapi.yml
- filename: manifest-cyber-products-api-openapi.yml
  format: yaml
  label: Manifest Cyber Products API
  slug: manifest-cyber-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manifest-cyber/openapi/manifest-cyber-products-api-openapi.yml
- filename: manifest-cyber-sboms-api-openapi.yml
  format: yaml
  label: Manifest Cyber SBO Ms API
  slug: manifest-cyber-sboms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manifest-cyber/openapi/manifest-cyber-sboms-api-openapi.yml
- filename: manifest-cyber-users-api-openapi.yml
  format: yaml
  label: Manifest Cyber Users API
  slug: manifest-cyber-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manifest-cyber/openapi/manifest-cyber-users-api-openapi.yml
- filename: manifest-cyber-vulnerabilities-api-openapi.yml
  format: yaml
  label: Manifest Cyber Vulnerabilities API
  slug: manifest-cyber-vulnerabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/manifest-cyber/openapi/manifest-cyber-vulnerabilities-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Manifest is the only SBOM management platform with FedRAMP ® High Authorization.
    type: authorization
  trust_center:
    url: https://www.manifestcyber.com/security
frameworks:
- FedRAMP
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Manifest Cyber
provenance_date: '2026-11-10'
provider_name: Manifest Cyber
provider_slug: manifest-cyber
slug: manifest-cyber-compliance
source_date: '2026-11-10'
source_filename: manifest-cyber-compliance.yml
source_heading: Compliance
source_page: https://www.manifestcyber.com/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Manifest Cyber\naid: manifest-cyber\nurl: https://www.manifestcyber.com/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/manifest-cyber-trust-center.yml\ntrust_center:\n  url: https://www.manifestcyber.com/security\nattestations:\n- framework: FedRAMP\n  type: authorization\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Manifest is the only SBOM management platform with FedRAMP ® High Authorization.\n"
source_yaml_url: https://artifacts.apis.io/manifest-cyber/compliance/manifest-cyber-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Manifest Cyber's own page on 2026-11-10.
synthetic: false
tags:
- Cybersecurity
- SBOM
- Supply Chain Security
- Vulnerability Management
---
