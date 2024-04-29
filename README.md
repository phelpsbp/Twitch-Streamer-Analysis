# Twitch Streamer Analysis

## Overview
This project focuses on analyzing Twitch streaming data to uncover insights into streamer performance metrics, viewer engagement, and the impact of partnership status on streamers' popularity and watch time. The project includes detailed data visualization and exploratory data analysis (EDA) to identify key attributes of successful Twitch streamers.

You can view the project [here](https://phelpsbp.github.io/Twitch-Streamer-Analysis/)

## Technologies Used
- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Jupyter Notebook

## Features
- **Data Cleaning and Preprocessing**: Ensuring the data integrity by cleaning and preprocessing the dataset.
- **Exploratory Data Analysis (EDA)**: Examination of various metrics such as watch times, followers gained, and streaming hours to uncover underlying patterns.
- **Visualization**: Utilizing Python libraries like Matplotlib and Seaborn to create insightful visual representations of the data.
- **Comparative Analysis**: Comparing partnered and non-partnered Twitch channels to assess the impact of partnership status on streamers' metrics.

## Dataset
The dataset comprises metrics for the top 1000 Twitch streamers, focusing on various aspects of streaming performance.

### Obtaining the Dataset
The dataset is available on Kaggle and can be downloaded using the following link:
- [Twitch Streamers Dataset on Kaggle](https://www.kaggle.com/datasets/aayushmishra1512/twitchdata)

This dataset is under the [Creative Commons Public Domain Dedication (CC0)](https://creativecommons.org/publicdomain/zero/1.0/).

### Using the Dataset
Place the downloaded `twitchdata-update.csv` file in the root directory of the project. Load the dataset using:
```python
import pandas as pd
twitch_data = pd.read_csv('twitchdata-update.csv')
```

### Dataset Description
Key metrics in the dataset include:
- **Channel**: Name of the Twitch channel
- **Watch time(Minutes)**
- **Stream time(Minutes)**
- **Followers**
- **Followers gained**
- **Views gained**

## Installation
To set up this project locally, follow the steps below:
1. Clone the repository:
   ```bash
   git clone https://github.com/phelpsbp/Twitch-Streamer-Analysis.git
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
After installation, you can run the Jupyter notebook `Twitch Streamer Analysis.ipynb` to view the analysis and visualizations:
```bash
jupyter notebook Twitch\ Streamer\ Analysis.ipynb
```

## Contributions
Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the [MIT License](LICENSE.md).

## Authors
- **Brittany Phelps** - *Initial work* - [BrittanyPhelps](https://github.com/phelpsbp)

----
