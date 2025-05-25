# machine-learning-lab-1
Lab no 1
Introduction to Machine Learning and Setting the Environment
Objective
•	To understand the basic concepts of Machine Learning.
•	To set up the Python environment using Anaconda.
•	To install and use fundamental machine learning libraries like NumPy, Pandas, Matplotlib, and Scikit-learn.
Introduction
Machine Learning (ML) is a core area of Artificial Intelligence where systems learn from data and improve performance without being explicitly programmed. It is widely applied in fields like image recognition, autonomous vehicles, predictive analytics, and natural language processing.
There are three main types of machine learning:
•	Supervised Learning – learns from labeled data (e.g., classification, regression).
•	Unsupervised Learning – finds patterns in unlabeled data (e.g., clustering).
•	Reinforcement Learning – learns from interactions with an environment.
Before implementing machine learning models, we need to set up the development environment. Python is the most commonly used language for ML due to its simple syntax and vast library support. Anaconda simplifies the setup process by providing all required tools and libraries in one platform.
Tools and Libraries
Tool	Purpose
Anaconda Prompt	Command-line interface for managing Python environments
Jupyter Notebook	Interactive environment for code and documentation
NumPy	Numerical computing library
Pandas	Data analysis and manipulation
Matplotlib	Data visualization
Scikit-learn	ML algorithms and data preprocessing
Procedure
Step 1: Open Anaconda Prompt
•	Click Start → Search Anaconda Prompt → Open it.
 
 

Step 2: Create a New Environment 
conda create --name umar python=3.9
 
 
Step 3: Activate the Environment
Write
conda activate umar
 
Step 4: Install Required Libraries
Write
conda install numpy pandas matplotlib scikit-learn jupyter
 
 
Step 5: Launch Jupyter Notebook
jupyter notebook
 
•	This will open Jupyter in your default browser.
•	Click New → Python 3 to open a new notebook.
 
 
Results
•	Successfully created a conda environment and installed the necessary libraries.
•	Launched and worked in Jupyter Notebook via Anaconda Prompt.
Conclusion
This lab successfully introduced Machine Learning and demonstrated how to set up a working ML environment using Anaconda Prompt. By using conda environments and Jupyter notebooks, we created a reliable and organized workflow for ML projects.

