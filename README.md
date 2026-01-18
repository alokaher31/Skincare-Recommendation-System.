# 🧴 Skincare Recommendation System.

## 📌 Project Overview
The **Skincare Recommendation System** is a machine learning–based web application that helps users discover suitable skincare products based on their **skin type, concerns, and preferences**.  
The system combines **content-based filtering** and **collaborative filtering** techniques to deliver personalized and relevant product recommendations.

This project is built using **Python, Machine Learning, and Dash**, making it interactive, scalable, and user-friendly.

---

## 🎯 Objectives
- Provide **personalized skincare product recommendations**
- Analyze product descriptions and user preferences using **Natural Language Processing (NLP)**
- Improve recommendation accuracy using **Matrix Factorization**
- Create an interactive **web-based dashboard**

---

## 🚀 Features
- 🔍 Content-based recommendation using **TF-IDF Vectorization**
- 🤝 Collaborative filtering using **SVD (Matrix Factorization)**
- 📊 Interactive dashboard built with **Dash**
- 🖼️ Product visualization with images
- 📁 CSV-based skincare product dataset
- ⚡ Fast and efficient recommendation engine

---

## 🧠 System Architecture
1. **Data Collection** – Skincare product data stored in CSV format  
2. **Data Processing** – Cleaning, preprocessing, and feature extraction  
3. **Content-Based Filtering** – TF-IDF and cosine similarity  
4. **Collaborative Filtering** – Surprise library with SVD  
5. **Web Interface** – Dash application for user interaction  

---

## 🛠️ Technologies & Libraries Used

### Programming Language
- **Python**

### Libraries & Frameworks
- **Dash** – Web application framework
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Scikit-learn** – TF-IDF Vectorizer & similarity calculations
- **Surprise** – Collaborative filtering (SVD model)
- **Pickle** – Model serialization
- **Base64** – Image encoding for dashboard display

---

## 📂 Project Structure
📁 skincare-recommendation-system
│── app.py
│── skindataall.csv
│── output1.png
│── output2.png
│── svd_model.pkl
│── README.md


---

## ⚙️ How It Works

### 🔹 Content-Based Filtering
- Uses **TF-IDF Vectorizer** to convert product descriptions into numerical features
- Calculates **cosine similarity** between products
- Recommends products with similar ingredients and descriptions

### 🔹 Collaborative Filtering
- Uses **SVD (Singular Value Decomposition)** from the Surprise library
- Learns user-product interaction patterns
- Predicts unseen product ratings for users

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/skincare-recommendation-system.git
cd skincare-recommendation-system

2️⃣ Install Required Libraries
pip install -r requirements.txt

3️⃣ Run the Application
python app.py

4️⃣ Open in Browser
http://127.0.0.1:8050/

## 📸 Output Screenshots
Screenshots will be added soon.
