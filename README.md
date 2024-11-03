# Python Cron Job for Service Management and Temporary Folder Cleanup

## Overview

This provides a step-by-step guide to setting up a Python script as a cron job on a Unix-based system. The script performs two task:
- Restarts a specified system service
- Clears a specified temporary folder

The cron job will run the script at a specific interval, ensuring automated management of the system service and cleanup of temporary files.


## Prerequisites

- A Unix-based operating system (Linux or MacOS).
- Python installed on the sytem.
- Sufficient permissions to manage services and set up cron jobs
- Basic knowledge of cron and Python scripting


## Objectives

1. Create a Python that:
    - Restarts a system service
    - Clears a specified temporary folder.
2. Set up a cron job to run the script at scheduled intervals.

## Steps
**Step 1: Create the Python Script**
1. Open your terminal and create a directory to store the Python script:
```
mkdir ~/cron_jobs
cd ~/cron_jobs
```
