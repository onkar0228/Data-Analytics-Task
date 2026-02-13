
This project performs exploratory data analysis and sentiment classification on a dataset of tweets. The environment used is **Jupyter Lite**, running entirely in the browser via Pyodide.

## 📂 Dataset Details
The dataset `Twitter_Data.csv` contains:
- **clean_text**: Pre-processed tweet content.
- **category**: Sentiment score where:
  - `1`: Positive
  - `0`: Neutral
  - `-1`: Negative

## 🛠️ Installation
To run the analysis in Jupyter Lite, install the following dependencies in the first cell:
```python
%pip install pandas matplotlib seaborn wordcloud
