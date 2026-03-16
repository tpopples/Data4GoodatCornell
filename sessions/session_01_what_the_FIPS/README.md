# Session 01 — Geography & Data Levels

This session introduces how **geography shapes data analysis and policy insights**. We focus on understanding what a row represents, how geography is encoded, and why aggregation choices matter.

## What We Cover

- U.S. census geography hierarchy (block → tract → county → state)
- Identifying the **unit of analysis** in a dataset
- Using geographic identifiers (FIPS codes)
- Aggregating data to appropriate geographic levels
- Introduction to the Modifiable Areal Unit Problem (MAUP) and gerrymandering


## Files

- **Slide deck** — concepts and discussion prompts used in the session
- **`build_block_level_dataset.ipynb`**  
  Pulls 2020 Census block-level population data via the Census API


## Data Notes

- Raw Census data is not committed to the repo
- All datasets are reproducible from the provided code
- Datasets used in session will be availablein the data folder

## Key Idea

> Every dataset assumes a geography.  
> That choice shapes what the data can (and cannot) tell us.
