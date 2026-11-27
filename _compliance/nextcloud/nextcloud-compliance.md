---
api_specs:
- filename: nextcloud-autocomplete-api-openapi.yml
  format: yaml
  label: Nextcloud Autocomplete API
  slug: nextcloud-autocomplete-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextcloud/openapi/nextcloud-autocomplete-api-openapi.yml
- filename: nextcloud-capabilities-api-openapi.yml
  format: yaml
  label: Nextcloud Capabilities API
  slug: nextcloud-capabilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextcloud/openapi/nextcloud-capabilities-api-openapi.yml
- filename: nextcloud-dav-api-openapi.yml
  format: yaml
  label: Nextcloud DAV API
  slug: nextcloud-dav-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextcloud/openapi/nextcloud-dav-api-openapi.yml
- filename: nextcloud-users-api-openapi.yml
  format: yaml
  label: Nextcloud Users API
  slug: nextcloud-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/nextcloud/openapi/nextcloud-users-api-openapi.yml
claim_count: 1
description: ''
doc:
  attestations:
  - framework: other
    issuer: ANSSI
    period: null
    report_access: unstated
    scope: Nextcloud Files
    text: Nextcloud Files has been CSPN-certified by the French cybersecurity authority ANSSI.
    type: CSPN certification (EN 17640)
  trust_center:
    url: https://nextcloud.com/compliance/
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Nextcloud
provenance_date: '2026-11-10'
provider_name: Nextcloud
provider_slug: nextcloud
slug: nextcloud-compliance
source_date: '2026-11-10'
source_filename: nextcloud-compliance.yml
source_heading: Compliance
source_page: https://nextcloud.com/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Nextcloud\naid: nextcloud\nurl: https://nextcloud.com/compliance/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/nextcloud-trust-center.yml\ntrust_center:\n  url: https://nextcloud.com/compliance/\nattestations:\n- framework: other\n  type: CSPN certification (EN 17640)\n  scope: Nextcloud Files\n  period: null\n  issuer: ANSSI\n  report_access: unstated\n  text: Nextcloud Files has been CSPN-certified by the French cybersecurity authority ANSSI.\n"
source_yaml_url: https://artifacts.apis.io/nextcloud/compliance/nextcloud-compliance.yml
stated_fields:
- attestations
summary_line: 1 quoted statement, read from Nextcloud's own page on 2026-11-10.
synthetic: false
tags:
- File Sync
- File Sharing
- Collaboration
- Self-Hosted
- Open Source
- Productivity
- WebDAV
---
