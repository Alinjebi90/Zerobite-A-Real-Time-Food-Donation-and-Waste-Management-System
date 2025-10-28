<h1 align="center">🍴 ZeroBite</h1>
<p align="center">A Real-Time Food Donation and Waste Management System</p>

---

## 🧠 Overview
**ZeroBite** is a full-stack web application that connects **restaurants, event organizers, and donors** with **NGOs** to minimize food waste.  
The platform enables **real-time food tracking**, **location-based donations**, and **automated communication** between donors and NGOs.

---

## 🚀 How to Run the Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/<your-username>/zerobite-project.git
cd zerobite-project
Step 2: Backend Setup (Django)
bash
Copy code
cd zerobite-backend

# Create virtual environment
python -m venv venv

# Activate environment
venv\Scripts\activate   # For Windows
# or
source venv/bin/activate  # For Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Run database migrations
python manage.py makemigrations
python manage.py migrate

# Start the backend server
python manage.py runserver
Backend runs on: http://127.0.0.1:8000

Step 3: Frontend Setup (React)
bash
Copy code
cd zerobite-frontend

# Install dependencies
npm install

# Start frontend development server
npm start
Frontend runs on: http://localhost:3000

💻 Technologies Used
🧩 Frontend
text
Copy code
• React.js  
• SCSS  
• React Router DOM  
• Axios  
• Google Maps API
⚙️ Backend
text
Copy code
• Django  
• Django REST Framework (DRF)  
• MySQL  
• JWT Authentication  
• Pillow  
• python-dotenv
🏷️ Technology Badges
<p align="center"> <img src="https://img.shields.io/badge/Frontend-React-blue?logo=react" /> <img src="https://img.shields.io/badge/Styling-SCSS-pink?logo=sass" /> <img src="https://img.shields.io/badge/Backend-Django-green?logo=django" /> <img src="https://img.shields.io/badge/API-REST%20Framework-red?logo=django" /> <img src="https://img.shields.io/badge/Database-MySQL-blue?logo=mysql" /> <img src="https://img.shields.io/badge/Authentication-JWT-orange?logo=jsonwebtokens" /> <img src="https://img.shields.io/badge/Maps-Google%20API-lightgrey?logo=googlemaps" /> </p>
✨ Features
• User Authentication: Separate roles for Restaurant and NGO
• Live Map Integration: View real-time donation locations
• Automatic Expiry Check: Removes expired food donations
• Live Status Updates: Instant communication between donors and NGOs
• Database Integration: MySQL-based structured data storage
• Modern UI: Clean, responsive React interface

🚧 Future Enhancements
• AI-based food prediction for smarter donations
• Mobile app version for Android and iOS
• Smart scheduling for donation timing

👩‍💻 Team Details
Project Title: ZeroBite – A Real-Time Food Donation and Waste Management System

Team Members:
• Alin Jebitha B – 211423104032
• Amrin Joshiga A – 211423104036

Guide: Mrs. K. Cinthuja

🎥 Project Demo
📽️ Watch Demo Video on Google Drive

🧾 Conclusion
ZeroBite helps reduce food wastage and promotes community responsibility by connecting donors and NGOs through real-time technology.
It serves as a bridge between surplus food providers and organizations in need.

📜 License
This project is developed for academic use only.
© 2025 ZeroBite Team. All rights reserved.
