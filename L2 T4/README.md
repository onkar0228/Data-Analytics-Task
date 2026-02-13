This project analyzes the app market ecosystem to understand category trends, pricing strategies, and user satisfaction.

## 📱 Dataset Features
- **App**: Name of the application.
- **Category**: Market segment (Games, Productivity, etc.).
- **Rating**: Average user rating (1.0 to 5.0).
- **Reviews**: Total number of user feedbacks.
- **Installs**: Total downloads (Numerical).
- **Type**: Free vs Paid.

## 🛠️ Data Cleaning Performed
- Removed special characters (`+`, `,`, `$`) from numerical columns.
- Handled missing values in the `Rating` column.
- Converted object types to `float` for mathematical analysis.

## 📁 Files
- `apps.csv`: Original store data.
- `Market_Analysis.ipynb`: Notebook with cleaning and visualization code.

---
*Created in Jupyter Lite using Python (Pyodide)*
