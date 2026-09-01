# MMFR Ultimate Analysis — Automatically Generated Result Summary

Generated: 2026-08-18T16:56:02

## Mapping performance
### Internal model diagnostic
- 1993: internal hold-out OA=1.000, Kappa=1.000, mangrove F1=1.000.
- 2003: internal hold-out OA=0.988, Kappa=0.972, mangrove F1=0.981.
- 2013: internal hold-out OA=0.979, Kappa=0.956, mangrove F1=0.973.
- 2023: internal hold-out OA=0.970, Kappa=0.935, mangrove F1=0.958.

### Exact-year CGMD external spatial audit
- 1993: repeated balanced agreement=0.915 (repeat range 0.908–0.932), Kappa=0.831, mangrove PA=0.861, mangrove UA=0.966.
- 2003: repeated balanced agreement=0.927 (repeat range 0.912–0.946), Kappa=0.854, mangrove PA=0.862, mangrove UA=0.991.
- 2013: repeated balanced agreement=0.947 (repeat range 0.926–0.964), Kappa=0.894, mangrove PA=0.900, mangrove UA=0.992.
- 2023: repeated balanced agreement=0.964 (repeat range 0.952–0.976), Kappa=0.927, mangrove PA=0.966, mangrove UA=0.961.

The CGMD audit is an external-product agreement test using balanced class sampling; it is not field ground truth or area-weighted accuracy.

## Long-term extent
- Study-specific RF mapped area changed from 36,058.1 ha (1993) to 38,934.2 ha (2023), equivalent to +7.98%.
- CGMD annual context changed from 42,972.0 ha (1993) to 41,282.4 ha (2023), equivalent to -3.93%.
- The RF–CGMD trajectory difference should be discussed as product/method disagreement, not resolved by assuming one is ground truth.

## Annual canopy condition
- NDMI Theil–Sen slope: -0.000604 per year; Hamed–Rao p=0.09099.
- Pettitt candidate change year: 2000 (p=0.01052).

## Water-edge exposure
- Loss fraction within 0–60 m of persistent water was 63.5%, compared with 13.8% at >300 m; descriptive near/interior ratio=4.59.
- This is spatial exposure evidence and does not by itself establish sea-level-rise causation.

## Climate/ocean QC
- Robust primary-driver outlier years flagged: [2001, 2018, 2020].

## Strongest detrended lag associations after FDR correction
- NDMI_median vs sea_surface_elevation_anomaly_m, lag 2 yr: ρ=-0.462, FDR p=0.2813.
- CGMD_FCC_pct_mean vs sea_surface_elevation_anomaly_m, lag 3 yr: ρ=-0.447, FDR p=0.4126.
- CGMD_FCC_pct_mean vs sea_surface_salinity_psu, lag 2 yr: ρ=-0.385, FDR p=0.4686.
- CGMD_FCC_pct_mean vs air_temperature_2m_C, lag 1 yr: ρ=-0.333, FDR p=0.5738.
- CGMD_FCC_pct_mean vs sea_surface_temperature_C, lag 1 yr: ρ=-0.249, FDR p=0.6331.

## Interpretation constraint
Use association language for climate/ocean and water-edge results. Do not convert these results into causal attribution without an additional causal design.