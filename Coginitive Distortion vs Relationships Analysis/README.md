## Code

The code is organized into the following notebooks, structured under a common directory `supplementary/`:

- `notebook_layer1.ipynb` – Contains code for data preprocessing, relation extraction, layer 1 clusters of the relationships
- `notebook_layer2.ipynb` – Contains analyses layer 1, layer 2 clusters (subclusters of layer 1), visualizations, and statistical analysis
- `notebook_layer3.ipynb` – Contains layer 3 clusters (subclusters of layer 2), visualizations, and statistical analysis
- `triples_df` - Relationship triples dataframe for running `notebook_layer1` and `notebook_layer2`

Each notebook is self-contained and includes explanations and outputs for reproducibility.

- `requirements.txt` – Lists the required Python packages and versions.
- `LICENSE` – States the open-source license used (MIT).
- `README.md` – This file, explaining the structure and usage.

All code is written in Python and was developed and tested on Google Colab with Python 3.11.13.

## How to Run

To reproduce the results:

1. Create a virtual environment or open a Colab notebook (https://colab.research.google.com).
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt


