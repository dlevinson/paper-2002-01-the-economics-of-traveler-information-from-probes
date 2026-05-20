# The Economics of Traveler Information From Probes

## Bibliographic Information

- Row ID: `paper-2002-01`
- Authors: David M. Levinson
- Venue: *Public Works Management & Policy* 6(4), 241-249, 2002
- DOI: `10.1177/1087724X02006004002`

## Audit Result

This paper is not a no-data/no-code case. The paper describes a stylized simulation model for probe-vehicle traveler information using Poisson arrivals, two parallel links, information subscription shares, probe shares, queue length, randomized service times, recurring congestion, and incident/service-rate scenarios.

The matching local artifacts are legacy Excel model workbooks from the PWMP-Probes publication folder. Because the same workbook lineage is also used by `paper-2003-03`, the workbooks are staged once as a shared source:

`../../../_shared_sources/probe-atis-spreadsheet-model`

Local absolute path:

`/Users/dlev2617/Documents/Code/Agents/github-packages/_shared_sources/probe-atis-spreadsheet-model`

## Package Contents

- `paper/Probes.pdf`: local reference copy used for validation. Review publisher rights before uploading the PDF itself.
- `documentation/PAPER_FIRST_VALIDATION.md`: paper-first evidence that the simulation model is the relevant archival target.
- `documentation/DEDUP_VERIFICATION.md`: current deduplication summary.
- `data/DEDUP_POINTER_MANIFEST.csv`: pointer from this paper package to the shared workbook source.

## Shared Source Boundary

The shared source contains:

- Original legacy workbooks: `Qp2.xls`, `Qpi2.xls`, `ServiceTime.xls`
- Modernized LibreOffice conversions: `Qp2.xlsx`, `Qpi2.xlsx`, `ServiceTime.xlsx`
- Workbook sheet inventory and deduplication verification against `paper-2003-03`

The source publication folder also contains drafts, correspondence, contracts, literature-review files, and publisher/admin material. Those are excluded from the archive package.

## Status

Ready for public package review as a code/model pointer package. No additional hard-drive search is expected for this paper; duplicate workbook copies and pre-dedup audit leftovers have been removed.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 14:46:37 AEST

- Pipeline: `READY-TO-UPLOAD/PUBLIC`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
