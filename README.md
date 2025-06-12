# Data_Analyst_bot

📊 Intelligent File Analyzer with LLaMA & Python
This project is an AI-powered data and document analysis tool built with Python. It supports a variety of file formats (CSV, Excel, PDF, DOCX, TXT, Images) and uses Meta's LLaMA-4 via the Together API to generate insights, summaries, and recommendations. It also produces rich visualizations such as histograms, correlation heatmaps, and time series plots.

🚀 Features
📁 Supports CSV, XLSX, PDF, DOCX, TXT, PNG, JPG files
🧠 Uses LLaMA-4 via Together API for:
Data insights & business recommendations
Text summarization for unstructured files

📈 Visualizes:
Histograms of numerical columns
Correlation heatmaps
Riders-over-time charts (for time-series data)

🧾 Auto-detects file type and processes accordingly
🔧 Technologies Used
Python 3.11
Pandas, Matplotlib, Seaborn
pdfplumber, python-docx, pytesseract, Pillow
Together API (meta-llama/Llama-4-Maverick)
Jupyter Notebook / Google Colab

📂 File Structure
bash
Copy
Edit
intelligent-analyzer/
├── Product_data.csv                # Sample input dataset
├── your_notebook.ipynb            # Main Colab / Jupyter Notebook
├── *.png                          # Auto-generated visualizations
├── README.md                      # Project documentation

⚙️ How to Use
Clone or download the repo and open the notebook.
Upload your file (CSV/XLSX/TXT/PDF/DOCX/Image).
Call agent(<filename>).
View visualizations and AI-generated insights.
Enjoy automated data understanding and document analysis!

📌 Example Use Case
A startup uploads product sales data in .csv format.
The system generates:
Histograms of key metrics
Correlation heatmap
A time-series chart of rider counts
AI-driven insights and recommendations for the business

🧠 Credits
Built by Ayush Rai
Model used: meta-llama/Llama-4-Maverick-17B-128E-Instruct-FP8 via Together API

