---
api_specs:
- filename: informatica-authentication-api-openapi.yml
  format: yaml
  label: Informatica Authentication API
  slug: informatica-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/informatica/openapi/informatica-authentication-api-openapi.yml
- filename: informatica-connections-api-openapi.yml
  format: yaml
  label: Informatica Connections API
  slug: informatica-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/informatica/openapi/informatica-connections-api-openapi.yml
- filename: informatica-jobs-api-openapi.yml
  format: yaml
  label: Informatica Jobs API
  slug: informatica-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/informatica/openapi/informatica-jobs-api-openapi.yml
- filename: informatica-mapping-tasks-api-openapi.yml
  format: yaml
  label: Informatica Mapping Tasks API
  slug: informatica-mapping-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/informatica/openapi/informatica-mapping-tasks-api-openapi.yml
- filename: informatica-mappings-api-openapi.yml
  format: yaml
  label: Informatica Mappings API
  slug: informatica-mappings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/informatica/openapi/informatica-mappings-api-openapi.yml
- filename: informatica-schedules-api-openapi.yml
  format: yaml
  label: Informatica Schedules API
  slug: informatica-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/informatica/openapi/informatica-schedules-api-openapi.yml
claim_count: 7
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: AICPA-authorized auditors
    period: null
    report_access: unstated
    scope: security program
    text: Our security program is audited annually by AICPA-authorized auditors against HIPAA/HITECH, SOC 1, SOC 2, and SOC 3 attestation standards.
    type: audit against HIPAA/HITECH
  - framework: SOC1
    issuer: AICPA-authorized auditors
    period: null
    report_access: unstated
    scope: security program
    text: Our security program is audited annually by AICPA-authorized auditors against HIPAA/HITECH, SOC 1, SOC 2, and SOC 3 attestation standards.
    type: audit attestation
  - framework: SOC2
    issuer: AICPA-authorized auditors
    period: null
    report_access: unstated
    scope: security program
    text: Our security program is audited annually by AICPA-authorized auditors against HIPAA/HITECH, SOC 1, SOC 2, and SOC 3 attestation standards.
    type: audit attestation
  - framework: SOC3
    issuer: AICPA-authorized auditors
    period: null
    report_access: unstated
    scope: security program
    text: Our security program is audited annually by AICPA-authorized auditors against HIPAA/HITECH, SOC 1, SOC 2, and SOC 3 attestation standards.
    type: audit attestation
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: some cloud products and corporate environments
    text: Some of our cloud products and corporate environments are certified to other industry-specific compliance such as GxP, U.K. Cyber Essentials Plus and U.S. Government FedRAMP Moderate.
    type: GxP
  - framework: CyberEssentials
    issuer: null
    period: null
    report_access: unstated
    scope: some cloud products and corporate environments
    text: Some of our cloud products and corporate environments are certified to other industry-specific compliance such as GxP, U.K. Cyber Essentials Plus and U.S. Government FedRAMP Moderate.
    type: Cyber Essentials Plus
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: some cloud products and corporate environments
    text: Some of our cloud products and corporate environments are certified to other industry-specific compliance such as GxP, U.K. Cyber Essentials Plus and U.S. Government FedRAMP Moderate.
    type: FedRAMP Moderate
  trust_center:
    url: https://trust.informatica.com/
frameworks:
- CyberEssentials
- FedRAMP
- HIPAA
- SOC1
- SOC2
- SOC3
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Informatica
provenance_date: '2026-11-09'
provider_name: Informatica
provider_slug: informatica
slug: informatica-compliance
source_date: '2026-11-09'
source_filename: informatica-compliance.yml
source_heading: Compliance
source_page: https://trust.informatica.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Informatica\naid: informatica\nurl: https://trust.informatica.com/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://trust.informatica.com/\nattestations:\n- framework: HIPAA\n  type: audit against HIPAA/HITECH\n  scope: security program\n  period: null\n  issuer: AICPA-authorized auditors\n  report_access: unstated\n  text: Our security program is audited annually by AICPA-authorized auditors against HIPAA/HITECH, SOC 1, SOC 2,\n    and SOC 3 attestation standards.\n- framework: SOC1\n  type: audit attestation\n  scope: security program\n  period: null\n  issuer: AICPA-authorized auditors\n  report_access:\
  \ unstated\n  text: Our security program is audited annually by AICPA-authorized auditors against HIPAA/HITECH, SOC 1, SOC 2,\n    and SOC 3 attestation standards.\n- framework: SOC2\n  type: audit attestation\n  scope: security program\n  period: null\n  issuer: AICPA-authorized auditors\n  report_access: unstated\n  text: Our security program is audited annually by AICPA-authorized auditors against HIPAA/HITECH, SOC 1, SOC 2,\n    and SOC 3 attestation standards.\n- framework: SOC3\n  type: audit attestation\n  scope: security program\n  period: null\n  issuer: AICPA-authorized auditors\n  report_access: unstated\n  text: Our security program is audited annually by AICPA-authorized auditors against HIPAA/HITECH, SOC 1, SOC 2,\n    and SOC 3 attestation standards.\n- framework: other\n  type: GxP\n  scope: some cloud products and corporate environments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Some of our cloud products and corporate environments are certified\
  \ to other industry-specific compliance\n    such as GxP, U.K. Cyber Essentials Plus and U.S. Government FedRAMP Moderate.\n- framework: CyberEssentials\n  type: Cyber Essentials Plus\n  scope: some cloud products and corporate environments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Some of our cloud products and corporate environments are certified to other industry-specific compliance\n    such as GxP, U.K. Cyber Essentials Plus and U.S. Government FedRAMP Moderate.\n- framework: FedRAMP\n  type: FedRAMP Moderate\n  scope: some cloud products and corporate environments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Some of our cloud products and corporate environments are certified to other industry-specific compliance\n    such as GxP, U.K. Cyber Essentials Plus and U.S. Government FedRAMP Moderate.\n"
source_yaml_url: https://artifacts.apis.io/informatica/compliance/informatica-compliance.yml
stated_fields:
- attestations
summary_line: 7 quoted statements, read from Informatica's own page on 2026-11-09.
synthetic: false
tags:
- Address Verification
- B2B Gateway
- Cloud Services
- Data Governance
- Data Integration
- Data Profiling
- Data Quality
- Enterprise Software
- ETL
- IDMC
- IICS
- Master Data Management
- Reference Data Management
- Data Catalog
---
