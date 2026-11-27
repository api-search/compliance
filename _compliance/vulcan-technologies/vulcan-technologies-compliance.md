---
claim_count: 5
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: independent auditor
    period: null
    report_access: on_request
    scope: security, availability, and confidentiality controls
    text: SOC 2 Independent audit of our security, availability, and confidentiality controls. Report available by request.
    type: SOC 2 audit report
  - framework: ISO27001
    issuer: null
    period: null
    report_access: on_request
    scope: information security management system
    text: Certified information security management system. Certificate available on request.
    type: ISO 27001 certification
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: Texas state agency security requirements for public-sector deployments
    text: Aligned to Texas state agency security requirements for public-sector deployments.
    type: TX-RAMP alignment
  - framework: FedRAMP
    issuer: accredited 3PAO
    period: null
    report_access: on_request
    scope: VulcanGov deployment in AWS GovCloud (US), assessed against FedRAMP Rev. 5 baseline
    text: An accredited third-party assessment organization (3PAO) independently assessed those controls, and VulcanGov is designated FedRAMP Ready and listed on the FedRAMP Marketplace as we pursue full authorization.
    type: FedRAMP Ready designation
  - framework: FedRAMP
    issuer: FedRAMP Marketplace listing; independently assessed by an accredited 3PAO
    period: null
    report_access: on_request
    scope: VulcanGov federal deployment inside AWS GovCloud (US)
    source: https://vulcan.ai/fedramp
    text: VulcanGov is designated FedRAMP Ready and listed on the FedRAMP Marketplace as we pursue full authorization.
    type: FedRAMP Ready designation
  trust_center:
    url: https://vulcan.ai/security
frameworks:
- FedRAMP
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Vulcan Technologies
provenance_date: '2026-11-10'
provider_name: Vulcan Technologies
provider_slug: vulcan-technologies
slug: vulcan-technologies-compliance
source_date: '2026-11-10'
source_filename: vulcan-technologies-compliance.yml
source_heading: Compliance
source_page: https://vulcan.ai/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Vulcan Technologies\naid: vulcan-technologies\nurl: https://vulcan.ai/security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/vulcan-technologies-trust-center.yml\n  sources:\n  - https://vulcan.ai/fedramp\n  - https://vulcan.ai/security\ntrust_center:\n  url: https://vulcan.ai/security\nattestations:\n- framework: SOC2\n  type: SOC 2 audit report\n  scope: security, availability, and confidentiality controls\n  period: null\n  issuer: independent auditor\n  report_access: on_request\n  text: SOC 2 Independent audit of our security, availability, and confidentiality controls. Report available by\n\
  \    request.\n- framework: ISO27001\n  type: ISO 27001 certification\n  scope: information security management system\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Certified information security management system. Certificate available on request.\n- framework: other\n  type: TX-RAMP alignment\n  scope: Texas state agency security requirements for public-sector deployments\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Aligned to Texas state agency security requirements for public-sector deployments.\n- framework: FedRAMP\n  type: FedRAMP Ready designation\n  scope: VulcanGov deployment in AWS GovCloud (US), assessed against FedRAMP Rev. 5 baseline\n  period: null\n  issuer: accredited 3PAO\n  report_access: on_request\n  text: An accredited third-party assessment organization (3PAO) independently assessed those controls, and VulcanGov\n    is designated FedRAMP Ready and listed on the FedRAMP Marketplace as we pursue full authorization.\n\
  - framework: FedRAMP\n  type: FedRAMP Ready designation\n  scope: VulcanGov federal deployment inside AWS GovCloud (US)\n  period: null\n  issuer: FedRAMP Marketplace listing; independently assessed by an accredited 3PAO\n  report_access: on_request\n  text: VulcanGov is designated FedRAMP Ready and listed on the FedRAMP Marketplace as we pursue full authorization.\n  source: https://vulcan.ai/fedramp\n"
source_yaml_url: https://artifacts.apis.io/vulcan-technologies/compliance/vulcan-technologies-compliance.yml
stated_fields:
- attestations
summary_line: 5 quoted statements, read from Vulcan Technologies's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Legal AI
- Government
- RegTech
- Regulatory Compliance
- Artificial Intelligence
- AI Agents
- FedRAMP
- Public Sector
---
