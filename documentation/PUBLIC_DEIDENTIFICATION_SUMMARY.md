# Public Deidentification Summary

Updated: 2026-05-17 12:25:10 AEST

## Decision

This package is staged as `UPLOADED` because the public payload is aggregate-only. The original alumni survey workbook is not copied. Respondent columns 1-20 are removed, and the profession/title rows are excluded because they are quasi-identifying in a small alumni sample.

## What Remains

The public data files retain only aggregate values: valid-response counts, averages, population standard deviations, and a categorical count for how central land-use/transportation work was to respondents' jobs. This supports the paper's assessment claims without publishing individual response vectors.

## Source Boundary

The source workbook at `/Users/dlev2617/Documents/Data/~Nexus_Data/Pedagogy-Evaluation Studies/AirRights/Survey results.xls` remains a checked local source, but it is not part of the public upload payload. The duplicate workbook at `/Users/dlev2617/Documents/Papers/~05-Published/Transportation Research Record (TRR) - Journal of the Transportation Research Board/TRR-LUTC-KingKrizek/JPER Version/Survey results.xls` is also not copied.
