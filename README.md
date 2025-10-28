<h1 align="center">🍴 ZeroBite</h1>
<p align="center">A Real-Time Food Donation and Waste Management System</p>

---

## 🧠 Overview
**ZeroBite** is a full-stack web application that connects **restaurants, event organizers, and donors** with **NGOs** to minimize food waste.  
The platform enables **real-time food tracking**, **location-based donations**, and **automated communication** between donors and NGOs.

---

## 🚀 How to Run the Project

### 🖥️ Backend Setup (Django)
```bash
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
```
💻 Frontend Setup (React)
```bash
cd zerobite-frontend

# Install dependencies
npm install

# Start frontend development server
npm start
Frontend runs on: http://localhost:3000
```
💻 Technologies Used
| **Part**     | **Technology**                                                                                          | **Purpose / How It’s Used**                                        |
| ------------ | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------ |
| **Frontend** | <img src="https://img.shields.io/badge/React-blue?logo=react&logoColor=white" />                        | Built the entire user interface for NGOs and Restaurants.          |
|              | <img src="https://img.shields.io/badge/SCSS-pink?logo=sass&logoColor=white" />                          | Used for styling and designing responsive layouts.                 |
|              | <img src="https://img.shields.io/badge/React%20Router%20DOM-orange?logo=reactrouter&logoColor=white" /> | Used for page navigation between login, register, and dashboard.   |
|              | <img src="https://img.shields.io/badge/Axios-5A29E4?logo=axios&logoColor=white" />                      | Handled API requests to connect frontend with backend.             |
|              | <img src="https://img.shields.io/badge/Google%20Maps%20API-lightgrey?logo=googlemaps&logoColor=blue" /> | Integrated live map tracking for donations and pickup points.      |
| **Backend**  | <img src="https://img.shields.io/badge/Django-green?logo=django&logoColor=white" />                     | Main backend framework managing logic and database operations.     |
|              | <img src="https://img.shields.io/badge/Django%20REST%20Framework-red?logo=django&logoColor=white" />    | Built RESTful APIs for communication between frontend and backend. |
|              | <img src="https://img.shields.io/badge/MySQL-blue?logo=mysql&logoColor=white" />                        | Stored user information, donation data, and NGO details.           |
|              | <img src="https://img.shields.io/badge/JWT-orange?logo=jsonwebtokens&logoColor=white" />                | Implemented secure login system with token-based authentication.   |


## ✨ Features
- User Authentication: Separate roles for Restaurant and NGO
- Live Map Integration: View real-time donation locations
- Automatic Expiry Check: Removes expired food donations
- Live Status Updates: Instant communication between donors and NGOs
- Database Integration: MySQL-based structured data storage
- Modern UI: Clean, responsive React interface

---

## 🚧 Future Enhancements
- AI-based food prediction for smarter donations
- Mobile app version for Android and iOS
- Smart scheduling for donation timing

---

## 👩‍💻 Team Details
**Project Title:** ZeroBite – A Real-Time Food Donation and Waste Management System

**Team Members:**  
- Alin Jebitha B – 211423104032  
- Amrin Joshiga A – 211423104036

**Guide:** Mrs. K. Cinthuja

🎥 Project Demo
📽️ Watch Demo Video on Google Drive

🧾 Conclusion
ZeroBite helps reduce food wastage and promotes community responsibility by connecting donors and NGOs through real-time technology.
It serves as a bridge between surplus food providers and organizations in need.

📜 License
This project is developed for academic use only.
© 2025 ZeroBite Team. All rights reserved.
