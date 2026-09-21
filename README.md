# humphreybao-pro.github.io
This repository includes a Python version analysis of penguin body mass and an R version analysis of iris petal length.

## Installation

Software required and versions used:
- Quarto: 1.10.18
- uv: 0.12.7
- R: 4.6.1
- Python: 3.14 (managed by uv)

## Build the website

Run these commands in a terminal:

```bash
git clone https://github.com/HumphreyBao-pro/humphreybao-pro.github.io.git
cd humphreybao-pro.github.io
uv sync
Rscript -e 'renv::restore(prompt = FALSE)'
uv run quarto render
uv run quarto preview
```

## Dataset

- Python: [Palmer Penguins](https://allisonhorst.github.io/palmerpenguins/),
  provided by the `palmerpenguins` package. Data license: CC0.
- R: [iris]
  included with R.

Network is needed to clone the repository and download dependencies.