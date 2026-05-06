

THE FOUNDER FINANCIAL INFRASTRUCTURE (FFI) STANDARD







Book 1: Financial Architecture
Beta v0.5





April 2026
















https://ffistandard.org/

© The Oakworth Group, 2026.
Published under Creative Commons Attribution 4.0 International (CC BY 4.0).
This Standard may be freely used, cited, adapted, and distributed with attribution.
Full license terms: creativecommons.org/licenses/by/4.0
BOOK 1: FINANCIAL ARCHITECTURE

Book 1 defines the financial architecture a company must maintain: the integrated financial statements, the cash management systems, the internal reporting structure, and the accounting integrity requirements that form the foundation of all subsequent financial infrastructure.


SECTION 1.1: THE THREE-STATEMENT STANDARD

PURPOSE

The three-statement standard governs the integrated financial model a company must maintain. The three-statement model is not three financial statements. It is one integrated system that produces three financial statements from a shared set of assumptions and drivers. The requirements of this section depend on the accounting integrity of the underlying records from which the model is derived; those requirements are set out in Section 1.4.

DEFINITIONS

The following terms are defined for application within this section. Terms defined in Book 0, Section 0.4 are used here with their operative definitions and are not restated.

ASSUMPTION LAYER: A discrete section of a financial model in which all input assumptions are stated and stored separately from the calculation cells that use them. Every calculation cell references the assumption layer by formula. An assumption layer is a structural feature of model architecture. A spreadsheet with a notes column explaining assumptions does not constitute an assumption layer.

COST OF GOODS SOLD: The direct cost of delivering the company's product or service to a customer, including only costs directly attributable to the production or delivery of the product. Cost of goods sold does not include sales and marketing costs, general and administrative costs, or research and development costs. The composition of cost of goods sold varies by company type as defined in Book 0, Section 0.6; the structural definition of what belongs in the category does not vary.

GROSS MARGIN: Revenue minus cost of goods sold, expressed as a percentage of revenue. Gross margin is calculated after cost of goods sold and before any operating expense. Gross margin and contribution margin are not equivalent and must not be reported interchangeably.

VARIANCE: The difference between an actual financial result and the corresponding forecast or budgeted figure for the same period. A favourable variance occurs when revenue exceeds forecast or when costs fall below forecast. An adverse variance occurs when revenue falls below forecast or when costs exceed forecast.

PRINCIPLES GOVERNING THIS SECTION

Compliance Principle 2 from Book 0, Section 0.3 governs the assumption documentation requirements in this section: clarity of assumptions governs over precision of outputs. The compliance criteria at Level 2 and Level 3 are direct applications of this principle.

The balance sheet must balance at all times as a structural consequence of correct model integration. An unbalanced balance sheet is evidence of a structural error in the model architecture. It is not a reconciliation item to be noted and carried forward. An unbalanced balance sheet invalidates the three-statement model for the purposes of this Standard at any compliance level.

COMPLIANCE CRITERIA

Compliance at each level is cumulative. Level 2 requires that all Level 1 criteria are met. Level 3 requires that all Level 1 and Level 2 criteria are met. This rule applies to all sections in Book 1.

Level 1

1.1.L1.1: The company maintains an income statement covering all completed periods from incorporation to the date of assessment, updated with actual figures within thirty calendar days of each period's close.

1.1.L1.2: The company maintains a record of its cash position, expressed as the confirmed balance of all cash and cash equivalent accounts, updated at minimum monthly.

1.1.L1.3: The company maintains a record of its current liabilities sufficient to allow calculation of the amount owed to each creditor at the date of assessment.

1.1.L1.4: All input assumptions used in any financial statement are known to the company and can be stated on request.

Level 2

1.1.L2.1: The company maintains a fully integrated three-statement model comprising an income statement, a cash flow statement, and a balance sheet, in which a change to any input assumption in the assumption layer updates all three statements without manual recalculation.

1.1.L2.2: The three-statement model is updated with actual financial data within fifteen working days of the close of each reporting period.

1.1.L2.3: All input assumptions are documented in a discrete assumption layer that is structurally separate from calculation cells, such that any assumption can be located, reviewed, and modified without altering any calculation cell.

1.1.L2.4: The balance sheet in the three-statement model balances at the close of every period for which actuals have been entered.

1.1.L2.5: Revenue is classified by revenue stream in the income statement, with each stream reported as a discrete line.

1.1.L2.6: Operating expenses are classified by functional category, including at minimum cost of goods sold, sales and marketing, product and engineering, and general and administrative, with each category reported as a discrete line in the income statement. For AI-Native companies as defined in Book 0, Section 0.6, cost of goods sold must separately identify computational inference costs as a distinct sub-line within the cost of goods sold category.

1.1.L2.7: The three-statement model includes a forward projection covering a minimum of twenty-four months from the date of assessment.

1.1.L2.8: The revenue recognition policy applied in the income statement is documented in writing and has been applied consistently across all periods included in the model.

Level 3

1.1.L3.1: The three-statement model is updated with actual financial data within ten working days of the close of each reporting period.

1.1.L3.2: The three-statement model is dynamically linked to departmental sub-models for each operational function, such that changes in departmental-level assumptions flow through to the company-level three-statement model without manual entry.

1.1.L3.3: Each assumption in the assumption layer includes a documented methodological basis stating whether the assumption is derived from historical data, market reference, management judgment, or a combination; and a stated sensitivity range for that assumption.

1.1.L3.4: The three-statement model is maintained under version control such that any prior version can be retrieved and compared to the current version with all changes identified.

1.1.L3.5: A rolling twenty-four-month forward model is maintained and updated each period, extending the forward period by one period as each period closes.

1.1.L3.6: The three-statement model can be provided to an investor or advisor in its current state without preparation, reformatting, or explanatory accompaniment from the model's preparer.

COMMON DEFICIENCIES

CD 1.1.1: The company maintains a revenue projection and a cost model as separate, unlinked documents and presents these as its financial model. Neither document includes a cash flow statement or a balance sheet. The company's cash position is tracked separately, outside the financial model, and is not reconciled to the model's outputs.

CD 1.1.2: Input assumptions are embedded directly in calculation cells throughout the model. To change a growth rate assumption, the figure must be located and updated in each cell where it appears. No discrete assumption layer exists. The model cannot be stress-tested by a third party without detailed knowledge of its architecture.

CD 1.1.3: The balance sheet in the three-statement model does not balance for one or more historical periods. The imbalance has not been investigated or resolved. The model is presented to investors and advisors with the imbalance present.

CD 1.1.4: The income statement classifies sales team salaries, customer success costs, and office infrastructure costs within cost of goods sold. Gross margin as reported is materially higher than the gross margin that would result from a classification consistent with this Standard. The classification has not been documented or disclosed.






SECTION 1.2: THE CASH MANAGEMENT STANDARD

PURPOSE

The cash management standard governs the minimum requirements for cash position visibility, burn rate calculation, runway monitoring, and working capital awareness. Cash position and burn rate are distinct from accounting entries and must be maintained independently of whether monthly financial statements have been prepared. The requirements of this section apply at all times, as established by Principle 1 in Book 0, Section 0.3.

DEFINITIONS

COMMITTED CASH FLOW: A cash receipt or payment that is contractually obligated and for which the amount and timing are determinable within the forecast period. Payroll, rent under a signed lease, and contracted supplier payments are committed cash flows. Revenue from anticipated but unsigned customer contracts is not a committed cash flow. Committed cash flows and projected cash flows must not be aggregated without disclosure.

CHART OF ACCOUNTS: A structured list of all financial accounts used by a company to classify its transactions, organised by category: assets, liabilities, equity, revenue, cost of goods sold, and operating expenses. Every financial transaction recorded by the company is classified to an account in the chart. A chart of accounts is not a reporting format; it is the underlying classification structure from which financial reports are produced.

PRINCIPLES GOVERNING THIS SECTION

The definition of net burn rate in Book 0, Section 0.4 governs all burn rate calculations in this section. Gross burn rate and net burn rate are defined separately in Book 0 and must be calculated and reported as separate figures at all compliance levels. The methodology used to calculate net burn rate must be consistent across all periods; any change in methodology must be disclosed and prior periods restated for comparability.

COMPLIANCE CRITERIA

Compliance at each level is cumulative as established in Section 1.1.

Level 1

1.2.L1.1: The company calculates and records its net burn rate for each completed month using a consistent methodology, stated and applied identically across all periods.

1.2.L1.2: The company calculates its cash runway at minimum monthly, using net burn rate as the denominator, as defined in Book 0, Section 0.4.

1.2.L1.3: The company's current cash position, expressed as the confirmed balance of all cash and cash equivalent accounts, is known and current within seven calendar days of the date of assessment.

1.2.L1.4: Gross burn rate and net burn rate are calculated and recorded as separate figures and are not reported interchangeably in any internal document or external communication.

Level 2

1.2.L2.1: Cash runway is calculated using a trailing three-month average net burn rate as the denominator; where the company uses a different base period, a written rationale is documented and included in the management report for the relevant period.

1.2.L2.2: The company maintains a rolling thirteen-week cash flow forecast, updated weekly, covering the thirteen weeks immediately following the date of update.

1.2.L2.3: The thirteen-week cash flow forecast identifies each line as either a committed cash flow or a projected cash flow, with each category totalled separately.

1.2.L2.4: Net burn rate is categorised by functional area, with separate figures maintained for at minimum: personnel costs; infrastructure and technology costs; sales and marketing costs; and general and administrative costs.

1.2.L2.5: Working capital is calculated quarterly and recorded as a figure distinct from the cash position.

1.2.L2.6: Any variance between the prior week's thirteen-week forecast and the actual cash position for that week is recorded, and the cause of the variance is noted.

Level 3

1.2.L3.1: The company's cash position is updated daily, either through manual reconciliation or through automated connection to company bank and payment accounts.

1.2.L3.2: Net burn rate is categorised at the departmental level, with a separate burn figure for each operational department.

1.2.L3.3: The company maintains documented cash alert thresholds, defined as minimum cash balances at which specific management actions are triggered, and those thresholds are reviewed quarterly.

1.2.L3.4: The thirteen-week rolling cash forecast includes a monthly-level extension to twelve months, updated monthly, that integrates with the forward projection in the three-statement model maintained under Section 1.1.

1.2.L3.5: Variance between the thirteen-week cash forecast and actual cash results is analysed formally on a monthly basis, with documented causes of material variances and adjustments to future forecast methodology where a variance reveals a systematic forecasting error.

COMMON DEFICIENCIES

CD 1.2.1: Cash runway is calculated by dividing current cash by the most recent single month's net burn rate. In months where expenditure was unusually high due to a non-recurring cost, the resulting runway figure is materially shorter than the operational trajectory warrants. In months where a large customer payment was received, the resulting runway figure is materially longer. No adjustment or documentation is applied.

CD 1.2.2: The company reports gross burn rate in investor materials without labelling it as gross burn. The figure presented as monthly burn does not account for revenue received in the period. The resulting runway calculation overstates the cash consumption of the business.

CD 1.2.3: The company maintains a monthly cash summary but does not distinguish between committed and projected inflows in its forward view. Revenue from verbal commitments from prospective customers is included as projected inflow in the cash forecast. The resulting cash position is more optimistic than the contractually committed position warrants.

CD 1.2.4: Working capital is not tracked as a distinct metric. The company monitors its cash balance and concludes from a positive cash balance that its near-term liquidity is sound. Accounts receivable aging has extended materially and accounts payable obligations due within thirty days exceed the cash balance net of expected receivables.


SECTION 1.3: THE FINANCIAL REPORTING STANDARD

PURPOSE

The financial reporting standard governs the content, frequency, format consistency, and distribution of internal financial reporting. Financial reporting is not the production of financial statements. Financial reporting is the structured communication of financial information to the people responsible for governing and managing the company. A company that produces financial statements but does not produce structured reporting has met the requirements of Section 1.1 but not the requirements of this section.

DEFINITIONS

No new terms are introduced in this section. All operative terms are defined in Book 0, Section 0.4, or in the preceding sections of this Book.

PRINCIPLES GOVERNING THIS SECTION

Principle 5 from Book 0, Section 0.3 governs the content requirements of this section: financial infrastructure serves decision-making before investor relations. The content requirements for the monthly management report are derived from what a governing body requires to make sound operational decisions, not from what investors require in due diligence. The investor-facing application of financial reports is governed by Book 5.

COMPLIANCE CRITERIA

Compliance at each level is cumulative as established in Section 1.1.

Level 1

1.3.L1.1: The company produces a financial summary for each completed month containing at minimum: current cash position; net burn rate for the period; and total revenue and total operating expenses for the period.

1.3.L1.2: The financial summary is available to all members of the founding team within thirty calendar days of the close of the period it covers.

1.3.L1.3: The financial summary uses consistent terminology and categorisation across all periods in which it has been produced.

Level 2

1.3.L2.1: The company produces a monthly management report within fifteen working days of the close of each reporting period.

1.3.L2.2: The monthly management report contains all of the following elements: current cash position and net burn rate for the period; revenue for the period versus the approved forecast; operating expenses by functional category for the period versus the approved forecast; variance commentary for every category where actual differs from forecast by more than ten percent of the forecast figure; current cash runway calculated on a trailing three-month average net burn basis; and an updated forecast for the remainder of the financial year where any material assumption has changed since the prior report.

1.3.L2.3: The monthly management report is distributed to the board or equivalent governing body within fifteen working days of the close of the period it covers.

1.3.L2.4: The monthly management report uses a consistent format across all periods; any change to that format is disclosed in the period in which the change is first applied.

1.3.L2.5: Prior-period comparative figures are restated in any revised format where the format change affects the comparability of figures across periods.

1.3.L2.6: Monthly management reports are retained for a minimum of thirty-six months from the date of production.

Level 3

1.3.L3.1: The monthly management report is produced within ten working days of the close of each reporting period.

1.3.L3.2: The monthly management report includes a written narrative section authored by the financial lead, interpreting the period's financial performance in the context of the company's approved annual operating plan and strategic position.

1.3.L3.3: The board financial package, comprising the monthly management report and the written narrative, is produced and distributed to the board or equivalent governing body in advance of each scheduled board meeting.

1.3.L3.4: A rolling twelve-month financial forecast, updated monthly and integrated with the three-statement model maintained under Section 1.1, is included as a standing section of the board financial package.

1.3.L3.5: The company maintains a documented financial calendar specifying the production deadline, distribution timeline, and recipient list for every recurring financial report.

COMMON DEFICIENCIES

CD 1.3.1: Financial reports are produced when an investor or board member requests them, rather than on a defined monthly schedule. The most recent report available at the time of a due diligence request covers a period that closed four months prior. Current period financial information exists only in raw accounting records and has not been compiled into a report.

CD 1.3.2: The monthly management report presents actuals and forecast in separate columns but does not include a variance column or variance commentary. Where actuals differ materially from forecast, no explanation is provided. The report does not distinguish between a variance caused by a change in business conditions and a variance caused by an error in the prior forecast.

CD 1.3.3: The format of the monthly management report changes between periods without disclosure. Expense categories present in earlier reports are merged or renamed in later reports. Revenue lines previously reported separately are consolidated. The reports across a twelve-month period cannot be compared directly without substantial reconstruction work.

CD 1.3.4: The board financial package contains the management report but no written narrative. The figures are presented without context. The board receives the data but not the financial lead's interpretation of what the data means for the company's trajectory. Material variances are visible in the numbers but not explained.


SECTION 1.4: THE ACCOUNTING INTEGRITY STANDARD

PURPOSE

The accounting integrity standard governs the minimum reliability, consistency, and accuracy requirements for the financial records from which all financial infrastructure in this Book derives. A financial model that meets the structural requirements of Section 1.1 but is built from accounting records that do not meet the requirements of this section does not constitute compliant financial infrastructure. The requirements of this section are foundational to all other requirements in Book 1.

DEFINITIONS

ACCRUAL: An accounting entry that records revenue earned or an expense incurred in a period before the corresponding cash receipt or payment occurs. Accruals are required under accrual accounting to ensure that the income statement reflects economic activity in the period it occurs rather than when cash moves. Accruals are distinct from deferrals; a deferral records a cash receipt or payment in a later period than when cash moves, because the revenue has not yet been earned or the expense not yet incurred.

DEFERRED REVENUE: Cash received from customers before the service or product has been delivered. Deferred revenue is a liability recorded on the balance sheet. It is recognised as revenue only in the period in which delivery occurs. Deferred revenue is not revenue at the point of receipt.

PRINCIPLES GOVERNING THIS SECTION

The accrual accounting definition in Book 0, Section 0.4 governs the accounting basis requirements in this section. The revenue recognition definition in Book 0, Section 0.4 governs the revenue recognition policy requirements. Both are applied here as compliance requirements, not restated as definitions.

A company that transitions from cash-basis to accrual-basis accounting upon reaching Growth Stage, as defined in Book 0, Section 0.5, must restate the financial statements for the two most recent completed financial periods on an accrual basis and retain those restated statements as part of its financial records. This is a compliance requirement, not a recommendation.

The requirement to record convertible instruments in accounting records, stated in criterion 1.4.L1.3 below, connects this section to the capital structure domain governed by Book 3. A SAFE, convertible note, or issued option grant that appears in the cap table but not in the accounting records does not satisfy the requirements of either domain.

COMPLIANCE CRITERIA

Compliance at each level is cumulative as established in Section 1.1.

Level 1

1.4.L1.1: The company's financial records are reconciled to all bank and payment account statements at minimum monthly.

1.4.L1.2: Revenue is recorded consistently, either on a cash basis or an accrual basis, across all periods; and the basis used is known to the company and applied identically in all periods.

1.4.L1.3: All outstanding SAFEs, convertible notes, and issued option grants are recorded in the company's financial records, regardless of whether those instruments have been entered in a separate cap table document.

1.4.L1.4: The company maintains a record of all expenses paid in the period with sufficient categorisation to allow calculation of total cost of goods sold and total operating expenses as separate figures.

Level 2

1.4.L2.1: The company's financial records are prepared on an accrual basis for all periods from the date on which the company reached Growth Stage as defined in Book 0, Section 0.5.

1.4.L2.2: A company that transitions from cash-basis to accrual-basis accounting upon reaching Growth Stage restates the financial statements for the two most recent completed financial periods on an accrual basis and retains those restated statements as part of its financial records.

1.4.L2.3: The company maintains a written revenue recognition policy that states, for each revenue stream, the specific event or condition that triggers revenue recognition; and that policy has been applied consistently across all periods covered by the three-statement model.

1.4.L2.4: The company maintains a defined chart of accounts that has been applied consistently across all periods; any change in account classification is disclosed; and prior-period figures are restated where the change affects the comparability of figures across periods.

1.4.L2.5: The company maintains a written cost classification policy that documents what is included in cost of goods sold and what is classified as an operating expense; and that policy has been applied consistently across all periods.

1.4.L2.6: Deferred revenue is recorded as a liability on the balance sheet in the period in which cash is received and is recognised as revenue only in the period in which delivery occurs.

1.4.L2.7: The company's financial records are reconciled to all bank and payment accounts within ten working days of each month end; and any unreconciled items outstanding for more than thirty calendar days are disclosed in the management report for that period.

1.4.L2.8: Any change in the company's revenue recognition policy is documented, disclosed in the financial report for the period in which it takes effect, and applied to all prior periods presented for comparison.

Level 3

1.4.L3.1: The company's financial records are reviewed by an external accountant or auditor at least annually; and a written report of the review findings is retained and available for inspection.

1.4.L3.2: The company applies the relevant accounting standard, being IFRS or the applicable local equivalent, consistently across all financial statements prepared for external distribution.

1.4.L3.3: Software development costs are classified in accordance with a documented capitalisation policy that distinguishes between development-phase costs eligible for capitalisation and research-phase costs that must be expensed; and that policy has been applied consistently across all periods.

1.4.L3.4: Any change in accounting policy is documented; its financial effect is quantified; and comparative prior-period figures are restated in all financial statements prepared after the change takes effect.

1.4.L3.5: The company maintains a documented accounting policies manual covering revenue recognition, cost classification, asset capitalisation, and expense accrual methodology; and that manual is updated to reflect any policy change within thirty calendar days of the change taking effect.

COMMON DEFICIENCIES

CD 1.4.1: The company's financial records have not been reconciled to bank statements for the current quarter. The accounting balance for cash differs from the confirmed bank balance by a material amount. The difference has not been investigated. Financial reports are produced from the unreconciled accounting records.

CD 1.4.2: The company records cash received from customers as revenue at the point of receipt, regardless of whether the service has been delivered. Annual subscription payments received in advance are recorded as revenue in the month of receipt. No deferred revenue balance appears on the balance sheet. The company's reported revenue in months with large renewal cohorts is materially higher than the revenue that would be reported under a compliant revenue recognition policy.

CD 1.4.3: Issued SAFEs and convertible notes are tracked in a document maintained by the company's legal advisor. They do not appear in the company's accounting records. The balance sheet does not reflect any liability or contingent equity obligation arising from these instruments. The financial statements presented to investors do not disclose their existence.

CD 1.4.4: The company changed its cost classification methodology during the financial year, moving customer success costs from operating expenses to cost of goods sold, without disclosing the change or restating prior-period comparative figures. Gross margin for the period of the change and all subsequent periods is not comparable to gross margin for prior periods. The change has not been noted in any financial report.




STAGE AND LEVEL APPLICABILITY

The compliance level expectations for each section of Book 1 are established in the Financial Infrastructure Maturity Model in Book 0, Section 0.8. The operative mappings for this Book are as follows.

Section 1.1: Financial Architecture
Pre-Incorporation: no requirement
Pre-Revenue: Level 1
Early Revenue: Level 1
Growth Stage: Level 2
Scale Stage: Level 3

Section 1.2: Cash Management
Pre-Incorporation: no requirement
Pre-Revenue: Level 1
Early Revenue: Level 1
Growth Stage: Level 2
Scale Stage: Level 3

Section 1.3: Financial Reporting
Pre-Incorporation: no requirement
Pre-Revenue: Level 1
Early Revenue: Level 1
Growth Stage: Level 2
Scale Stage: Level 2

Section 1.4: Accounting Integrity
Pre-Incorporation: no requirement
Pre-Revenue: Level 1
Early Revenue: Level 1
Growth Stage: Level 2
Scale Stage: Level 2

Stage definitions are as established in Book 0, Section 0.5. Compliance level expectations reflect the Maturity Model established in Book 0, Section 0.8. Neither the stage definitions nor the maturity model expectations are restated here.

Feedback on Book 1 may be submitted to standard@ffistandard.org with reference to the specific section and criterion number. Feedback received before the close of the beta review period will be considered in the preparation of v1.0.
