---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: ISO27001
    issuer: Accredited certification body
    period: null
    report_access: public
    scope: development, hosting, and operation of the DentalMonitoring platform
    text: Certified ISO/IEC 27001 Information security management system covering the development, hosting, and operation of the DentalMonitoring platform.
    type: certified
  - framework: other
    issuer: null
    period: null
    report_access: public
    scope: Medical device QMS
    text: Certified ISO 13485 Quality management system for medical devices, governing how our software is designed, validated, released, and monitored.
    type: certified ISO 13485
  - framework: other
    issuer: null
    period: null
    report_access: public
    scope: Health data hosted on HDS-certified AWS infrastructure
    text: Certified HDS (Hébergeur de Données de Santé) French health-data hosting certification, required to store and process personal health data for patients in France.
    type: certified HDS
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Administrative, technical, and physical safeguards for protected health information of patients in the United States
    text: Compliant HIPAA Administrative, technical, and physical safeguards for protected health information of patients in the United States.
    type: self-assessed
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: data processing agreements, records of processing, and patient rights handling
    text: Full compliance with the EU General Data Protection Regulation, including data processing agreements, records of processing, and patient rights handling.
    type: self-assessed
  trust_center:
    url: https://dentalmonitoring.com/security/
frameworks:
- GDPR
- HIPAA
- ISO27001
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Dental Monitoring
provenance_date: '2026-11-09'
provider_name: Dental Monitoring
provider_slug: dental-monitoring
slug: dental-monitoring-compliance
source_date: '2026-11-09'
source_filename: dental-monitoring-compliance.yml
source_heading: Compliance
source_page: https://dentalmonitoring.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Dental Monitoring\naid: dental-monitoring\nurl: https://dentalmonitoring.com/security/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://dentalmonitoring.com/security/\nattestations:\n- framework: ISO27001\n  type: certified\n  scope: development, hosting, and operation of the DentalMonitoring platform\n  period: null\n  issuer: Accredited certification body\n  report_access: public\n  text: Certified ISO/IEC 27001 Information security management system covering the development, hosting, and operation\n    of the DentalMonitoring platform.\n- framework: other\n  type: certified ISO 13485\n  scope: Medical\
  \ device QMS\n  period: null\n  issuer: null\n  report_access: public\n  text: Certified ISO 13485 Quality management system for medical devices, governing how our software is designed,\n    validated, released, and monitored.\n- framework: other\n  type: certified HDS\n  scope: Health data hosted on HDS-certified AWS infrastructure\n  period: null\n  issuer: null\n  report_access: public\n  text: Certified HDS (Hébergeur de Données de Santé) French health-data hosting certification, required to store\n    and process personal health data for patients in France.\n- framework: HIPAA\n  type: self-assessed\n  scope: Administrative, technical, and physical safeguards for protected health information of patients in the\n    United States\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Compliant HIPAA Administrative, technical, and physical safeguards for protected health information of patients\n    in the United States.\n- framework: GDPR\n  type: self-assessed\n  scope:\
  \ data processing agreements, records of processing, and patient rights handling\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Full compliance with the EU General Data Protection Regulation, including data processing agreements, records\n    of processing, and patient rights handling.\n"
source_yaml_url: https://artifacts.apis.io/dental-monitoring/compliance/dental-monitoring-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Dental Monitoring's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Dental
- Artificial Intelligence
- Healthcare
- Orthodontics
---
