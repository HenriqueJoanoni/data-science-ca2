# NBA Player Performance Prediction

This project aims to predict NBA player performance metrics, with a particular focus on forecasting points per game (
PPG) in future seasons using historical career statistics and performance trends. The project follows a data science
workflow, progressing through business understanding, data mining, cleaning, exploration, feature engineering,
predictive modelling, and presentation of findings.

## Contents

- [NBA Player Performance Prediction](#nba-player-performance-prediction)
  - [Contents](#contents)
  - [Objective](#objective)
  - [Business Context](#business-context)
  - [Project Steps](#project-steps)
  - [How to Run](#how-to-run)
  - [Dependencies](#dependencies)
  - [Authors](#authors)
      - [This project is academic and uses public NBA data for the purpose of studying and demonstrating data science techniques applied to sports.](#this-project-is-academic-and-uses-public-nba-data-for-the-purpose-of-studying-and-demonstrating-data-science-techniques-applied-to-sports)

## Objective

To develop a robust predictive model for estimating NBA players' PPG, identifying key performance indicators, and
providing actionable insights for teams, coaches, and analysts.

## Business Context

Accurate player performance prediction is crucial for:

- Contract negotiations and salary cap management
- Draft strategy and talent acquisition
- Game strategy and rotation decisions
- Injury prevention and load management
- Applications in sports betting, fantasy sports, and sports media

## Project Steps

1. **Business Understanding**: Problem definition, response variable specification, and context.
2. **Data Mining**: Data collection via [nba_api](https://github.com/swar/nba_api).
3. **Data Cleaning**: Handling missing values, inconsistencies, and outliers.
4. **Data Exploration**: Statistical analysis and data visualisation.
5. **Feature Engineering**: Creation and selection of relevant variables.
6. **Predictive Modelling**: Building and validating regression models.
7. **Presentation of Findings**: Generating insights and recommendations.

## How to Run

1. **Clone the repository**:
   ```sh
   git clone https://github.com/HenriqueJoanoni/data-science-ca2.git
   cd nba-player-performance
   ```

2. **Create and activate a virtual environment**:
    ```sh
    python3 -m venv nba_env
    source nba_env/bin/activate
    ```

3. **Install Dependencies**:
   ```sh
    pip install nba_api
    pip install -r requirements.txt
    ```

4. **Run the notebook**:
    ```sh
    jupyter notebook nba_data_mining.ipynb
    ```

## Dependencies

- Python 3.12+
- nba_api
- pandas
- jupyter

## Authors

    - Jose Henrique Pinto Joanoni
    - Shane Smyth

#### This project is academic and uses public NBA data for the purpose of studying and demonstrating data science techniques applied to sports.