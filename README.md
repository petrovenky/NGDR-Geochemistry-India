# NGDR-Geochemistry-India

A collection of geochemical datasets obtained from the **National Geoscience Data Repository (NGDR), Government of India**, organized by sample type and state.

The repository currently contains **soil C-horizon** and **stream sediment** geochemical datasets, including state-wise source archives and consolidated Parquet datasets for large-scale analysis.

## Data Statistics

| Sample Type     | Coverage | Records |
| --------------- | -------- | ------: |
| Soil C-Horizon  | India    | 39324 |
| Stream Sediment | India    | 450575 |

Detailed state-wise sample counts, geographic coverage, sampling density, and dataset sizes are provided in the `metadata/` directory.

## Datasets

* **Soil C-Horizon Geochemistry**
* **Stream Sediment Geochemistry**

State-wise source datasets are retained as ZIP archives, while consolidated datasets are provided in **Parquet format**.

## Structure

```text
data/
├── soil/
│   ├── raw/
│   └── parquet/
│
└── stream_sediment/
    ├── raw/
    └── parquet/

metadata/
processing/
docs/
```

## Source

**National Geoscience Data Repository (NGDR)**
Government of India

## Applications

The datasets can support:

* Geochemical mapping
* GIS and spatial analysis
* Statistical analysis
* Mineral exploration
* AI/ML-based geoscientific modelling

## Data & Attribution

The original datasets are sourced from NGDR and are **not relicensed by this repository**. Users should follow the applicable NGDR terms, conditions, and attribution requirements.

See `metadata/` for dataset-specific information and `processing/` for processing workflows.
