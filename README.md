# Housing Market Analysis — King County
Data-Driven Insights & Recommendations for a Budget-Constrained Home Buyer

# Project Overview

This project analyzes the King County housing market to help a specific client, Thomas Hansen, a father of five with a limited budget, find the most affordable and suitable areas to buy a home. Using exploratory data analysis, regression modeling, geospatial mapping, and neighborhood evaluation, the project identifies key drivers of housing value and recommends the best timing, location, and property characteristics for the client.

## Set up your Environment

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the notebooks.

### **`macOS`** type the following commands : 

- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
    ```
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```


*Note: If there are errors during environment setup, try removing the versions from the failing packages in the requirements file.*

