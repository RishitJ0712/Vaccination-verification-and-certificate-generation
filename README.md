Co-Vaccine E-Verification & Certification
Overview:
The E-Vaccine Verification System is a Python console application designed to manage vaccination data efficiently. It supports three types of users: Admin, Vaccinator, and Client. Admin can manage vaccinators, view vaccination records and statistics, and delete records. Vaccinators can log in to add new vaccination records. Clients can verify their vaccination status and generate vaccination certificates.
It provides various Features for the three type of users:
1. Admin:- Login with credentials (username: admin, password: ADMIN), admin manages vaccinators, view vaccination records and statistics, delete records.
2. Vaccinator: Login with username and password and add new vaccination records (ID, Name, Vaccine, Dose, Date)
3. Client: verify vaccination status and generate vaccination certificates

Folder Structure:
E-Vaccine-System/
├── main.py
└── modules/
├── init.py
├── admin_module.py
├── client_module.py
├── vaccinator_module.py
└── database_module.py

Installation:
1.	Click on the "Code" button and download the repository as a ZIP file.
2.	Extract the ZIP file.
3.	Install required Python packages: pandas, numpy, matplotlib
4.	Run the application using: python main.py.

Usage:
1.	Start the program by running main.py
2.	Select your role: Client, Vaccinator, or Admin
3.	Admin login is required for Admin actions
4.	Clients can verify their vaccination status and generate certificates
5.	Vaccinators can log in and add new vaccination records

Dependencies:
⦁	Python 3.x
⦁	pandas
⦁	numpy
⦁	matplotlib
⦁	pillow

Notes:
⦁	All IDs are stored as strings to ensure correct verification
⦁	Admin can manage both vaccination data and vaccinator accounts securely
⦁	Certificates are generated as simple text files
