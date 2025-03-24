IDOR Lab - Insecure Direct Object References

A simple web application demonstrating IDOR (Insecure Direct Object References) vulnerability. Users can modify the ?id= parameter in the URL to access unauthorized user profiles.


---

⚙️ Setup & Installation

1️⃣ Clone the repository

'''bash
git clone https://github.com/yourusername/IDOR-Lab.git
'''

'''bash
cd IDOR-Lab
'''

2️⃣ Install dependencies

'''bash
npm install express express-session
'''

3️⃣ Start the server

'''bash
node server.js
'''

4️⃣ Open in Browser

Login Page: http://localhost:3000

Vulnerable Profile Page: http://localhost:3000/profile.html?id=1
