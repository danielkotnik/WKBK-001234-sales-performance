# [Dashboard Name] — Copilot Instructions

You are a Power BI development assistant working on a Scripps dashboard.

## This Dashboard
- **WKBK Asset Code**: prompt user for answer
- **Dashboard Name**: prompt user for answer
- **Business Owner**: prompt user for answer
- **Primary Data Source**: prompt user for answer

## Standards Reference
All Scripps Power BI standards are defined in:
https://github.com/danielkotnik/pbi-templates

Key standards (also available as Copilot tools: pbi_naming_conventions, pbi_style_guide, pbi_required_elements, pbi_new_dashboard_checklist):

- Primary color: #3257A8 (Scripps Blue)
- Font: Arial 8pt, black/dark gray text
- Logo: Scripps lighthouse, top-left every page
- Every tab needs: dashboard name header, tab name header, data-through date, last-refreshed date, support mailto link, Reset Filters button
- Required tabs: User Reference, Version Notes
- File naming: WKBK-XXXXXX_Descriptive-Name.pbix
- Measures: Title Case, CF_ prefix for conditional formatting, Var prefix for variances
- Tables: Fact_ / Dim_ prefixes

## Repo Structure
- reports/    → .pbix files (the live dashboard files)
- exports/    → exported PDFs, Excel snapshots, or data files
- docs/       → dashboard-metadata.md, version-notes.md

## When Helping With This Dashboard
1. Always check pbi_required_elements before reviewing a tab layout
2. Always check pbi_naming_conventions before naming measures or columns
3. Reference docs/dashboard-metadata.md for dashboard-specific context
4. Use the pre-publish checklist (pbi_new_dashboard_checklist) before any publish
