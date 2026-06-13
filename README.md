# Semantic Resume Matching Engine

A simple NLP-powered web application that compares a candidate's resume with a job description and calculates a similarity score using **TF-IDF Vectorization** and **Cosine Similarity**.

Built with **Python**, **Streamlit**, and **Scikit-Learn**.

---

## 🚀 Features

* Upload Resume in PDF format
* Paste Job Description
* Automatic PDF Text Extraction
* Text Cleaning and Preprocessing
* Stopword Removal using NLTK
* TF-IDF Vectorization
* Cosine Similarity Matching
* Match Score Visualization
* Resume Match Feedback

---

## 🛠️ Tech Stack

### Frontend

* Streamlit

### NLP & Machine Learning

* NLTK
* Scikit-Learn

### Data Processing

* PyPDF2
* Regular Expressions (re)

### Visualization

* Matplotlib

---

## 📂 Project Structure

```text
Resume-Match-Scorer/
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/resume-match-scorer.git

cd resume-match-scorer
```

### 2. Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / Mac**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 📊 How It Works

### Step 1

Upload a PDF resume.

### Step 2

Paste the job description.

### Step 3

The application:

* Extracts text from the resume
* Cleans and preprocesses text
* Removes stopwords
* Converts text into TF-IDF vectors
* Computes cosine similarity

### Step 4

Displays:

* Match Score (%)
* Similarity Visualization
* Resume Feedback

---

## 🧠 Machine Learning Approach

### TF-IDF Vectorization

Converts resume and job description text into numerical vectors based on word importance.

### Cosine Similarity

Measures the similarity between the resume and job description vectors.

Higher scores indicate stronger alignment with job requirements.

---

## 📈 Example Output

```text
Match Score: 82.45%

Feedback:
Excellent Match! Strong alignment detected.
```

---

## 🔮 Future Improvements

* ATS Score Calculation
* Skill Extraction
* Missing Skill Detection
* Resume Recommendations
* Keyword Analysis
* Semantic Similarity using Word2Vec
* Resume Section Detection
* Deployment on Streamlit Cloud

---

## 📚 Learning Outcomes

Through this project, I learned:

* Natural Language Processing (NLP)
* Text Preprocessing
* TF-IDF Vectorization
* Cosine Similarity
* PDF Data Extraction
* Streamlit Application Development
* Machine Learning Workflow Design

---

## 👨‍💻 Author

Aksh Maity

Aspiring Data Scientist | Python Developer | NLP Enthusiast
