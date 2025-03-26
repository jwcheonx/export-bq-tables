## Overview

The `export_bq_tables` script exports all tables from a specified BigQuery dataset
as CSV files and downloads them to the local machine.

## Usage

1. Upload the script to your Cloud Shell home directory.
2. Grant execute permission: `chmod +x export_bq_tables`
3. Execute the script: `./export_bq_tables -h`

## Output

The script creates a directory at `~/bq_exports/<PROJECT_ID>/<DATASET_ID>_<TIMESTAMP>/`,
which contains CSV files for each table in the dataset.
