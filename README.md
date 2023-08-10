# DISCOVER Experiment Template
A template repo for DISCOVER experiments that users may fork or reference when creating experiments. Each experiment should follow this template for the highest chance of success when submitting to the DISCOVER infrastructure.

Each experiment should:

1. Be formatted as a GitHub repository based on this template.
2. Have a designated location for receiving experiment results, such as a shared Google Drive folder.

Once you submit an experiment, it will be transformed into a simple Docker application to help with experiment management and maintenance on the DISCOVER infrastructure. For this to work well, it's prudent to have detailed build and run instructions in your README.

If you are new to GitHub, we have compiled some helpful steps to get you started: (link here)

---

All code files should be stored in the `src/` folder and the primary execution file should be located in `src/main.py`. Please use the following outline as a guide for setting up your experiment repo README.

# Soil Data Collection
My experiment is intended to get a better understanding of the soil conditions at Northern Arizona University. This code accesses three SDI-12 sensors that are connected to a Stationary Node, namely the TEROS-12, MPS-6, and the 100K thermistor for ambient temperature.

# Installation
This program is dependant on pyserial, run the following command:
`pip install pyserial`

# Run
Since this program accesses the SDI-12 USB adapter, I usually call my program with `sudo`, run the following command to start my code:
`sudo python3 main.py`

# Results
Provide a cloud storage link for the DISCOVER Operator to upload your experiment results. This should also be included in the experiment details on the DISCOVER portal. Google Drive works well for this, just be sure to share it with anyone who has access to the link of your shared folder.

Cloud storage link: https://drive.google.com/drive/folders/1jorMT5u7E7JSW6Q5nnsQGnENOL5TnZ19?usp=sharing

To see this template applied to an actual experiment, check out the branches associated with this repository:
 - [RoverDemo experiment](https://github.com/DiscoverCCRI/DISCOVER-Experiment-Template/tree/RoverDemo)
