# 📊 Apache Spark-Based Big Data Analytics on E-commerce Trends

## 🚀 Project Overview
In the era of digital commerce, platforms generate massive volumes of data. This project presents a complete solution to process, analyze, and visualize e-commerce datasets using Apache Spark and Streamlit. It also integrates Gemini AI to generate insightful narratives from selected data.

## 🔧 Tech Stack
- **Apache Spark**: For scalable big data processing
- **PySpark & Pandas**: For data wrangling and transformation
- **Streamlit**: For building interactive dashboards
- **Matplotlib & Seaborn**: For data visualization
- **Google Gemini API**: For AI-generated insights
- **FPDF**: To generate downloadable PDF reports

## 🎯 Features
- Upload and analyze CSV/Parquet e-commerce datasets
- Real-time data cleaning (e.g., drop nulls)
- Dynamic chart suggestions based on data types
- Visualizations: Bar charts, scatter plots, heatmaps
- Gemini AI-generated insights from sample data
- Downloadable PDF and CSV reports
- Dark and light theme toggle

## 📁 Folder Structure
```
📦ecommerce_trends_analytics
├── app.py                # Main Streamlit app
├── requirements.txt      # Project dependencies
├── spark_backend/
│   └── spark_processor.py  # Spark session and reader class
├── temp_data.csv         # Temporary uploaded file
```

## 🧠 How It Works
1. User uploads a CSV/Parquet dataset.
2. Apache Spark processes it in-memory.
3. Cleaned data is displayed via Streamlit.
4. User selects columns to visualize.
5. Based on types, chart suggestions are made.
6. Selected chart is plotted using Matplotlib/Seaborn.
7. Gemini AI analyzes sample data and provides insights.
8. Final results can be exported as PDF or CSV.

## 🛠️ Setup Instructions
1. Clone the repo:
```bash
git clone https://github.com/your-username/ecommerce-trends-analytics.git
cd ecommerce-trends-analytics
```

2. Create virtual environment and activate:
```bash
python -m venv venv
venv\Scripts\activate  # Windows
```

3. Install requirements:
```bash
pip install -r requirements.txt
```

4. Run the app:
```bash
streamlit run app.py
```

## 🔐 Gemini API Setup
- Visit [Google AI Studio](https://makersuite.google.com/app)
- Create a Gemini API key
- Replace `GEMINI_API_KEY` in `app.py`

## 📄 Sample Output
- Cleaned dataset preview
- Correlation matrix heatmap
- AI-generated insight example
- Downloadable PDF report

## 📌 Acknowledgement
Developed as a Final Year Project by **Ayushika Singh** (B.Tech, CSE - Data Science), NIET.

## 📬 Let's Connect
- [LinkedIn](https://www.linkedin.com/in/ayushika-singh-13399923b/)
- [GitHub](https://github.com/aayu-7)

---
**#ApacheSpark #DataAnalytics #BigData #Streamlit #GeminiAI #PythonProjects #FinalYearProject**
