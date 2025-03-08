# Netflix Movie Recommendation System  

## **Overview**  
This project builds a **Movie Recommendation System** using Netflix user ratings. It applies **collaborative filtering (SVD algorithm)** to generate personalized movie suggestions based on user preferences.  

## **Dataset Details**  
📂 **Files Used:**  
- `combined_data_1.txt` – Netflix movie ratings dataset  
- `movie_titles.csv` – Movie titles with release years  

📊 **Key Features:**  
- **Movie ID** – Unique identifier for movies  
- **Customer ID** – Unique identifier for users  
- **Rating** – User ratings (1-5 scale)  
- **Date** – Timestamp of rating  

---

## **Project Workflow**  

### **1️⃣ Data Preprocessing**  
✅ Loads **Netflix ratings dataset**  
✅ Cleans missing values & converts ratings to float  
✅ Filters out **inactive users & low-rated movies**  

### **2️⃣ Exploratory Data Analysis (EDA)**  
✅ Computes **most-rated movies**  
✅ Visualizes **rating distributions**  
✅ Identifies **popular movies based on user engagement**  

### **3️⃣ Collaborative Filtering (SVD Model)**  
✅ Trains a **Singular Value Decomposition (SVD) model**  
✅ Performs **cross-validation (RMSE & MAE)**  
✅ Predicts movie ratings for a **specific user (Cust_Id 712664)**  
✅ Generates **top 10 movie recommendations**  

### **4️⃣ Recommendation Function**  
✅ Accepts **User ID** as input  
✅ Predicts **top movies for that user**  
✅ Filters out low-rated movies  
✅ Displays **top 10 recommended movies**  

---

## **Technologies Used**  
🚀 **Python, Pandas, NumPy, Matplotlib, Seaborn, Surprise Library (SVD)**  

## **Results & Insights**  
📌 **Higher-rated movies tend to have more engagement**  
📌 **Collaborative filtering effectively predicts user preferences**  
📌 **Filtering inactive users improves recommendation accuracy**  

## **Future Improvements**  
🔹 **Implement Content-Based Filtering** (based on movie genres & descriptions)  
🔹 **Hybrid Model** – Combine **SVD with deep learning (Neural Networks)**  
🔹 **Improve Performance** – Optimize dataset handling for faster predictions  
