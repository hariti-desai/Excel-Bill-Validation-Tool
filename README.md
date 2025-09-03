# Excel-Bill-Validation-Tool

Sample – Billing Validation (BV)

This project is a comprehensive billing validation system built in Excel for analyzing and verifying electricity and gas utility invoices. It cross-checks supplier invoices against contractual rates and metered consumption to detect overcharges, undercharges, and validation errors.

The system automates validation for different types of energy meters (Half-Hourly HH, Non-Half-Hourly NHH, and Gas) and consolidates the results into a clear dashboard and summary.

---

Workbook Structure

 1. Dashboard

* Front-end interface with month selector (`Select Month ▼`).
* Displays overcharges/undercharges across different months.
* Provides high-level financial and consumption insights.

 2. Summary

* Consolidated KPIs:

  * ✅ Total Meters
  * ✅ Validation Passed vs. Failed
  * ✅ Total Overcharge (£)
  * ✅ Total Amount Payable (£)
* Quick snapshot of billing health and supplier accuracy.

 3. How to

* User manual for navigating the workbook.
* Explains purpose of each sheet and validation logic.

 4. Electricity HH Data

* Raw invoice data for Half-Hourly electricity meters.
* Includes:

  * Gross cost, VAT, CCL
  * Day/Night usage split
  * Standing charges
  * Reactive power charges

 5. Electricity HH Validation

* Cross-checks HH invoices against:

  * Day/Night consumption profiles
  * Contracted rates and standing charges
  * VAT & CCL compliance
* Flags Overcharged / Undercharged / Match cases.
* Produces breakdowns of usage, costs, billing errors, and validation status.

 6. Electricity Control Tab

* Stores contract details:

  * Supplier info, contract dates
  * Unit rates (Day/Night)
  * Standing charges
  * KVA allowances
  * VAT & levy rates
* Provides reference data for validation.

 7. Electricity HH Profile Data

* Half-hourly consumption records (30-min intervals).
* Validates supplier invoices against actual load profiles.

 8. Gas Data

* Raw gas invoice dataset:

  * Units consumed, cost, VAT, CCL
  * Calorific values & correction factors
  * Fixed & variable charges

 9. Gas Validation

* Verifies gas invoices:

  * Meter reads vs. supplier charges
  * Standing charges & CCL
  * VAT correctness
* Flags anomalies and provides pass/fail status.

 10. Gas Control Tab

* Stores gas contract information:

  * Supplier details
  * Unit rates
  * Standing charges
  * Calorific values, correction factors
  * VAT & CCL rates

 11. Electricity NHH Data

* Invoice data for Non-Half-Hourly electricity sites.
* Includes:

  * Unit rates, fixed charges, VAT, CCL
  * Meter reads (start & end)

 12. Electricity NHH Validation

* Validation checks for NHH invoices:

  * Meter read verification
  * Day usage cost
  * Standing charges
  * VAT & CCL accuracy
* Flags anomalies with pass/fail validation status.

---

⚡ Key Features

* Multi-Utility Support → Handles Electricity (HH & NHH) + Gas.
* Contract Validation → Ensures invoices match supplier agreements.
* Error Detection → Flags VAT errors, standing charge mismatches, manipulated day/night splits.
* Dashboard & Reporting → Clear financial and usage insights.
* Automated Checks → Reduces manual work and human error.

---

 🚀 Use Cases

* Energy Managers → Verify supplier invoices.
* Finance Teams → Ensure accurate billing.
* Sustainability Teams → Track energy usage vs. actual meter data.
* Auditors → Identify overcharging trends.

---

 ✅ In Short

This Excel workbook is a Billing Validation System that compares utility supplier invoices against contractual terms and metered data. It detects overcharges/undercharges, validates accuracy, and provides a consolidated financial summary for better decision-making.

---
