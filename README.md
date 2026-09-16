# ETHOS.Data-Catalogue

Public catalogue of datasets published by Forschungszentrum Jülich, Institute of
Climate and Energy Systems (ICE-2).

> **Generated — do not edit.**
> Produced from the internal catalogue by `ethos-data catalog publish`.
> Changes made here will be overwritten. Open an issue instead.

The data itself lives on [DESY dCache InfiniteSpace][dcache] and is served over
anonymous HTTPS — no Helmholtz account is needed to download it.

```bash
pip install ethos_data
ethos-data ls
ethos-data fetch <dataset-or-key>
```

## Datasets

| Dataset | Title | Files | Size | Availability |
|:--|:--|--:|--:|:--|
| `corine-land-cover` | CORINE Land Cover 2018, 100 m raster, version 20 (Europe) | 67 | 270.2 MB | downloadable |
| `esa-cci-landcover` | ESA CCI Land Cover Classification, 300 m, 1992-2015 (v2.0.7) | 28 | 10,033.8 MB | downloadable |
| `geothermal-conductivity-assumptions` | Franzmann lithology-to-thermal-conductivity assumptions | 1 | 0.0 MB | downloadable |
| `geothermal-resource` | Global subsurface temperature and sustainable heat flow | 2 | 6.2 MB | downloadable |
| `global-lithological-map-glim-v1` | Global Lithological Map Database (GLiM) v1.0, 0.5-degree grid | 2 | 1.2 MB | downloadable |
| `global-solar-atlas` | Global Solar Atlas, long-term average solar resource and air temperature | 117 | 28,023.4 MB | downloadable |
| `global-wind-atlas-era5-expanded` | GWA 4.0 100 m wind speed, expanded to full global coverage with the ERA5 long-run average | 1 | 67,808.3 MB | downloadable |
| `global-wind-atlas-v1` | Global Wind Atlas 1.0, mean wind speed at 50, 100 and 200 m (global and Europe) | 11 | 6,396.2 MB | downloadable |
| `global-wind-atlas-v2` | Global Wind Atlas 2.0, mean wind speed (global and Europe) | 9 | 7,255.3 MB | downloadable |
| `global-wind-atlas-v3` | Global Wind Atlas 3.0, wind speed, Weibull parameters and RIX (250 m, global) | 14 | 144,276.4 MB | downloadable |
| `global-wind-atlas-v4` | Global Wind Atlas 4.0, mean wind speed (250 m, global) | 6 | 71,364.9 MB | downloadable |
| `goutorbe-global-heat-flow-2011` | Goutorbe et al. (2011) global heat flow and geophysical proxies | 1 | 9.6 MB | downloadable |
| `icon-lam-southern-africa` | ICON-LAM convection-permitting simulation, southern Africa 2017-2019, 0.033 deg, 15 min, zoom-7 tiles for RESKit | 3861 | 3,116,089.2 MB | downloadable |
| `nasa-power-geothermal-climatology` | NASA POWER Earth Skin Temperature climatology used by Franzmann | 1 | 13.5 MB | downloadable |
| `reskit-test-data/boundaries` | RESKit administrative boundary test fixtures | 8 | 0.0 MB | downloadable |
| `reskit-test-data/corine` | RESKit CORINE Land Cover test fixture, Aachen | 1 | 0.1 MB | downloadable |
| `reskit-test-data` | RESKit test fixtures - real weather and geospatial data, clipped | 88 | 7.9 MB | downloadable |
| `reskit-test-data/dist2coast` | RESKit distance-to-coast test fixture, German Bight | 1 | 0.0 MB | downloadable |
| `reskit-test-data/era5` | RESKit ERA5 test fixtures, Aachen | 21 | 1.3 MB | downloadable |
| `reskit-test-data/era5-csp` | RESKit ERA5 and ERA5-Land test fixtures, Morocco | 4 | 1.5 MB | downloadable |
| `reskit-test-data/esa-cci-landcover` | RESKit ESA CCI land cover test fixtures, Aachen and Bulawayo | 2 | 0.1 MB | downloadable |
| `reskit-test-data/gebco` | RESKit GEBCO bathymetry test fixture, German Bight | 1 | 0.0 MB | downloadable |
| `reskit-test-data/global-solar-atlas` | RESKit Global Solar Atlas test fixtures | 4 | 1.2 MB | downloadable |
| `reskit-test-data/global-wind-atlas` | RESKit Global Wind Atlas 3 test fixtures, Aachen | 4 | 0.3 MB | downloadable |
| `reskit-test-data/icon-lam` | RESKit ICON-LAM test fixtures (FZJ ICON-LAM, southern Africa, clipped) | 9 | 1.1 MB | downloadable |
| `reskit-test-data/merra2` | RESKit MERRA-2 test fixtures, Aachen | 12 | 1.0 MB | downloadable |
| `reskit-test-data/placements` | RESKit turbine and module placement tables | 8 | 0.1 MB | downloadable |
| `reskit-test-data/sarah` | RESKit CM SAF SARAH-2 test fixtures, Aachen | 2 | 1.1 MB | downloadable |
| `reskit-test-data/srtm` | RESKit SRTM elevation test fixture, Aachen | 1 | 0.0 MB | downloadable |
| `reskit-test-data/synthetic` | RESKit synthetic test fixtures | 10 | 0.0 MB | downloadable |
| `reskit-turbine-library` | RESKit turbine library, 880 turbines (derived from thewindpower.net, licensed) | 880 | 0.7 MB | **listed only** |
| `thewindpower-power-curves` | Wind turbine power curves (thewindpower.net, licensed) | 1 | 0.9 MB | **listed only** |
| `thewindpower-turbines` | Wind turbine model table (thewindpower.net, licensed) | 1 | 1.4 MB | **listed only** |
| `thewindpower-windfarms` | Global wind farm table (thewindpower.net, licensed) | 1 | 21.2 MB | **listed only** |
| `trep-db` | Tool for Renewable Energy Potentials (TREP) Database | 120 | 173.9 MB | downloadable |

Datasets marked **listed only** are described here but cannot be downloaded
publicly: their bytes are licensed or institute-internal. The entry exists so a
workflow that needs them fails with a useful message rather than a mystery.

[dcache]: https://hifis.net/doc/cloud-services/Storage_DESY/
