README for Cyclecast-Projet:

Introduction
This repository contains a Python project for interacting with the JcDecaux API to collect and analyze data from bike-sharing stations. It includes scripts for data collection, analysis, and visualization.

Prerequisites
Before running the project, ensure you have the following installed:

Python 3.x
MongoDB
Required Python libraries: pymongo, requests, matplotlib, numpy

---------------------------------------------------------------------------------

Installation
1. Clone the Repository:

2. Install Dependencies:
It's recommended to use a virtual environment:
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install required packages:
pip install pymongo requests matplotlib numpy

3. Set Up MongoDB:
Ensure MongoDB is installed and running on your system.
By default, the project connects to MongoDB at mongodb://localhost:27017/. Adjust the connection settings in the script if your setup is different.

4. API Key Configuration:
Obtain an API key from JcDecaux.
Replace the key variable value in the script with your API key:
key = "YOUR_API_KEY_HERE"

---------------------------------------------------------------------------------
Running the Scripts

1) Data Collection:
Run the data collection script to fetch data from the JcDecaux API and store it in MongoDB:
python script_name.py  # replace with the actual script name for data collection

2) Data Analysis and Visualization:
After collecting data, you can run the analysis and visualization scripts:
python analysis_script.py  # replace with the actual name of the analysis script

3) Additional Scripts:
For other functionalities (like specific data visualizations), run the respective scripts in a similar manner.


###       Troubleshooting
- Connection Issues: If you face issues connecting to MongoDB, ensure MongoDB is running and the connection URL in the script is correct.
- API Key: Issues related to the JcDecaux API key (like limits or invalid key) will need to be resolved by generating a new key or contacting JcDecaux support.

---------------------------------------------------------------------------------











