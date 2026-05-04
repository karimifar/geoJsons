# GeoJSON Data Repository

A collection of GeoJSON and JSON geographic data files used across Texas and Massachusetts health mapping projects.

## Files

| File | Description |
|------|-------------|
| `MassTowns.geojson` | Massachusetts towns (local coordinate system) |
| `MassTownsWGS84.geojson` | Massachusetts towns (WGS84 / standard lat-lng) |
| `c2016_zipcodes_inc_nodata.geojson` | Texas ZIP code boundaries (Census 2016) |
| `cnty2_lfex_estonly_3d.json` | Texas county life expectancy estimates (3-decimal precision) |
| `cnty_lfex_estonly_3d.json` | Texas county life expectancy (alternate county set, 3-decimal) |
| `zip_lfex_estonly_3d.json` | Texas ZIP-level life expectancy (3-decimal) |
| `zip_lfex_inconly_est_6d.geojson` | Texas ZIP life expectancy, income-only model (6-decimal precision) |
| `tcmhcc/cpan/inst-areas.geojson` | CPAN institution coverage areas |
| `tcmhcc/cpan/region-areas.geojson` | CPAN region boundaries |

## Usage

These files serve as geographic data sources for:
- [cpanmap](https://github.com/karimifar/cpanmap) — Texas CPAN institution map
- [peripanmap](https://github.com/karimifar/peripanmap) — Texas perinatal network map
- Life expectancy and health disparity mapping projects

## Coordinate System

All GeoJSON files use **WGS84** (EPSG:4326) unless otherwise noted in the filename.
