# Business Intelligence (BI) Project - University Course

This project is part of a university course aimed at providing specialized skills for designing and managing modern Business Intelligence (BI) infrastructures. The project is divided into four parts, each contained in a distinct folder and aimed at a specific objective.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
  - [Data Preprocessing](#data-preprocessing)
  - [Visualization with Streamlit](#visualization-with-streamlit)
  - [Visualization with PowerBI](#visualization-with-powerbi)
  - [Process Simulation with Bonita](#process-simulation-with-bonita)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

The course aims to provide specialized skills for designing and managing modern BI infrastructures supporting directional information systems. It covers open-source and commercial BI suites, Data Mining methodologies and techniques, and modern ERP/CRM technologies supporting operational business processes. Furthermore, it addresses the methodological principles of some phases of the lifecycle of an Information System, focusing not only on technological aspects but also on organizational and economic contexts, including assessment and benchmarking issues.

## Project Structure

The project is divided into the following four parts:

### Data Preprocessing

Contained in the `Preprocessing` folder, this part of the project deals with data preprocessing, including cleaning, transforming, and preparing data for analysis.

### Visualization with Streamlit

Contained in the `Dashboard` folder, this part of the project uses Streamlit to create an interactive data visualization dashboard.

### Visualization with PowerBI

Contained in the `PowerBIDashboard` folder, this part of the project uses PowerBI to create interactive dashboards and reports.

### Process Simulation with Bonita

Contained in the `Bonita` folder, this part of the project represents and simulates a business process using Bonita BPM. The example used is the business process behind the production of products for a Fast Fashion company.

## Dataset

The dataset used in this project contains measurements of humidity, temperature, and pests in a cultivation. It is used in the first three parts of the project as follows:

- **Data Preprocessing**: The raw data is cleaned and transformed for analysis.
- **Visualization with Streamlit**: The preprocessed data is visualized through an interactive dashboard created with Streamlit.
- **Visualization with PowerBI**: The preprocessed data is further analyzed and visualized using PowerBI.

## Installation

The steps required to install and configure each part of the project are described in the respective folders. Here is a general guide:

1. Clone the repository
    ```bash
    git clone https://github.com/FabioBoccia/Information-Systems-and-Business-Intelligence.git
    cd bi-project
    ```

2. Follow the specific instructions for each part of the project:
    - [Data Preprocessing](./Preprocessing/README.md)
    - [Visualization with Streamlit](./Dashboard/README.md)
    - [Visualization with PowerBI](./PowerBIDashboard/README.md)
    - [Process Simulation with Bonita](./Bonita/README.md)

## Usage

Details on how to use each part of the project are provided in the respective README files within the specific folders.

### Example of using Streamlit

```bash
# Enter the Streamlit folder
cd Dashboard

# Install the dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py
