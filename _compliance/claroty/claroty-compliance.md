---
api_specs:
- filename: claroty-authenticate-api-openapi.yml
  format: yaml
  label: Claroty Authenticate API
  slug: claroty-authenticate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-authenticate-api-openapi.yml
- filename: claroty-health-api-openapi.yml
  format: yaml
  label: Claroty Health API
  slug: claroty-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-health-api-openapi.yml
- filename: claroty-is-key-registered-api-openapi.yml
  format: yaml
  label: Claroty Is Key Registered API
  slug: claroty-is-key-registered-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-is-key-registered-api-openapi.yml
- filename: claroty-jwks-api-openapi.yml
  format: yaml
  label: Claroty Jwks API
  slug: claroty-jwks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-jwks-api-openapi.yml
- filename: claroty-jwthenticator-api-openapi.yml
  format: yaml
  label: Claroty JW Thenticator API
  slug: claroty-jwthenticator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-jwthenticator-api-openapi.yml
- filename: claroty-refresh-api-openapi.yml
  format: yaml
  label: Claroty Refresh API
  slug: claroty-refresh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-refresh-api-openapi.yml
- filename: claroty-register-key-api-openapi.yml
  format: yaml
  label: Claroty Register Key API
  slug: claroty-register-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-register-key-api-openapi.yml
- filename: claroty-validate-api-openapi.yml
  format: yaml
  label: Claroty Validate API
  slug: claroty-validate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-validate-api-openapi.yml
- filename: claroty-validate-request-api-openapi.yml
  format: yaml
  label: Claroty Validate Request API
  slug: claroty-validate-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/claroty/openapi/claroty-validate-request-api-openapi.yml
claim_count: 13
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: nda
    scope: security, availability, processing integrity, confidentiality, and privacy
    text: To obtain the external audit reports and pen test documents, an NDA must be signed first
    type: SOC 2 Type 2
  - framework: ISO27001
    issuer: null
    period: null
    report_access: unstated
    scope: information security management systems
    text: ISO 27001 is the internationally recognized standard for information security management systems (ISMS).
    type: ISO 27001:2022
  - framework: ISO27701
    issuer: null
    period: null
    report_access: unstated
    scope: privacy information management systems
    text: ISO 27701 extends the ISO 27001 standard to include privacy information management systems (PIMS).
    type: ISO 27701:2019
  - framework: ISO27017
    issuer: null
    period: null
    report_access: unstated
    scope: cloud-specific security controls
    text: ISO 27017 complements ISO 27001 by providing cloud-specific guidance for information security controls.
    type: ISO 27017:2015
  - framework: ISO27018
    issuer: null
    period: null
    report_access: unstated
    scope: privacy of PII in public cloud
    text: ISO 27018 complements ISO 27001 by providing privacy-specific guidance for protecting personally identifiable information (PII) in public cloud environments.
    type: ISO 27018:2019
  - framework: C5
    issuer: German Federal Office for Information Security (BSI) developed the standard
    period: null
    report_access: unstated
    scope: cloud services
    text: C5 (Cloud Computing Compliance Controls Catalog) Type 2
    type: C5 Type 2
  - framework: CSA-STAR
    issuer: null
    period: null
    report_access: unstated
    scope: cloud security
    text: CSA STAR Level 2
    type: CSA STAR Level 2
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: health information solutions
    text: Our adherence to HIPAA ensures that our solutions meet strict privacy, security, and breach notification requirements
    type: HIPAA adherence
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: personal data of EU individuals
    text: Claroty complies with the European Union’s General Data Protection Regulation (GDPR)
    type: GDPR compliance
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Australian critical infrastructure
    text: The Security of Critical Infrastructure Act 2018 (SOCI)
    type: SOCI Act 2018 adherence
  - framework: SOC3
    issuer: null
    period: null
    report_access: unstated
    scope: security, availability, and confidentiality
    text: Our SOC 3 report provides public assurance that Claroty maintains effective controls
    type: SOC 3 report
  - framework: TISAX
    issuer: ENX Association
    period: null
    report_access: unstated
    scope: automotive information security
    text: Claroty’s assessment result is exclusively retrievable by registered participants through the ENX Portal
    type: TISAX assessment (VDA ISA)
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: public-sector IT systems in Spain
    text: By complying with CCN guidelines, we ensure that our solutions meet stringent information security and risk management requirements
    type: CCN standards
  trust_center:
    url: https://www.claroty.com/trust
frameworks:
- C5
- CSA-STAR
- GDPR
- HIPAA
- ISO27001
- ISO27017
- ISO27018
- ISO27701
- SOC2
- SOC3
- TISAX
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Claroty
provenance_date: '2026-11-09'
provider_name: Claroty
provider_slug: claroty
slug: claroty-compliance
source_date: '2026-11-09'
source_filename: claroty-compliance.yml
source_heading: Compliance
source_page: https://www.claroty.com/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Claroty\naid: claroty\nurl: https://www.claroty.com/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.claroty.com/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: security, availability, processing integrity, confidentiality, and privacy\n  period: null\n  issuer: null\n  report_access: nda\n  text: To obtain the external audit reports and pen test documents, an NDA must be signed first\n- framework: ISO27001\n  type: ISO 27001:2022\n  scope: information security management systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27001 is the internationally\
  \ recognized standard for information security management systems (ISMS).\n- framework: ISO27701\n  type: ISO 27701:2019\n  scope: privacy information management systems\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27701 extends the ISO 27001 standard to include privacy information management systems (PIMS).\n- framework: ISO27017\n  type: ISO 27017:2015\n  scope: cloud-specific security controls\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27017 complements ISO 27001 by providing cloud-specific guidance for information security controls.\n- framework: ISO27018\n  type: ISO 27018:2019\n  scope: privacy of PII in public cloud\n  period: null\n  issuer: null\n  report_access: unstated\n  text: ISO 27018 complements ISO 27001 by providing privacy-specific guidance for protecting personally identifiable\n    information (PII) in public cloud environments.\n- framework: C5\n  type: C5 Type 2\n  scope: cloud services\n  period: null\n  issuer:\
  \ German Federal Office for Information Security (BSI) developed the standard\n  report_access: unstated\n  text: C5 (Cloud Computing Compliance Controls Catalog) Type 2\n- framework: CSA-STAR\n  type: CSA STAR Level 2\n  scope: cloud security\n  period: null\n  issuer: null\n  report_access: unstated\n  text: CSA STAR Level 2\n- framework: HIPAA\n  type: HIPAA adherence\n  scope: health information solutions\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our adherence to HIPAA ensures that our solutions meet strict privacy, security, and breach notification\n    requirements\n- framework: GDPR\n  type: GDPR compliance\n  scope: personal data of EU individuals\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Claroty complies with the European Union’s General Data Protection Regulation (GDPR)\n- framework: other\n  type: SOCI Act 2018 adherence\n  scope: Australian critical infrastructure\n  period: null\n  issuer: null\n  report_access: unstated\n\
  \  text: The Security of Critical Infrastructure Act 2018 (SOCI)\n- framework: SOC3\n  type: SOC 3 report\n  scope: security, availability, and confidentiality\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Our SOC 3 report provides public assurance that Claroty maintains effective controls\n- framework: TISAX\n  type: TISAX assessment (VDA ISA)\n  scope: automotive information security\n  period: null\n  issuer: ENX Association\n  report_access: unstated\n  text: Claroty’s assessment result is exclusively retrievable by registered participants through the ENX Portal\n- framework: other\n  type: CCN standards\n  scope: public-sector IT systems in Spain\n  period: null\n  issuer: null\n  report_access: unstated\n  text: By complying with CCN guidelines, we ensure that our solutions meet stringent information security and risk\n    management requirements\n"
source_yaml_url: https://artifacts.apis.io/claroty/compliance/claroty-compliance.yml
stated_fields:
- attestations
summary_line: 13 quoted statements, read from Claroty's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- OT Security
- Cyber-Physical Systems
- IoT Security
- Industrial Control Systems
- Threat Detection
- Exposure Management
- Healthcare Security
---
