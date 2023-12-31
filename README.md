# Spotify Trends 2023 Analysis 🎵

![Spotify Trends 2023](https://martech.org/wp-content/uploads/2017/09/spotify-logo-1920x1080.jpg)

## Overview

The Spotify Trends 2023 Analysis project aims to explore and analyze the latest trends in music on the Spotify platform for the year 2023. By leveraging data science and machine learning techniques, we seek to uncover insights into user preferences, popular genres, and emerging artists.

## Project Structure

The project is organized into the following main components:

- **data:** Contains the dataset used for analysis.
- **notebooks:** Jupyter notebooks for data exploration, preprocessing, modeling, and visualization.
- **models:** Saved machine learning models.
- **images:** Images and visualizations generated during the analysis.
- **src:** Source code files.

## Technologies Used

The key technologies and libraries used in this project include:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TensorFlow
- Scikit-learn
- Spotipy (Spotify API wrapper)

## Dataset

The dataset used in this analysis consists of Spotify user listening data for the year 2023. It includes information about track popularity, user preferences, and artist details.

### Data Size:

10,000 records

### Data Cleaning and Preprocessing:

- Handling missing values
- Removing duplicates
- Feature engineering

## Analysis Steps

1. **Data Exploration:**
   - Understanding the distribution of features
   - Identifying patterns and outliers

2. **Data Preprocessing:**
   - Cleaning and transforming data for modeling
   - Feature scaling and normalization

3. **Modeling:**
   - Implementing a recommendation system using collaborative filtering
   - Training machine learning models for genre classification

4. **Evaluation:**
   - Assessing the performance of the recommendation system
   - Evaluating genre classification models

5. **Visualization:**
   - Creating interactive visualizations to showcase trends

## Model Architecture

### Recommendation System:

- Collaborative Filtering with Matrix Factorization

### Genre Classification:

- Convolutional Neural Network (CNN)

## Results

The analysis revealed several interesting trends:

- Top genres among Spotify users
- Emerging artists gaining popularity
- User preferences based on geographical location

Visualizations and detailed results can be found in the [results](/images/results) directory.

## Future Work

- Incorporate more features for genre classification
- Implement user segmentation for personalized recommendations
- Explore additional data sources for a more comprehensive analysis

## How to Run

Follow these steps to reproduce the analysis:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/spotify-trends-2023.git
   
2. Install the required dependencies:
   
   ```bash
   pip install -r requirements.txt

## LİCENCE

   ```bash
   
   MIT License

Copyright (c) 2023 Pınar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
