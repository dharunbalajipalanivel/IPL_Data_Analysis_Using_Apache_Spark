# IPL Data Analysis Using Apache Spark

## 📌 Project Overview
This project analyzes IPL (Indian Premier League) data using Apache Spark to gain insights into match statistics, player performance, and team trends. It leverages big data processing capabilities to handle large datasets efficiently, storing and processing data in Amazon S3.

## 🔧 Technologies Used
- Apache Spark (PySpark)
- Jupyter Notebook
- Python (Pandas, Matplotlib, Seaborn)
- Amazon S3 (For Data Storage)
- Databricks (Optional)

## 📂 Dataset
The dataset contains IPL match data from 2008 to 2017, including:
- Ball-by-ball records
- Match summaries
- Player statistics
- Team details

## 📊 Analysis Performed
- Team Performance Analysis
- Top Players and Their Impact
- Toss Decision Impact
- Match-winning Factors
- Batsman vs Bowler Analysis
- Venue-based Performance Trends

## 📌 Requirements
- Python 3.x
- Apache Spark
- Jupyter Notebook
- AWS Account (for S3 data storage)
- Required Python libraries (see below)

## 🚀 Installation & Usage
### Clone the repository:
```sh
git clone https://github.com/dharunbalajipalanivel/IPL_Data_Analysis_Using_Apache_Spark.git
```

### Install dependencies:
```sh
pip install pyspark pandas matplotlib seaborn boto3
```

### Configure AWS S3 credentials (if accessing S3 data):
```sh
export AWS_ACCESS_KEY_ID=your_access_key
export AWS_SECRET_ACCESS_KEY=your_secret_key
```

### Run the Jupyter Notebook or Python script:
```sh
jupyter notebook ipl_data_analysis.ipynb
```
or
```sh
python ipl_data_analysis.py
```

## 📜 License
This project is licensed under the BSD-2-Clause License.

## 👨‍💻 Author
Dharun Balaji Palanivel
