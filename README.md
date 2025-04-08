# French Cities Visualization: Population & Area Distribution
This project visualizes **French cities** with a population greater than 10,000 using **Python and Matplotlib**. The dataset contains geographical (latitude, longitude), demographic (population), and physical (area, altitude) data for French communes.

## 📈 Features
- **Filtering**: Cities with a population > 10,000

- **Scatter plot visualization:**

  - Longitude and latitude determine the position

  - Color reflects population size (logarithmic scale)

  - Size of points corresponds to city area (in km²)

- **City labels:** Displaying names for cities with population > 50,000

- **Legend:** Explains city size variations based on area

- **Clean and readable layout:** Titles, axis labels, grid, and colorbar

## 🛠️ Technologies Used
- **Python:** Main programming language

- **Pandas:** Data manipulation and filtering

- **Matplotlib:** Data visualization

- **NumPy:** For numerical operations

## 📊 Dataset
The dataset is a CSV file containing the following columns:

- **Postal Code:** Unique identifier for each city

- **x:** Longitude

- **y:** Latitude

- **population:** City population

- **surface:** City area (in km²)

- **place:** City name

## 🔍 Project Objectives
_ Learn to filter and manipulate **geospatial and demographic data** using Pandas

_ **Visualize cities' population and area** distribution with scatter plots

_ **Enhance data presentation** through color maps, legends, and annotations

_ Understand how to handle real-world datasets and represent them meaningfully

## 📌 Installation
1. Clone this repository:

```bash

git clone https://github.com/yourusername/French-Cities-Visualization.git
```

2.Install the required dependencies:

```bash

pip install pandas numpy matplotlib
```

## 📂 How to Run

1. Download or place the dataset (`french_cities.csv`) in the project folder.

2. Open and run the Jupyter Notebook (`Data Visualization french_cities.ipynb`):

```bash
jupyter notebook
```

This will open the notebook in your browser, and you can execute the code cells to generate the scatter plot showing the cities with population > 10,000, with area and population visualized.

## 🎯 Future Improvements

- Interactive visualization using Plotly
- Advanced filtering options (e.g., based on altitude, density)
- Additional data analysis (e.g., identifying urban vs rural trends)

## 🔑 License

This project is open source and available under the MIT License. See the LICENSE file for more details.
