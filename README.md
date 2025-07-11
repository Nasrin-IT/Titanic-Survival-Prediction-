🚢 Titanic Survival Analysis & Search Tool

This project provides a simple data visualization and search interface using the Titanic dataset. It includes a bar plot showing survival counts by gender and allows users to search for individual passengers to view their survival status.

📊 Features

Gender-based Survival Count Visualization
Uses Seaborn to plot survival counts categorized by gender.

Passenger Search Tool
Allows users to input a passenger's name (or part of it) and returns survival status with visual cues.


🧪 Dependencies

Python 3.x

pandas

seaborn

matplotlib


Install dependencies using pip:

pip install pandas seaborn matplotlib



🗂️ Files

titanic.csv – Dataset containing passenger information.

titanic_analysis.py – Main script that handles visualization and name-based search.


🚀 Usage

1. Clone the repository and navigate to the project folder.


2. Make sure titanic.csv is in the same directory as the script.


3. Run the script:



python titanic_analysis.py

4. A plot showing survival counts by gender will be displayed.


5. You'll be prompted to enter a passenger name to check their survival status.



Example output:

🔎 Enter passenger name (or part of it): smith
Passenger:     Smith, Mr. James → 🔴 Did Not Survive
Passenger:     Smith, Mrs. Margaret → 🟢 Survived

📌 Notes

The search is case-insensitive and supports partial name matches.

Missing values in Name, Sex, or Survived columns are dropped for cleaner results.
