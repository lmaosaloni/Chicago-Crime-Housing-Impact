
# Chicago Crime and Housing Analysis

## Overview
This project is part of the coursework for Class 418: Introduction to Data Science, by the team "KungFu Pandas". The aim is to investigate the relationship between crime rates and housing prices in Chicago, assessing the safety of neighborhoods and the impact of the COVID-19 pandemic on crime rates.

## Datasets
The analysis utilizes two main datasets:
- **Chicago Crime Data (2001 - Present)**: Available [here](https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-Present/ijzp-q8t2).
- **Zillow Housing Data**: Available [here](https://www.zillow.com/research/data/).

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/uic-cs418/group-project-kungfu-pandas.git
   ```
2. Navigate to the project directory:
   ```
   cd group-project-kungfu-pandas
   ```

## Usage
Ensure you have Python installed and run:
```
python -m pip install -r requirements.txt
```
Run the Jupyter notebooks within the repository to reproduce the analysis.

## Project Structure
- `CleaningPR.py`: Data cleaning and preprocessing.
- `ML_pr.py`: Machine learning operations.
- `Visualization*.py`: Scripts for data visualization.
- `EDA_pr.py`: Exploratory data analysis.
- `t_test.py`: Statistical testing scripts.

## Analysis
- **Data Cleaning**: Simplification and structuring of raw data into usable formats.
- **Exploratory Data Analysis (EDA)**: Initial data exploration to understand trends and patterns.
- **Machine Learning**: Logistic regression model to predict arrest probabilities.
- **Visualizations**: Various plots showing crime trends, housing prices, and their relationships.

## Findings
- An inverse relationship exists between housing prices and battery incidents.
- No significant relationship between theft rates and housing prices.
- Post-COVID data shows a decrease in theft but no significant change in battery rates.

## Contributors
- Raj Patel
- Ayush Jamindar
- Amrita Rajesh
- Saloni Mhatre
- Lakshmi Krishna

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
