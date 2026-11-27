---
api_specs:
- filename: myome-institutional-interface-api-openapi.yml
  format: yaml
  label: MyOme Institutional Interface API
  slug: myome-institutional-interface-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/myome/openapi/myome-institutional-interface-api-openapi.yml
- filename: myome-requisitions-and-orders-api-openapi.yml
  format: yaml
  label: MyOme Requisitions and Orders API
  slug: myome-requisitions-and-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/myome/openapi/myome-requisitions-and-orders-api-openapi.yml
- filename: myome-resources-api-openapi.yml
  format: yaml
  label: MyOme Resources API
  slug: myome-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/myome/openapi/myome-resources-api-openapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: HIPAA
    issuer: null
    period: null
    report_access: unstated
    scope: Health and Genetic Information
    text: Health and Genetic Information (collected and processed in compliance with HIPAA regulations)
    type: Compliance with HIPAA regulations for health and genetic information
  - framework: other
    issuer: null
    period: null
    report_access: unstated
    scope: MyOme, Inc. laboratory tests
    text: a clinical laboratory certified under the Clinical Laboratory Improvement Amendments of 1988 (CLIA)
    type: CLIA certification
  - framework: other
    issuer: College of American Pathologists
    period: null
    report_access: unstated
    scope: High complexity clinical laboratory testing
    text: College of American Pathologist (CAP) accredited to perform high complexity clinical laboratory testing.
    type: CAP accreditation
  trust_center:
    url: https://myome.com/about-us/privacy-and-security
frameworks:
- HIPAA
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: MyOme
provenance_date: '2026-11-10'
provider_name: MyOme
provider_slug: myome
slug: myome-compliance
source_date: '2026-11-10'
source_filename: myome-compliance.yml
source_heading: Compliance
source_page: https://myome.com/about-us/privacy-and-security
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: MyOme\naid: myome\nurl: https://myome.com/about-us/privacy-and-security\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ntrust_center:\n  url: https://myome.com/about-us/privacy-and-security\nattestations:\n- framework: HIPAA\n  type: Compliance with HIPAA regulations for health and genetic information\n  scope: Health and Genetic Information\n  period: null\n  issuer: null\n  report_access: unstated\n  text: Health and Genetic Information (collected and processed in compliance with HIPAA regulations)\n- framework: other\n  type: CLIA certification\n  scope: MyOme, Inc. laboratory tests\n  period: null\n  issuer: null\n  report_access:\
  \ unstated\n  text: a clinical laboratory certified under the Clinical Laboratory Improvement Amendments of 1988 (CLIA)\n- framework: other\n  type: CAP accreditation\n  scope: High complexity clinical laboratory testing\n  period: null\n  issuer: College of American Pathologists\n  report_access: unstated\n  text: College of American Pathologist (CAP) accredited to perform high complexity clinical laboratory testing.\n"
source_yaml_url: https://artifacts.apis.io/myome/compliance/myome-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from MyOme's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Genomics
- Healthcare
- Clinical Laboratory
- Whole Genome Sequencing
- Precision Medicine
- Bioinformatics
- Polygenic Risk Scores
- Pharmacogenomics
- Rare Disease
- Diagnostics
- Life Sciences
---
