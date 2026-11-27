---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Dremio maintains compliance with the American Institute of Certified Public Accountants (AICPA) System and Organization Controls - Trust Services Criteria, commonly known as SOC 2.
    type: SOC 2 Type II report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Obtaining ISO 27001:2022 certification demonstrates that Dremio employs a comprehensive framework of legal, physical, and technical controls for information risk management.
    type: ISO 27001:2022 certification
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: storage and security of its data
    text: Dremio is compliant with the storage and security of its data according to Article 27 of the General Data Protection Regulation (GDPR).
    type: compliance statement
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Dremio maintains compliance with the California Consumer Privacy Act (CCPA)
    type: compliance statement
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: Dremio is compliant with the Health Insurance Portability and Accountability Act (HIPAA)
    type: compliance statement
  trust_center:
    url: https://docs.dremio.com/dremio-cloud/security/compliance/
frameworks:
- CCPA
- GDPR
- HIPAA
- ISO27001
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Dremio
provenance_date: '2026-11-09'
provider_name: Dremio
provider_slug: dremio
slug: dremio-compliance
source_date: '2026-11-09'
source_filename: dremio-compliance.yml
source_heading: Compliance
source_page: https://docs.dremio.com/dremio-cloud/security/compliance/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Dremio\naid: dremio\nurl: https://docs.dremio.com/dremio-cloud/security/compliance/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://docs.dremio.com/dremio-cloud/security/compliance/\nattestations:\n- framework: SOC2\n  type: SOC 2 Type II report\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dremio maintains compliance with the American Institute of Certified Public Accountants (AICPA) System and\n    Organization Controls - Trust Services Criteria, commonly known as SOC 2.\n- framework: ISO27001\n  type: ISO 27001:2022 certification\n  scope: null\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: Obtaining ISO 27001:2022 certification demonstrates that Dremio employs a comprehensive framework of legal,\n    physical, and technical controls for information risk management.\n- framework: GDPR\n  type: compliance statement\n  scope: storage and security of its data\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dremio is compliant with the storage and security of its data according to Article 27 of the General Data\n    Protection Regulation (GDPR).\n- framework: CCPA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dremio maintains compliance with the California Consumer Privacy Act (CCPA)\n- framework: HIPAA\n  type: compliance statement\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Dremio is compliant with the Health Insurance Portability and Accountability Act (HIPAA)\n"
source_yaml_url: https://artifacts.apis.io/dremio/compliance/dremio-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Dremio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Lakehouse
- Analytics
- SQL Query Engine
- Apache Iceberg
- Apache Arrow
- Data Catalog
- Semantic Layer
- AI Agents
- MCP
---
