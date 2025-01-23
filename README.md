# ## Healthcare Management System

## Overview

The Healthcare Management System is a comprehensive platform designed to streamline hospital management and improve patient care. It provides seamless integration of various healthcare functionalities through dedicated portals for Admins, Doctors, and Patients.

Features

# 1. Admin Portal

Approve or reject appointments, doctors, and patients.

Discharge patients and generate bills.

Full access to all system functionalities.

# 2. Doctor Portal

Secure login and registration with admin approval.

View assigned patients and their records.

Manage appointments (view/cancel).

Access discharged patient records.

# 3. Patient Portal

Secure login with OTP verification.

Access personal health records.

Book, reschedule, or cancel appointments.

Receive warnings if booking on holidays.

View all available doctors.

# 4. Prescription Portal

Patients can input symptoms.

ML model predicts medicines, precautions, diets, and disease descriptions.

Personalized recommendations based on health conditions.

# 5. Nearby Hospital Locator

View nearby hospitals based on location.

Get directions and contact details.

Distance calculation for each hospital.

# 6. About Page

Provides complete information about the platform.

# 7. Contact Us
Users can send feedback or report issues to the admin.
# Some photos of Medicare
![Screenshot 2025-01-22 234330](https://github.com/user-attachments/assets/e4fcecd2-ccde-48ed-978c-79161a703a80)
![Screenshot 2025-01-23 185712](https://github.com/user-attachments/assets/6dfb177e-6e41-40f8-afe2-56d7435140dc)
![Screenshot 2025-01-23 185850](https://github.com/user-attachments/assets/b14ecc2e-c610-4b85-bb40-a22c7155ef4f)
![Screenshot 2025-01-23 185947](https://github.com/user-attachments/assets/b2888df2-8d00-419a-b618-8478046228b3)




# Instructions to start
 ```bash
1. Clone this repo:
 
git clone https://github.com/FlopCoder35/healthcare_system
cd healthcare_system

2. Create a virtual environment and activate it:
 
python -m venv venv
venv\Scripts\activate

3. Install dependencies:

pip install -r requirement.txt

4. Apply migrations:

python manage.py migrate

5. Create a superuser:

python manage.py createsuperuser

6. Run the server:

python manage.py runserver




 
