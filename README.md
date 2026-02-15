# Book-recommendation-system-using-collaborative-filtering
🚀 Project Overview

This notebook implements a basic recommendation engine that:

Creates a user–book rating dataset

Builds a user–item interaction matrix

Computes similarity between users

Recommends books based on similar users

The goal is to illustrate the core ideas behind recommendation systems in a minimal and beginner-friendly way.

🛠️ Technologies Used

Python

Pandas – Data manipulation & matrix creation

Scikit-learn – Cosine similarity calculation

📊 How It Works

Dataset Creation
A small sample dataset of users, books, and ratings is created.

User–Book Matrix
Data is converted into a pivot table where:

Rows → Users

Columns → Books

Values → Ratings

Similarity Calculation
Cosine similarity is used to measure how similar users are based on ratings.

Recommendation Logic
Books liked by similar users are suggested to the target user.
