---
api_specs:
- filename: envoisms-ma-api-openapi.json
  format: json
  label: EnvoiSMS API API
  slug: envoisms-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/envoisms-ma/openapi/_original/envoisms-ma-api-openapi.json
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Information security management system covering 93 Annex A controls, operated by VEXT AI SARL AU
    text: Attestation formelle de conformité du SMSI selon ISO/IEC 17050-1 et dossier d'engagement d'audit accrédité IAF MLA pour l'opérateur VEXT AI SARL AU.
    type: ISO/IEC 27001:2022 SMSI certification/conformity attestation
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Edge, WAF and storage infrastructure (Cloudflare) on which EnvoiSMS runs
    text: Attestations officielles d'audit SOC 2 Type II et certifications ISO/IEC 27001 des datacenters et du réseau de distribution Edge sur lesquels s'exécute EnvoiSMS.
    type: SOC 2 Type II audit of underlying infrastructure
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: Physical infrastructure and Edge network hosting the service
    text: Infrastructure physique et Edge Cloudflare auditée SOC 2 Type II et certifiée ISO 27001 / ISO 27701.
    type: ISO 27001 certification of infrastructure
  - framework: ISO27701
    issuer: null
    period: null
    report_access: on_request
    scope: Edge Cloudflare infrastructure
    text: Infrastructure physique et Edge Cloudflare auditée SOC 2 Type II et certifiée ISO 27001 / ISO 27701.
    type: ISO 27701 certification of infrastructure
  - framework: TISAX
    issuer: null
    period: null
    report_access: on_request
    scope: Automotive supplier information security; AL3 stated not applicable, AL2 readiness
    text: Mémoire formel de démarcation de périmètre excluant les données prototypes et CAO (TISAX AL3 non applicable).
    type: TISAX assessment scope demarcation and readiness
  trust_center:
    url: https://envoisms.ma/fr/trust/
frameworks:
- ISO27001
- ISO27701
- SOC2
- TISAX
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: envoisms-ma
provenance_date: '2026-11-09'
provider_name: envoisms-ma
provider_slug: envoisms-ma
slug: envoisms-ma-compliance
source_date: '2026-11-09'
source_filename: envoisms-ma-compliance.yml
source_heading: Compliance
source_page: https://envoisms.ma/fr/trust/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: envoisms-ma\naid: envoisms-ma\nurl: https://envoisms.ma/fr/trust/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://envoisms.ma/fr/trust/\nattestations:\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 SMSI certification/conformity attestation\n  scope: Information security management system covering 93 Annex A controls, operated by VEXT AI SARL AU\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Attestation formelle de conformité du SMSI selon ISO/IEC 17050-1 et dossier d'engagement d'audit accrédité\n    IAF MLA pour l'opérateur VEXT AI SARL AU.\n- framework: SOC2\n  type: SOC\
  \ 2 Type II audit of underlying infrastructure\n  scope: Edge, WAF and storage infrastructure (Cloudflare) on which EnvoiSMS runs\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Attestations officielles d'audit SOC 2 Type II et certifications ISO/IEC 27001 des datacenters et du réseau\n    de distribution Edge sur lesquels s'exécute EnvoiSMS.\n- framework: ISO27001\n  type: ISO 27001 certification of infrastructure\n  scope: Physical infrastructure and Edge network hosting the service\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Infrastructure physique et Edge Cloudflare auditée SOC 2 Type II et certifiée ISO 27001 / ISO 27701.\n- framework: ISO27701\n  type: ISO 27701 certification of infrastructure\n  scope: Edge Cloudflare infrastructure\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Infrastructure physique et Edge Cloudflare auditée SOC 2 Type II et certifiée ISO 27001 / ISO 27701.\n- framework: TISAX\n  type: TISAX\
  \ assessment scope demarcation and readiness\n  scope: Automotive supplier information security; AL3 stated not applicable, AL2 readiness\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Mémoire formel de démarcation de périmètre excluant les données prototypes et CAO (TISAX AL3 non applicable).\n"
source_yaml_url: https://artifacts.apis.io/envoisms-ma/compliance/envoisms-ma-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from envoisms-ma's own page on 2026-11-09.
synthetic: false
tags:
- Company
- SMS
- WhatsApp
- Messaging
- Morocco
- CPaaS
---
