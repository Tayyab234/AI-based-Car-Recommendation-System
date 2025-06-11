# Car-recommendation-system
Car Recommendation System using Content-Based Filtering

📚 Description
This Jupyter Notebook presents a car recommendation system that helps users find similar cars based on the features of a selected car. It applies natural language processing and cosine similarity on preprocessed car specifications such as brand, engine size, mileage, fuel type, and more.

🛠️ Technologies Used
Python

Pandas: Data manipulation

Scikit-learn: Feature extraction (TF-IDF), cosine similarity

NumPy: Numerical operations

📂 Main Sections in the Notebook
Data Loading & Cleaning: Reads and preprocesses the car dataset, handling missing or irrelevant values.

Feature Engineering: Combines multiple features into a single text column for similarity analysis.

Vectorization: Uses TF-IDF to convert text data into vectors.

Similarity Calculation: Applies cosine similarity to determine closeness between cars.

Recommendation Function: A user-defined function to return the top N similar cars for a given car.

Example Recommendations: Runs the system with example inputs to show how it suggests alternatives.

🧪 How to Run
Install dependencies: pip install pandas scikit-learn numpy

Open the .ipynb file in Jupyter Notebook or any compatible IDE.

Run all cells sequentially.

Use the function call (e.g., recommend('Hyundai i20 Sportz')) to test.

✅ Output
A list of similar cars with their names and similarity scores, helping users explore alternatives.
