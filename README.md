# PatientPilot AI

I wanted to build something around healthcare tech, so I put together PatientPilot. It's a Python web app where I can explore fictional patient records, ask questions about them, and experiment with a few care-navigation ideas.

**[Live app](https://patientpilot-ai-dwit.streamlit.app/)** · **[GitHub](https://github.com/dwitdev)**

## What I built

- A patient dashboard for sample labs, medications, appointments, allergies, and insurance info
- A record-search assistant with optional Gemini answers based on the selected patient's data
- Draft appointment, refill, clinic, and insurance requests with an approval step
- A read-only FHIR sandbox explorer and hospital search/directions links
- Patient-specific checks, basic activity logs, and automated Python tests

## Stack

**Python** · **Streamlit** · **Google Gemini API** · **JSON / FHIR-style records** · **REST APIs** · **GitHub Actions** · **unittest**

I started with the patient dashboard, added the chatbot, then built out the request workflow and FHIR sandbox features. It was a good way for me to get more comfortable working with Python, external APIs, session state, testing, and web app design.

## Screenshots

### Patient dashboard
![PatientPilot dashboard](Screenshot%202026-10-30%20002839.png)

### Patient records
![PatientPilot records](Screenshot%202026-10-30%20003010.png)

### Care workflow
![PatientPilot workflow](Screenshot%202026-10-30%20003047.png)

This is a personal learning project using **fictional patient data only**. Care requests are simulated and nothing is sent to real doctors, pharmacies, or insurers. It isn't a medical service or a place to enter private health information.
