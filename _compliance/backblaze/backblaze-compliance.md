---
api_specs:
- filename: backblaze-application-keys-api-openapi.yml
  format: yaml
  label: Backblaze Application Keys API
  slug: backblaze-application-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backblaze/openapi/backblaze-application-keys-api-openapi.yml
- filename: backblaze-authorization-api-openapi.yml
  format: yaml
  label: Backblaze Authorization API
  slug: backblaze-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backblaze/openapi/backblaze-authorization-api-openapi.yml
- filename: backblaze-buckets-api-openapi.yml
  format: yaml
  label: Backblaze Buckets API
  slug: backblaze-buckets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backblaze/openapi/backblaze-buckets-api-openapi.yml
- filename: backblaze-files-api-openapi.yml
  format: yaml
  label: Backblaze Files API
  slug: backblaze-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backblaze/openapi/backblaze-files-api-openapi.yml
- filename: backblaze-large-files-api-openapi.yml
  format: yaml
  label: Backblaze Large Files API
  slug: backblaze-large-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backblaze/openapi/backblaze-large-files-api-openapi.yml
- filename: backblaze-notifications-api-openapi.yml
  format: yaml
  label: Backblaze Notifications API
  slug: backblaze-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backblaze/openapi/backblaze-notifications-api-openapi.yml
claim_count: 12
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: an independent third-party firm
    period: null
    report_access: unstated
    scope: Backblaze infrastructure
    text: Backblaze has achieved Service Organization Control (SOC) 2 Type 2 compliance by an independent third-party firm.
    type: SOC 2 Type 2 compliance
  - framework: HIPAA
    issuer: null
    period: null
    report_access: on_request
    scope: business customers who are Covered Entities
    text: Backblaze can provide a Business Associate Agreement (BAA) upon request for business customers who are Covered Entities under the Health Insurance Portability and Accountability Act (HIPAA).
    type: Business Associate Agreement available
  - framework: other
    issuer: State Risk and Authorization Management Program (GovRAMP)
    period: null
    report_access: unstated
    scope: Backblaze product
    text: Backblaze is listed as a Progressing Product in the State Risk and Authorization Management Program (GovRAMP) Authorized Product List.
    type: GovRAMP Progressing Product listing
  - framework: other
    issuer: Texas Risk and Authorization Management Program (TX-RAMP)
    period: null
    report_access: unstated
    scope: Backblaze cloud product
    text: Backblaze is listed in the Texas Risk and Authorization Management Program (TX-RAMP) Certified Cloud Products list with a Certification Status of TX-RAMP Provisional.
    type: TX-RAMP Provisional certification listing
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: HECVAT lite and full version 3.06
    text: Backblaze completed the Higher Education Community Vendor Assessment Tool (HECVAT) lite and full version 3.06 assessments. Documents can be accessed via Whistic.
    type: HECVAT assessments completed
  - framework: PCI-DSS
    issuer: null
    period: null
    report_access: unstated
    scope: card data stored and processed via Stripe combined with internal controls
    text: contributes to Backblaze’s adherence to Payment Card Industry Data Security Standard (PCI-DSS) requirements.
    type: adherence to PCI-DSS requirements
  - framework: other
    issuer: Trusted Partner Network (TPN)
    period: null
    report_access: unstated
    scope: aligned with MPA Content Security Best Practices (CSBP)
    text: Backblaze obtained Trusted Partner Network (TPN) Blue Shield status which is aligned with the Motion Picture Association (MPA) Content Security Best Practices (CSBP) framework.
    type: TPN Blue Shield status
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: primarily data centers Backblaze operates in
    text: Backblaze operates primarily in data centers that hold International Organization for Standardization (ISO) 27001 certificates, which can be accessed via Whistic.
    type: data centers hold ISO 27001 certificates
  - framework: GDPR
    issuer: null
    period: null
    report_access: on_request
    scope: EEA/EU and UK residents
    text: Data Processing Agreement Addendums (DPAs) for EEA/EU and UK residents are available for compliance standards.
    type: GDPR privacy policies and Data Processing Agreement addendums
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: consumer requests, data inventory, privacy notice
    text: Backblaze satisfies California Consumer Privacy Act/California Privacy Rights Act (CCPA/CPRA) privacy obligations, including consumer requests, data inventory, and a privacy notice.
    type: satisfies CCPA/CPRA privacy obligations
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: Section 508 accessibility guidelines
    text: Backblaze obtained a Voluntary Product Accessibility Template (VPAT) report documenting compliance with Section 508 accessibility guidelines. This report can be accessed via Whistic.
    type: VPAT report (Section 508)
  - framework: other
    issuer: Internet2
    period: null
    report_access: unstated
    scope: research and educational institutions
    text: Backblaze has completed the Internet2 Cloud Scorecard for research and educational institutions
    type: Internet2 Cloud Scorecard completed
  trust_center:
    url: https://www.backblaze.com/cloud-storage/compliance
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- PCI-DSS
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Backblaze
provenance_date: '2026-11-09'
provider_name: Backblaze
provider_slug: backblaze
slug: backblaze-compliance
source_date: '2026-11-09'
source_filename: backblaze-compliance.yml
source_heading: Compliance
source_page: https://www.backblaze.com/cloud-storage/compliance
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Backblaze\naid: backblaze\nurl: https://www.backblaze.com/cloud-storage/compliance\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/backblaze-trust-center.yml\ntrust_center:\n  url: https://www.backblaze.com/cloud-storage/compliance\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 compliance\n  scope: Backblaze infrastructure\n  period: null\n  issuer: an independent third-party firm\n  report_access: unstated\n  text: Backblaze has achieved Service Organization Control (SOC) 2 Type 2 compliance by an independent third-party\n    firm.\n- framework: HIPAA\n  type: Business Associate Agreement\
  \ available\n  scope: business customers who are Covered Entities\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Backblaze can provide a Business Associate Agreement (BAA) upon request for business customers who are Covered\n    Entities under the Health Insurance Portability and Accountability Act (HIPAA).\n- framework: other\n  type: GovRAMP Progressing Product listing\n  scope: Backblaze product\n  period: null\n  issuer: State Risk and Authorization Management Program (GovRAMP)\n  report_access: unstated\n  text: Backblaze is listed as a Progressing Product in the State Risk and Authorization Management Program (GovRAMP)\n    Authorized Product List.\n- framework: other\n  type: TX-RAMP Provisional certification listing\n  scope: Backblaze cloud product\n  period: null\n  issuer: Texas Risk and Authorization Management Program (TX-RAMP)\n  report_access: unstated\n  text: Backblaze is listed in the Texas Risk and Authorization Management Program (TX-RAMP) Certified\
  \ Cloud Products\n    list with a Certification Status of TX-RAMP Provisional.\n- framework: other\n  type: HECVAT assessments completed\n  scope: HECVAT lite and full version 3.06\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Backblaze completed the Higher Education Community Vendor Assessment Tool (HECVAT) lite and full version\n    3.06 assessments. Documents can be accessed via Whistic.\n- framework: PCI-DSS\n  type: adherence to PCI-DSS requirements\n  scope: card data stored and processed via Stripe combined with internal controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: contributes to Backblaze’s adherence to Payment Card Industry Data Security Standard (PCI-DSS) requirements.\n- framework: other\n  type: TPN Blue Shield status\n  scope: aligned with MPA Content Security Best Practices (CSBP)\n  period: null\n  issuer: Trusted Partner Network (TPN)\n  report_access: unstated\n  text: Backblaze obtained Trusted Partner Network (TPN)\
  \ Blue Shield status which is aligned with the Motion Picture\n    Association (MPA) Content Security Best Practices (CSBP) framework.\n- framework: ISO27001\n  type: data centers hold ISO 27001 certificates\n  scope: primarily data centers Backblaze operates in\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Backblaze operates primarily in data centers that hold International Organization for Standardization (ISO)\n    27001 certificates, which can be accessed via Whistic.\n- framework: GDPR\n  type: GDPR privacy policies and Data Processing Agreement addendums\n  scope: EEA/EU and UK residents\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Data Processing Agreement Addendums (DPAs) for EEA/EU and UK residents are available for compliance standards.\n- framework: CCPA\n  type: satisfies CCPA/CPRA privacy obligations\n  scope: consumer requests, data inventory, privacy notice\n  period: null\n  issuer: null\n  report_access: unstated\n  text:\
  \ Backblaze satisfies California Consumer Privacy Act/California Privacy Rights Act (CCPA/CPRA) privacy obligations,\n    including consumer requests, data inventory, and a privacy notice.\n- framework: other\n  type: VPAT report (Section 508)\n  scope: Section 508 accessibility guidelines\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Backblaze obtained a Voluntary Product Accessibility Template (VPAT) report documenting compliance with\n    Section 508 accessibility guidelines. This report can be accessed via Whistic.\n- framework: other\n  type: Internet2 Cloud Scorecard completed\n  scope: research and educational institutions\n  period: null\n  issuer: Internet2\n  report_access: unstated\n  text: Backblaze has completed the Internet2 Cloud Scorecard for research and educational institutions\n"
source_yaml_url: https://artifacts.apis.io/backblaze/compliance/backblaze-compliance.yml
stated_fields:
- attestations
summary_line: 12 quoted statements, read from Backblaze's own page on 2026-11-09.
synthetic: false
tags:
- Cloud Storage
- Object Storage
- Storage
- Backup
---
