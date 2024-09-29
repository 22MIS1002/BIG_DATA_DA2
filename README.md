# BIG_DATA_DA2
## 1. Project Overview
This project uses Self-Organizing Maps (SOM) to perform customer segmentation based on their annual income and spending score. The SOM algorithm helps visualize and cluster customers with similar spending habits and income levels into groups (nodes) on a 2D grid.

## 2. Dataset
The dataset used in this project is Mall_Customers.csv, which includes information about customer income and spending behavior.

## 3. Software Requirements
To run this implementation, you'll need the following software installed on your system:

Python 3.x
Libraries:
pandas
numpy
minisom
scikit-learn
matplotlib
To install the required libraries, you can run the following command:
pip install pandas numpy minisom scikit-learn matplotlib
## 4. Hardware Requirements
CPU: Any modern processor (Intel/AMD with at least 2 cores)
RAM: Minimum of 4 GB (8 GB recommended)
Disk Space: ~500MB of free disk space
GPU: Not required (optional for enhanced performance)
## 5. Running the Project
Steps in the Code:
Load the dataset.
Preprocess the data by scaling it.
Initialize and train the SOM on a 10x10 grid.
Retrieve clusters from specific nodes on the SOM grid.
Optionally visualize the clustering with a heatmap.
Expected Output: The SOM will segment customers into clusters based on their spending habits. Each cluster corresponds to a node in the SOM grid, and the script will print the customers in each node (e.g., nodes (5,5), (6,6), etc.). You can also visualize the SOM grid with a heatmap showing how closely the nodes are related.

# Executable File
Since Python scripts are executed via interpreters, a direct executable isn't typically provided. However, if you want to convert the Python script into an executable file (.exe) for easy execution, you can use PyInstaller.

Steps to Create an Executable (.exe)
Install PyInstaller:
pip install pyinstaller
Create Executable: Navigate to the folder containing your Python script and run the following command:
pyinstaller --onefile customer_segmentation_som.py
Locate Executable: After running the command, the executable file will be located in the dist/ folder created by PyInstaller.

Run the Executable: You can then run the executable (customer_segmentation_som.exe) by double-clicking it or running it from the command line:
./dist/customer_segmentation_som.exe
Note: This method packages all required dependencies into a single executable file.

