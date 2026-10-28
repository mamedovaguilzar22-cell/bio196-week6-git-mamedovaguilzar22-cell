# RNA-seq Sample Metadata QC

**Author:** Giulzar Mamedova

## Purpose

This repository demonstrates a small RNA-seq sample metadata quality-control workflow.

## Project Structure

- `data/` contains the synthetic sample metadata file.
- `scripts/` contains the R script used to perform quality-control checks.

## How to Run

From the repository root, run:

`Rscript scripts/qc_check.R`

## Expected Result

The script checks that the required sample identifier columns are present, verifies that sample identifiers are not duplicated, and prints the number of samples in each condition.

## Data Policy

Raw sequencing data, private data, credentials, and large generated files must not be committed to this repository.
