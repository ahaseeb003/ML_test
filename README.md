🤖 Machine Learning Playground: Supervised vs. Unsupervised vs. Reinforcement

Status: 🟢 Active Learning & Testing

Goal: To visualize and understand the fundamental differences in how ML models learn.

📖 About This Project

I am currently testing and learning the approaches of different Machine Learning models. The goal of this repository is to break down complex ML concepts into simple, runnable Python code to see exactly how they differ in processing data.

This project implements three distinct types of learning on synthetic datasets:

Supervised Learning: Teaching with answers.

Unsupervised Learning: Learning without answers.

Reinforcement Learning: Learning through trial and error.

📂 Files Overview

File

Type

Description

create_data.py

Data Gen

Generates the users.csv (labeled data) and maze.csv (environment) used by the models.

supervised.py

Supervised

Uses Random Forest to classify users into "Buyers" vs "Non-Buyers" based on Age/Salary labels.

unsupervised.py

Unsupervised

Uses K-Means Clustering to find hidden groups in the user data without looking at the labels.

reinforcement.py

RL

Uses Q-Learning to train an agent to navigate a grid maze loaded from a CSV file.

🚀 How to Run

Install Dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn


Generate Data:
First, run the data generator to create the CSV files.

python create_data.py


Run the Models:
Run any of the scripts to see the visualization.

python supervised.py
python unsupervised.py
python reinforcement.py


📊 Visualizations

Supervised: Shows decision boundaries (red vs blue regions).

Unsupervised: Shows clusters and centroids (where the center of the group is).

Reinforcement: Shows a heatmap of the maze and the path the agent learned to take.

This code was written for educational purposes to demonstrate ML concepts.
