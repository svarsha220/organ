# CareBridge-organ
# Introduction
The organ donation website is a platform designed to bridge the gap between organ donors, patients in need, doctors, and administrators. It aims to raise awareness about the importance of organ donation and streamline the process of matching donors with recipients. By simplifying the management of organ availability and doctor schedules, the website facilitates life-saving interventions in an efficient and user-friendly manner.

# Features
*  <h3>User Roles and Actions</h3>
* ***Donor***:
 Register their willingness to donate organs.
 Update details about the organs they are willing to donate.
* ***Patients***:
Submit requests for specific organ needs.
Update personal details and requirements.
* ***Doctors***:
Update their availability for surgeries and consultations.
View assigned tasks related to transplants.
* ***Admin***:
Manage the entire workflow, including donor and patient records.
Assign doctors to patients in need.
Monitor organ availability and ensure data consistency.

* <h3>Statistics and Awareness</h3>
Real-time information on the number of patients in need.
Educational content highlighting the impact of organ donation.
Call-to-action sections to encourage participation.

*  <h3>Interactive Dashboard</h3>
Simple and intuitive interface for each user role.
Navigation buttons for donors, patients, doctors, and administrators.

*  <h3>Local Storage for Data</h3>
Data is stored locally using PHP and organized for quick retrieval.
Ensures privacy and security of sensitive user information.

# Technologies Used
*  <h3>Frontend</h3>
HTML5, CSS3, and JavaScript for a responsive and visually appealing user interface.
Graphics and icons to enhance usability and clarity.

*  <h3>Backend</h3>
PHP: Used to handle server-side logic, manage user interactions, and communicate with the local storage.
Local Storage: Data is stored efficiently to support user actions and maintain session details.

*  <h3>Database</h3>
Local database setup using PHP for storing donor, patient, and doctor information securely.

*  <h3>Additional Tools</h3>
Streamlined File Handling: Efficiently processes data updates and form submissions.
Session Management: Tracks user activity to ensure smooth navigation and secure transactions.

# Implementation:

* # Home Page :
The homepage serves as an introduction to the platform, allowing users (patients, doctors, donors, and admins) to log in or register. It provides links to key sections and explains the platform's purpose. Once logged in, users are directed to their respective dashboards based on their roles. Features include a welcome message, navigation to doctor details, donation options, patient requests, and admin control. It offers easy access for each user type, ensuring smooth interaction and guiding users to the resources they need.

![Screenshot 2024-12-28 195739](https://github.com/user-attachments/assets/5898fe0f-0789-42f0-b088-71f468093352)
![Screenshot 2024-12-28 195756](https://github.com/user-attachments/assets/68a42454-62dd-41bb-bdf5-fd4bb4830be3)

* # Donor Page :
The Donor Page allows donors to register and update their willingness to donate (e.g., blood, organs). Donors can specify their donation preferences, such as the type of donation and preferred locations. They can view their donation history and respond to donation requests based on patient needs. The page ensures easy management of donor profiles, offering a way to update availability and willingness. It also displays a list of patients or hospitals needing donations, enabling donors to select those they can assist. The page aims to facilitate the matching of donors with patients in need.

![Screenshot 2024-12-28 195834](https://github.com/user-attachments/assets/a2d4e49c-6773-4a73-b271-5b40fc8b7b64)

* # Doctor Detail Page :
The Doctor Detail Page showcases the doctor's profile, including name, specialization, experience, and contact details. It displays available time slots for consultation, which doctors can update. Patients can book appointments based on availability and specify medical concerns. Additional sections include the doctor’s consultation fees, location, and services offered. Reviews and ratings from previous patients can be seen to help others make informed decisions. This page facilitates a seamless connection between patients and doctors, allowing patients to choose and schedule appointments efficiently.

![Screenshot 2024-12-28 195848](https://github.com/user-attachments/assets/49d31f1b-3d6c-4ef8-b02e-60a4f6c8f80e)

* # Admin Page
The Admin Page is a central management interface for overseeing the platform’s operations. Admins can manage user accounts (patients, doctors, donors), approve or reject registrations, and disable accounts. They can monitor doctor availability and schedules, review patient requests, and ensure timely matching with donors. The page provides analytics and reports to track user activity and platform health. Admins can send notifications to users and manage platform settings, including security features. It ensures smooth operations by giving admins control over all activities, ensuring the platform runs efficiently and securely.

![Screenshot 2024-12-28 195912](https://github.com/user-attachments/assets/5b2b48d0-91fb-4638-84b4-c7ffcd3d8eda)

* # Patient Page
The Patient Page allows patients to request organ donations, update their medical needs, and provide personal details. Patients can specify the type of organ needed (e.g., kidney, liver, etc.), urgency, and any relevant medical information. They can also update their personal information, such as contact details and medical history, to ensure accurate matching with donors. The page enables patients to track the status of their requests and communicate with doctors and admin regarding their needs. This page serves as a central hub for managing organ donation requests and receiving timely assistance from the platform.

![Screenshot 2024-12-28 195952](https://github.com/user-attachments/assets/090e656d-2429-406a-baca-68f3f97b125a)

# Future Enhancement :
1. <h3>Real-Time Data Syncing with MongoDB</h3>
Enhancement: Enhance MongoDB integration to ensure real-time syncing of data (e.g., doctor schedules, patient requests, donations) across all user interfaces.
Tech: Utilize MongoDB’s change streams for real-time data updates.

2. <h3>Real-Time Notifications</h3>
Enhancement: Implement real-time notifications for patients, doctors, and donors about updates or changes (e.g., appointment confirmations, donation requests, status updates).
Tech: Use WebSockets or services like Firebase to push notifications directly to users.

3. <h3>AI Chatbot for Patient Queries</h3>
Enhancement: Integrate an AI-powered chatbot that can assist patients with common queries, booking appointments, or finding doctors, even outside working hours.
Tech: Leverage natural language processing (NLP) with frameworks like GPT-3, Rasa, or Dialogflow.



