import pandas as pd
import matplotlib.pyplot as plt

# Load the dataset
df = pd.read_csv('vgsales (2).csv')

# --- Project Title ---
PROJECT_TITLE = "Video Game Sales Analysis: Pre-2005 vs. Post-2005"

# --- Getting Started ---
GETTING_STARTED = """
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

"""

# --- Prerequisites ---
PREREQUISITES = """
### Prerequisites

What things you need to install the software and how to install them.

* Python 3.x ([https://www.python.org/downloads/](https://www.python.org/downloads/))
* Pandas library (install using pip: `pip install pandas`)
* Matplotlib library (install using pip: `pip install matplotlib`)
"""

# --- Installation ---
INSTALLING = """
### Installing

A step-by-step series of examples that tell you how to get a development environment running.

1.  Clone the repository:
    ```bash
    git clone [https://github.com/YourUsername/YourRepositoryName.git](https://www.google.com/search?q=https://github.com/YourUsername/YourRepositoryName.git)
    ```
2.  Navigate to the project directory:
    ```bash
    cd Your_Repository_Name
    ```
3.  Install the required libraries:
    ```bash
    pip install pandas matplotlib
    ```
4.  Ensure the `vgsales (2).csv` dataset is in the same directory as the Python script.
"""

# --- Running the Script ---
RUNNING_THE_SCRIPT = """
## Running the Script

Explain how to run the script and what the expected output is.

To execute the analysis, run the Python script:

```bash
python analyze_vgsales.py
