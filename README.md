Here's a README.md file for your IDOR Lab project. It includes installation steps, usage instructions, an example attack scenario, and a note on fixing IDOR vulnerabilities.


---

IDOR Lab - Insecure Direct Object References

A simple web application demonstrating IDOR (Insecure Direct Object References) vulnerability. Users can modify the ?id= parameter in the URL to access unauthorized user profiles.


---

📁 Project Structure

IDOR-Lab/
│── public/
│   ├── index.html       # Login Page
│   ├── profile.html     # Vulnerable Profile Page (IDOR)
│   ├── script.js        # Handles authentication & API requests
│   ├── styles.css       # Basic styling
│── server.js            # Backend API (Express.js)
│── package.json         # Dependencies
│── README.md            # Project Documentation


---

⚙️ Setup & Installation

1️⃣ Clone the repository

git clone https://github.com/yourusername/IDOR-Lab.git
cd IDOR-Lab

2️⃣ Install dependencies

npm install express express-session

3️⃣ Start the server

node server.js

4️⃣ Open in Browser

Login Page: http://localhost:3000

Vulnerable Profile Page: http://localhost:3000/profile.html?id=1
