# Health Records Database — prototype

A one-page mock-up of a combined patient and medicine record form for a clinic pharmacy. It was an early design study for what became [HealthRecords](https://github.com/hlaolil/HealthRecords).

**Live page:** https://hlaolil.github.io/inventory/

## What it shows

A "data input and lookup" form and table, with the fields a dispensing record needs:

- **Patient**: name, gender, age group, locality, position and company
- **Clinical**: condition treated, treatment history, family history, allergies to medication and prescriber
- **Medicine**: SKU code, description, quantity required, available stock, unit price, cost, date and expiry status
- **Comment**

It is a single static `index.html` (HTML and CSS). Submitting the form does not store anything.
