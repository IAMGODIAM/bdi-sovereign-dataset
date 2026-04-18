# BDI Sovereign Dataset v1.0
## Black Distress Index — Synthesized Flagship Dataset
**Publisher:** E5 Enclave Incorporated | EIN 99-3822441 | Liberty City, Miami, Florida
**License:** CC0 1.0 Universal — Public Domain. No rights reserved.
**Version:** v1.0-SEALED | **Date:** April 17, 2026
**DAG:** bdi-sovereign-dataset-v1-sealed-2026-0417

---

## WHAT THIS IS

This is **Product A** of the IAMGODIAM data stack — the **BDI National Structural Record**.

A synthesized, 8-pillar empirical instrument documenting Black American structural conditions from 1991–2024, with historical evidence context from 1514.

**For the canonical stack architecture, see:**
→ `github.com/IAMGODIAM/bdi-raw-data-vault/STACK.md`

---

## CORRECTED DATA POINT COUNT

**Verified empirical observations: 1,574** across 8 pillars.

Previous public claim of "1,855" included JSON metadata keys counted as data points — this was incorrect per our explicit counting rule (one row in a time series = one data point). Full counting methodology: `BDI_QUANT_SPEC.md`.

---

## THE 8 PILLARS

| # | Pillar | Core Metrics | Source | Years |
|---|--------|-------------|--------|-------|
| 1 | Economic | Wealth gap, unemployment ratio, poverty ratio, income gap | Fed Reserve SCF, BLS, Census ACS | 1989–2024 |
| 2 | Health | Maternal mortality ratio, life expectancy gap | NCHS NVSR | 1915–2022 |
| 3 | Criminal Justice | Incarceration ratio, police killings rate | BJS, Mapping Police Violence | 1925–2023 |
| 4 | Education | NAEP 8th-grade reading/math gap | NCES NAEP | 1992–2022 |
| 5 | Housing | Homeownership gap, mortgage denial ratio, eviction ratio | Census Decennial/ACS, CFPB HMDA, Eviction Lab | 1940–2022 |
| 6 | Political | Black voter turnout gap | Census CPS | 1964–2022 |
| 7 | Environmental | County toxic burden, facility density | EPA EJScreen (v2.0) | 2022 |
| 8 | Historical | Slave Voyages aggregate, land loss, wealth extraction | Slave Voyages DB, USDA NASS | 1514–2024 |

---

## COMPOSITE FORMULA

```
BDI = Economic×0.20 + Health×0.20 + CriminalJustice×0.20 +
      Education×0.15 + Housing×0.10 + Environmental×0.10 + Political×0.05
```

Normalization: 0–100 scale. State-level resolution: 17 priority states.
Full weighting rationale: `BDI_QUANT_SPEC.md`

---

## HOW TO CITE

E5 Enclave Incorporated. (2026). *Black Distress Index Sovereign Dataset v1.0*.
GitHub. https://github.com/IAMGODIAM/bdi-sovereign-dataset | CC0 1.0 Universal.

**Cite for:** BDI composite scores, national disparity trends, pillar-level structural record, state-level distress rankings.

**Do not cite for:** Census tract or county-level FDI scoring — use `farmblock-data` or `farmblock-dataset` instead.

---

## REPLICATION

Raw source data for all series is in the companion vault:
→ `github.com/IAMGODIAM/bdi-raw-data-vault`

All raw files were committed before analysis. Anyone with access to the listed federal APIs can reproduce the input series from documented vintages.

---

## YEAR RANGE NOTE

**Empirical scoring window:** 1991–2024 (structured comparable annual data)
**Historical evidence context:** 1514–2024 (Slave Voyages 1514–1866; land loss, Census wealth 1910–2024)

The 1514–2024 span is used in public communication as historical context. It is not a claim that all 510 years of data are in the same normalized scoring pipeline. See `BDI_QUANT_SPEC.md` §7 for full historical pillar treatment.

---

*By Grace, perfect ways.*
