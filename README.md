# Data Visualization

A collection of Jupyter notebooks demonstrating common techniques for exploring and visualizing data with Python.

## Notebooks

| Notebook | Topics |
| --- | --- |
| `DataVisualization/MatplotLib.ipynb` | Matplotlib basics, subplots, figure and axes objects, plot types, styling, and images |
| `DataVisualization/Distributionplot.ipynb` | Seaborn histograms, joint plots, pair plots, and rug plots |
| `DataVisualization/Categoricalplots.ipynb` | Seaborn count, bar, box, violin, strip, and swarm plots |
| `DataVisualization/Regression.ipynb` | Seaborn regression plots and grouped visualizations |
| `DataVisualization/Matrixplot.ipynb` | Seaborn heat maps, cluster maps, and pivot tables |
| `DataVisualization/plotlyandcufflinks.ipynb` | Interactive Plotly charts with Cufflinks |

The Matplotlib notebook also uses `DataVisualization/images.jpeg` for its image examples.

## Requirements

- Python 3
- Jupyter Notebook
- NumPy, pandas, Matplotlib, Seaborn, Plotly, and Cufflinks

Install the dependencies from a terminal:

```bash
python -m pip install jupyter numpy pandas matplotlib seaborn plotly cufflinks
```

## Run the notebooks

From the repository root, start Jupyter:

```bash
jupyter notebook
```

Open a notebook in `DataVisualization/` and run its cells. Some examples use Seaborn's sample datasets, which may need to be downloaded the first time and therefore require an internet connection.
