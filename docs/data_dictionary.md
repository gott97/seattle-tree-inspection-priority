# Core data dictionary

This document describes the principal analytical fields used by the project. Confirm exact field names and aliases against the final notebooks and hosted feature layers before creating a tagged release.

| Field or concept | Type | Description |
|---|---|---|
| Asset identifier | Text or integer | Stable identifier carried from the source tree inventory |
| Species | Text | Available source species or common-name attribute |
| Site | Text | Available source site or location descriptor |
| `DBH_ORIG` | Numeric/text | Original diameter-at-breast-height value preserved from the source inventory |
| `DBH_CLEAN` | Numeric | Standardized usable DBH measurement |
| `DBH_IMPUTED` | Short integer | Flag indicating that `DBH_CLEAN` uses a documented fallback value |
| `DBH_METHOD` | Text | Indicates whether the analytical diameter was original, cleaned, or imputed |
| `MATURITY` | Text/ordinal | Generalized maturity class derived from diameter information |
| `SIM_COND` | Text | Explicitly labeled simulated condition category |
| `COND_SCORE` | Numeric | Simulated condition expressed on the common 0-100 scale |
| `LAST_INSP` | Date | Simulated most recent inspection date |
| `INSP_SOURCE` | Text | Identifies the source of the inspection-history value |
| `OVERDUE_SC` | Numeric | Time-since-inspection score, capped at 100 after seven years |
| `NEAR_SCHOOL` | Short integer | 1 when within 500 feet of a school; otherwise 0 |
| `NEAR_SIDEWALK` | Short integer | 1 when within 25 feet of a sidewalk; otherwise 0 |
| `NEAR_ARTERIAL` | Short integer | 1 when within 75 feet of a selected arterial street; otherwise 0 |
| `NEAR_TRAIL` | Short integer | 1 when within 40 feet of a trail; otherwise 0 |
| `RSE_PERCENT` | Numeric | Joined Racial and Social Equity Index percentile value |
| `RSE_QUINT` | Text | Joined Racial and Social Equity Index category |
| `EQUITY_HIGH` | Short integer | 1 when the asset falls within the model's highest-priority RSE areas; otherwise 0 |
| `PRIORITY` | Numeric | Weighted 0-100 Inspection Priority Index |
| `PRIOR_CLASS` | Text | Critical, High, Moderate, or Low communication class |
| `ANNUAL_SEL` | Short integer | 1 for assets selected within the highest-ranked 5 percent |
| `PLAN_YEAR` | Short integer | Modeled inspection-program year derived from rank |
| `INSP_HRS` | Numeric | Modeled direct inspection time in hours |
| `MODEL_VER` | Text | Model-version identifier |
| `DATA_OK` | Short integer | Core-data QA status |
| `QA_NOTES` | Text | Data-quality notes generated during inventory preparation |
| `SPATIAL_NOTE` | Text | Notes produced during spatial processing |
| `MODEL_NOTE` | Text | Interpretation and modeling notes |

Binary criteria are represented as 0 or 100 before their weights are applied. Field aliases in the public web layers may be more readable than the underlying analytical field names.

