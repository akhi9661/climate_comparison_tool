# Climate Data Visualization Tool

This repository contains an interactive data visualization tool for analyzing and comparing rainfall and temperature data from multiple sources (BOM, NASA-POWER, and ERA5). The tool provides an intuitive interface to explore correlations, visualize trends, and perform lagged accumulations for selected sites.

## Features

- **Dynamic Data Loading**:
  - Load rainfall or temperature data directly from online CSV files.
  - Automatically updates based on the selected variable type (Rainfall or Temperature).

- **Customizable Widgets**:
  - Select data type (`Rainfall` or `Temperature`) via toggle buttons.
  - Choose data source (e.g., `NASA-POWER` or `ERA5`).
  - Specify lag duration for rolling correlations.
  - Filter by site or BOM station.

- **Interactive Plotting**:
  - Scatterplots to visualize original and lagged rolling correlations.
  - Displays Spearman correlation coefficients for original and rolling datasets.
  - Configurable plot titles, axis labels, and legends.

- **Responsive Layout**:
  - Toggle buttons and widgets arranged in a user-friendly layout for seamless interaction.
  - Clear separation between controls and plot output.

---

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.7+
- Required Python packages:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `ipywidgets`
  - `scipy`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/climate-comparison-tool.git
   cd climate-comparison-tool

 2. Install the necessary packages  

## Usage
1. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook  
2. **Open the Notebook**: After running the Jupyter Notebook server, navigate to the notebook file in your browser and open it.

4. **Use the Widgets**: Interact with the tool using the intuitive widgets provided:
   - **Variable Type**: Use toggle buttons to switch between `Rainfall` and `Temperature`. This dynamically loads the relevant data.
   - **Site/Station Selection**: Use the dropdown to filter the data by site or BOM station.
   - **Lag Duration**: Adjust the slider to specify the number of days for rolling lag analysis (1–30 days).
   - **Source Selection**: Choose between `NASA-POWER` and `ERA5` as the data source for visualization.
   
5. **Visualize the Data**: After making your selections:
   - View the scatterplot comparing BOM data with the selected source.
   - Analyze original and rolling correlations (Spearman coefficients are displayed on the plot).

---

## Layout

- **Left Column**:
  - Contains the **toggle buttons** for selecting the variable type (`Rainfall` or `Temperature`).

- **Right Column**:
  - Widgets for refining the data and plot:
    - **Row 1**: 
      - `Site/Station Selection` dropdown.
      - `Lag Duration` slider.
    - **Row 2**:
      - `Site/Station` widget.
      - `Source Selection` dropdown.


