# Classification of pathological types of lung cancer from CT images

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Installation](#installation)
5. [Usage](#usage)


## Introduction
In this Project we are helping Cancer Patients to detect the disease in Early Stages. Using AIMl we create and implement heuristic deep learning algorithms, that are trained specially for detecting cancerous lung nodules in their early stage. And to ensure erroneous result easily accessible as a service or interface,so that non-IT person like doctors can utilize it.

## Features
- Cancer Detection : The system can detect Cancer Nodules in an CT Scan Image and track the Cancereous Cells.
- Result: Analyze the Image and Detect whether Patient CT Scan Image is cancereous or not.



## Requirements
- Python 3.x
- OpenCV
- CNN Algorithm
- MaxPool
- Numpy
- Pandas
- Matplotlib (for visualization)

## Installation
1. Clone this repository to your local machine.
2. Install the required dependencies using `pip` or `conda`:
   ```bash
   pip install opencv-python numpy pandas matplotlib
   ```
   or
   ```bash
   conda install opencv  numpy pandas matplotlib
   ```
3. Download the pre-trained model weights (if required) and place them in the appropriate directories.

## Usage
1. Open a terminal or command prompt and navigate to the project directory.
2. Run the Cancer Detection application:
   ```bash
   python Cancer_Detection.py
   ```
3. The application will start processing the image feed and display the results, including Cancer detection,  and other insights.


## Contributing
Contributions to this project are welcome! If you find any issues or want to enhance the system's capabilities, feel free to open an issue or submit a pull request.
