---
api_specs:
- filename: ostium-labs-prices-asyncapi.yml
  format: yaml
  label: Ostium Builder API
  slug: ostium-builder-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/ostium-labs/asyncapi/ostium-labs-prices-asyncapi.yml
claim_count: 3
description: ''
doc:
  attestations:
  - framework: other
    issuer: Zellic
    period: null
    report_access: unstated
    scope: Core trading, vault and liquidation contracts; trading execution, position settlement, fee calculations and oracle price handling
    text: Zellic is a smart contract audit firm specializing in DeFi security reviews and vulnerability research.
    type: Smart contract security audit
  - framework: other
    issuer: ThreeSigma
    period: February 19 to March 22, 2024
    report_access: unstated
    scope: Secondary audit of trading contracts, OLP vault mechanics, rollover fee calculations and position closure logic
    text: Conducted from February 19 to March 22, 2024.
    type: Smart contract security audit
  - framework: other
    issuer: Pashov Audit Group
    period: January 2025, April 2025, and January 2026
    report_access: unstated
    scope: Core trading and vault contracts, oracle integration, price verification and liquidation automation; 13 core contracts in the January 2026 review
    text: 'Three security reviews: January 2025, April 2025, and January 2026.'
    type: Smart contract security review
  trust_center:
    url: https://docs.ostium.com/protocol/security/audits
frameworks:
- other
layer: compliance
layer_version: 0.1.0
layout: compliance
method: harvested
model: claude-haiku-5-5
name: Ostium Labs
provenance_date: '2026-11-10'
provider_name: Ostium Labs
provider_slug: ostium-labs
slug: ostium-labs-compliance
source_date: '2026-11-10'
source_filename: ostium-labs-compliance.yml
source_heading: Compliance
source_page: https://docs.ostium.com/protocol/security/audits
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\ncompliance: 0.1.0\nprovider: Ostium Labs\naid: ostium-labs\nurl: https://docs.ostium.com/protocol/security/audits\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  discovered_via:\n  - security/ostium-labs-trust-center.yml\ntrust_center:\n  url: https://docs.ostium.com/protocol/security/audits\nattestations:\n- framework: other\n  type: Smart contract security audit\n  scope: Core trading, vault and liquidation contracts; trading execution, position settlement, fee calculations\n    and oracle price handling\n  period: null\n  issuer: Zellic\n  report_access: unstated\n  text: Zellic is a smart contract audit firm specializing in DeFi security reviews and vulnerability\
  \ research.\n- framework: other\n  type: Smart contract security audit\n  scope: Secondary audit of trading contracts, OLP vault mechanics, rollover fee calculations and position closure\n    logic\n  period: February 19 to March 22, 2024\n  issuer: ThreeSigma\n  report_access: unstated\n  text: Conducted from February 19 to March 22, 2024.\n- framework: other\n  type: Smart contract security review\n  scope: Core trading and vault contracts, oracle integration, price verification and liquidation automation; 13\n    core contracts in the January 2026 review\n  period: January 2025, April 2025, and January 2026\n  issuer: Pashov Audit Group\n  report_access: unstated\n  text: 'Three security reviews: January 2025, April 2025, and January 2026.'\n"
source_yaml_url: https://artifacts.apis.io/ostium-labs/compliance/ostium-labs-compliance.yml
stated_fields:
- attestations
summary_line: 3 quoted statements, read from Ostium Labs's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Perpetual Futures
- Decentralized Finance
- DeFi
- Trading
- Real World Assets
- Derivatives
- Arbitrum
- Blockchain
- Web3
- Market Data
- SDK
- Real-Time
---
