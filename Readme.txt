YouTube Analysis

This repository contains a Jupyter Notebook dedicated to analyzing YouTube channel data. The analysis focuses on extracting and visualizing statistics from a specific YouTube channel using the YouTube Data API.
Contents

    youtube_analysis.ipynb: The Jupyter Notebook containing the code for data extraction and analysis.
    beluga.json: A JSON file storing the YouTube channel statistics.
    beluga.csv: A CSV file containing the channel statistics for further analysis.

Prerequisites

To run the notebook smoothly, ensure you have the following Python packages installed:

    json
    requests
    jdc
    tqdm
    pandas
    seaborn
    matplotlib

You can install these packages using pip:

pip install requests jdc tqdm pandas seaborn matplotlib

Credentials

To access the YouTube Data API, the following credentials are used:

    API Key: AIzaSyANM5Hb3bpK9frCy3VK7bvXmDqQ5dfo5Ps
    Channel ID: UCmSp4bDxS9R0jpeZEvkut2g

Note: Ensure that the API key has the necessary permissions and is active for successful data retrieval.
Usage

    Clone the repository:

git clone https://github.com/maddy333/YoutubeAnalysis.git
cd YoutubeAnalysis

Install the required packages (if not already installed):

pip install requests jdc tqdm pandas seaborn matplotlib

Open the Jupyter Notebook:

    jupyter notebook youtube_analysis.ipynb

    Run the notebook cells to perform data extraction and analysis.

Analysis Overview

The notebook performs the following tasks:

    Data Extraction: Retrieves channel statistics and video details using the YouTube Data API.
    Data Storage: Saves the extracted data into JSON and CSV formats for record-keeping and further analysis.
    Data Visualization: Utilizes seaborn and matplotlib to create visual representations of the data, aiding in understanding trends and patterns.

Notes

    Ensure that your environment has internet access to connect to the YouTube Data API.
    Handle the API key securely and avoid exposing it in public platforms.
    The provided API key and channel ID are specific to this analysis; for analyzing other channels, replace the channel_id variable in the notebook with the desired channel's ID.

