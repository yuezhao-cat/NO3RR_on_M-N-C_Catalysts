# NO3RR on M-N-C Catalysts: computational structures

DFT-optimized structures supporting the manuscript

**Condition-Resolved Activity Prediction of Peripheral Substituent Effects in Nitrate Reduction Catalysts**

All files are VASP `CONTCAR` files (direct coordinates) and can be opened with VESTA, ASE, or pymatgen.

## Contents

| Folder | Content | Files |
|---|---|---|
| `CoPc-X/` | Five peripherally substituted cobalt phthalocyanines, Co-Pc-X (X = NH2-1, NH2-2, CO2H, F, NO2): bare catalyst and catalyst with adsorbed *NH2 | 10 |
| `MNx_references/substrate/` | The 62 M-Nx reference structures listed in Table S9 of the Supporting Information | 62 |
| `MNx_references/NH2_adsorbed/` | *NH2-adsorbed geometries of the M-Nx references (available for 51 of the 62) | 51 |

## File naming

- `CONTCAR_<name>_substrate`: bare Co-Pc-X catalyst
- `CONTCAR_<name>_NH2`: structure with adsorbed *NH2
- `CONTCAR_<name>` in `MNx_references/substrate/`: bare M-Nx reference
- Reference names follow Table S9 of the Supporting Information.

## Co-Pc-X catalysts

| Catalyst | ΔG_PZC(*NH2) (eV) | Bare | *NH2 |
|---|---|---|---|
| Co-Pc-NH2-2 | -5.82 | `CoPc-X/CONTCAR_Co-Pc-NH2-2_substrate` | `CoPc-X/CONTCAR_Co-Pc-NH2-2_NH2` |
| Co-Pc-NH2-1 | -5.80 | `CoPc-X/CONTCAR_Co-Pc-NH2-1_substrate` | `CoPc-X/CONTCAR_Co-Pc-NH2-1_NH2` |
| Co-Pc-CO2H | -5.60 | `CoPc-X/CONTCAR_Co-Pc-CO2H_substrate` | `CoPc-X/CONTCAR_Co-Pc-CO2H_NH2` |
| Co-Pc-F | -5.54 | `CoPc-X/CONTCAR_Co-Pc-F_substrate` | `CoPc-X/CONTCAR_Co-Pc-F_NH2` |
| Co-Pc-NO2 | -5.33 | `CoPc-X/CONTCAR_Co-Pc-NO2_substrate` | `CoPc-X/CONTCAR_Co-Pc-NO2_NH2` |

ΔG_PZC(*NH2) values are those reported in Table S4 of the Supporting Information.

## M-Nx references

The 62 references span eight 3d metals (Ti, V, Cr, Mn, Fe, Co, Ni, Cu) in pyrrolic and pyridinic coordination environments. ΔG_PZC(*NH2) values are those reported in Table S9.

| No. | Reference | Metal | Coordination | ΔG_PZC(*NH2) (eV) | *NH2 geometry provided |
|---|---|---|---|---|---|
| 1 | V-COF-366 | V | Pyrrolic | -10.341 | yes |
| 2 | Ti-pyridine-N4 | Ti | Pyridinic | -9.283 | yes |
| 3 | V-pyridine-N3 | V | Pyridinic | -8.609 | yes |
| 4 | Ti-pyridine-N3 | Ti | Pyridinic | -8.500 | yes |
| 5 | Ti-pyrrole-N2-diag | Ti | Pyrrolic | -8.372 | yes |
| 6 | Ti-COF-366 | Ti | Pyrrolic | -8.300 | yes |
| 7 | V-pyridine-N2-diag | V | Pyridinic | -8.234 | yes |
| 8 | V-N1-pyrrole | V | Pyrrolic | -8.195 | yes |
| 9 | Ti-pyridine-N2-diag | Ti | Pyridinic | -8.151 | yes |
| 10 | Mn-pyridine-N2 | Mn | Pyridinic | -8.146 | yes |
| 11 | Ti-N2-pyrrole | Ti | Pyrrolic | -8.131 | yes |
| 12 | V-pyridine-N1 | V | Pyridinic | -8.130 | yes |
| 13 | V-pyridine-N4 | V | Pyridinic | -8.122 | yes |
| 14 | Ti-N3-pyrrole | Ti | Pyrrolic | -8.097 | yes |
| 15 | V-pyridine-N2 | V | Pyridinic | -8.032 | yes |
| 16 | Ti-pyridine-N1 | Ti | Pyridinic | -8.025 | yes |
| 17 | Ti-pyridine-N2 | Ti | Pyridinic | -8.017 | yes |
| 18 | Fe-pyridine-N1 | Fe | Pyridinic | -8.003 | yes |
| 19 | V-N2-pyrrole | V | Pyrrolic | -7.992 | yes |
| 20 | Ti-pyrrole-N4 | Ti | Pyrrolic | -7.972 | yes |
| 21 | Ti-N1-pyrrole | Ti | Pyrrolic | -7.902 | yes |
| 22 | Cr-pyridine-N2-diag | Cr | Pyridinic | -7.762 | yes |
| 23 | Cr-pyridine-N1 | Cr | Pyridinic | -7.583 | yes |
| 24 | V-pyrrole-N4 | V | Pyrrolic | -7.468 | yes |
| 25 | Cr-pyridine-N2 | Cr | Pyridinic | -7.446 | yes |
| 26 | Cr-N1-pyrrole | Cr | Pyrrolic | -7.395 | yes |
| 27 | Cr-pyridine-N3 | Cr | Pyridinic | -7.362 | yes |
| 28 | Cr-N2-pyrrole | Cr | Pyrrolic | -7.063 | yes |
| 29 | Cu-N3-pyrrole | Cu | Pyrrolic | -6.981 | yes |
| 30 | Mn-pyridine-N1 | Mn | Pyridinic | -6.885 | yes |
| 31 | Fe-pyridine-N4 | Fe | Pyridinic | -6.870 | yes |
| 32 | Mn-pyridine-N2-diag | Mn | Pyridinic | -6.834 | yes |
| 33 | Cr-N3-pyrrole | Cr | Pyrrolic | -6.826 | yes |
| 34 | Fe-COF-366 | Fe | Pyrrolic | -6.816 | yes |
| 35 | Cr-pyridine-N4 | Cr | Pyridinic | -6.802 | yes |
| 36 | Fe-Pc-N4 | Fe | Pyrrolic | -6.688 | yes |
| 37 | Mn-pyridine-N3 | Mn | Pyridinic | -6.640 | yes |
| 38 | Fe-pyridine-N2-diag | Fe | Pyridinic | -6.520 | yes |
| 39 | Cr-pyrrole-N4 | Cr | Pyrrolic | -6.506 | yes |
| 40 | Co-pyridine-N1 | Co | Pyridinic | -6.451 | yes |
| 41 | Ni-N3-pyrrole | Ni | Pyrrolic | -6.406 | yes |
| 42 | Fe-pyridine-N2 | Fe | Pyridinic | -6.298 | yes |
| 43 | Fe-N3-pyrrole | Fe | Pyrrolic | -6.250 | yes |
| 44 | Co-pyridine-N2 | Co | Pyridinic | -6.209 | yes |
| 45 | Mn-N2-pyrrole | Mn | Pyrrolic | -6.187 | yes |
| 46 | Fe-N1-pyrrole | Fe | Pyrrolic | -6.176 | yes |
| 47 | Co-N2-pyrrole | Co | Pyrrolic | -6.159 | yes |
| 48 | Fe-pyridine-N3 | Fe | Pyridinic | -6.144 | yes |
| 49 | Cu-pyridine-N3 | Cu | Pyridinic | -5.313 | no |
| 50 | Cu-pyridine-N4 | Cu | Pyridinic | -5.232 | no |
| 51 | Cu-pyridine-N2-diag | Cu | Pyridinic | -5.174 | no |
| 52 | Cr-COF-366 | Cr | Pyrrolic | -5.135 | no |
| 53 | Ni-pyrrole-N2-diag | Ni | Pyrrolic | -5.088 | no |
| 54 | Ni-N2-pyrrole | Ni | Pyrrolic | -5.083 | no |
| 55 | Cu-pyridine-N2 | Cu | Pyridinic | -5.038 | no |
| 56 | Cu-N2-pyrrole | Cu | Pyrrolic | -4.834 | no |
| 57 | Cu-pyrrole-N4 | Cu | Pyrrolic | -4.799 | no |
| 58 | Cu-pyridine-N1 | Cu | Pyridinic | -4.709 | yes |
| 59 | Cu-COF-366 | Cu | Pyrrolic | -4.706 | no |
| 60 | Cu-Pc-N4 | Cu | Pyrrolic | -4.672 | no |
| 61 | Ni-pyrrole-N4 | Ni | Pyrrolic | -4.571 | yes |
| 62 | Ni-COF-366 | Ni | Pyrrolic | -3.059 | yes |

## Computational settings

Structures were optimized with VASP using the RPBE functional with D3 dispersion correction. Full computational details are given in Section 1 of the Supporting Information.

## Contact

Questions about these structures can be raised through the Issues page of this repository.
