# PlanIndex

PlanIndex indexes planning applications published by UK local planning
authorities: 2.1 million applications across 373 councils in England,
Scotland, Wales and Northern Ireland, read from the councils' own registers
every day. Every application has a permanent page at
[planindex.co.uk](https://planindex.co.uk), every council, ward and postcode
district has a hub, and a decision-times study ranks councils by how long
they take to decide.

This organisation is where the data is published openly.

## What is here

- **[uk-planning-applications](https://github.com/planindex/uk-planning-applications)**:
  one CSV per council of the applications first seen in the last 30 days
  (reference, address, postcode district, proposal, category, status,
  received, validated and decided dates, decision, and the PlanIndex URL),
  rebuilt nightly. A data dictionary and the licence sit beside the files.
- **Decision times and approval rates** from the study, as CSV:
  [planning-decision-times.csv](https://planindex.co.uk/planning-decision-times.csv)
  and [planning-approval-rates.csv](https://planindex.co.uk/planning-approval-rates.csv),
  with the [methodology](https://planindex.co.uk/planning-decision-times/methodology)
  stating what is counted, what is excluded, and the sample size behind every figure.

## Licence and attribution

The files are published under
[Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/).
Use them for anything, including commercial work, and credit PlanIndex with a
link: "Data: PlanIndex, https://planindex.co.uk".

The application facts themselves are the public records of the planning
authority named in each row, collected from its published register. Where a
council's data reaches us through planning.data.gov.uk or PlanIt, the data
dictionary says so.

Names of applicants and agents are not included in any file. If you are named
on an application and want a page removed or an address withheld, use
[planindex.co.uk/takedown](https://planindex.co.uk/takedown).

## Checking anything

Every application page on planindex.co.uk links the council's own portal
entry, and every figure in the decision-times study states its measurement
window and sample size, so anything taken from here can be traced back to
the source.

## Contact

[planindex.co.uk/contact](https://planindex.co.uk/contact), or open an issue
on the repository.
