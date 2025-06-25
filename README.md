# uk-ward-boundaries

## Purpose

Simplified UK ward boundary GeoJSON.

## Accessing

Each snapshot file is published via GitHub Pages at:

```
https://justice-for-tenants.github.io/uk-ward-boundaries/<YEAR>/<FILENAME>.json
```

For example:

- December 2023: [https://justice-for-tenants.github.io/uk-ward-boundaries/2023/december.json](https://justice-for-tenants.github.io/uk-ward-boundaries/2023/december.json)
- December 2024:       [https://justice-for-tenants.github.io/uk-ward-boundaries/2024/december.json](https://justice-for-tenants.github.io/uk-ward-boundaries/2024/december.json)

## Available Ward Boundary Files

| Year | Snapshot | URL                                                                                                                                                        |
| ---- | -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 2023 | December | [https://justice-for-tenants.github.io/uk-ward-boundaries/2023/december.json](https://justice-for-tenants.github.io/uk-ward-boundaries/2023/december.json) |
| 2024 | December | [https://justice-for-tenants.github.io/uk-ward-boundaries/2024/december.json](https://justice-for-tenants.github.io/uk-ward-boundaries/2024/december.json) |


## Usage in Metabase

1. In Metabase: **Admin Settings → Maps → Add a map**
2. Set **URL** to your chosen file, e.g.:
   ```
   https://justice-for-tenants.github.io/uk-ward-boundaries/2023/december.json
   ```
3. Give the layer a name (e.g. “UK Wards Dec 2023”) and save.


## License & Attribution

```
Source: Office for National Statistics licensed under the Open Government Licence v.3.0
Contains OS data © Crown copyright and database right 2023
Contains OS data © Crown copyright and database right 2024
```


---

> **Note**: All GeoJSON files in this repo are based on the ONS “Wards (MMMM YYYY) Boundaries UK BSC” dataset, simplified via mapshaper to meet Metabase’s 5 MB cap.

