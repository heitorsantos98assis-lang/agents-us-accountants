# 57 Agents for US Accountants

**57 specialized Claude Code subagents for US-licensed CPAs, EAs, bookkeepers, and small-firm partners** — built by senior practitioners, regulated for US business reality.

Each agent is a single drop-in Markdown file you copy into `.claude/agents/`. Claude Code routes work to the right specialist automatically.

---

## What's inside

| # | Agent | Focus |
|---|---|---|
| 01 | 01-passthrough-entity-tax-planning | Specialist in US pass-through entity tax planning for SMB owners — sole proprietor (Schedule C), single-member LLC, multi-membe |
| 02 | 02-state-sales-use-tax-wayfair-nexus | Specialist in multi-state sales and use tax compliance under the post-Wayfair regime (South Dakota v |
| 03 | 03-federal-excise-tax-form-720 | Specialist in US federal excise tax compliance via Form 720 (Quarterly Federal Excise Tax Return) and Form 2290 (Heavy Highway  |
| 04 | 04-corporate-federal-tax-1120 | Specialist in C-Corporation federal income tax via Form 1120 — 21% flat rate post-TCJA (I.R.C |
| 05 | 05-tax-deposit-payment-verification | Specialist in verifying US federal and state tax payments after the fact — EFTPS confirmation numbers, IRS Direct Pay receipts, |
| 06 | 06-sales-tax-return-multistate-filing | Specialist in operational multi-state sales tax return filing and validation — extracting gross receipts from QuickBooks Online |
| 07 | 07-annual-federal-return-prep-1120-1065-1120s | Specialist in the annual federal entity return preparation workflow — trial balance import from QuickBooks Online / Xero / Sage |
| 08 | 08-form-941-quarterly-payroll-return | Specialist in Form 941 quarterly federal payroll tax return — reconciles FICA withheld + employer match (6.2% Social Security u |
| 09 | 09-form-1099-issuance-workflow | Specialist in annual 1099 issuance — W-9 collection at vendor onboarding, TIN matching via IRS TIN Match, $600 threshold per pa |
| 10 | 10-payroll-tax-filings-integrated-calendar | Specialist in building and running an integrated US payroll tax filings calendar — Form 941 quarterly federal, Form 940 annual  |
| 11 | 11-pay-stub-generation-review | Specialist in US pay stub generation and review — W-4 application (2020+ redesign Steps 1–4c), federal withholding via IRS Publ |
| 12 | 12-pto-bonus-accrual-and-payout | Specialist in US PTO (Paid Time Off) accrual policy + year-end bonus tax treatment |
| 13 | 13-final-paycheck-cobra-separation | Specialist in US employee separation workflow — at-will termination (49 states; MT exception), final paycheck timing per state  |
| 14 | 14-fica-futa-suta-employer-payroll-tax | Specialist in the full US employer payroll tax stack — FICA 7.65% (6.2% Social Security on first $168,600 2026 wage base + 1.45 |
| 15 | 15-new-hire-onboarding-i9-w4-w9 | Specialist in US new-hire onboarding for both W-2 employees and 1099 contractors — Form I-9 (DHS / USCIS, complete within 3 bus |
| 16 | 16-bank-reconciliation-monthly-qbo-xero | Specialist in monthly bank reconciliation for SMB clients using QuickBooks Online, Xero, or Sage Intacct — download OFX / CSV / |
| 17 | 17-client-billing-collections-cpacharge-bill-com | Specialist in US CPA firm billing and collections — engagement letter fee structure, invoicing via Stripe / QBO Payments / CPAC |
| 18 | 18-management-pl-report-fathom-spotlight | Specialist in US-format Income Statement / management P&L reporting — Revenue → COGS → Gross Profit → Operating Expenses by cat |
| 19 | 19-cash-flow-forecast-13-week-float-jirav | Specialist in the 13-week rolling cash flow forecast — the US standard inherited from turnaround / restructuring practice (work |
| 20 | 20-client-intake-triage-secure-messaging | Specialist in secure client intake and triage for US CPA firms — Karbon / Canopy / TaxDome client portal messaging, Liscio / Pa |
| 21 | 21-document-request-organizer-automation | Specialist in US tax document request automation — building the request list (W-2, 1099 series, K-1, 1098 mortgage, 1098-T tuit |
| 22 | 22-client-onboarding-engagement-letter-7216 | Specialist in US CPA firm client onboarding — engagement letter (MANDATORY per AICPA SSARS for compilations / reviews / prepara |
| 23 | 23-client-follow-up-cadence-multi-channel | Specialist in US CPA firm client follow-up cadence across multiple channels — email (primary), portal message (Karbon / Canopy  |
| 24 | 24-invoice-bill-capture-hubdoc-dext-ramp | Specialist in US invoice and bill capture for SMB clients via Hubdoc, Dext (formerly Receipt Bank), AutoEntry, Ramp, Brex, Bill |
| 25 | 25-tax-deadline-reminder-calendar | Specialist in US tax deadline calendar — 1/15 Q4 estimated tax, 1/31 W-2 / 1099-NEC + Form 941 Q4 + Form 940, 2/15 1099-B / 109 |
| 26 | 26-monthly-client-financial-report-packet | Specialist in monthly CAS (Client Accounting Services) financial report packet — P&L MTD / YTD / PY comparison + Balance Sheet  |
| 27 | 27-firm-data-security-irs-pub-4557-wisp | Specialist in US CPA firm data security compliance — IRS Publication 4557 (Safeguarding Taxpayer Data, REQUIRED for every paid  |
| 28 | 28-sole-proprietor-schedule-c-quarterly-planning | Specialist in US sole proprietor / single-member LLC quarterly tax planning via Schedule C — revenue / expense categorization,  |
| 29 | 29-federal-excise-form-720-pcori-fuel-tobacco | Specialist in federal excise tax preparation on Form 720 (quarterly), Form 2290 heavy highway vehicle use, Form 8849 fuel tax r |
| 30 | 30-federal-state-income-tax-withholding-pub-15t | Specialist in federal and state income-tax withholding calculation per IRS Publication 15-T (Methods for federal withholding) a |
| 31 | 31-backup-withholding-1099-nec-w9-vendor-compliance | Specialist in payer-side withholding obligations — W-9 (Form W-9 Request for TIN), backup withholding at 24% (I.R.C |
| 32 | 32-state-sales-tax-monthly-multistate-deep-dive | Specialist in multistate sales/use tax operations — rolling nexus monitoring (Wayfair economic + physical), exemption certifica |
| 33 | 33-form-1099-s-1099-misc-real-estate-rentals | Specialist in real estate and rental information reporting — Form 1099-S (proceeds from real estate transactions, $600+ thresho |
| 34 | 34-form-1095-aca-employer-coverage-reporting | Specialist in Affordable Care Act employer reporting — Form 1094-C transmittal + Form 1095-C statements for Applicable Large Em |
| 35 | 35-monthly-payroll-run-gusto-adp-paychex | Specialist in US payroll runs (weekly, biweekly, semimonthly, monthly) executed through Gusto, ADP RUN/WorkforceNow, Paychex Fl |
| 36 | 36-us-gaap-chart-of-accounts-template | Specialist in US GAAP chart-of-accounts (COA) design and tuning in QuickBooks Online, Xero, Sage Intacct, and NetSuite |
| 37 | 37-journal-entry-templates-month-end-close | Specialist in standard month-end and quarter-end journal entries for SMB and CAS clients in QuickBooks Online, Xero, Sage Intacct |
| 38 | 38-merchant-processor-reconciliation-stripe-square | Specialist in monthly merchant-processor reconciliation for Stripe, Square, PayPal, Shopify Payments, Authorize.net, QBO Paymen |
| 39 | 39-ap-vendor-reconciliation-bill-com | Specialist in accounts-payable vendor reconciliation through Bill.com (BILL), Ramp, Brex, Divvy, QBO Bill Pay, Melio, and Plooto |
| 40 | 40-ar-customer-reconciliation-aging | Specialist in accounts-receivable customer reconciliation and aging analysis in QBO, Xero, Sage Intacct |
| 41 | 41-month-end-close-checklist-cas | Specialist in CAS (Client Accounting Services) month-end close — 7-day, 10-day, or 15-day close standards, cutoff procedures, a |
| 42 | 42-trial-balance-analytical-review | Specialist in trial-balance analytical review for monthly close, audit prep, and tax return prep |
| 43 | 43-fixed-assets-depreciation-macrs-section-179-bonus | Specialist in fixed-asset capitalization and depreciation under US tax (MACRS — Modified Accelerated Cost Recovery System, I.R.C |
| 44 | 44-entity-tax-structure-comparison-llc-s-corp-c-corp | Specialist in US entity tax structure comparison — Sole Proprietor (Schedule C) vs Single-Member LLC (default disregarded) vs M |
| 45 | 45-erc-r-d-credit-fuel-credit-refund-claims | Specialist in US federal credit and refund claim recovery — Employee Retention Credit (ERC) post-IRS moratorium handling (Form  |
| 46 | 46-tax-return-vs-information-return-cross-check | Specialist in tax-return preparation cross-check and information-return reconciliation — pre-filing comparison of W-2 wages to  |
| 47 | 47-cp2000-underreporter-individual-response | Specialist in IRS CP2000 / Automated Underreporter (AUR) response for individual 1040 returns |
| 48 | 48-irs-business-notice-cp-response-1120-1065-1120s | Specialist in IRS business notice response — CP161 (balance due), CP162 (failure-to-file penalty), CP259 (return required not r |
| 49 | 49-financial-due-diligence-quality-of-earnings-sell-side | Specialist in financial due diligence and Quality of Earnings (QofE) analysis for sell-side and buy-side M&A transactions in th |
| 50 | 50-smb-business-valuation-dcf-multiples-401k-esop | Specialist in SMB business valuation under US standards (USPAP — Uniform Standards of Professional Appraisal Practice; AICPA VS |
| 51 | 51-individual-tax-return-1040-multistate-multiform | Specialist in comprehensive Form 1040 preparation for US individual taxpayers — Forms 1040 + Schedules 1/2/3 + Schedules A (ite |
| 52 | 52-business-formation-ein-state-registration-boi | Specialist in US business formation end-to-end — entity selection (LLC, S-Corp election, C-Corp, partnership, PLLC, B-Corp, non |
| 53 | 53-entity-amendment-operating-agreement-bylaw-changes | Specialist in US entity amendments — Articles of Amendment filed with state Secretary of State (name change, registered agent,  |
| 54 | 54-business-dissolution-final-returns-1120-1065 | Specialist in US business dissolution and wind-down — members/shareholders vote, Articles of Dissolution filed with state SoS,  |
| 55 | 55-irs-installment-agreement-oic-collections | Specialist in IRS collections — Installment Agreement (Form 9465 / Online Payment Agreement, Streamlined ≤$50K = 72 months, Non |
| 56 | 56-irs-audit-examination-response-2848 | Specialist in IRS audit / examination representation — correspondence audit (CP2000-style document-based), office audit (distri |
| 57 | 57-tcja-sunset-2026-tax-legislation-planning | Specialist in US tax legislation monitoring and planning — TCJA (Tax Cuts and Jobs Act, P.L |

---

## Install one agent

```bash
cd path/to/your/project
mkdir -p .claude/agents
unzip 01-passthrough-entity-tax-planning.zip
cp 01-passthrough-entity-tax-planning/01-passthrough-entity-tax-planning.md .claude/agents/
```

Restart Claude Code or run `/agents`. Done.

## Install all 57

```bash
unzip completo-57-agents-us-accountants.zip
for z in [0-9][0-9]-*.zip; do unzip -o "$z"; done
mkdir -p ~/.claude/agents
find . -mindepth 2 -name '*.md' -not -name 'HOW-TO-INSTALL.md' -exec cp {} ~/.claude/agents/ \;
```

## How agents work

Each `.md` has YAML frontmatter defining when it fires. Claude Code reads the `description` and routes automatically — or invoke explicitly:

```
Use the passthrough-entity-tax-planning subagent to ...
```

Each agent:
- Knows its scope (when to fire, when NOT to fire — delegates back to peers)
- Carries reference tables (codes, regulations, forms, formulas)
- Operates with a deliberate workflow (inputs → core deliverable → checklists)
- Cites authority in Bluebook style where regulatory ground matters
- Produces deliverables in `/tmp/` for review before pushing forward

## Requirements

- [Claude Code](https://docs.claude.com/claude-code) installed and logged in
- `unzip` on your machine

## Versioning

**v1.0** (May 2026). Updates ship as new uploads to this repo.

---

© HL. Built by operators for operators. No fluff.
