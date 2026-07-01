# [Dashboard Name]

> **WKBK Code**: WKBK-XXXXXX  
> **Business Owner**:  
> **Support**: [email@scripps.com](mailto:email@scripps.com?subject=Question regarding WKBK-XXXXXX)

## About This Dashboard

(Brief description of what this dashboard shows and who uses it.)

## Repository Structure

```
.github/
  copilot-instructions.md   ← Copilot auto-loads this for every session
reports/
  WKBK-XXXXXX_Name.pbix    ← Live Power BI dashboard file(s)
exports/
  *.pdf / *.xlsx            ← Exported snapshots
docs/
  dashboard-metadata.md     ← Data sources, ownership, refresh schedule
  version-notes.md          ← Change log
```

## Getting Started

1. **Open the `.pbix`** from `reports/` in Power BI Desktop
2. **Fill in `docs/dashboard-metadata.md`** with data source and ownership info
3. **Update `.github/copilot-instructions.md`** with the WKBK code, dashboard name, and owner
4. Before publishing, run through the [pre-publish checklist](https://github.com/danielkotnik/pbi-templates/blob/main/checklists/new-dashboard-checklist.md)

## Standards

This dashboard follows Scripps Power BI standards defined in:  
👉 [github.com/danielkotnik/pbi-templates](https://github.com/danielkotnik/pbi-templates)
