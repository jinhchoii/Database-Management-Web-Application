# Database-Management-Web-Application
How to Test on your settings

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
