# Tutorials for data modeling with FIWARE

The tutorials showcase how to create data models for specific use cases and integrate these models with FIWARE-based platforms.
We provide examples for:
1. [Buildings automation](example_weatherstation_buildings)
2. [Electrical grid operation and monitoring](example_electrical_grid )
3. [District heating](examples_district_heating)

All tutorials are given in form of Jupyter Notebook. The following guideline provides instructions for setting up your environment and launching Jupyter Notebook.

## Prerequisites

- Python installed on your system
- pip package manager

## Setup Instructions

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/N5GEH/n5geh.tutorials.data_model.git
    ```

2. Navigate to the project directory:

    ```bash
    cd n5geh.tutorials.data_model
    ```

3. Install the required dependencies using pip:

    ```bash
    pip install -r requirements.txt
    ```
>Note: If you are using conda environment, you need to create a kernel for your conda environment: 
> ```bash
> python -m ipykernel install --user --name=<your_environment_name>
> ```

## Launching Jupyter Notebook

1. Once the dependencies are installed, launch Jupyter Notebook by running the following command in your terminal:

    ```bash
    jupyter notebook
    ```

2. Your default web browser should open automatically, displaying the Jupyter Notebook dashboard.

3. Navigate to the notebook file you want to work on (e.g. ``use_case_specific_models.ipynb``) and click on it to open.

4. You can now interact with the notebook, running cells and editing code as needed.
