# PollNow Company Registry

Canonical company-registry datasets in normalized Parquet, built from official public registries.

| File | Source | Rows |
|---|---|---|
| nta.parquet | 国税庁法人番号 (Japan) | ~5.0M |
| ch.parquet | UK Companies House | ~5.6M |
| gleif.parquet | GLEIF Golden Copy LEI | ~1.9M |
| sirene.parquet | INSEE Sirene (France) | ~8.9M |

Schema: `source, external_id, name, name_en, name_alt, country_code, region, city, address, founded_year, kind`

Downloads are in [Releases](../../releases). Query directly with DuckDB httpfs.
