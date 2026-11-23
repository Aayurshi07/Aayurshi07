<div align="center">

<img src="https://capsule-render.vercel.app/api?type=cylinder&height=220&color=0:0A66C2,50:5B3FD6,100:7F52FF&text=Aayurshi%20Gawande&fontColor=ffffff&fontSize=50&fontAlignY=50&desc=Data%20Analytics%20%7C%20Full%20Stack%20%7C%20Product%20%7C%20GenAI&descSize=18&descAlignY=72" width="100%" alt="Hi I am Aayurshi Gawande"/>

<a href="https://www.linkedin.com/in/aayurshigawande-1a6743254"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:aayurshigawande@student.sfit.ac.in"><img src="https://img.shields.io/badge/Email-Get%20in%20Touch-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://www.instagram.com/aayurshi_7"><img src="https://img.shields.io/badge/Instagram-aayurshi__7-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>

<br/><br/>

<img src="https://img.shields.io/badge/Open%20to-Internships%20and%20Fresher%20Roles-2ea44f?style=for-the-badge" alt="Open to work"/>

</div>

---

## About me

I'm a final-year B.E. student in Electronics and Telecommunication Engineering,Mumbai.

I like taking messy data and turning it into something a person can act on. Most of my projects are on retail and customer data, and I'm now moving into building apps and backends around that, like a search tool over PDFs using embeddings and an LLM.

I'm looking for internships and fresher roles.

---

## Projects

**NotesSeek: Q&A and search over academic PDFs**
A RAG pipeline. PDFs are split into chunks, embedded with Gemini, stored in SQLite and searched by cosine similarity. The top 3 chunks go to Gemini, which answers from them. Served through a FastAPI backend with /search and /ask endpoints. I'm now measuring retrieval quality with a 15-question test set (Recall@3). Python, FastAPI, Gemini API, SQLite, NumPy.
[View repo](https://github.com/Aayurshi07/notesseek)

**Autonomous AI Data Analyst**
Ask questions about e-commerce data in plain English. Gemini writes the SQL, the code checks it is safe and runs it, and if it fails the error goes back to Gemini to fix. It also flags unusual revenue days with Z-scores and writes a summary. It picked out Black Friday 2017 as the biggest spike without being told about holidays. Live on Streamlit. Python, Gemini API, SQLite, Streamlit, GitHub Actions.
[View repo](https://github.com/Aayurshi07/autonomous-ai-data-analyst)

**Sales Forecasting with Prophet**
Forecast weekly revenue for a UK online retailer. Tuning the trend setting brought the error down from 28.0% to 9.4% MAPE, and I wrote down why one year of data limits the model. Power BI dashboard on top.
[View repo](https://github.com/Aayurshi07/sales-forecasting-prophet)

**Customer Churn Prediction**
Logistic Regression on RFM features. A first model with 80% accuracy caught no churners at all, so I fixed the class imbalance and got churn recall to 91%. I left Recency out of the features to avoid data leakage.
[View repo](https://github.com/Aayurshi07/customer-churn-prediction-logistic-regression)

**Customer Segmentation (RFM + K-Means)**
Cleaned 541,909 transactions down to 397,884 and found four customer segments. 13 VIP customers bring in about 19% of revenue, and about a quarter of customers are at risk. Power BI dashboard.
[View repo](https://github.com/Aayurshi07/customer-segmentation-rfm-kmeans)

**Car Sales Dashboard**
Two-page Power BI report with KPI cards, weekly trend, a US map, company rankings and a drill-down over 17,557+ transactions. Data cleaned with Python and SQL.
[View repo](https://github.com/Aayurshi07/car-sales-dashboard-powerbi)

**Amazon Review Sentiment App**
A live Streamlit app with a DistilBERT sentiment predictor, a dashboard of sentiment over time and topics, and a data explorer.
[View repo](https://github.com/Aayurshi07/amazon-review-sentiment-app)

---

## Skills

**Languages**
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
<img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL"/>
<img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin"/>
<img src="https://img.shields.io/badge/DAX-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="DAX"/>

**Data and BI**
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white" alt="Matplotlib"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>

**Machine learning**
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn"/>
<img src="https://img.shields.io/badge/Prophet-0A66C2?style=for-the-badge&logo=meta&logoColor=white" alt="Prophet"/>

Logistic Regression, K-Means, RFM analysis, time-series forecasting, anomaly detection (Z-score), hyperparameter tuning, class imbalance, MAE / RMSE / MAPE

**GenAI and backend**
<img src="https://img.shields.io/badge/Gemini%20API-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" alt="Gemini API"/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
<img src="https://img.shields.io/badge/DistilBERT-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="DistilBERT"/>

RAG pipelines, text embeddings, cosine similarity search, text-to-SQL, REST APIs, retrieval evaluation (Recall@k), sentiment analysis

**Apps**
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit"/>
<img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android"/>
<img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white" alt="Jetpack Compose"/>

**Tools**
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
<img src="https://img.shields.io/badge/Overleaf-47A141?style=for-the-badge&logo=overleaf&logoColor=white" alt="Overleaf"/>

---

## Contact

- LinkedIn: [linkedin.com/in/aayurshigawande-1a6743254](https://www.linkedin.com/in/aayurshigawande-1a6743254)
- Email: [aayurshigawande@student.sfit.ac.in](mailto:aayurshigawande@student.sfit.ac.in)
- Instagram: [@aayurshi_7](https://www.instagram.com/aayurshi_7)

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:7F52FF,50:5B3FD6,100:0A66C2&section=footer" width="100%" alt="footer"/>
</div>
