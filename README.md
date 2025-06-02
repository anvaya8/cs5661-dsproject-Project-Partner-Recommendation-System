## 🤝 GitHub Project Partner Recommendation System

## 🚀 Elevator Pitch (Big Idea)
This project builds a **hybrid recommendation system** to suggest ideal GitHub project collaborators. By analyzing public metadata — such as repositories, languages, bios, and interaction metrics — it identifies developers with aligned interests and technical backgrounds. The system combines:

- 🔍 Content-Based Filtering (Languages & Repositories)
- 👥 Collaborative Filtering (Followers & Following)
- 🧠 NLP-Based Semantic Matching (User Bios)


---

## ⚙️ Installation Instructions

To get started with this project locally:

```bash
# Clone the repository
git clone https://github.com/EKTAMULKALWAR/cs5661-dsproject-Project-Partner-Recommendation-System.git
cd cs5661-dsproject-Project-Partner-Recommendation-System

# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```
To run the full-stack application:

```bash
# Backend
cd backend
source ../venv/bin/activate
python app.py

# Frontend
cd frontend
npm install
npm start
```
 
## 📂 Repository Description
```bash
├── data/             # Raw and processed GitHub user data
├── backend/          # Flask backend for API endpoints
├── frontend/         # React-based frontend app
├── notebooks/        # Jupyter notebooks (EDA, modeling, evaluation)
├── requirements.txt  # Python dependencies
└── docs              # Dataset documentation (Google’s Data Card style)

```


## 👥 Team Members & Roles

Ekta Mulkalwar – Lead Data Engineer & Content-Based Modeling
Designed scraping pipeline, handled preprocessing, built the content-based system and hybrid model.

Apoorva Durge – NLP & Feature Extraction
Processed user bios using TF-IDF and Sentence-BERT embeddings.

Anand Gutte – Collaborative Filtering Developer
Built cosine-based user interaction similarity metrics.

Mansi Aher – Data Cleaning Specialist
Addressed missing values and data consistency.

Anvaya Chandrika Gudibanda Sreesha – Visualization & Geo Insights
Created charts and processed location-based metadata.

Shalini Nistala – Evaluation & Metrics
Defined validation metrics: precision, recall, MAP.

Shah Drashti Kirtibai – Encoding & Feature Engineering
Used LabelEncoder and vectorized categorical fields.

Neel Jaysukhbhai Khunt – Repository & Documentation Lead
Maintained GitHub repo structure and version control.

Movva Jeevan Sidhardha – Location Processing Support
Geocoded user locations and enriched spatial data.

Sai Kiran Bandapally – Repo Insights Engineer
Parsed repositories for language richness and diversity.

---

## 💡 About
This system analyzes 5,000+ public GitHub profiles to help users find project partners that match on:

Technologies used

Bio semantics

Engagement behavior

All models are modular, allowing future additions such as GitHub activity scores, real-time search, or OAuth-based login.

---

## 📌 Resources
Notebook-based experiments: notebooks/

Live Flask API server: backend/app.py

React frontend app: frontend/src/

Cluster & domain evaluation: UMAP + DBSCAN



