IDOR Lab - Insecure Direct Object References

A simple web application demonstrating IDOR (Insecure Direct Object References) vulnerability. Users can modify the ?id= parameter in the URL to access unauthorized user profiles.


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
