# Spotify_Trends
This project performs an Exploratory Data Analysis (EDA) on a comprehensive Spotify tracks dataset. Using Python with Pandas, Matplotlib, and Seaborn, the analysis investigates how musical attributes like danceability, energy, and loudness have evolved over the years.
## Features

-   **Temporal Analysis:** Tracks and visualizes the evolution of key audio features (danceability, energy, valence, etc.) from the 1920s to the modern era.
-   **Correlation Analysis:** A heatmap reveals the correlations between different musical attributes (e.g., loudness and energy).
-   **Artist Popularity:** Identifies and plots the most popular artists in the dataset based on track popularity scores.
-   **Data Cleaning:** Prepares the dataset for analysis by handling missing values and converting data types.
-   **Rich Visualizations:** Uses Seaborn and Matplotlib to create insightful line plots, heatmaps, and bar charts.

## Technology Stack

-   **Python**
-   **Pandas:** For loading and manipulating the data.
-   **NumPy:** For numerical operations.
-   **Matplotlib & Seaborn:** For creating high-quality data visualizations.
-   **Jupyter Notebook:** As the environment for conducting the analysis.

## Setup and Usage

A virtual environment is highly recommended for this project.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/Anjali-Ajesh/spotify-music-trends.git](https://github.com/Anjali-Ajesh/spotify-music-trends.git)
    cd spotify-music-trends
    ```

2.  **Install Dependencies:**
    ```bash
    # Create and activate a virtual environment
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate

    # Install the required libraries
    pip install pandas numpy matplotlib seaborn jupyter
    ```

3.  **Download the Dataset:**
    * This project uses the "Spotify Tracks Dataset" from Kaggle, which contains over 500,000 songs.
    * [Download Link](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset)
    * Download the `tracks.csv` file and place it in the root directory of your project.

4.  **Launch Jupyter Notebook and Run:**
    Start Jupyter Notebook from your terminal:
    ```bash
    jupyter notebook
    ```
    Open a new notebook, copy the code from `spotify_trends_analysis.py`, and run the cells sequentially to perform the analysis.
