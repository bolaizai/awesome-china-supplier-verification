# Awesome China Supplier Verification & Factory Audit

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) ![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg) ![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg) [![Stars](https://img.shields.io/github/stars/sasharun/awesome-china-supplier-verification?style=social)](https://github.com/sasharun/awesome-china-supplier-verification) ![Last update](https://img.shields.io/badge/last%20update-2026--07-blue.svg)

> A practical shortlist for overseas importers, procurement managers, sourcing agents, and Amazon/DTC sellers who need to **verify a China supplier** before wiring money. Covers Chinese factory audit options, supplier verification tools, business-registry checks, customs data, third-party inspection, and due diligence steps that actually catch fake factories and traders posing as manufacturers.

---

## Why this matters

Skipping vetting is how you fund a "factory" that is three desks and a WeChat account. Common failure modes: trading companies listing someone else's workshop photos, sample quality that never shows up in bulk, certificates photoshopped overnight, and bank accounts that do not match the company on the contract. One bad container costs more than a year of audits. Treat verification as cost of goods, not optional paperwork.

---

## The 5-minute gut check

Run this before you negotiate price. If any box fails hard, pause.

| Check | What you want | Where to look |
|---|---|---|
| Business license / Unified Social Credit Code | Real legal entity, scope matches the product | [GSXT](https://www.gsxt.gov.cn), Qichacha, Tianyancha |
| Factory vs trader | Own production lines, not just a sales desk | ICP filing, live video of the floor, 1688 reverse-check |
| Export / customs history | They have actually shipped, volume is plausible | ImportYeti, ImportGenius, Panjiva |
| Certificate authenticity | ISO / CE / FCC numbers resolve at the issuer | SGS, BV, Intertek, TÜV portals — not a PDF from the supplier |
| Third-party or on-site audit | Capacity, QC, and labor claims hold up in person | QIMA, SGS, BV, or your own visit |

No single tool clears a supplier. Cross-check at least three of the rows above.

---

## Contents

- [B2B Marketplaces & Supplier Directories](#b2b-marketplaces--supplier-directories)
- [Business Registry & Company Credit Checks](#business-registry--company-credit-checks)
- [Customs & Trade Data](#customs--trade-data)
- [Third-Party Inspection & Factory Audit](#third-party-inspection--factory-audit)
- [Telling a Factory from a Trading Company](#telling-a-factory-from-a-trading-company)
- [Samples, Golden Sample & Pre-shipment](#samples-golden-sample--pre-shipment)
- [Payment Terms & Trade Assurance](#payment-terms--trade-assurance)
- [Red Flags & Scam Avoidance](#red-flags--scam-avoidance)
- [FAQ](#faq)
- [Toolbox & templates](#toolbox--templates)
- [Related lists](#related-lists)
- [Contributing](#contributing)
- [Star History](#star-history)
- [License](#license)

---

## B2B Marketplaces & Supplier Directories

Treat these as lead sources, not proof of legitimacy. Gold badges and "Verified" tags are paid products — useful filters, not clearance.

- [Alibaba.com](https://www.alibaba.com) — Largest global B2B marketplace; huge supplier base and noise. Use with Trade Assurance and your own registry/customs checks, not alone.
- [Made-in-China](https://www.made-in-china.com) — Long-running China export directory; relatively stronger in machinery, industrial parts, and hardware than fashion flash-sellers.
- [Global Sources](https://www.globalsources.com) — Asia-focused export platform tied to Hong Kong trade shows; solid for electronics and consumer goods sourcing.
- [ThomasNet](https://www.thomasnet.com) — North America industrial directory; useful when you need a non-China backup or a US/CA manufacturer alternative.
- [Kompass](https://www.kompass.com) — Global B2B company directory; good for mapping who else makes the same product in other countries.
- [Europages](https://www.europages.com) — European B2B directory; handy if your buyers or secondary suppliers sit in the EU.
- [1688](https://www.1688.com) — Alibaba's domestic wholesale site (Chinese). Reverse-search a product here to see if your "factory" is actually buying from someone else.
- [DHgate](https://www.dhgate.com) — Smaller-lot wholesale marketplace; fine for test orders, thin on deep factory due diligence data.
- [GZWM](https://guangzhouwholesalemarket.com) — Verified vendor directory for China's physical wholesale markets (Baiyun Leather City, Zhanxi Shoes, Kinbo, Nanyou) with stall-level booth details; paid membership unlocks direct supplier WeChat contacts.

---

## Business Registry & Company Credit Checks

This is the spine of supplier verification. If the legal entity is wrong, everything else is theater.

- [National Enterprise Credit Information Publicity System (GSXT)](https://www.gsxt.gov.cn) — Official Chinese business registry. Check license status, business scope, shareholders, and annual reports. Source of truth other apps scrape from.
- [Tianyancha](https://www.tianyancha.com) — Commercial aggregator of Chinese company data; equity charts make shell companies and related entities easier to spot. Mostly Chinese UI.
- [Qichacha](https://www.qcc.com) — Peer to Tianyancha; cross-check when one database is incomplete or slower to update. Mostly Chinese UI.
- [Dun & Bradstreet (D&B)](https://www.dnb.com) — International credit reports and D-U-N-S numbers; what many HQ risk teams require for approved-vendor lists. Paid, slower, globally recognized.
- [China Judgments Online](https://wenshu.court.gov.cn) — Official court judgment database. Search the company name for contract disputes and lawsuits — free and underused by foreign buyers.
- [China Enforcement Information (zxgk)](https://zxgk.court.gov.cn) — Check if the company or legal rep is a dishonest judgment debtor ("laolai"). Harder signal than a clean business license.
- [Alibaba Verified Supplier](https://seller.alibaba.com/tw-new/lp/verified-supplier) — Platform-run on-site verification (often with SGS/TÜV/Intertek). Helpful filter; still not independent due diligence.
- [FactoryBase](https://factorybase.ai) — Free verification database of Chinese factories: one page per factory with business-registry data, certifications, products and export records, searchable by category and readable by AI search (ChatGPT/Claude). Free to browse; you pay only for deeper verification.

---

## Customs & Trade Data

China does not publish line-level export invoices to the public. These tools mostly reverse-engineer shippers from US, India, and other importers' bills of lading. Use as a signal, not a complete census.

- [ImportYeti](https://importyeti.com) — Friendliest free tier for US customs bills of lading. Paste a company name and see if they have actually shipped, and roughly how much.
- [ImportGenius](https://www.importgenius.com) — Multi-country customs data; paid plans go deeper for competitor mapping and volume checks.
- [Panjiva (S&P Global)](https://panjiva.com) — Enterprise-grade trade intelligence and supply-chain graphs. Expensive; common inside large procurement teams.
- [Tendata](https://www.tendata.cn) — China-based trade-data platform with broad country coverage; widely used by Chinese exporters for lead gen — same data helps you reverse-check them.
- [52wmb (Waimao Bang)](https://www.52wmb.com) — Another China-side customs database; often compared on price vs Tendata for the same class of queries.

---

## Third-Party Inspection & Factory Audit

Supplier-issued test reports are marketing. Independent inspectors are the bill you pay so you do not argue over a container later. Clarify whether you are buying a product inspection, a social/compliance audit, or a full systems audit — prices and scope differ a lot.

- [SGS](https://www.sgs.com) — Global testing and certification giant; factory audits, PSI, and lab testing. Highest name recognition; quote accordingly.
- [Bureau Veritas](https://www.bureauveritas.com) — French inspection group strong on factory and social-compliance audits; frequent requirement in big-brand supply chains.
- [Intertek](https://www.intertek.com) — Major testing/certification house; deep coverage in electronics, textiles, and toys.
- [TÜV Rheinland](https://www.tuv.com) — German certification body; natural fit when EU standards (CE, energy labels, etc.) are on the line.
- [QIMA](https://www.qima.com) — Formerly AsiaInspection; Asia-focused inspections and factory audits at lower entry prices than the "big four" — common for first orders and mid-size buyers.
- [AsiaInspection heritage note](https://www.qima.com/about-us) — Same org under the QIMA brand; older SOWs or supplier emails may still say AsiaInspection.

---

## Telling a Factory from a Trading Company

Platform labels lie. Traders often list as "Manufacturer." You want primary production capability for the SKUs you care about — or at least honest disclosure that they outsource.

- [MIIT ICP filing lookup](https://beian.miit.gov.cn) — Check whether the supplier website's ICP filing entity matches the company on the quote. Mismatches and missing filings are common with pure traders.
- [TinEye](https://tineye.com) — Reverse image search. Drop workshop or product photos; stolen factory shots show up constantly.
- [Google Maps](https://www.google.com/maps) — Drop the address into satellite/Street View. Industrial park vs residential block vs empty lot tells you a lot in thirty seconds.
- [LinkedIn](https://www.linkedin.com) — Look at employee titles and headcount. People writing "sales at trading co" while the pitch deck says "own factory" is a tell.
- [Zoom](https://zoom.us) — Insist on a live video walk of the production floor. Pre-recorded tours are edited; live is harder to fake.
- [WhatsApp Business](https://www.whatsapp.com/business) — Default chat channel for most export salespeople; useful for quick voice/video plant checks once you already have the legal entity sorted.

---

## Samples, Golden Sample & Pre-shipment

Sample quality is a sales tool. Bulk quality is what you get paid on. Lock a golden sample and inspect before the container leaves.

- [QIMA product inspection](https://www.qima.com/quality-control-services/product-inspection) — Book AQL-based during-production or pre-shipment inspection against your golden sample and written specs.
- [SGS product inspection](https://www.sgs.com/en/services/product-inspection) — PSI and loading supervision when the order value or brand risk justifies the fee.
- [Bureau Veritas consumer products](https://www.bureauveritas.com/en/consumer-products-services) — Lab testing plus inspection when retail or regulated markets are involved.
- [Intertek quality assurance](https://www.intertek.com/quality-assurance/) — Inspection and testing programs tied to retailer programs and safety standards.
- [ISO 2859 / AQL overview (ISO)](https://www.iso.org) — Reference the sampling standard your inspector will use so "AQL 2.5" means the same thing to both sides.

Practical rule: approve a sealed golden sample in writing, put critical dimensions and materials on the PO, and never skip pre-shipment on the first two bulk orders.

---

## Payment Terms & Trade Assurance

First order with a new Chinese supplier is not the time for 100% T/T to a personal account. Structure payment so goods quality gates the money.

- [Alibaba Trade Assurance](https://tradeassurance.alibaba.com) — Platform escrow-style protection on Alibaba orders; useful when you already buy on-platform. Read coverage limits before you rely on it.
- [Escrow.com](https://www.escrow.com) — Neutral third-party escrow; release funds after inspection. Worth the fee on first large off-platform orders.
- [PayPal](https://www.paypal.com) — Fine for samples and small deposits with buyer protection; many factories refuse it on bulk (fees + chargeback risk).
- [Wise](https://wise.com) — Lower-fee international transfers than many banks; still not protection — only cheaper rails. Confirm beneficiary name matches the contract entity.
- [Sinosure (China Export & Credit Insurance)](https://www.sinosure.com.cn) — If a supplier carries Sinosure cover, it is a weak positive signal on their export credit profile — not a substitute for your own checks.
- [ICC (International Chamber of Commerce)](https://iccwbo.org) — Home of UCP 600 and standard trade terms. Use when letters of credit or Incoterms disputes land on the table.

Hard stop: beneficiary name on the wire must match the company on the contract and commercial invoice. No exceptions for "my cousin's account is faster."

---

## Red Flags & Scam Avoidance

Most losses cluster around the same pattern: chat-only relationship, no registry check, full prepayment, and a bank account that does not match the paperwork.

- [FBI IC3](https://www.ic3.gov) — US buyers who have been defrauded on a cross-border wire can file here; official channel for internet crime complaints.
- [Better Business Bureau (BBB)](https://www.bbb.org) — Useful for vetting US-side brokers, freight forwarders, and middlemen in the chain — not Chinese factories themselves.
- [Trustpilot](https://www.trustpilot.com) — Check reviews on a supplier's independent site; watch for all five-stars from brand-new accounts.
- [Have I Been Pwned](https://haveibeenpwned.com) — Not China-specific, but if a "factory" emails from a free Gmail that later shows up in breaches alongside phishing kits, treat contact channels as compromised.

Classic red flags (no tool required): pressure to pay today, refusal of video plant tour, certificates only as unreadable photos, MOQ that collapses the moment you ask for audit access, and English that flips from fluent sales copy to broken once you ask about process capability.

---

## FAQ

### How do I tell a factory from a trading company?

Do not trust the Alibaba badge. Check whether the ICP filing entity matches the business license, demand a live video of running lines (not a reel), ask which processes are subcontracted, reverse-search products on 1688, and compare claimed capacity to customs shipment history. One channel is never enough.

### What can I verify for free?

Legal existence and business scope (GSXT / Tianyancha / Qichacha), lawsuits and enforcement records, basic platform badges, ICP filing owner, rough US import history (ImportYeti free tier), and reverse image search on their photos. You cannot freely verify real throughput, QC systems, or whether they will subcontract your order to a no-name workshop.

### Is a paid audit worth it?

On first orders that are large, safety-critical (electronics, toys, food-contact), or with a supplier who ducks video tours — yes. A few hundred to a few thousand dollars is cheaper than a rejected container or a retail recall. For tiny reorders with a known factory, you can often skip full systems audits and still run PSI.

### How reliable is customs data?

Partial. Most tools see what US/India/other importers declared, not China's full export book. Pure domestic makers turning to export, or shipments routed via Hong Kong/third countries, often disappear. Treat hits as confirmation they ship; treat missing data as "unknown," not "fraud."

### What certificates should I distrust?

Any PDF that only the supplier can produce, with no verifiable certificate number on the issuer's site. Especially common fakes: ISO 9001, CE, FCC, BSCI/Sedex printouts with wrong logos or expired dates. Always re-verify at SGS, BV, Intertek, TÜV, or the scheme owner.

### Do I still need to vet a supplier I met at Canton Fair?

Yes. Booths are rented. Traders and agents share floor space and hand out "manufacturer" cards. A fair meeting gets you a contact and a first impression — then run the same registry, customs, and audit steps you would for an Alibaba lead.

---

## Toolbox & templates

### Stable official references

- [GSXT — National Enterprise Credit Information Publicity System](https://www.gsxt.gov.cn) — First stop for Chinese business-license verification.
- [General Administration of Customs of China](https://www.customs.gov.cn) — Official policy, stats, and regulatory notices (not line-level B/L data).
- [ISO](https://www.iso.org) — Confirm that a cited ISO standard number actually exists and what it covers.
- [SGS](https://www.sgs.com) · [Bureau Veritas](https://www.bureauveritas.com) · [Intertek](https://www.intertek.com) · [TÜV Rheinland](https://www.tuv.com) · [QIMA](https://www.qima.com) — Book audits/inspections and re-check certificate numbers.

### Copyable checklists

| Template | Fields to fill |
|---|---|
| Supplier verification checklist | Business license / USC code, business scope, registered capital, legal rep & shareholders, ICP filing entity, export history hit/miss, lawsuits & enforcement, certificate numbers + issuer links |
| Factory audit checklist | Site area & ownership, equipment list, number of lines & running status, headcount, monthly capacity, QC process, recent export order samples, subcontracted processes |
| Sample & golden-sample log | Spec version, material, critical dimensions, photos, approval date, sealed sample ID, who holds the sealed unit |
| First-order risk gate | Beneficiary name = contract entity?, escrow/LC/Trade Assurance used?, PSI booked?, golden sample referenced on PO?, audit budget reserved? |

---

## Related lists

- [Awesome China Supplier Sourcing](https://github.com/sasharun/awesome-china-supplier-sourcing) — Finding suppliers before you verify them
- [Awesome Gongchang Website](https://github.com/sasharun/awesome-gongchang-website) — Factory websites and manufacturer site-building resources
- [Awesome Factory Customer Acquisition (工厂获客)](https://github.com/sasharun/awesome-gongchang-huoke) — How Chinese factories win overseas buyers

---

## Contributing

PRs welcome. Dead links, solid verification tools, inspection firms, or hard-won scam patterns all help.

**Format:**

```
- [Name](https://real-url.example) — One line (15–30 words) on what it does and when a buyer should use it.
```

Rules: resource must exist and be currently usable; must relate to verifying or auditing Chinese suppliers/factories; keep the blurb objective — no hype, no hard sells. Drop it under the right section.

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=sasharun/awesome-china-supplier-verification&type=Date)](https://star-history.com/#sasharun/awesome-china-supplier-verification&Date)

## License

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is dedicated to the public domain under **CC0 1.0**. Use, copy, modify, and redistribute freely — no attribution required.

---

Maintained by a team that builds factory websites — [ModalCube](https://modalcube.com).
