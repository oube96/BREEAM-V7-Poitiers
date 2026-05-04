# Review notes - BREEAM NC V7 Tra 01 reports

## Deliverables

- `SBY/TRA01_SBY_2_Rapport_final.docx`
- `MIXTE/TRA01_Mixte_2_Rapport_final.docx`
- `MBY/TRA01_MBY_3_4_Rapport_final.docx`

## Inputs used

- Visual/style reference: `Exemple à suivre.docx`
- Project plan PDFs from the repository:
  - `03 SBY.pdf`
  - `04 MIXTE.pdf`
  - `02 MBY.pdf`
- Technical source DOCX files supplied locally by Oussama:
  - `TRA01_SBY_2_Poitiers_contenu_technique.docx`
  - `TRA01_MIXTE_2_Poitiers_contenu_technique.docx`
  - `TRA01_MBY_3_4_Poitiers_contenu_technique.docx`

## Method

- Reused the visual logic of `Exemple à suivre.docx`: cover page, Essor branding, green heading system, header/footer treatment, caption style, and sober table styling.
- Preserved the technical values and conclusions from the three technical DOCX sources.
- Removed preparation/draft wording and harmonized dossier names as `SBY 2`, `Mixte 2`, and `MBY 3&4`.
- Renamed the evidence appendix to `Pièces justificatives à joindre / statut de preuve`.
- Used the repository project PDFs as cover visuals and kept the supplied figures/graphs from the technical DOCX files.
- Kept PTAI/distances and amenities language conservative where exact measured distances were not provided: distances remain to be confirmed by scaled plan and/or BREEAM Platform.

## Tools and QA

- Generated the final DOCX files with Python and `python-docx`, using the reference DOCX as the style base.
- Rendered each final DOCX to PDF/PNG using LibreOffice and Poppler for visual inspection.
- Checked all 9 rendered pages for each report: cover, sommaire, figures, tables, headers, footers, and page numbering.
- Audited table geometry so table widths, grids, and cell widths match the page layout.
- Verified the required project-specific values:
  - SBY 2: 63 people, 21 to 42 PLU parking spaces, 41 drawn spaces, 3 to 5 PLU bike spaces, 7 BREEAM bike spaces.
  - Mixte 2: 63 people, 42 to 112 PLU parking spaces, 60 drawn spaces, 6 PLU bike spaces, 7 BREEAM bike spaces.
  - MBY 3&4: 120 people, 59 to 143 PLU parking spaces, 75 drawn spaces, 6 to 15 PLU bike spaces with 12 m² minimum, 12 BREEAM bike spaces.
- Checked that final DOCX text no longer contains `préparatoire`, `à mettre en forme`, `Codex`, `draft`, or `Livrable technique`.
