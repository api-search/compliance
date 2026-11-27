---
api_specs:
- filename: mithril-api-keys-api-openapi.yml
  format: yaml
  label: Mithril API Keys API
  slug: mithril-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-api-keys-api-openapi.yml
- filename: mithril-image-versions-api-openapi.yml
  format: yaml
  label: Mithril image versions API
  slug: mithril-image-versions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-image-versions-api-openapi.yml
- filename: mithril-instance-types-api-openapi.yml
  format: yaml
  label: Mithril instance types API
  slug: mithril-instance-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-instance-types-api-openapi.yml
- filename: mithril-instances-api-openapi.yml
  format: yaml
  label: Mithril Instances API
  slug: mithril-instances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-instances-api-openapi.yml
- filename: mithril-kubernetes-clusters-api-openapi.yml
  format: yaml
  label: Mithril kubernetes clusters API
  slug: mithril-kubernetes-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-kubernetes-clusters-api-openapi.yml
- filename: mithril-lifecycle-scripts-api-openapi.yml
  format: yaml
  label: Mithril lifecycle scripts API
  slug: mithril-lifecycle-scripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-lifecycle-scripts-api-openapi.yml
- filename: mithril-pricing-api-openapi.yml
  format: yaml
  label: Mithril Pricing API
  slug: mithril-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-pricing-api-openapi.yml
- filename: mithril-profile-api-openapi.yml
  format: yaml
  label: Mithril Profile API
  slug: mithril-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-profile-api-openapi.yml
- filename: mithril-projects-api-openapi.yml
  format: yaml
  label: Mithril Projects API
  slug: mithril-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-projects-api-openapi.yml
- filename: mithril-quotas-api-openapi.yml
  format: yaml
  label: Mithril Quotas API
  slug: mithril-quotas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-quotas-api-openapi.yml
- filename: mithril-reservations-api-openapi.yml
  format: yaml
  label: Mithril Reservations API
  slug: mithril-reservations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-reservations-api-openapi.yml
- filename: mithril-spot-api-openapi.yml
  format: yaml
  label: Mithril Spot API
  slug: mithril-spot-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-spot-api-openapi.yml
- filename: mithril-ssh-keys-api-openapi.yml
  format: yaml
  label: Mithril SSH Keys API
  slug: mithril-ssh-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-ssh-keys-api-openapi.yml
- filename: mithril-volumes-api-openapi.yml
  format: yaml
  label: Mithril Volumes API
  slug: mithril-volumes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mithril/openapi/mithril-volumes-api-openapi.yml
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: availability, security, and confidentiality
    text: Mithril is SOC 2 Type II certified in availability, security, and confidentiality.
    type: SOC 2 Type II
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: compute hosted in Tier 3 and 4 datacenters with SOC 2 Type II or ISO 27001 compliance
    text: All compute available through Mithril is hosted in Tier 3 and 4 datacenters with SOC 2 Type II or ISO 27001 compliance that have passed our security requirements.
    type: datacenter compliance
  trust_center:
    url: https://docs.mithril.ai/security-and-trust/mithrils-approach-to-security
frameworks:
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Mithril
provenance_date: '2026-11-10'
provider_name: Mithril
provider_slug: mithril
slug: mithril-compliance
source_date: '2026-11-10'
source_filename: mithril-compliance.yml
source_heading: Compliance
source_page: https://docs.mithril.ai/security-and-trust/mithrils-approach-to-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Mithril\naid: mithril\nurl: https://docs.mithril.ai/security-and-trust/mithrils-approach-to-security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/mithril-trust-center.yml\ntrust_center:\n  url: https://docs.mithril.ai/security-and-trust/mithrils-approach-to-security\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: availability, security, and confidentiality\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Mithril is SOC 2 Type II certified in availability, security, and confidentiality.\n- framework: ISO27001\n  type: datacenter compliance\n  scope: compute hosted\
  \ in Tier 3 and 4 datacenters with SOC 2 Type II or ISO 27001 compliance\n  period: null\n  issuer: null\n  report_access: unstated\n  text: All compute available through Mithril is hosted in Tier 3 and 4 datacenters with SOC 2 Type II or ISO 27001\n    compliance that have passed our security requirements.\n"
source_yaml_url: https://artifacts.apis.io/mithril/compliance/mithril-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Mithril's own page on 2026-11-10.
synthetic: false
tags:
- Company
- GPU Cloud
- AI Infrastructure
- Machine Learning
- Cloud Computing
- Compute
- Spot Instances
- Kubernetes
- GPU
---
