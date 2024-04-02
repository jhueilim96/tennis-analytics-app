# Tennis Analytics Dashboard App 🎾📊

Welcome to the Tennis Analytics Dashboard project! This project aims to provide comprehensive insights into tennis analytics for the major championships of 2023.

For Data Engineering, please visit [tennis-analytics-dbt](https://github.com/jhueilim96/tennis-analytics-dbt).

### Contributors

- Tennis Data Analyst - _[Azura Aziz](https://github.com/azuraaziz)_
- Data Engineer - _[JH](https://github.com/jhueilim96)_

### Purpose

This project serves as a demonstration of the skillset

- data analysis & dashboard building
- python and SQL proficiency
- container application deployment

## Features & Technology

- **Interactive Visualization**: Explore a variety charts and graphs built using **streamlit** to understand player performances and match trends.

- **Data Query**: Data is retrieved using a local datawarehouse method powered by **DuckDB** with its suporior performance to perform analytics data querying at edge device.

- **Container Deployment**: The application is packaged as a container image using **docker** and deployment with **Azure Container Apps**.

## Requirements

To run the Tennis Analytics Dashboard locally, you'll need to have the following dependencies installed:

- Python 3.10
- Streamlit
- DuckDB
- Other necessary Python libraries (specified in requirements.txt)

You can install the required dependencies using [uv](https://pypi.org/project/uv/) (a new performant python package manager) :

```bash
pip install uv
uv venv -p "3.10"
source .venv/Scripts/activate
uv pip install -r requirements.txt
```

## Usage

To launch the dashboard, navigate to the project directory and run the following command:

```bash
cd app
streamlit run main.py
```

This will start a local server, and you can access the dashboard through your web browser.

## Acknowledgements

- All Tennis ATP data are credited to
  - [ultimatetennisstatisic](https://www.ultimatetennisstatistics.com/)
  - [JeffSackmann](https://github.com/JeffSackmann/tennis_atp)

## Contact

For any inquiries or feedback regarding the Tennis Analytics Dashboard project, feel free to contact contributors. We'd love to hear from you!
