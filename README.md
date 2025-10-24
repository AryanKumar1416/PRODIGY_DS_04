# Social Media Sentiment Analysis on Gaming Data

## Overview
This project analyzes sentiment patterns in social media text data related to different games. Using natural language processing (NLP) and VADER sentiment analysis, the notebook identifies how positively or negatively each game is perceived by the public. Visualizations provide insights into overall sentiment trends and comparisons across games.

---

## Features
- **Data Loading and Cleaning:**  
  - Load data from CSV.  
  - Rename columns for clarity.  
  - Clean text by removing URLs, mentions, hashtags, and special characters.  
  - Handle missing text entries by replacing them with empty strings.

- **Sentiment Analysis:**  
  - Use **VADER** to calculate a compound sentiment score for each text entry.  
  - Categorize sentiment into **positive**, **negative**, or **neutral** based on predefined thresholds.

- **Sentiment Distribution by Game:**  
  - Compute distribution of sentiment labels for each game.  
  - Compare public perception across different games.

- **Visualization:**  
  - Display overall sentiment distribution.  
  - Create a **heatmap** to illustrate sentiment distribution across games, showing the proportion of positive, neutral, and negative sentiment for each game.

---

## Technologies Used
- **Programming Language:** Python  
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `nltk`, `vaderSentiment`  
- **Jupyter Notebook:** Interactive analysis and visualization  

---

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/AryanKumar1416/PRODIGY_DS_04.git
    cd PRODIGY_DS_04
    ```
2. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## Usage
1. Open the notebook `TASK4.ipynb` in Jupyter Notebook or Jupyter Lab.  
2. Run all cells sequentially to:  
   - Load and clean the data  
   - Perform sentiment analysis using VADER  
   - Visualize overall and per-game sentiment distributions  

---

## Example Visualizations
- **Overall Sentiment Distribution:** Bar chart showing the counts of positive, neutral, and negative posts.  
- **Heatmap of Sentiment by Game:** Shows the proportion of each sentiment type for all games, highlighting which games are positively or negatively perceived.

---

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for improvements, bug fixes, or additional features.


---

## Contact
- **Author:** Aryan Kumar  
- **GitHub:** [github.com/AryanKumar1416](https://github.com/AryanKumar1416)
