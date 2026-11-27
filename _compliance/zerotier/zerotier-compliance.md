---
api_specs:
- filename: zerotier-controller-api-openapi.yml
  format: yaml
  label: ZeroTier Controller API
  slug: zerotier-controller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-controller-api-openapi.yml
- filename: zerotier-network-api-openapi.yml
  format: yaml
  label: ZeroTier Network API
  slug: zerotier-network-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-network-api-openapi.yml
- filename: zerotier-network-member-api-openapi.yml
  format: yaml
  label: ZeroTier Network Member API
  slug: zerotier-network-member-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-network-member-api-openapi.yml
- filename: zerotier-organizations-api-openapi.yml
  format: yaml
  label: ZeroTier Organizations API
  slug: zerotier-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-organizations-api-openapi.yml
- filename: zerotier-peer-api-openapi.yml
  format: yaml
  label: ZeroTier Peer API
  slug: zerotier-peer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-peer-api-openapi.yml
- filename: zerotier-status-api-openapi.yml
  format: yaml
  label: ZeroTier Status API
  slug: zerotier-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-status-api-openapi.yml
- filename: zerotier-user-api-openapi.yml
  format: yaml
  label: ZeroTier User API
  slug: zerotier-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-user-api-openapi.yml
- filename: zerotier-util-api-openapi.yml
  format: yaml
  label: ZeroTier Util API
  slug: zerotier-util-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zerotier/openapi/zerotier-util-api-openapi.yml
claim_count: 6
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: SOC 2 Type II
    type: SOC 2 Type II
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: 'FIPS 140-3, Certificate #5424'
    type: FIPS 140-3 certificate
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: GDPR
    type: GDPR
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.zerotier.com/
    text: SOC 2 Type II
    type: SOC 2 Type II
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    source: https://trust.zerotier.com/
    text: GDPR
    type: GDPR
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: controls protecting customer data and service reliability in hosted services
    source: https://docs.zerotier.com/security/
    text: ZeroTier has completed a SOC 2 Type II examination of the controls protecting customer data and service reliability in our hosted services.
    type: Type II examination
  trust_center:
    url: https://trust.zerotier.com/
frameworks:
- GDPR
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: ZeroTier
provenance_date: '2026-11-10'
provider_name: ZeroTier
provider_slug: zerotier
slug: zerotier-compliance
source_date: '2026-11-10'
source_filename: zerotier-compliance.yml
source_heading: Compliance
source_page: https://trust.zerotier.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: ZeroTier\naid: zerotier\nurl: https://trust.zerotier.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/zerotier-trust-center.yml\n  sources:\n  - https://docs.zerotier.com/security/\n  - https://trust.zerotier.com/\ntrust_center:\n  url: https://trust.zerotier.com/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n- framework: other\n  type: FIPS 140-3 certificate\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: 'FIPS 140-3, Certificate #5424'\n- framework: GDPR\n\
  \  type: GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n- framework: SOC2\n  type: SOC 2 Type II\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: SOC 2 Type II\n  source: https://trust.zerotier.com/\n- framework: GDPR\n  type: GDPR\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: GDPR\n  source: https://trust.zerotier.com/\n- framework: SOC2\n  type: Type II examination\n  scope: controls protecting customer data and service reliability in hosted services\n  period: null\n  issuer: null\n  report_access: on_request\n  text: ZeroTier has completed a SOC 2 Type II examination of the controls protecting customer data and service\n    reliability in our hosted services.\n  source: https://docs.zerotier.com/security/\n"
source_yaml_url: https://artifacts.apis.io/zerotier/compliance/zerotier-compliance.yml
stated_fields:
- attestations
summary_line: 6 quoted statements, read from ZeroTier's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Networking
- Software Defined Networking
- SDN
- VPN
- Security
- Connectivity
- Overlay Network
- Zero Trust
- Infrastructure
---
