---
api_specs:
- filename: exclaimer-end-users-api-openapi.yml
  format: yaml
  label: Exclaimer End Users API
  slug: exclaimer-end-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-end-users-api-openapi.yml
- filename: exclaimer-mailboxes-api-openapi.yml
  format: yaml
  label: Exclaimer Mailboxes API
  slug: exclaimer-mailboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-mailboxes-api-openapi.yml
- filename: exclaimer-miscellaneous-api-openapi.yml
  format: yaml
  label: Exclaimer Miscellaneous API
  slug: exclaimer-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-miscellaneous-api-openapi.yml
- filename: exclaimer-msp-api-openapi.yml
  format: yaml
  label: Exclaimer MSP API
  slug: exclaimer-msp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-msp-api-openapi.yml
- filename: exclaimer-reference-resources-api-openapi.yml
  format: yaml
  label: Exclaimer Reference Resources API
  slug: exclaimer-reference-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-reference-resources-api-openapi.yml
- filename: exclaimer-resellers-api-openapi.yml
  format: yaml
  label: Exclaimer Resellers API
  slug: exclaimer-resellers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-resellers-api-openapi.yml
- filename: exclaimer-subscription-transfers-api-openapi.yml
  format: yaml
  label: Exclaimer Subscription Transfers API
  slug: exclaimer-subscription-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-subscription-transfers-api-openapi.yml
- filename: exclaimer-subscription-users-api-openapi.yml
  format: yaml
  label: Exclaimer Subscription Users API
  slug: exclaimer-subscription-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-subscription-users-api-openapi.yml
- filename: exclaimer-subscriptions-api-openapi.yml
  format: yaml
  label: Exclaimer Subscriptions API
  slug: exclaimer-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exclaimer/openapi/exclaimer-subscriptions-api-openapi.yml
claim_count: 9
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: AICPA
    period: null
    report_access: unstated
    scope: null
    text: We are SOC 2 Type II certified by the AICPA, ensuring high standards of security, availability, and confidentiality.
    type: SOC 2 Type II certification
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: Information Security Management System
    text: We’re ISO/IEC 27001 and 27018 certified, demonstrating that we manage sensitive data and protect personally identifiable information (PII) in the cloud through a rigorously maintained Information Security Management System (ISMS).
    type: ISO/IEC 27001 certification
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: We’re ISO/IEC 27001 and 27018 certified
    type: ISO/IEC 27018 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: EU and EEA
    text: We are fully compliant with the General Data Protection Regulation (GDPR), supporting your data protection and privacy obligations across the EU and EEA.
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: California Consumer Privacy Act of 2018 and other U.S. privacy laws
    text: Our practices adhere to the California Consumer Privacy Act of 2018 (CCPA) and all other U.S. privacy laws.
    type: compliance statement
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: protected health information (PHI)
    text: We are HIPAA compliant, meeting U.S. federal standards for protecting and handling protected health information (PHI).
    type: compliance statement
  - framework: CyberEssentials
    issuer: National Cyber Security Centre (NCSC)
    period: null
    report_access: unstated
    scope: null
    text: Certified under the UK government-backed Cyber Essentials scheme, managed by the National Cyber Security Centre (NCSC)
    type: accreditation
  - framework: CSA-STAR
    issuer: Cloud Security Alliance
    period: null
    report_access: unstated
    scope: cloud service security controls
    text: We are certified by Cloud Security Alliance, following a rigorous independent assessment of our cloud service security controls.
    type: certification
  - framework: PCI-DSS
    issuer: null
    period: annually reviewed
    report_access: unstated
    scope: self-assessment questionnaire; card payments handled by a PCI DSS-certified third-party provider
    text: We self-certify against PCI DSS through an annually reviewed self-assessment questionnaire.
    type: self-certification
  trust_center:
    url: https://exclaimer.com/product/security/
frameworks:
- CCPA
- CSA-STAR
- CyberEssentials
- GDPR
- HIPAA
- ISO27001
- ISO27018
- PCI-DSS
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Exclaimer
provenance_date: '2026-11-09'
provider_name: Exclaimer
provider_slug: exclaimer
slug: exclaimer-compliance
source_date: '2026-11-09'
source_filename: exclaimer-compliance.yml
source_heading: Compliance
source_page: https://exclaimer.com/product/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Exclaimer\naid: exclaimer\nurl: https://exclaimer.com/product/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://exclaimer.com/product/security/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II certification\n  scope: null\n  period: null\n  issuer: AICPA\n  report_access: unstated\n  text: We are SOC 2 Type II certified by the AICPA, ensuring high standards of security, availability, and confidentiality.\n- framework: ISO27001\n  type: ISO/IEC 27001 certification\n  scope: Information Security Management System\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We’re\
  \ ISO/IEC 27001 and 27018 certified, demonstrating that we manage sensitive data and protect personally\n    identifiable information (PII) in the cloud through a rigorously maintained Information Security Management\n    System (ISMS).\n- framework: ISO27018\n  type: ISO/IEC 27018 certification\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We’re ISO/IEC 27001 and 27018 certified\n- framework: GDPR\n  type: compliance statement\n  scope: EU and EEA\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are fully compliant with the General Data Protection Regulation (GDPR), supporting your data protection\n    and privacy obligations across the EU and EEA.\n- framework: CCPA\n  type: compliance statement\n  scope: California Consumer Privacy Act of 2018 and other U.S. privacy laws\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our practices adhere to the California Consumer Privacy Act of 2018 (CCPA) and all other\
  \ U.S. privacy laws.\n- framework: HIPAA\n  type: compliance statement\n  scope: protected health information (PHI)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: We are HIPAA compliant, meeting U.S. federal standards for protecting and handling protected health information\n    (PHI).\n- framework: CyberEssentials\n  type: accreditation\n  scope: null\n  period: null\n  issuer: National Cyber Security Centre (NCSC)\n  report_access: unstated\n  text: Certified under the UK government-backed Cyber Essentials scheme, managed by the National Cyber Security\n    Centre (NCSC)\n- framework: CSA-STAR\n  type: certification\n  scope: cloud service security controls\n  period: null\n  issuer: Cloud Security Alliance\n  report_access: unstated\n  text: We are certified by Cloud Security Alliance, following a rigorous independent assessment of our cloud service\n    security controls.\n- framework: PCI-DSS\n  type: self-certification\n  scope: self-assessment questionnaire;\
  \ card payments handled by a PCI DSS-certified third-party provider\n  period: annually reviewed\n  issuer: null\n  report_access: unstated\n  text: We self-certify against PCI DSS through an annually reviewed self-assessment questionnaire.\n"
source_yaml_url: https://artifacts.apis.io/exclaimer/compliance/exclaimer-compliance.yml
stated_fields:
- attestations
summary_line: 9 quoted statements, read from Exclaimer's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Email
- Email Signatures
- Email Signature Management
- Microsoft 365
- Google Workspace
- Marketing
- Productivity
- Software-as-a-Service
- Security
---
