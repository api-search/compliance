---
claim_count: 10
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: Own platform
    text: Own's latest SOC 2 Type II report is available upon request under NDA.
    type: SOC 2 Type II attestation report
  - framework: SOC1
    issuer: null
    period: null
    report_access: nda
    scope: internal controls over financial reporting
    text: Own's latest SOC 1 Type II report is available upon request under NDA.
    type: SOC 1 Type II attestation report
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: Own Government Cloud solution
    text: Own achieved FedRAMP authorization for its Own Government Cloud solution.
    type: FedRAMP authorization
  - framework: ISO27001
    issuer: null
    period: null
    report_access: public
    scope: Information Security Management System
    text: Own is ISO 27001:2013 and ISO 27701:2019 certified
    type: ISO 27001:2013 certificate
  - framework: ISO27701
    issuer: null
    period: null
    report_access: public
    scope: Privacy Information Management System
    text: ISO 27701:2019 Certificate Privacy Information Management System (PIMS)
    type: ISO 27701:2019 certificate
  - framework: other
    issuer: null
    period: null
    report_access: public
    scope: personal health data hosting
    text: Own's HDS certification demonstrates our commitment to securing and protecting the confidentiality of personal health data.
    type: Hébergeur de Données de Santé (HDS) certification
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: public
    scope: UK government requirements
    text: Own is Cyber Essentials certified to comply with UK government requirements
    type: Cyber Essentials certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: Own products support customer GDPR obligations
    text: Own products are designed to support our customer's compliance obligations with data privacy regulations, including GDPR requirements.
    type: GDPR compliance support
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: cross-border transfers of personal data, including UK Extension and Swiss-U.S. DPF
    text: Own is registered under the EU-U.S. Data Privacy Framework (EU-U.S. DPF), UK Extension to the EU-U.S. DPF, and Swiss-U.S. DPF
    type: EU-U.S. Data Privacy Framework registration
  - framework: other
    issuer: Cloud Security Alliance
    period: null
    report_access: unstated
    scope: cloud security
    text: Cloud Security Alliance (CSA) has recognized Own as a Trusted Cloud Provider
    type: Cloud Security Alliance Trusted Cloud Provider recognition
  trust_center:
    url: https://www.owndata.com/trust
frameworks:
- CyberEssentials
- FedRAMP
- GDPR
- ISO27001
- ISO27701
- SOC1
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: OwnBackup
provenance_date: '2026-11-10'
provider_name: OwnBackup
provider_slug: ownbackup
slug: ownbackup-compliance
source_date: '2026-11-10'
source_filename: ownbackup-compliance.yml
source_heading: Compliance
source_page: https://www.owndata.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: OwnBackup\naid: ownbackup\nurl: https://www.owndata.com/trust\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ownbackup-trust-center.yml\ntrust_center:\n  url: https://www.owndata.com/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II attestation report\n  scope: Own platform\n  period: null\n  issuer: null\n  report_access: nda\n  text: Own's latest SOC 2 Type II report is available upon request under NDA.\n- framework: SOC1\n  type: SOC 1 Type II attestation report\n  scope: internal controls over financial reporting\n  period: null\n  issuer: null\n  report_access: nda\n  text: Own's\
  \ latest SOC 1 Type II report is available upon request under NDA.\n- framework: FedRAMP\n  type: FedRAMP authorization\n  scope: Own Government Cloud solution\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Own achieved FedRAMP authorization for its Own Government Cloud solution.\n- framework: ISO27001\n  type: ISO 27001:2013 certificate\n  scope: Information Security Management System\n  period: null\n  issuer: null\n  report_access: public\n  text: Own is ISO 27001:2013 and ISO 27701:2019 certified\n- framework: ISO27701\n  type: ISO 27701:2019 certificate\n  scope: Privacy Information Management System\n  period: null\n  issuer: null\n  report_access: public\n  text: ISO 27701:2019 Certificate Privacy Information Management System (PIMS)\n- framework: other\n  type: Hébergeur de Données de Santé (HDS) certification\n  scope: personal health data hosting\n  period: null\n  issuer: null\n  report_access: public\n  text: Own's HDS certification demonstrates our commitment\
  \ to securing and protecting the confidentiality of personal\n    health data.\n- framework: CyberEssentials\n  type: Cyber Essentials certification\n  scope: UK government requirements\n  period: null\n  issuer: null\n  report_access: public\n  text: Own is Cyber Essentials certified to comply with UK government requirements\n- framework: GDPR\n  type: GDPR compliance support\n  scope: Own products support customer GDPR obligations\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Own products are designed to support our customer's compliance obligations with data privacy regulations,\n    including GDPR requirements.\n- framework: other\n  type: EU-U.S. Data Privacy Framework registration\n  scope: cross-border transfers of personal data, including UK Extension and Swiss-U.S. DPF\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Own is registered under the EU-U.S. Data Privacy Framework (EU-U.S. DPF), UK Extension to the EU-U.S. DPF,\n    and Swiss-U.S.\
  \ DPF\n- framework: other\n  type: Cloud Security Alliance Trusted Cloud Provider recognition\n  scope: cloud security\n  period: null\n  issuer: Cloud Security Alliance\n  report_access: unstated\n  text: Cloud Security Alliance (CSA) has recognized Own as a Trusted Cloud Provider\n"
source_yaml_url: https://artifacts.apis.io/ownbackup/compliance/ownbackup-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from OwnBackup's own page on 2026-11-10.
synthetic: false
tags:
- Data Protection
- SaaS Backup
---
