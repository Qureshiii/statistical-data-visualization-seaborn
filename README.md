| Multi-plots | MultiGridPlots | [`06_Multiplots/`](./06_Multiplots/) |
| Utility functions | Shared plotting utilities | [`07_Utility_Functions.ipynb`](./07_Utility_Functions.ipynb) |

<details>
<summary><strong>Browse the notebook list</strong></summary>

```text
Seaborn/
├── 01_Relational_Plots/
│   └── 01_Scatter+Line.ipynb
├── 02_Distribution_Plots/
│   ├── 01_Histogram.ipynb
│   ├── 02_KDE_Plot.ipynb
│   └── 03_Rug_Plot.ipynb
├── 03_Categorical_Plots/
│   └── 01_Categorical.ipynb
├── 04_Matrix_Plots/
│   ├── 01_Heatmap.ipynb
│   └── 02_Clustermap.ipynb
├── 05_Regression_Plots/
│   └── 01_Regression_plots.ipynb
├── 06_Multiplots/
│   └── 01_MultiGridPlots.ipynb
└── 07_Utility_Functions.ipynb
```

</details>

## Learning checklist

- [ ] Relational plots
- [ ] Distribution plots
- [ ] Categorical plots
- [ ] Matrix plots
- [ ] Regression plots
- [ ] Multi-plot layouts
- [ ] Utility functions

## Getting started

### Requirements

- Python 3
- JupyterLab or Jupyter Notebook
- Seaborn, Pandas, Matplotlib, and SciPy

### Install dependencies

```bash
python -m pip install seaborn pandas matplotlib scipy jupyterlab
```

On Windows, use `py` if `python` is not recognized:

```powershell
py -m pip install seaborn pandas matplotlib scipy jupyterlab
```

### Launch the notebooks

From the repository root, run:

```bash
jupyter lab
```

Open a notebook from the topic folders and run its cells in order. Keep the repository's directory structure intact so any relative file paths continue to work.

## Suggested workflow

1. Start with relational and distribution plots.
2. Continue through categorical, matrix, and regression visualizations.
3. Explore multi-plot layouts and utility functions after trying the individual plot types.
4. Change a parameter or data mapping, rerun the cell, and compare the figure.

## Contributing

Improvements to explanations, examples, and reproducibility are welcome. Keep notebooks focused, use descriptive filenames, and include the expected output or a short explanation when it helps readers understand a plot.

## License

This project is licensed under the [MIT License](LICENSE). The license applies to original code and documentation in this repository. Any third-party datasets or other included material may have separate terms.

---

<div align="center">
  <sub>Learn statistical visualization by exploring one plot family at a time.</sub>
</div>
