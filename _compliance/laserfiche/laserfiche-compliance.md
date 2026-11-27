---
api_specs:
- filename: laserfiche-oauth-api-openapi.yml
  format: yaml
  label: Laserfiche OAuth API
  slug: laserfiche-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserfiche/openapi/laserfiche-oauth-api-openapi.yml
- filename: laserfiche-odata4-api-openapi.yml
  format: yaml
  label: Laserfiche Odata4 API
  slug: laserfiche-odata4-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserfiche/openapi/laserfiche-odata4-api-openapi.yml
- filename: laserfiche-repositories-api-openapi.yml
  format: yaml
  label: Laserfiche Repositories API
  slug: laserfiche-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserfiche/openapi/laserfiche-repositories-api-openapi.yml
- filename: laserfiche-repository-api-openapi.yml
  format: yaml
  label: Laserfiche Repository API
  slug: laserfiche-repository-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/laserfiche/openapi/laserfiche-repository-api-openapi.yml
claim_count: 11
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: Laserfiche Cloud security, availability and confidentiality principles
    text: To view a copy of this report, please contact us .
    type: SOC 2 Type 2 Plus report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management system covering SaaS and self-hosted ECM and process automation applications
    text: Laserfiche has obtained the ISO/IEC 27001:2022 certification for its information security management system (ISMS) within the scope defined by its Statement of Applicability
    type: ISO/IEC 27001:2022 certification
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: HIPAA security requirements, 45 CFR 164.308-312
    text: Laserfiche’s SOC Type 2 Plus covers the security requirements set forth in the Health Insurance Portability and Accountability Act of 1996 (HIPAA)
    type: Security Requirements alignment via SOC Type 2 Plus
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Laserfiche AI data privacy for low to moderate risk data
    text: Laserfiche AI addresses privacy and security standards of our current data center locations supporting GDPR (EU), CCPA/CPRA (USA), and PIPEDA (Canada) for low to moderate risk data.
    type: Compliance support statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: Laserfiche AI data privacy for low to moderate risk data
    text: Laserfiche AI addresses privacy and security standards of our current data center locations supporting GDPR (EU), CCPA/CPRA (USA), and PIPEDA (Canada) for low to moderate risk data.
    type: Compliance support statement
  - framework: NIST-800-53
    issuer: null
    period: null
    report_access: unstated
    scope: Laserfiche security controls
    text: Laserfiche security controls are aligned with NIST 800-53.
    type: Security controls alignment
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Laserfiche Cloud security controls aligned with GovRAMP and NIST SP 800-53
    text: Laserfiche will achieve GovRAMP Verified status, demonstrating its implementation of security controls aligned with GovRAMP and NIST SP 800-53.
    type: GovRAMP Verified (pending)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Laserfiche Cloud support for Criminal Justice Information
    text: Laserfiche Cloud supports CJIS-ready controls that help organizations securely manage Criminal Justice Information (CJI).
    type: CJIS-ready controls
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Records management capabilities of self-hosted product
    text: Laserfiche Cloud records management controls are based on our self-hosted Department of Defense 5015.2 version 3-certified electronic records management capabilities.
    type: DoD 5015.2 certified capabilities
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Laserfiche Cloud and self-hosted products
    text: Laserfiche has published VPATs and ACRs available for all Laserfiche Cloud and self-hosted products.
    type: VPAT and ACR accessibility documentation; WCAG 2.2 AA alignment
  - framework: other
    issuer: null
    period: null
    report_access: on_request
    scope: Higher Education Community Vendor Assessment Toolkit
    text: Laserfiche has completed the Higher Education Community Vendor Assessment Toolkit ( HECVAT ) questionnaire. Contact us for more information.
    type: HECVAT questionnaire completed
  trust_center:
    url: https://www.laserfiche.com/products/trust-security/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- NIST-800-53
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Laserfiche
provenance_date: '2026-11-09'
provider_name: Laserfiche
provider_slug: laserfiche
slug: laserfiche-compliance
source_date: '2026-11-09'
source_filename: laserfiche-compliance.yml
source_heading: Compliance
source_page: https://www.laserfiche.com/products/trust-security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Laserfiche\naid: laserfiche\nurl: https://www.laserfiche.com/products/trust-security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.laserfiche.com/products/trust-security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 Plus report\n  scope: Laserfiche Cloud security, availability and confidentiality principles\n  period: null\n  issuer: null\n  report_access: on_request\n  text: To view a copy of this report, please contact us .\n- framework: ISO27001\n  type: ISO/IEC 27001:2022 certification\n  scope: information security management system covering SaaS and self-hosted ECM and process\
  \ automation applications\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Laserfiche has obtained the ISO/IEC 27001:2022 certification for its information security management system\n    (ISMS) within the scope defined by its Statement of Applicability\n- framework: HIPAA\n  type: Security Requirements alignment via SOC Type 2 Plus\n  scope: HIPAA security requirements, 45 CFR 164.308-312\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Laserfiche’s SOC Type 2 Plus covers the security requirements set forth in the Health Insurance Portability\n    and Accountability Act of 1996 (HIPAA)\n- framework: GDPR\n  type: Compliance support statement\n  scope: Laserfiche AI data privacy for low to moderate risk data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Laserfiche AI addresses privacy and security standards of our current data center locations supporting GDPR\n    (EU), CCPA/CPRA (USA), and PIPEDA (Canada) for low to moderate\
  \ risk data.\n- framework: CCPA\n  type: Compliance support statement\n  scope: Laserfiche AI data privacy for low to moderate risk data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Laserfiche AI addresses privacy and security standards of our current data center locations supporting GDPR\n    (EU), CCPA/CPRA (USA), and PIPEDA (Canada) for low to moderate risk data.\n- framework: NIST-800-53\n  type: Security controls alignment\n  scope: Laserfiche security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Laserfiche security controls are aligned with NIST 800-53.\n- framework: other\n  type: GovRAMP Verified (pending)\n  scope: Laserfiche Cloud security controls aligned with GovRAMP and NIST SP 800-53\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Laserfiche will achieve GovRAMP Verified status, demonstrating its implementation of security controls aligned\n    with GovRAMP and NIST SP 800-53.\n- framework: other\n\
  \  type: CJIS-ready controls\n  scope: Laserfiche Cloud support for Criminal Justice Information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Laserfiche Cloud supports CJIS-ready controls that help organizations securely manage Criminal Justice Information\n    (CJI).\n- framework: other\n  type: DoD 5015.2 certified capabilities\n  scope: Records management capabilities of self-hosted product\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Laserfiche Cloud records management controls are based on our self-hosted Department of Defense 5015.2 version\n    3-certified electronic records management capabilities.\n- framework: other\n  type: VPAT and ACR accessibility documentation; WCAG 2.2 AA alignment\n  scope: Laserfiche Cloud and self-hosted products\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Laserfiche has published VPATs and ACRs available for all Laserfiche Cloud and self-hosted products.\n- framework: other\n  type:\
  \ HECVAT questionnaire completed\n  scope: Higher Education Community Vendor Assessment Toolkit\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Laserfiche has completed the Higher Education Community Vendor Assessment Toolkit ( HECVAT ) questionnaire.\n    Contact us for more information.\n"
source_yaml_url: https://artifacts.apis.io/laserfiche/compliance/laserfiche-compliance.yml
stated_fields:
- attestations
summary_line: 11 quoted statements, read from Laserfiche's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Enterprise Content Management
- Document Management
- Process Automation
- Artificial Intelligence
---
