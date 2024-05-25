# Startup Market Analysis

This project is a comprehensive analysis of the startup market, focusing on various aspects such as funding, valuation, revenue, and industry trends. It includes data cleaning, exploratory data analysis (EDA), and visualization using Python libraries like Pandas, Matplotlib, Seaborn, and Streamlit.

## Project Structure

- `Dashboard.py`: This file contains the Streamlit application that provides an interactive user interface for data visualization and analysis.
- `DataCleaning.py`: This script performs data cleaning and preprocessing tasks on the raw dataset.
- `ploting.py`: This file contains various plotting and visualization functions used in the Streamlit application.

## Dataset

The project utilizes a dataset containing information about startups, including company details, funding, valuation, revenue, industry, and other relevant attributes. The dataset is cleaned and preprocessed using `DataCleaning.py` before being used for analysis.

## Features

- **Data Cleaning and Preprocessing**: The `DataCleaning.py` script handles data cleaning tasks such as removing duplicates, handling missing values, and converting data types.
- **Exploratory Data Analysis (EDA)**: The project includes various visualizations and analyses to explore the dataset, such as histograms, bar charts, scatter plots, and correlation matrices.
- **Streamlit Dashboard**: The `Dashboard.py` file provides an interactive dashboard built using the Streamlit library. It allows users to filter data, visualize trends, and perform analysis based on different criteria.
- **Visualization**: The `ploting.py` file contains various plotting and visualization functions used in the Streamlit application, including line charts, bar charts, scatter plots, treemaps, and more.
- **Startup Analysis**: The project includes analyses of startup trends, funding evolution, industry distributions, and the impact of funding on startup growth.
- **Investor Location Analysis**: The project provides insights into the relationship between investor locations and industry preferences.

## Setup and Usage

1. Install the required Python libraries:
   - streamlit
   - pandas
   - matplotlib
   - seaborn
   - plotly

2. Download or clone the project repository.

3. Place the dataset file (e.g., `DataAnalysis.csv`) in the project directory.

4. Run the Streamlit application by executing the following command in your terminal or command prompt:

   ```
   streamlit run Dashboard.py
   ```

5. The Streamlit application will open in your default web browser, allowing you to interact with the dashboard and visualizations.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
