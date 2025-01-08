# Restaurant Recommendation System

This project implements a restaurant recommendation system using machine learning techniques and natural language processing (NLP). It analyzes restaurant reviews and other features to recommend similar restaurants to users based on their preferences.

---

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Setup and Usage](#setup-and-usage)
- [Example](#example)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction

The recommendation system is designed to assist users in discovering restaurants based on their preferences. By leveraging user reviews and cosine similarity, the system identifies restaurants with similar reviews and characteristics, providing a ranked list of recommendations.

---

## Features

- **Data Cleaning:** Handles missing values, duplicates, and inconsistent data formats.
- **Feature Engineering:** Includes calculations like mean ratings and TF-IDF vectorization for reviews.
- **Recommendation Engine:** Utilizes cosine similarity to recommend restaurants based on user input.
- **Customizable Output:** Provides a list of the top 10 recommended restaurants with details.

---

## Dataset

The dataset (`zomato.csv`) includes information about restaurants, such as:

- Name
- Location
- Cuisine types
- Ratings and reviews
- Cost for two people
- Online order and table booking availability

The dataset is preprocessed to remove duplicates, handle missing data, and format columns for consistency.

---

## Technologies Used

- **Programming Language:** Python
- **Libraries:**
  - `pandas`, `numpy` for data manipulation and analysis
  - `nltk`, `re` for text preprocessing
  - `sklearn` for machine learning and vectorization
  - `matplotlib`, `seaborn` for visualization

---

## Setup and Usage

### Prerequisites

Ensure you have Python installed on your system. Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn
```

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/restaurant-recommendation-system.git
   ```

2. Navigate to the project directory:

   ```bash
   cd restaurant-recommendation-system
   ```

3. Place the `zomato.csv` file in the project directory.

4. Run the script:

   ```bash
   python main.py
   ```

### Outputs

The script generates a CSV file (`dataset.csv`) with cleaned data and prints the top 10 restaurant recommendations for the given input.

---

## Example

### Input

Restaurant: `Pai Vihar`

### Output

| Rank | Name           | Cuisines              | Mean Rating | Cost  |
| ---- | -------------- | --------------------- | ----------- | ----- |
| 1    | Shree Thali    | North Indian          | 3.94        | 150.0 |
| 2    | Swad Punjab Da | North Indian          | 3.94        | 150.0 |
| 3    | Cinnamon       | North Indian, Chinese | 3.71        | 550.0 |
| ...  | ...            | ...                   | ...         | ...   |

---

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.

### Steps to Contribute

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push them to your branch.
4. Submit a pull request explaining your changes.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

Feel free to contact us for further queries or collaboration opportunities!

To download the dataset : https\://www\.kaggle.com/datasets/abhishekkanase/zomato
