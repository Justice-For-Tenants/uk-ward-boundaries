# uk-administrative-boundaries

## Purpose

Simplified UK Ward and Local Authority District boundary GeoJSON files, sized for Metabase (< 5 MB per file).

## Accessing

Each snapshot is published via GitHub Pages at:

```
https://justice-for-tenants.github.io/uk-ward-boundaries/<YEAR>/<MONTH>/<FILENAME>.geojson
```

Where `<FILENAME>` is either `wards` or `local_authority_districts`.

## Available Boundary Files

| Year | Month    | Type                      | URL                                                                                          |
|------|----------|---------------------------|----------------------------------------------------------------------------------------------|
| 2023 | December | Wards                     | https://justice-for-tenants.github.io/uk-ward-boundaries/2023/december/wards.geojson          |
| 2023 | December | Local Authority Districts | https://justice-for-tenants.github.io/uk-ward-boundaries/2023/december/local_authority_districts.geojson |
| 2024 | December | Wards                     | https://justice-for-tenants.github.io/uk-ward-boundaries/2024/december/wards.geojson          |
| 2024 | December | Local Authority Districts | https://justice-for-tenants.github.io/uk-ward-boundaries/2024/december/local_authority_districts.geojson



## Usage in Metabase

1. In Metabase: **Admin Settings → Maps → Add a map**  
2. Set **URL** to the desired GeoJSON (e.g. the Wards or Local Authority Districts file for that snapshot).  
3. Give the layer a descriptive **Name** (e.g. “UK Wards Dec 2023”).  
4. For **Region identifier**, choose the ward or LAD code property (e.g. `wd23cd` for wards, `lad23cd` for districts).  
5. For **Display name**, choose the matching name property (e.g. `wd23nm` or `lad23nm`).  
6. Save.

## License & Attribution


```text
Source: Office for National Statistics licensed under the Open Government Licence v.3.0
Contains OS data © Crown copyright and database right 2024
Contains OS data © Crown copyright and database right 2025
```

---

> **Note**: All GeoJSON files here derive from the ONS “Wards (MMMM YYYY) Boundaries UK BSC” and “Local Authority Districts (MMMM YYYY) Boundaries UK BSC” datasets, simplified via mapshaper to meet Metabase’s 5 MB limit.

