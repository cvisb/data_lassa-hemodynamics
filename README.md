# Lassa Hemodynamic Dataset

Clinical and point-of-care ultrasound (hemodynamic) data from patients with PCR-confirmed Lassa fever. Each patient had up to three serial bedside exams, and the dataset records their outcome (discharge or death).

## Files

* `data/lassa_hemodynamic_dataset_cleaned.csv`

## Cohort summary

- **Number of patients:** 35 (one row per patient, all IDs unique)
- **Admission dates:** 2025-01-14 to 2026-04-13
- **Sex:** 19 female (54.3%), 16 male (45.7%)
- **Lassa PCR positive:** 35/35 (100%)
- **Malaria antigen positive:** 1/35 (2.9%)

### Age

Age in years: mean 38.1 (SD 13.8), median 36 (IQR 29.5–42.5), range 17–70.

| Age bin (years) | Patients | % of cohort | Discharged | Died |
|---|---:|---:|---:|---:|
| < 18 | 2 | 5.7% | 2 | 0 |
| 18–29 | 7 | 20.0% | 7 | 0 |
| 30–39 | 14 | 40.0% | 11 | 3 |
| 40–49 | 5 | 14.3% | 4 | 1 |
| 50–59 | 3 | 8.6% | 2 | 1 |
| ≥ 60 | 4 | 11.4% | 4 | 0 |
| **Total** | **35** | **100%** | **30** | **5** |

### Outcome

| Outcome | Patients | % | Median age (years) | Days from admission to outcome, mean (range) |
|---|---:|---:|---:|---|
| Discharged | 30 | 85.7% | 35.5 | 14.2 (up to 32) |
| Death | 5 | 14.3% | 37 | 4.2 (up to 7) |

Outcome by sex: females 3/19 died (15.8%), males 2/16 died (12.5%).

### Presenting symptoms

| Symptom | Positive | % |
|---|---:|---:|
| Emesis | 18 | 51.4% |
| Anorexia | 16 | 45.7% |
| Diarrhea | 12 | 34.3% |
| Hemorrhage | 6 | 17.1% |


