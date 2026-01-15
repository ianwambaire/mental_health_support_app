# Mental Health Support Application 

This is a mobile mental health support application designed for young adult patients and therapists, as part of Strathmore's Bachelors of Informatics and Computer Science CS Project Unit.

## The Project Members
This project was completed by the following students:
- Wambaire Ian Nganga - 159799
- Mohamed Junaid Chaudhry - 166335

The project was also supervised by **Dr. Esther Khakata**.

## Application Features
The application has two users, each with their own set of features. These are the patients and therapists.

### Patient Features
- [x] Finding and requesting for a therapist
- [x] Booking appointments with a therapist
- [x] Sentiment/mood analysis tracking using the DASS-21 questionnaire
- [x] Meditation system with background soundtracks
- [x] Journaling system

### Therapist Features
- [x] Viewing patient details
- [x] Seeing bookings with patients

### Features For Both Users
- [x] Loging in and signing up
- [x] Basic account management (edit/delete account)

## Development Tools & Frameworks
The following development tools and frameworks were used in building the project:
- Flutter and Dart
- Firebase (authentication and firestore database)
##Visuals Of the Application
1. Security and Authentication Module
Users can sign up with their email address or by using Google sign in for the system. This is done by providing their username, email address, password, and in the case of therapists, their area of expertise, as shown in Figure 5.1. When registering with email and password, a verification email is also sent to verify the new account. A forgot password button is also present to help users reset their password.

<img width="203" height="153" alt="image" src="https://github.com/user-attachments/assets/008cf3b9-f096-4289-9176-c7631da3e4ea" />

5.2.1.2	Patient’s Module
i.	Patient’s Homepage
This page is only accessible to the patient once he has logged in and is shown in Figure 5.2. Patients can view the list of upcoming sessions with details like the topic to be covered, date, duration, and cost. 
ii.	Meditation Page
On the meditation page, the patient can access and play relaxing background sound audios, for example, sea waves or a forest ambience, to help relax in case he or she is feeling stressed, depressed, or anxious, as shown in Figure 5.3.

iii.	Therapist Search and Details Page
Patients can view a list of available therapists and send a request to them, as shown in Error! Reference source not found.. The patient can use the search bar to search for a therapist by name or specialty as well. Once a therapist accepts a request, the patient can view their details, along with book a session with the therapist and start a video call.



iv.	Journal Page
On the journal page, the patient can view existing journal entries, add a new entry with a title and contents, edit an entry, and delete entries, as shown in 









v.	Patient’s Profile page
On the patient’s profile page, the patients can edit their details, such as their username, and carry out actions such as logging out or deleting the account from the profile page as shown in Figure 5.6. To edit their username, the patients will have to click on edit username. The patient can also delete their account by clicking the “Delete Account” button. The therapist’s profile page is also identical to the patient's one.




vi.	Book Session Page
The patient can access the book session page by clicking the book session on the therapist details page, as shown in Figure 5.4. On this page, the patient can select a date, time, and duration for the therapy session, as shown in Figure 5.7. The cost for the therapy session will change depending on the duration selected. The patient will have to input a session topic, then book a session. They will receive a prompt to add their phone number and another prompt to confirm payment, and after the payment has been confirmed, the session will be created.






vii.	Video Call Page
Both the patient and therapist have access to the same video call page, which is shown below in Figure 5.8: Video call page.



viii.	Sentimental Analysis Form and Report
On the sentimental analysis page, the patient can fill out a sentimental analysis form, which is based on the DASS-21 test (Lovibond & Lovibond, 1994) and used to determine the patient's depression, anxiety, and stress score. As shown in Figure 5.9









5.2.1.3	Therapist’s Module
i.	Therapist’s Homepage
This page can be accessed by registered therapists after logging in to the platform. The therapist can view the upcoming therapy sessions and access notifications. The therapist can view the session details like topic, cost, duration, time, and date as shown in Figure 5.10.







ii.	Therapist’s Patients Page
 The therapist’s patients page contains a list of patients assigned to the therapist. The therapist must accept a patient's request for a patient’s details to be on this page. To view more information on the patient, the therapist can click on the patient’s card to be directed to the patient's details page, as shown in Figure 5.11.






iii.	Appointments Page
On the appointments page, the therapist can view their appointments and filter them by date, either today, this week, or this month, as shown in Figure 5.12.







iv.	Notifications page
On this page, the therapist will receive notifications such as a patient sending a request, a patient booking a therapy session, and session reminders, as shown in Figure 5.13. The therapist can delete a read notification by clicking on the bin icon or delete all the notifications and accept or reject requests.








v.	Therapist sessions Page
 On the therapist sessions page, the therapist can access all the sessions, including past and upcoming sessions. This page can be accessed when the therapist clicks on the “View All Sessions” page on the therapist’s homepage. The therapist can filter the sessions to view past sessions only, upcoming sessions, or all sessions, as shown in Figure 5.14. The therapist can edit a session’s details, such as the date, time, and duration as well.
