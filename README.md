
# Medication Reminder App
The Medication Reminder App helps caretakers (doctors and nurses) manage medications for their patients efficiently. Patients can also use the app to track their medications and receive timely reminders.
# These are some of the User Stories we are to implement
# User Registration
•	As a new user, I want to register with my name, email/phone number, and username.
•	As a new user, I want to choose whether I am a patient or a caretaker (doctor/nurse) during registration.
# Profile Management
•	As a caretaker (doctor/nurse), I want to create my profile with details such as my name and organization/hospital name.
•	As a patient, I want to create my profile with details such as my name, location, gender, and assigned doctor.
# Patient Management
•	As a caretaker (doctor/nurse), I want to add patients I am responsible for, including their details (name, location, gender, doctor).
•	As a caretaker (doctor/nurse), I want to add medications for each patient, specifying sickness name, medication name, and prescription.
•	As a caretaker (doctor/nurse), I want to set reminders for each medication added to a patient.
# Medication Reminders
•	As a caretaker (doctor/nurse), I want to receive notifications/reminders for each medication added to a patient.
•	As a patient, I want to receive notifications/reminders for each medication prescribed to me.
## Patient Interaction
•	As a user, I want to view a list of all patients I have added.
•	As a user, I want to view details about each patient, including their medications and reminders.
•	As a user, I want to edit patient information (both general and medication details).
# Medication Verification
•	As a caretaker (doctor/nurse), I want to verify if a patient has taken their medication based on the set reminders.
•	As a caretaker (doctor/nurse), I want to record and save verification statements including the medication name, reminder details, and verification date.
## Record Keeping
•	As a caretaker (doctor/nurse), I want to generate PDF statements of verification records for downloading and future reference.
# Functional Requirements
**User Authentication and Registration**
•	The app will provide a user registration and login mechanism.
•	Users will be able to register either as patients or caretakers (doctors/nurses).
# Profile Management 
•	Caretakers (doctors/nurses) will be able to create and update their profiles, including their names and organization/hospital names.
•	Patients will be able to create and update their profiles, including their names, locations, gender and assigned doctors.
Patient and Medication Management
•	Caretakers (doctors/nurses) will be able to add new patients, edit patient details, and delete patients from their list.
•	Caretakers (doctors/nurses) will be able to add medications for each patient, including sickness names, medication names, prescriptions, and set reminders for each medication.
# Medication Reminders
•	Users (both caretakers and patients) will receive timely reminders for medications set by caretakers.
# Patient Interaction
•	Users will be able to view a list of all patients they have added.
•	Users will be able to view detailed information about each patient, including their medications and reminders.
•	Users will have the ability to edit patient information, both general details and medication details.
# Medication Verification and Record Keeping
•	Caretakers (doctors/nurses) will be able to verify if a patient has taken their medication based on the set reminders.
•	Verification records will be recorded and saved, including the medication name, reminder details, and verification date.
•	Caretakers (doctors/nurses) will be able to generate PDF statements of verification records for downloading.
# User Interface
•	The app will have an intuitive and user-friendly interface designed with Flutter.
•	Navigation between different screens and functionalities will be seamless and straightforward.
## Below are the APIs we will use to develop our app
 # 1 User Authentication and Registration:
•	We will use Firebase Authentication to securely handle user login and sign-up.
 # 2 Local Notifications:
•	We will set up a notification system to remind users when it's time to take their medications.
# 3  PDF Generation:
•	We will implement a PDF generator to create and manage documents for medication schedules and records.
 # 4 State Management:
•	We will manage app state to ensure data is updated and accessible across different parts of the app.
# 5 Navigation:
•	We will use Flutter's navigation system to help users move between different screens and functionalities.
#  6 Database Integration:
•	We will integrate Firebase Realtime Database or Fire store to store and retrieve patient details, medications, and verification records securely.
# 7 Date Time and Time zone Handling:
•	We will handle date and time zones to accurately schedule medication reminders regardless of the user's location.
# 8 UI Components:
•	We will design intuitive UI components using Flutter's Material and Cupertino widgets for a user-friendly experience.
# 9 PDF Viewer:
•	We will integrate a PDF viewer to allow users to view saved documents directly within the app.
#  10 Other Considerations:
•	We will use a form builder to create dynamic forms for user input during registration and profile management.
