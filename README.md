# Loan Management Web Application

Developed a Loan Management System using Django and MySQL with loan application, EMI tracking, admin approval workflow, and PDF receipt generation.

---

## 🚀 Features

* **User Authentication:** Secure signup, login, and profile management for borrowers and loan officers.
* **Loan Application Workflow:** Seamless submission form for applicants to apply for loans with custom amounts, terms, and purposes.
* **Admin Dashboard:** Comprehensive management panel for administrators to review, approve, or reject loan applications.
* **Status Tracking:** Real-time application updates for users to monitor the stage of their active loans.



## 🛠️ Tech Stack

* **Backend:** Python, Django Web Framework
* **Frontend:** HTML5, CSS3, JavaScript 
* **Database:** SQLite 



## 📂 Project Structure

```text
├── loan_project/          # Main project configuration directory
├── loan_app/              # Core application logic (models, views, forms)
├── templates/             # HTML templates for the user interface
├── manage.py              # Django command-line utility
└── .gitignore             # Files excluded from version control

---------
⚙️ **Getting Started**
Follow these steps to set up and run the project locally.

**Prerequisites**
Make sure you have Python installed (v3.8 or higher recommended).

**1. Clone the Repository**
Bash
git clone [https://github.com/AkashModdugalla86/loan-management-webapp.git](https://github.com/AkashModdugalla86/loan-management-webapp.git)
cd loan-management-webapp

**2. Create and Activate a Virtual Environment**
Bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate

**3. Install Dependencies**
(Note: If you have a requirements.txt file, run the following; otherwise, ensure Django is installed)

Bash
pip install django

**4. Run Migrations**
Set up your database tables by running:

Bash
python manage.py migrate
5. Create a Superuser
Create an admin account to access the dashboard:

Bash
python manage.py createsuperuser

**6. Start the Development Server**
Bash
python manage.py runserver
Open your browser and navigate to http://127.0.0.1:8000/. You can access the admin dashboard at http://127.0.0.1:8000/admin/.
