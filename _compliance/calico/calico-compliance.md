---
api_specs:
- filename: calico-bgpconfiguration-api-openapi.yml
  format: yaml
  label: Calico BGPConfiguration API
  slug: calico-bgpconfiguration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-bgpconfiguration-api-openapi.yml
- filename: calico-bgppeer-api-openapi.yml
  format: yaml
  label: Calico BGPPeer API
  slug: calico-bgppeer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-bgppeer-api-openapi.yml
- filename: calico-globalnetworkpolicy-api-openapi.yml
  format: yaml
  label: Calico GlobalNetworkPolicy API
  slug: calico-globalnetworkpolicy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-globalnetworkpolicy-api-openapi.yml
- filename: calico-hostendpoint-api-openapi.yml
  format: yaml
  label: Calico HostEndpoint API
  slug: calico-hostendpoint-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-hostendpoint-api-openapi.yml
- filename: calico-profile-api-openapi.yml
  format: yaml
  label: Calico Profile API
  slug: calico-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-profile-api-openapi.yml
- filename: calico-ip-pool-api-openapi.yml
  format: yaml
  label: Calico IP Pool API
  slug: calico-ip-pool-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-ip-pool-api-openapi.yml
- filename: calico-network-policy-api-openapi.yml
  format: yaml
  label: Calico Network Policy API
  slug: calico-network-policy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calico/openapi/calico-network-policy-api-openapi.yml
claim_count: 5
description: ''
doc:
  attestations:
  - framework: CSA-STAR
    issuer: Cloud Security Alliance
    period: null
    report_access: public
    scope: Calico Cloud
    text: Calico Cloud is certified with Cloud Security Alliance and you can download the report from here
    type: certification
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: Calico Cloud
    text: Calico Cloud is SOC 2, CCPA, GDPR compliant.
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Calico Cloud
    text: Calico Cloud is SOC 2, CCPA, GDPR compliant.
    type: compliance statement
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Calico Cloud
    text: Calico Cloud is SOC 2, CCPA, GDPR compliant.
    type: compliance statement
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: Payment processing system
    text: Our payment processing system is PCI compliant.
    type: compliance statement
  trust_center:
    url: https://www.tigera.io/tigera-products/calico-cloud-trust-center/
frameworks:
- CCPA
- CSA-STAR
- GDPR
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Calico
provenance_date: '2026-11-09'
provider_name: Calico
provider_slug: calico
slug: calico-compliance
source_date: '2026-11-09'
source_filename: calico-compliance.yml
source_heading: Compliance
source_page: https://www.tigera.io/tigera-products/calico-cloud-trust-center/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Calico\naid: calico\nurl: https://www.tigera.io/tigera-products/calico-cloud-trust-center/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/calico-trust-center.yml\ntrust_center:\n  url: https://www.tigera.io/tigera-products/calico-cloud-trust-center/\nattestations:\n- framework: CSA-STAR\n  type: certification\n  scope: Calico Cloud\n  period: null\n  issuer: Cloud Security Alliance\n  report_access: public\n  text: Calico Cloud is certified with Cloud Security Alliance and you can download the report from here\n- framework: SOC2\n  type: compliance statement\n  scope: Calico Cloud\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: Calico Cloud is SOC 2, CCPA, GDPR compliant.\n- framework: CCPA\n  type: compliance statement\n  scope: Calico Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Calico Cloud is SOC 2, CCPA, GDPR compliant.\n- framework: GDPR\n  type: compliance statement\n  scope: Calico Cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Calico Cloud is SOC 2, CCPA, GDPR compliant.\n- framework: PCI-DSS\n  type: compliance statement\n  scope: Payment processing system\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our payment processing system is PCI compliant.\n"
source_yaml_url: https://artifacts.apis.io/calico/compliance/calico-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Calico's own page on 2026-11-09.
synthetic: false
tags:
- CNI
- Containers
- eBPF
- Kubernetes
- Network Policy
- Network Security
- Networking
- Open Source
- Service Mesh
---
