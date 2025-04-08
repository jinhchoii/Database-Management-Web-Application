# Database-Management-Web-Application
![스크린샷 2025-04-08 020816](https://github.com/user-attachments/assets/59c68e3a-0afa-4c45-b0fd-363e03502442)

This is a web-based application built using PHP and MySQL for managing an academic conference. It includes features for attendee registration, session scheduling, sponsor management, and more.

**Video Demo Link:
https://www.youtube.com/watch?v=hXhwl1mGloc

## Technologies Used
- PHP (with PDO)
- MySQL
- HTML/CSS
- XAMPP / phpMyAdmin


## Setup Instructions

✅ How to Run the Conference Web Application
🧳 What’s included in the conference.zip:
- All PHP files (e.g., conference.php, pages/, includes/)
- CSS and images
- Database setup script: conferenceDB.txt (rename to .sql if needed)

🛠 Requirements:
- [XAMPP](https://www.apachefriends.org/download.html) installed (includes Apache + MySQL)
- Web browser (Chrome, Firefox, etc.)

🔄 Step-by-Step Setup Instructions:
1. Extract the project files
- Unzip conference.zip to the htdocs/ folder in your XAMPP installation directory.
Example path:
C:\xampp\htdocs\conference

2. Start XAMPP
Open the XAMPP Control Panel

Click Start next to:
- Apache
- MySQL

3. Create the database
- Open your browser and go to:
http://localhost/phpmyadmin
- Click on the "Import" tab
- Choose the file: conferenceDB.txt (you can rename it to conferenceDB.sql)
- Click Go to import the schema and test data

💡 The script will automatically DROP, CREATE, and POPULATE the ConferenceDB database.

4. Access the application
In your browser, go to:
http://localhost/conference/conference.php
