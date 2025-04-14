
# 📺 Netflix Data Analysis with MySQL & Python

This project explores Netflix's content dataset using Python (Pandas) and MySQL. It loads, stores, and analyzes data to uncover trends in content production, release patterns, and genre popularity.

---

## 📌 Features

- ✅ Connects to MySQL using SQLAlchemy  
- ✅ Stores Netflix dataset in MySQL  
- ✅ Performs exploratory data analysis (EDA)  
- ✅ Handles missing or null values  
- ⏳ Visualizes trends (in progress)

---

## 🛠 Tech Stack

- **Python**
- **Pandas**
- **MySQL**
- **SQLAlchemy**
- **Jupyter Notebook** (optional)

---

## 📊 Dataset

- **Source:** [Netflix Titles CSV from Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- The dataset contains information about movies and TV shows available on Netflix as of 2021.

---

## ⚙️ Setup Instructions

Follow these steps to run the project on your system:

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/netflix-data-analysis.git
cd netflix-data-analysis
```

### 2. Install Required Libraries
Make sure Python is installed, then run:
```
pip install pandas sqlalchemy mysql-connector-python
```

### 3. Set Up MySQL Database
- Start your MySQL server.
- Create a new database called `netflix`.

### 4. Update MySQL Credentials
In the `main.py` file, update the database password:
```
# Example
engine = create_engine("mysql+mysqlconnector://root:your_password@localhost/netflix")
```

### 5. Run the Script to Load Data
```
python main.py
```

### 6. (Optional) Open Jupyter Notebook
```
jupyter notebook
```
Use it for deeper exploration and data visualization.

---

## 📝 To-Do

- [ ] Add data visualizations using matplotlib or seaborn  
- [ ] Create an interactive dashboard (optional with Streamlit)  
- [ ] Explore more advanced analysis like clustering or recommendation

---


