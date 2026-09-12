<p align="center">
  <a href=""><img width="200" height="200" src="https://github.com/Soljira/Student-Handbook-App/blob/main/app/src/main/res/mipmap-xxxhdpi/ic_launcher_round.webp"></a>
</p>
<h1 align="center">Student Handbook App</h1>
<p align="center">
  <img src="https://img.shields.io/badge/status-archived-lightgrey?style=for-the-badge" alt="Status: Archived">
  <img src="https://img.shields.io/badge/type-school%20project-blue?style=for-the-badge" alt="School Project">
  <img src="https://img.shields.io/badge/ITE%20393-Application%20Development-orange?style=for-the-badge" alt="ITE 393">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white" alt="Kotlin">
  <img src="https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=white" alt="Android">
  <img src="https://img.shields.io/badge/Android%20Views-XML-3DDC84?style=flat" alt="Android Views">
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black" alt="Firebase">
  <img src="https://img.shields.io/badge/Google%20Maps-4285F4?style=flat&logo=googlemaps&logoColor=white" alt="Google Maps">
</p>

---

> [!IMPORTANT]
> **Archived & No Longer Maintained**
> This project is archived as of 2025. It was developed solely as an academic requirement for **BSCS2-2S: ITE 393 - Application Development** and is **not affiliated with, endorsed by, or officially connected to PHINMA University of Pangasinan**.
> No further features, bug fixes, or security updates will be provided. Feel free to fork for learning purposes.

Stay on top of your educational journey with your **Student Handbook App.**

The Student Handbook App helps students stay informed, organized, and connected. It features secure login with Firebase Authentication, profile management, and an event tracker for school activities. Access the student manual, scholarship info, and class modalities easily. The FAQ-based support chat provides quick answers, while the navigation drawer keeps everything within reach.

Simplify your school experience with the Student Handbook App — your all-in-one academic companion.

---

<h2>Screenshots</h2>

![](https://github.com/user-attachments/assets/5fe68a5c-54a7-4c9b-8a39-843e635cb301)

| ![](https://github.com/user-attachments/assets/e3f11c53-16af-41f0-a248-2d5b032919ec) | ![](https://github.com/user-attachments/assets/06cbb56c-e880-4b7b-a9a7-148b59864b7a) | ![](https://github.com/user-attachments/assets/326323ba-8961-4f6e-a202-91fa5e1b58ee) |
|---|---|---|
| ![](https://github.com/user-attachments/assets/7d2cd741-5924-48a6-983c-abff4f92deb6) | ![](https://github.com/user-attachments/assets/469e7dac-4a48-4a51-b031-483f6bb3aeef) | ![](https://github.com/user-attachments/assets/6cb14c8c-44ad-4abd-a867-5213aa00e9f7) |

---

## What the project does

Student Handbook App is a native Android app built with **Kotlin + Android Views (XML)** that centralizes essential student resources:

- **School Selection** - onboarding flow for campus context
- **Login & Profile Management** - secure authentication via Firebase Authentication
- **Event & Calendar Tracking** - track school activities and academic events
- **Student Manual & Scholarship Info** - quick access to policies, guidelines, and scholarships
- **Class Modalities** - view learning delivery modes
- **FAQ-Based Support Chat** - offline FAQ data for instant answers
- **Navigation Drawer** - clean, accessible navigation for all modules
- **Maps Integration** - campus/location features via Google Maps SDK

<h2>Highlights</h2>

- School Selection
- Login & Profile Management
- Event & Calendar Tracking
- Student Manual & Scholarship Info
- FAQ-Based Support Chat
- Easy Navigation with Drawer Menu

## Why the project is useful

- **For students:** One app to find manual rules, scholarships, events, and support instead of searching scattered PDFs and FB posts.
- **For ITE 393:** Demonstrates core Android concepts — Firebase Auth, Firestore/Realtime DB, RecyclerView, Navigation Component, Material Design, and Maps API integration.
- **For portfolio:** Shows end-to-end app development from UI in XML to Firebase backend integration, built as a real-world academic use case.

## How users can get started with the project

This project is archived, but you can still run it locally for learning.

**Prerequisites**
- Android Studio Ladybug or newer
- JDK 17
- Android SDK 24+
- Firebase Project

**1. Clone**
```bash
git clone https://github.com/fpaulpalis/student-handbook-app.git
cd student-handbook-app
```

**2. Firebase Setup**
1. Create a project at [Firebase Console](https://console.firebase.google.com/)
2. Enable Authentication (Email/Password)
3. Download `google-services.json` and place it in `/app/` folder (Project view)

**3. Maps API Key**
1. Get a key from [Google Cloud Console > Maps SDK for Android](https://console.cloud.google.com/)
2. Open `local.properties` in project root and add:
```properties
MAPS_API_KEY=YOUR_API_KEY_HERE
```
> Contact original owner `Soljira` if you are forking the upstream template that used `MAPS_KEY`.

**4. Run**
- Sync Gradle and Run on emulator or device.

## Where users can get help with your project

Since this repo is **archived**, active support is limited:

- **Check FAQ Chat in-app:** Most common questions are answered inside the app's support module.
- **Open an Issue:** Use GitHub Issues for documentation questions. Response is not guaranteed due to archived status.
- **Read the docs in code:** See `app/src/main/` for feature implementation reference.
- **Upstream reference:** Original template at `Soljira/Student-Handbook-App`

> For security issues, please do not open a public issue. This project will not receive security patches.

## Who maintains and contributes to the project

**Status: Archived - No active maintainer**

This project was developed as a school activity for **BSCS2-2S: ITE 393 - Application Development** and is now archived. Contributions are closed, but you are welcome to fork for learning purposes.

**Submitted By:**
- Jilbert Danao
- Rainer Fernandez
- Leeian Lacorte
- Breiah Mendavia
- Francis Paul Palis
- Cyrus Jr. Saguiped
- Gabriel Iñigo Simon

**Submitted To:**
- Sir Chocen Peronilla

**Disclaimer:** This application was developed solely as an academic requirement. It is an independent student project and is strictly not affiliated with, endorsed by, or officially connected to PHINMA University of Pangasinan or any of its institutions.

---
<p align="center">Made for ITE 393 - BSCS2-2S | Submitted to Sir Chocen Peronilla</p>
