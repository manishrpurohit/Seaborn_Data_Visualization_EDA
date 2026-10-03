# Seaborn Data Visualization EDA

This project contains a Jupyter notebook that demonstrates a wide range of exploratory data analysis and data visualization techniques using Python, Matplotlib, and Seaborn.

## Contents

- Notebook: `Eda_sns_data_visualisation.ipynb`
- Dataset examples: `diamonds`, `tips`, and `flights` from Seaborn
- Visual styles: histograms, KDE plots, pie charts, scatter plots, heatmaps, box plots, violin plots, radar charts, and more

## Project Goal

The notebook is designed to showcase practical EDA patterns and visually explain distributions, relationships, and trends in sample datasets.

## Requirements

Install the following Python packages:

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

## Run the Notebook

1. Open the project folder in VS Code or Jupyter.
2. Launch Jupyter Notebook or VS Code Notebook support.
3. Open `Eda_sns_data_visualisation.ipynb`.
4. Run all cells in order.

## Notes

- Some visualizations may take a few seconds to render depending on dataset size.
- If Matplotlib raises compatibility warnings, ensure you are using a recent version.
- The notebook includes a wide set of chart types and is useful for learning and experimentation.

## Example usage

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Load datasets
Diamonds = sns.load_dataset('diamonds')
tips = sns.load_dataset('tips')
flights = sns.load_dataset('flights')

sns.histplot(Diamonds['carat'], bins=30, kde=False)
plt.show()
```

## License

This project is intended for educational and learning purposes.
