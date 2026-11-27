---
claim_count: 3
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: null
    period: null
    report_access: on_request
    scope: null
    text: Expo is committed to enterprise-grade security and has obtained SOC 2 Type 2 attestation.
    type: SOC 2 Type 2 attestation
  - framework: GDPR
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: In all scenarios regarding our users' data, Expo is GDPR-, CCPA-, and Data Privacy Framework-compliant.
    type: compliance
  - framework: CCPA
    issuer: null
    period: null
    report_access: unstated
    scope: null
    text: In all scenarios regarding our users' data, Expo is GDPR-, CCPA-, and Data Privacy Framework-compliant.
    type: compliance
  trust_center:
    url: https://expo.dev/trust
frameworks:
- CCPA
- GDPR
- SOC2
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Expo
provenance_date: '2026-11-09'
provider_name: Expo
provider_slug: expo
slug: expo-compliance
source_date: '2026-11-09'
source_filename: expo-compliance.yml
source_heading: Compliance
source_page: https://expo.dev/trust
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Expo\naid: expo\nurl: https://expo.dev/trust\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/expo-trust-center.yml\ntrust_center:\n  url: https://expo.dev/trust\nattestations:\n- framework: SOC2\n  type: SOC 2 Type 2 attestation\n  scope: null\n  period: null\n  issuer: null\n  report_access: on_request\n  text: Expo is committed to enterprise-grade security and has obtained SOC 2 Type 2 attestation.\n- framework: GDPR\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: In all scenarios regarding our users' data, Expo is GDPR-, CCPA-, and Data Privacy\
  \ Framework-compliant.\n- framework: CCPA\n  type: compliance\n  scope: null\n  period: null\n  issuer: null\n  report_access: unstated\n  text: In all scenarios regarding our users' data, Expo is GDPR-, CCPA-, and Data Privacy Framework-compliant.\n"
source_yaml_url: https://artifacts.apis.io/expo/compliance/expo-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Expo's own page on 2026-11-09.
synthetic: false
tags:
- React Native
- Mobile Development
- Build Automation
- Over-the-Air Updates
- CI/CD
- App Store Submission
- Push Notifications
- Cloud Build
- Developer Tools
---
