# 📚 Academic Curriculum Mapping  
A web-based system designed to map academic curriculum outcomes, manage course data, and streamline the evaluation process.  
This project integrates **React.js (frontend)**, **Python Flask (backend)**, and **SQL database** to provide an end-to-end solution for academic data management.

---

## 🚀 Features

### 🔹 **Frontend (React.js)**
- Responsive user interface  
- Data visualization components  
- Interactive forms for course & curriculum mapping  
- Organized file structure (`public`, `src`)

### 🔹 **Backend (Python Flask)**
- API endpoints to manage curriculum data  
- Database queries and CRUD operations  
- Handles communication between frontend & SQL database  

### 🔹 **Database**
- SQL schema stored in [`db.sql`](db.sql)  
- Stores:
  - Course details  
  - Mapping records  
  - Outcome data  

---

## 🗂 Project Structure

Academic-Curriculum-Mapping/

├── public/                 
├── src/                   
├── app.py                 
├── db.sql                  
├── package.json           
├── package-lock.json       
├── node_modules.zip        
├── .gitignore   
└── README.md

---

## 🛠️ Technologies Used

### **Frontend**
- React.js  
- JavaScript  
- HTML5, CSS3  

### **Backend**
- Python  
- Flask Framework  

### **Database**
- SQL  
- PostgreSQL / MySQL (based on your implementation)

---

## 🧪 How to Run the Project

### 🔸 **1. Frontend Setup (React)**
npm install
npm start

### 🔸 **2. Backend Setup (Flask)**
pip install -r requirements.txt
python app.py

### 🔸 **3. Database Setup**
db.sql

### 🌟 Future Enhancements
- Role-based login system (Admin / Faculty / Student)
- Automatic mapping recommendations
- Insights dashboard with charts
- Export reports in PDF/CSV
