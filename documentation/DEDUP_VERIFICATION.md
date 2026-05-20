# Deduplication Verification

The probe/ATIS spreadsheet model workbooks overlap with `paper-2003-03`.

Canonical shared source:

`/Users/dlev2617/Documents/Code/Agents/github-packages/_shared_sources/probe-atis-spreadsheet-model`

Comparison summary:

- `ServiceTime.xls` is byte-identical across the `paper-2002-01` and `paper-2003-03` contexts.
- `Qp2.xls` is not byte-identical to the `paper-2003-03` copy, but the LibreOffice-converted workbook cell/formula values are identical across 321,071 compared cells.
- `Qpi2.xls` is not byte-identical to the `paper-2003-03` copy, but the LibreOffice-converted workbook cell/formula values are identical across 334,310 compared cells.

Detailed verification is stored at:

`/Users/dlev2617/Documents/Code/Agents/github-packages/_shared_sources/probe-atis-spreadsheet-model/metadata/DEDUP_VERIFICATION_2002_01_2003_03.csv`

Decision: this paper package points to the shared source rather than carrying duplicate workbook copies.
