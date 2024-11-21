
# GDP Dashboard Project

This Streamlit-based  dashboard visualizes global GDP data sourced directly from the World Bank Open Data, providing a free and reliable resource for economic insights.

You can check it out here: [Open](https://world-gdp-dashboard.streamlit.app/)

## Features

- 🌍 Explore GDP Trends
- 📊 Filter and Compare
- 🛠 Metrics displays

### Libraries
  - **Python**
  - **Streamlit**: For building the app interface.
  - **Pandas**: For data manipulation.
  - **Pathlib**: For file path management.



## Project Structure

```plaintext
gdp-dashboard/
│
├── app.py              # Main application script.
├── data/
│   └── gdp_data.csv    # GDP data file
├── README.md           # Project documentation.
├── requirements.txt    # List of Python dependencies.
└── ...
```

## Usage 

1. **Set the Year Range**: Use the slider to specify the range of years to analyze.
2. **Select Countries**: Choose one or more countries from the dropdown menu.
3. **View Visualizations**:
   - Line chart displays GDP trends over the selected years.
   - Metrics summarize GDP and growth rates for the selected countries.


## Acknowledgments

- **Data Source**: [World Bank Open Data](https://data.worldbank.org/)
