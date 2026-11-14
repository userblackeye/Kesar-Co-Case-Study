# Kesar & Co. – Final Correction Report

**Files:** `Kesar_Co_24_Month_Financial_Model_Corrected.xlsx` and `Kesar_Co_24_Month_Growth_Plan_Corrected.pptx`  
**Scope:** Targeted corrections only; existing strategy, model structure and annual targets retained.

## 1. Month 24 online revenue target

- **Monthly Plan!E23 / H23 / I23 (M21):** online revenue moved from ₹7.00 Cr to ₹6.60 Cr; offline adjusted from ₹33.00 Cr to ₹33.40 Cr; online share remains formula-driven.
- **Monthly Plan!E26 / H26 / I26 / J26 (M24):** online revenue moved from ₹2.00 Cr to ₹2.40 Cr; offline adjusted from ₹10.00 Cr to ₹9.60 Cr; share formula is `=E26/D26`; orders recalculate to 16,000 at the existing ₹1,500 AOV.
- **Result:** M24 online share = ₹2.40 Cr / ₹12.00 Cr = **20.0%**. Year 2 remains ₹230 Cr total / ₹46 Cr online = **20.0% annual share**. The ₹0.40 Cr timing shift preserves all Year 2 annual totals.
- **Quarterly result:** Year 2 Q1 ₹27 Cr / ₹7.50 Cr online; Q2 ₹35 Cr / ₹11.50 Cr; Q3 ₹113 Cr / ₹17.60 Cr; Q4 ₹55 Cr / ₹9.40 Cr. Q4 and annual totals remain reconciled.
- **PPT updates:** slides 2, 17, 19 and 20; slide 17 distinguishes the annual test from the Month 24 test, and slide 20 shows the revised M21 and M24 monthly figures.

## 2. Budget attribution control

- **Budget!I5:I6:** clarified the ₹11.9 Cr Meta + Google and ₹9.0 Cr marketplace sales figures as gross ROAS-attributed estimates, not deduplicated or incremental revenue.
- **Budget!A49:I59:** added an attribution-control section. Formula outputs show ₹11.88 Cr + ₹9.00 Cr = ₹20.88 Cr gross claims versus the ₹15.00 Cr Year 1 online net-sales plan; ₹5.88 Cr is labelled an **unreconciled excess**, not a measured overlap amount.
- The workbook does not supply order-level deduplication, attribution-window definitions or evidence that the claims include offline/store influence. It therefore does **not** claim that offline influence is included or confirmed. Validation steps are documented: order-ID deduplication, aligned click/view windows and store POS/QR mapping.
- **PPT update:** slide 15 adds the same distinction and explicitly says the ₹20.88 Cr should not be read as incremental online revenue.

## 3. Quarterly revenue build

Added the **Quarterly Revenue** worksheet:

- **A6:H16:** quarterly channel build—total revenue, D2C, marketplaces, online total, offline, online share and reconciliation check; includes Year 1 and Year 2 totals.
- **A19:G29:** quarterly category build—winterwear, basic cotton, cotton knit polos and waffle loungewear; includes annual totals and checks.
- **A32:H42:** quarterly region build—Core North, UP + Uttarakhand, West/South metros, Rajasthan and Rest of India; includes annual totals and checks.
- Channel figures roll directly from the Monthly Plan. Category and region figures use each quarter's total multiplied by the existing annual category/region mix. This is explicitly labelled a **planning allocation**, because source data does not contain quarterly mix by category or region.
- Every quarterly view ties to its quarter total; all four quarters reconcile to the existing annual totals. The workbook note distinguishes the case's 70% Oct–Jan historical seasonality from the existing forecast assumption, which improves to about 65% in Year 1 and 62% in Year 2.
- **PPT updates:** slides 18–20 refer to the Quarterly Revenue worksheet; slides 19–20 include compact quarterly total/online summaries.

## 4. Documentation and assumption fixes

- **Sources!A14:D14:** added Technopak Advisors Pvt. Ltd., *Industry Report on Apparel Market in India and South India*, 12 August 2025, with the RSB Retail-hosted report URL. The model retains its existing IBEF/CareEdge sizing basis; Technopak remains a separate cross-check.
- **Sources!B8:C8; PPT slide 7:** competitor naming standardised to **Monte Carlo**; descriptions made neutral and factual.
- **Budget!A61:D67:** product-test allocation added—cotton knit polos ₹0.90 Cr (60%) and waffle loungewear ₹0.60 Cr (40%), a labelled planning assumption. Formula-linked total is ₹1.50 Cr and is part of the existing Budget!F11 line, not additional spend.
- **Inputs!A28:D28; Unit Economics!C20 and A24:F24; PPT slide 10:** 10% marketplace delivery/returns/RTO cost is labelled as an assumption to validate with platform/vendor data. It is explicitly separate from the 22% return-rate kill gate.
- **Unit Economics!D38; Assumptions Log!A27:D27:** ₹4.57 Cr Year 2 growth funding is labelled indicative and uncommitted, subject to operating cash availability and quarterly Finance approval. If funding is unavailable, paid acquisition and revenue expectations must be reduced.
- **Read Me!A27:B27:** documents the new quarterly worksheet and its allocation method; Read Me online-share description now distinguishes annual share from Month 24.

## 5. Reconciliation and QA checklist

| Check | Result | Detail |
|---|---|---|
| Month 24 online share | **PASS** | ₹2.40 Cr / ₹12.00 Cr = 20.0%. |
| Year 2 annual base and online totals | **PASS** | ₹230 Cr total; ₹46 Cr online; 20.0% annual share. |
| Year 1 revenue / online targets | **PASS** | ₹200 Cr total; ₹15 Cr online. |
| Year 2 stretch case | **PASS** | ₹250 Cr stretch case retained as conditional. |
| Year 1 budget | **PASS** | Budget total remains ₹15.00 Cr. |
| Product-test split | **PASS** | ₹0.90 Cr + ₹0.60 Cr = ₹1.50 Cr within the existing budget line. |
| Quarterly channel / category / region checks | **PASS** | Quarter checks are zero; annual views reconcile to existing totals. |
| Spreadsheet formula-error scan | **PASS** | No `#REF!`, `#VALUE!`, `#DIV/0!`, `#NAME?` or `#N/A` cells detected in the exported workbook. |
| Formula preservation / cycle review | **PASS WITH SCOPE NOTE** | Existing model formula structure retained; added quarter and budget formulas reference upstream plan inputs and do not feed back into the Monthly Plan. Modified formula chains reviewed for cycles. |
| Attribution data validation | **PENDING BUSINESS DATA** | Gross attribution estimates are documented; order-level deduplication and offline/assisted influence require platform and POS data before incremental ROI claims. |
| PowerPoint length | **PASS** | 20 slides; no additional main-deck slide added. |
| PowerPoint layout test | **PASS** | Automated overflow test passed; updated slides visually reviewed. |

**Important interpretation:** The ₹20.88 Cr attributed-sales sum has deliberately not been reduced or relabelled as incremental sales. It remains a gross attribution estimate pending order-level reconciliation. Similarly, quarterly category and regional rows are planning allocations—not observed market data or reported quarterly sales.
