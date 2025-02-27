# India Census Data Visualization

## Overview
This project is a data visualization tool for Indian census data using **Streamlit** and **Plotly**. It allows users to explore census data by selecting different states and parameters, visualizing the information on an interactive map.

## Features
- **State Selection:** Users can choose a specific state or view overall India.
- **Parameter Selection:** Two parameters can be selected for visualization.
- **Interactive Map:** The data is displayed on a scatter map using Plotly's mapbox.
- **Dynamic Filtering:** The map updates dynamically based on user selections.

## Technologies Used
- **Python**
- **Streamlit** for UI and dashboard development
- **Pandas** for data handling
- **Numpy** for numerical operations
- **Plotly** for interactive visualizations

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/india-census-viz.git
   cd india-census-viz
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```

## Usage
- Select a state from the sidebar dropdown.
- Choose the primary and secondary parameters for visualization.
- Click the "Plot Graph" button to view the interactive map.

## Dataset
The project uses an `india.csv` dataset containing:
- **State** and **District** names
- **Latitude** and **Longitude**
- **Census-related parameters**



