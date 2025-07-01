# NEUROHEALTH AWARENESS & SUPPORT WEBSITE WITH BRAINTUMOR DETECTION USING DEEP LEARNING

## 👨‍💻 Project Team
- **Rudradip Mukherjee - BWU/BCA/22/337**
- **Saheli Roy - BWU/BCA/22/330**  
  **Trisha Samanta - BWU/BCA/22/347**  
  **Moumita Dholey - BWU/BCA/22/351**  
  **Nabin Ghorui - BWU/BCA/22/356**
  **Sagar Sarkar - BWU/BCA/22/325**      

## 📄 Project Overview
This project uses **transfer learning with the VGG16 model** to classify brain MRI images into four categories:  
- Glioma Tumor  
- Meningioma Tumor  
- Pituitary Tumor  
- No Tumor  

A Flask-based web interface allows users to upload MRI images and get real-time tumor predictions.  
Additionally, there is a **consultation form** that stores patient booking data into an SQLite database for future reference.

---

## 🚀 Features
✅ VGG16-based transfer learning for high accuracy  
✅ User-friendly web interface built with Flask  
✅ Consultation form with SQLite database storage  
✅ Responsive, modern front-end  
✅ Admin view for submitted consultation requests

---

## ⚙️ Project Structure

Major project/
│
├── templates/
│ ├── index.html
│ └── submissions.html
│
├── static/ # Optional static files (CSS/JS)
├── uploads/ # Stores uploaded MRI images (empty initially)
├── models/ # Contains model.h5 (removed from GitHub for size)
│
├── main.py # Flask app
├── requirements.txt # Python dependencies
├── consultation.db # SQLite database storing consultation form entries
└── README.md


---

## ⚠️ About `model.h5`

> **IMPORTANT:**  
> The trained `model.h5` file is over 100 MB and **cannot be uploaded to GitHub** due to the 25 MB file size limit.  
> Please contact the project owner if you wish to get the model file for testing or demo purposes.

📧 Email: *suradip123@example.com*  
📁 Or download from Google Drive (link provided on request)

---

## 🖥️ Execution Steps

1. **Clone the repository**  
git clone https://github.com/Rudradip04/bca_major_project.git
cd bca_major_project

2. **Install dependencies**  
pip install -r requirements.txt


3. **Download the model file**  
- Contact the project owner to get `model.h5`  
- Place it inside the `models/` directory

4. **Run the Flask app**


5. **Open the web interface**  
Go to [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser

6. **Consultation data view**  
Go to [http://127.0.0.1:5000/submissions](http://127.0.0.1:5000/submissions) to see stored consultation requests

---

## 🤝 Contributions & Credits

- Rudradip Mukherjee (Project lead, model training, web integration)  

---

## 📌 Notes for Reviewers
- The dataset folder was **not uploaded** to GitHub for storage reasons  
- The trained `model.h5` is **not uploaded** because of GitHub’s 25 MB file limit  
- It can be provided via Google Drive or pen drive during viva  
- All code is available and can be run after placing the model file

---

## 📝 License
This project is for academic purposes only.

---

*Feel free to contact for any clarifications or improvements!*

