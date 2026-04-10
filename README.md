# 🔐 Phishing Website Detection using Machine Learning

## 📌 Project Overview

This project is a web-based application developed using **Django** that detects whether a website is **phishing or legitimate** using Machine Learning techniques.

Phishing websites are designed to steal sensitive user data such as login credentials and banking information. This system helps users identify malicious URLs and stay safe online.

---

## 🚀 Features

* 🔍 URL-based phishing detection
* 🤖 Machine Learning model integration
* 🌐 User-friendly web interface
* 📊 Real-time prediction results
* 🧠 Feature extraction from URLs
* 📁 Admin panel for management

---

## 🛠️ Technologies Used

* **Frontend:** HTML, CSS
* **Backend:** Django (Python)
* **Machine Learning:** Scikit-learn
* **Database:** SQLite
* **Tools:** VS Code, Git

---

## 🧠 Machine Learning Approach

The model is trained using various features extracted from URLs such as:

* URL length
* Presence of special characters (@, -, etc.)
* HTTPS usage
* Domain age
* Redirection behavior

### Algorithms Used:

* Logistic Regression / Random Forest (based on your implementation)

---

## 📂 Project Structure

```
Detection_of_phishing_websites/
│── admins/
│── users/
│── templates/
│── static/
│── media/
│── Phishing_website_Detection/
│── db.sqlite3
│── manage.py
│── model_phishing_webpage_classifier
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/PoojithaCoder-10/Detection_of_phishing_websites_using_ML_Approaches.git
cd Detection_of_phishing_websites_using_ML_Approaches
```

### 2️⃣ Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run migrations

```bash
python manage.py migrate
```

### 5️⃣ Run the server

```bash
python manage.py runserver
```

### 6️⃣ Open in browser

```
http://127.0.0.1:8000/
```

---

## 📸 Screenshots

(Add your project screenshots here)

---

## 🎯 Future Enhancements

* 🔗 API integration for live URL scanning
* 📱 Mobile responsive UI
* ☁️ Deployment on cloud (AWS/Heroku)
* 🔐 Advanced ML models (Deep Learning)

---

## 👩‍💻 Author

**Poojitha Devireddy**

* 🎓 B.Tech CSE
* 💡 Frontend Developer | AI Enthusiast

---

## 📜 License

This project is for educational purposes.
