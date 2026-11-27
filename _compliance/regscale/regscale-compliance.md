---
claim_count: 10
description: ''
doc:
  attestations:
  - framework: CyberEssentials
    issuer: A-LIGN, an authorized C3PAO
    period: null
    report_access: on_request
    scope: CMMC Level 2 (NIST SP 800-171 requirements) on RegScale CCM platform
    text: Certified by A-LIGN, an authorized C3PAO. Available upon Request
    type: CMMC Level 2 certification
  - framework: ISO27001
    issuer: A-LIGN
    period: null
    report_access: on_request
    scope: ISMS built and managed on RegScale platform
    text: RegScale achieved ISO 27001:2022 certification in under 30 days, with zero nonconformities across 123 fully implemented controls.
    type: ISO 27001:2022 certification
  - framework: FedRAMP
    issuer: DHS agency sponsorship
    period: Approved in June 2025
    report_access: unstated
    scope: FedRAMP Class D High Authorized
    text: FedRAMP High Approved in June 2025 with agency sponsorship from DHS.
    type: FedRAMP High authorization
  - framework: SOC2
    issuer: null
    period: Achieved in January 2024
    report_access: on_request
    scope: Continuous Controls Monitoring platform
    text: SOC 2 TYPE 2 Achieved in January 2024.
    type: SOC 2 Type 2
  - framework: other
    issuer: Texas Risk and Authorization Management Program
    period: null
    report_access: unstated
    scope: Meets full NIST SP 800-53 Moderate control baseline
    text: RegScale is TX-RAMP Level 2 certified, the highest authorization level under the Texas Risk and Authorization Management Program.
    type: TX-RAMP Level 2 certification
  - framework: CSA-STAR
    issuer: Cloud Security Alliance
    period: August 2024
    report_access: unstated
    scope: Self-assessment via CAIQ
    text: RegScale achieved CSA STAR Level 1 certification in August 2024.
    type: CSA STAR Level 1 certification
  - framework: CSA-STAR
    issuer: Cloud Security Alliance
    period: Sep 2025
    report_access: unstated
    scope: Consensus Assessments Initiative Questionnaire (CAIQ) score of 97.7%
    text: RegScale achieved Cloud Security Alliance (CSA) STAR designation as a Valid-AI-ted solution in Sep 2025 after earning a 97.7% score
    type: CSA STAR Valid-AI-ted designation
  - framework: other
    issuer: DoD
    period: null
    report_access: on_request
    scope: DoD Impact Level 5 under DoD CC SRG
    text: DoD IL5 In Process
    type: DoD IL5 in process
  - framework: SOC2
    issuer: null
    period: null
    report_access: unstated
    scope: core platform
    source: https://trust.regscale.com/
    text: RegScale maintains SOC 2 and FedRAMP High certifications for our core platform.
    type: certification
  - framework: FedRAMP
    issuer: null
    period: null
    report_access: unstated
    scope: core platform (FedRAMP High)
    source: https://trust.regscale.com/
    text: RegScale maintains SOC 2 and FedRAMP High certifications for our core platform.
    type: certification
  trust_center:
    url: https://regscale.com/security/
frameworks:
- CSA-STAR
- CyberEssentials
- FedRAMP
- ISO27001
- SOC2
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: RegScale
provenance_date: '2026-11-10'
provider_name: RegScale
provider_slug: regscale
slug: regscale-compliance
source_date: '2026-11-10'
source_filename: regscale-compliance.yml
source_heading: Compliance
source_page: https://regscale.com/security/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: RegScale\naid: regscale\nurl: https://regscale.com/security/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  sources:\n  - https://regscale.com/security/\n  - https://trust.regscale.com/\ntrust_center:\n  url: https://regscale.com/security/\nattestations:\n- framework: CyberEssentials\n  type: CMMC Level 2 certification\n  scope: CMMC Level 2 (NIST SP 800-171 requirements) on RegScale CCM platform\n  period: null\n  issuer: A-LIGN, an authorized C3PAO\n  report_access: on_request\n  text: Certified by A-LIGN, an authorized C3PAO. Available upon Request\n- framework: ISO27001\n  type: ISO 27001:2022 certification\n  scope: ISMS\
  \ built and managed on RegScale platform\n  period: null\n  issuer: A-LIGN\n  report_access: on_request\n  text: RegScale achieved ISO 27001:2022 certification in under 30 days, with zero nonconformities across 123 fully\n    implemented controls.\n- framework: FedRAMP\n  type: FedRAMP High authorization\n  scope: FedRAMP Class D High Authorized\n  period: Approved in June 2025\n  issuer: DHS agency sponsorship\n  report_access: unstated\n  text: FedRAMP High Approved in June 2025 with agency sponsorship from DHS.\n- framework: SOC2\n  type: SOC 2 Type 2\n  scope: Continuous Controls Monitoring platform\n  period: Achieved in January 2024\n  issuer: null\n  report_access: on_request\n  text: SOC 2 TYPE 2 Achieved in January 2024.\n- framework: other\n  type: TX-RAMP Level 2 certification\n  scope: Meets full NIST SP 800-53 Moderate control baseline\n  period: null\n  issuer: Texas Risk and Authorization Management Program\n  report_access: unstated\n  text: RegScale is TX-RAMP Level 2\
  \ certified, the highest authorization level under the Texas Risk and Authorization\n    Management Program.\n- framework: CSA-STAR\n  type: CSA STAR Level 1 certification\n  scope: Self-assessment via CAIQ\n  period: August 2024\n  issuer: Cloud Security Alliance\n  report_access: unstated\n  text: RegScale achieved CSA STAR Level 1 certification in August 2024.\n- framework: CSA-STAR\n  type: CSA STAR Valid-AI-ted designation\n  scope: Consensus Assessments Initiative Questionnaire (CAIQ) score of 97.7%\n  period: Sep 2025\n  issuer: Cloud Security Alliance\n  report_access: unstated\n  text: RegScale achieved Cloud Security Alliance (CSA) STAR designation as a Valid-AI-ted solution in Sep 2025\n    after earning a 97.7% score\n- framework: other\n  type: DoD IL5 in process\n  scope: DoD Impact Level 5 under DoD CC SRG\n  period: null\n  issuer: DoD\n  report_access: on_request\n  text: DoD IL5 In Process\n- framework: SOC2\n  type: certification\n  scope: core platform\n  period: null\n\
  \  issuer: null\n  report_access: unstated\n  text: RegScale maintains SOC 2 and FedRAMP High certifications for our core platform.\n  source: https://trust.regscale.com/\n- framework: FedRAMP\n  type: certification\n  scope: core platform (FedRAMP High)\n  period: null\n  issuer: null\n  report_access: unstated\n  text: RegScale maintains SOC 2 and FedRAMP High certifications for our core platform.\n  source: https://trust.regscale.com/\n"
source_yaml_url: https://artifacts.apis.io/regscale/compliance/regscale-compliance.yml
stated_fields:
- attestations
summary_line: 10 quoted statements, read from RegScale's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Compliance
- Governance Risk and Compliance
- Continuous Controls Monitoring
- Security
- FedRAMP
- OSCAL
- Risk Management
- Audit
- Compliance as Code
- Vulnerability Management
- Government
---
