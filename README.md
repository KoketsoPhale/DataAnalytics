Include:
# Overview
This repository demonstrates a complete data analysis workflow, from exploratory data analysis and data cleaning to statistical hypothesis testing and data visualisation. The notebooks combine theoretical explanations of key data analysis concepts with practical Python implementations, providing both the reasoning behind each step and the code used to perform the analysis.

The repository includes:

* **Exploratory Data Analysis (EDA):** Investigation of the dataset's structure, variables, distributions, and potential data quality issues.
* **Data Cleaning:** Identification and treatment of missing values, inconsistencies, duplicates, and other data preparation tasks.
* **Hypothesis Testing:** Investigation of a specific analytical question using an appropriate statistical hypothesis test, including interpretation of the results.
* **Data Visualisation:** Creation of visualisations to communicate insights and support data-driven conclusions.

The project is intended to showcase the end-to-end process of conducting a data analysis project while demonstrating both technical proficiency and analytical thinking.


# Dataset description

The dataset is available for download at,
https://www.kaggle.com/datasets/bhadramohit/customer-shopping-latest-trends-dataset?resource=download 

The dataset offers a comprehensive view of consumer shopping trends, aiming to uncover patterns and behaviors in retail purchasing. It contains detailed transactional data across various product categories, customer demographics, and purchase channels. Key features may include:

Transaction Details: Purchase date, transaction value, product category, and payment method.
Customer Information: Age group, gender, location, and loyalty status.
Shopping Behavior: Frequency of purchases, average spend per transaction, and seasonal trends.

# Results
The results from exploring the dataset can be found in the reports folder. The reports are named in accordance to the corresponding notebooks.

# Installation and Setup

Follow the steps below to set up this project on your local machine.

## Prerequisites

Before you begin, ensure that the following software is installed:

* Python 3.10 or later
* Git
* Visual Studio Code (optional, but recommended)

You can verify your installations by running:

python --version
git --version

---

## 1. Clone the Repository

Open a terminal and navigate to the directory where you would like to store the project.

Clone the repository:
git clone <repository-url>

Navigate into the project directory:
cd <repository-name>
## 2. Create a Virtual Environment

Create a new virtual environment named `venv`:

### macOS / Linux
python3 -m venv venv

### Windows
python -m venv venv
---

## 3. Activate the Virtual Environment

Activate the newly created virtual environment.

### macOS / Linux
source venv/bin/activate

### Windows (Command Prompt)
venv\Scripts\activate

### Windows (PowerShell)
.\venv\Scripts\Activate.ps1

Once activated, your terminal prompt should display `(venv)` at the beginning of the line.

## 4. Install Project Dependencies
Install all required Python packages using the provided `requirements.txt` file:

pip install -r requirements.txt

Depending on your internet connection, this may take a few minutes.

## 5. Open the Project in VS Code (Optional)
Launch Visual Studio Code from the project directory:

code .

Select the project's Python interpreter:

1. Open the Command Palette (`Ctrl + Shift + P` on Windows/Linux or `Cmd + Shift + P` on macOS).
2. Search for **Python: Select Interpreter**.
3. Select the interpreter located inside the `venv` folder.

## 6. Verify the Installation

To confirm that the dependencies were installed successfully, run:
pip list


You should see the project dependencies listed in the output.
## 7. Running the Project

After activating the virtual environment, you can run the notebooks as required.

python main.py

or launch any Jupyter notebooks included in the repository.

## Deactivating the Virtual Environment

When you are finished working on the project, deactivate the virtual environment:

deactivate

