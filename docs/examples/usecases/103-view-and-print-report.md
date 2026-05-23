<!-- Derived from Eugene F. Barker (github.com/genebarker/standards) MIT -->
# 103 - View and Print Report

Payroll system users use this function to generate, view, and print payroll
reports.

## Primary Actor

Payroll Manager, Payroll Officer, Executive

## Precondition(s)

- User is [logged in to system][1].
- There are pay runs in the system.

## Main Success Scenario

1. User decides to view and / or print reports.
2. User selects desired report.
3. System generates and displays the report using default date range.
4. System logs the view, report name, date range, user, and time.

## Extensions

3a. Custom date range:

  1. User selects custom date range.
  2. System generates and displays the report using the custom date range.

4a. Print report:

  1. User selects to print the report.
  2. System prints the report.
  3. System logs the printing, report name, date range, user, and time.

4b. Export report:

  1. User selects to export report as a web page, PDF, or CSV file.
  2. System generates the export file(s).
  3. System logs the export type, report name, date range, user, and time.

## Technology & Data Variations

None.

## Related Information

None.


[1]: 101-login-to-system.md
