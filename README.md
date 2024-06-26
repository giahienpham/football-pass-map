# Messi Pass Map vs Real Betis

This project visualizes the passes made by Lionel Messi in a match against Real Betis using a pitch plot. The data is processed, and the passes are color-coded based on their success.

## Files

- **matches.csv**: Contains data on football matches, including various match statistics.
- **predict.ipynb**: Jupyter notebook for preprocessing match data and making predictions using a machine learning model.
- **pass.ipynb**: Jupyter notebook for visualizing passes using `mplsoccer`.

## Requirements

- Python 3.7+
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `mplsoccer`

## Setup

1. Clone the repository.
2. Install the required libraries using `pip`:
   ```sh
   pip install pandas numpy matplotlib mplsoccer
   ```
3. Ensure you have the data files (matches.csv, pass.ipynb) in the appropriate directory.

## Usage

### Running the Visualization

1. Open the pass.ipynb notebook in Jupyter Notebook or JupyterLab.
2. Execute the cells to generate the pitch plot and visualize Messi's passes.