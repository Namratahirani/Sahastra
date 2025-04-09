# Sahastra

An AI-powered solution for real-time crowd monitoring, overcrowding alerts, and intelligent navigation in public spaces.
Designed to enhance safety and optimize crowd flow at events, stations, and large venues using computer vision, heatmaps, and smart routing algorithms.

Sahastra – AI-Powered Crowd Safety & Smart Navigation System
"Predict. Prevent. Protect."

Tech Stack
Frontend: Flutter (Dart), Firebase Cloud Messaging (FCM)
Backend: Python, OpenCV, Firestore, Google Cloud Storage
AI: Google Video AI & Intelligence, Smart Heatmap Generation
APIs: Firebase, Google Cloud Platform
Database: Firestore (GCP)
Hosting & Storage: Google Cloud Services
Problem Statement
Public spaces, events, and commute systems often face the risk of overcrowding, stampedes, and delayed emergency response due to the lack of real-time monitoring and automated navigation systems.
Manual approaches are reactive and slow, putting public safety at risk.

Our Solution
Sahastra is an AI-based crowd management and safety system that provides:

Real-time monitoring of crowd density using live CCTV feeds and heatmaps
Smart navigation to guide users through safer, less congested routes
Automated alerts and an SOS system for instant emergency communication
Admin dashboard for real-time monitoring, security deployment, and evacuation protocols
Symbiotic Control System:
Enables both users and authorities to act dynamically via a unified platform, ensuring real-time coordination and enhanced public safety.

Features
User Features
Live Crowd View: Get real-time crowd density updates at key points (e.g., Main Entrance, Food Court)
Smart Navigation: Enter start and destination points to receive the safest route
Automated Alerts: Receive overcrowding notifications and venue updates
SOS: Trigger emergency help, with a 10-second cancelation window
Admin Features
AI-Powered Monitoring: Detects crowd surges using Google Intelligence
Admin Dashboard: Manage users, monitor live crowd data, and deploy response teams
SOS & Alerts Management: View incoming SOS alerts and overcrowding warnings
Customized Alerts: Admin can customize alerts based on crowd severity (if required)
How to Run the Project
Backend Setup (Python + Flask + Firestore)
Install dependencies:

pip install -r requirements.txt
Configure Google Cloud service account and Firestore credentials

Run the server:

python app.py
Frontend Setup (Flutter App)
Fetch dependencies:

flutter pub get
Set up Firestore integration

Launch the app:

flutter run
How to Use the App
Login Page
Choose access type:

User
Admin
For Users
View real-time crowd density by location
Get safest navigation path
Receive live alerts for overcrowding and important updates
Send SOS requests
For Admins
Monitor real-time crowd density
Respond to SOS requests
AI-generated alerts
API Key Setup
To run this project: Service Account JSON Key Place your Google Cloud service account JSON key file in the backend folder. Update the path in the code with your JSON key and credentials. Gemini API Key Replace "GEMINI_API_KEY" in the code with your actual Gemini API key. Store it securely (e.g., in a .env file if you're using environment variables).

About
An AI-powered solution for real-time crowd monitoring, overcrowding alerts, and intelligent navigation in public spaces. Designed to enhance safety and optimize crowd flow at events, stations, and large venues using computer vision, heatmaps, and smart routing algorithms.

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Create a new release
Packages
No packages published
Publish your first package
Languages
Python
55.2%
 
Dart
44.7%
 
Procfile
0.1%
Suggested workflows
Based on your tech stack
Python Package using Anaconda logo
Python Package using Anaconda
Create and test a Python package on multiple Python versions using Anaconda for package management.
SLSA Generic generator logo
SLSA Generic generator
Generate SLSA3 provenance for your existing release workflows
Publish Python Package logo
Publish Python Package
Publish a Python Package to PyPI on release.
More workflows
Footer
