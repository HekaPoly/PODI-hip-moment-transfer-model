# PODI-hip-moment-transfer-model
This repo is for testing a sensor domain transfer for task agnostic hip estimation ML models for exoskeleton assistance.
# Project Structure

This repository is organized to separate raw data, analysis notebooks, generated figures, executable scripts, and reusable source code.

```text
├── data/
├── fig_output/
├── notebooks/
├── scripts/
└── src/
```

### `data/`

Contains datasets used throughout the project, including raw, processed, and intermediate data files.

### `fig_output/`

Contains figures, plots, and other visual outputs generated during data analysis and processing.

### `notebooks/`

Contains Jupyter notebooks used for exploratory analysis, data visualization, experimentation, and documenting analysis workflows.

### `scripts/`

Contains standalone scripts used to run processing pipelines, automate repetitive tasks, or execute specific analyses.

### `src/`

Contains the main reusable source code for the project, including functions, classes, and modules shared across notebooks and scripts.

## General Workflow

A typical workflow is:

1. Store or retrieve data in `data/`.
2. Develop and explore analyses in `notebooks/`.
3. Move reusable functionality into `src/`.
4. Use `scripts/` for repeatable or automated processing.
5. Save generated figures and visualizations in `fig_output/`.
