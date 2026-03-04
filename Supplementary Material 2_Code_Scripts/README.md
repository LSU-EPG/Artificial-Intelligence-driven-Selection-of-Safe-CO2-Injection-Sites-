# node_attribute

This repo builds edge lists between:
- sink nodes (from an Excel file),
- candidate nodes (from two shapefiles),
- population clusters / tracts (from the same Excel file),
- CO2 sources (from a source shapefile),
- pipelines (from a pipeline shapefile),

and merges the resulting edge lists into one `merged_edge_list.csv`.

## Folder conventions
- Put input files in `data/raw/` (see `data/README.md`).
- Generated CSVs are written to `outputs/`.

## Quickstart

```bash
python -m venv .venv
# activate your venv
pip install -r requirements.txt
pip install -e .

python scripts/run_all.py
```

## Notes
- All paths are defined in `src/node_attribute/config.py`.
- No absolute paths are used in the codebase.
