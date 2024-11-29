PharmaLive - Medicine Finder App
PharmaLive is a web-based application designed to help users quickly locate medicines at nearby pharmacies. By simply searching for a medicine, users can view a list of pharmacies that have the medication in stock, along with details like location and contact information.

Technologies Used
Frontend: HTML, CSS, JavaScript, Bootstrap
Backend: MySQL (via XAMPP for local development)
Database: MySQL
Server: XAMPP (for running the PHP server)
Features
Medicine Search: Users can search for any medicine in the search bar.
Nearby Pharmacies: View a list of pharmacies that have the searched medicine.
Location Details: Each pharmacy entry includes relevant information such as contact details, availability of medicine, and its location.
Installation
To run PharmaLive on your local machine:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/pharmalive.git
Set up XAMPP:

Install XAMPP if you haven’t already.
Start the Apache and MySQL modules in XAMPP.
Database Setup:

Open the XAMPP control panel and go to phpMyAdmin.
Create a new database (e.g., pharmalive).
Import the provided SQL file (pharmalive.sql) into the new database (if available).
Update the database connection details in your project’s config file.
Running the App:

Place the cloned project folder in your XAMPP htdocs directory (e.g., C:\xampp\htdocs\pharmalive).
Open your browser and navigate to http://localhost/pharmalive to view the app in action.
Usage
Search for Medicine:
Enter the name of a medicine in the search bar.
View Pharmacies:
After searching, view a list of pharmacies that carry the medicine you requested.
Get Details:
Each pharmacy entry provides detailed information, including address and contact number.
