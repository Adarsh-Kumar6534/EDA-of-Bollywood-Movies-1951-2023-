📂 Read My File

🎬 Project Title:

Lights, Camera, Data! An Exploratory Data Analysis of Bollywood Movies (1951–2023)




This project begins with importing the **Bollywood Movie Dataset (1951–2023)**, which contains rich metadata about Hindi films spanning over seven decades.

### 📄 Dataset File:
- `bollywood_movie_dataset.csv`

### 🧾 Key Columns:
- `Movie_ID` – Unique identifier for each movie  
- `Movie_Name` – Title of the movie  
- `Release_Year` – Year of release  
- `Genre` – Movie genre(s)  
- `Synopsis` – Short description of the storyline  
- `Director` – Name(s) of the director(s)  
- `Cast` – Main actors and actresses featured  

### 🛠️ How the Data is Loaded:
The dataset is read using **Pandas**, a powerful Python library for data analysis.

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('bollywood_movie_dataset.csv')

# Quick preview of the dataset
print(df.head())
