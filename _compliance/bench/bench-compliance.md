---
claim_count: 2
description: ''
doc:
  attestations:
  - framework: SOC2
    issuer: third party audit firm
    period: annual
    report_access: unstated
    scope: security, availability, processing integrity, confidentiality and privacy of platform and supporting infrastructure
    text: Bench undergoes a SOC 2 Type 2 examination of our security controls against the AICPA defined standards on an annual basis with a third party audit firm to assure security of our platform and its supporting infrastructure.
    type: examination of security controls (Type 2)
  - framework: SOC3
    issuer: third party audit firm
    period: annual
    report_access: unstated
    scope: AICPA defined standards security controls
    text: Bench undergoes annual SOC 2 and SOC 3 examinations of our security controls against the AICPA defined standards.
    type: examination of security controls
  trust_center:
    url: https://www.bench.co/security
frameworks:
- SOC2
- SOC3
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Bench
provenance_date: '2026-11-09'
provider_name: Bench
provider_slug: bench
slug: bench-compliance
source_date: '2026-11-09'
source_filename: bench-compliance.yml
source_heading: Compliance
source_page: https://www.bench.co/security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Bench\naid: bench\nurl: https://www.bench.co/security\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://www.bench.co/security\nattestations:\n- framework: SOC2\n  type: examination of security controls (Type 2)\n  scope: security, availability, processing integrity, confidentiality and privacy of platform and supporting infrastructure\n  period: annual\n  issuer: third party audit firm\n  report_access: unstated\n  text: Bench undergoes a SOC 2 Type 2 examination of our security controls against the AICPA defined standards\n    on an annual basis with a third party audit firm to assure security of our\
  \ platform and its supporting infrastructure.\n- framework: SOC3\n  type: examination of security controls\n  scope: AICPA defined standards security controls\n  period: annual\n  issuer: third party audit firm\n  report_access: unstated\n  text: Bench undergoes annual SOC 2 and SOC 3 examinations of our security controls against the AICPA defined standards.\n"
source_yaml_url: https://artifacts.apis.io/bench/compliance/bench-compliance.yml
stated_fields:
- attestations
summary_line: 2 quoted statements, read from Bench's own page on 2026-11-09.
synthetic: false
tags:
- Accounting
- Bookkeeping
- Small Business
- Software-as-a-Service
- Finance
---
