# PLANT2CLINIC IoT article materials

Working materials for **From Cultivation to Care: Edge IoT, Digital Supervision and Mobile Interfaces for Medicinal-Plant Traceability**, prepared for Internet of Things (Elsevier).

Corresponding author: Francisco-Javier Ferrández-Pastor, University of Alicante, fjferran@ua.es.

## Repository contents

- `08_latex_source.zip`: editable LaTeX manuscript, supplement, demonstration guide and figures. Extract and compile `main.tex`, `supplementary.tex` and `demonstration_guide.tex` separately with pdfLaTeX, twice for references.
- Numbered PDF, DOCX and TXT files: submission documents, manuscript, supplements and form text.
- `18_evaluation_data.zip`: evaluation summaries, query records and historical scripts, with provenance notes.
- MP4 videos and PNG stills: four technical demonstrations.
- `GUIA_DE_CARGA.md`: Spanish upload guide and outstanding editorial steps. Files are at the repository root; the local submission folder is named `envio`.

## Evidence and reproducibility limits

The S2 audit checks recorded anomaly bands and reconstructed room states. It does not independently establish complete anomaly detection, sensor accuracy or valid agronomic thresholds. It reports 136,005 anomaly-band checks and 54,982 room states, with 284 freshness states excluded. The historic summary span describes retained sensor readings, not the full evaluation-log period. The 0.24 ms median comes from a separate 100-case probe. Scripts requiring the operational database or local services cannot be rerun from these shared files alone.

The mobile applications illustrate complementary workflows; simulated inputs and proposed integrations are identified in the article. No clinical outcomes or patient data are reported.

## Access and publication status

This repository is intended to remain **private** at the author's request. It is a working repository, not a public archival deposit or a published article. It has no DOI. Do not describe the data as publicly accessible while the repository is private. A journal data-availability statement must accurately reflect access and any restrictions at submission time.

Operational SQLite databases, credentials, clinical application manuals and the production application's Git history are not included. No open-source or data reuse licence has been selected; repository access does not itself grant a licence.
