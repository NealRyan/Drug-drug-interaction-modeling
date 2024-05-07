# Overview

This project is an extension/recreation of the work done by Mohammad Hussain Al-Rabeah and Amir Lakizadeh to model drug-drug interactions. 

The original code can be found [HERE](https://github.com/Mohammad-Hussain95/GNN_DDI/tree/main)

# Result Replication

Please refer to the [Simplified DDI Model](https://github.com/NealRyan/Drug-drug-interaction-modeling/blob/main/Simplified_DDI_Model) notebook to observe the results of the model recreation. Note that by default training in this notebook is commented out (You can use control/command + / to block uncomment).

# How to Run

All of the code replicating our experiments are stored in the `Final_Report_Simplified_DDI_Model.ipynb` Jupyter notebook. To run the notebook we recommend:
* Using Python 3.10.12
* Using a clean python environment, such as via virtualenv.
  * To create one with virtualenv you can run: `python3 -m virtualenv venv`
    * If the virtualenv module isn't available run `python3 -m pip install virtualenv`
  * Activate the virutalenv with `source venv/bin/activate`
* We recommend installing Jupyter to run the notebook directly:
  * `pip install jupyter-client==8.6.1 jupyter-core==5.7.2`
* The notebook can now be directly ran. The notebook will auto-magically install all requirements to run itself.