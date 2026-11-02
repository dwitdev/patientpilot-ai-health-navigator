
# PatientPilot AI

I wanted to build something around healthcare technology, so I created PatientPilot AI. It's a Python web app where I can explore fictional patient records, ask questions about them, and experiment with how AI could make healthcare information easier to navigate.

I started with a basic patient dashboard, added a chatbot, and gradually built more features around care navigation, patient records, and request workflows.

**[Live Application](https://patientpilot-ai-dwit.streamlit.app/)** · **[GitHub Repository](https://github.com/dwitdev/patientpilot-ai-health-navigator)**

## What I Built

- **Patient Dashboard:** A central place to view fictional patient information, including medications, allergies, lab results, appointments, and insurance details.
- **AI-Powered Assistant:** A patient-specific chatbot that searches available records and can use Google Gemini to explain retrieved information.
- **Care Actions:** A workflow for drafting appointment inquiries, medication refill inquiries, clinic messages, and insurance questions with an approval step.
- **FHIR Sandbox Integration:** A read-only interface for exploring structured healthcare data from a public synthetic FHIR sandbox.
- **Care Navigation:** Hospital search and directions using Google Maps links.
- **Patient Data Isolation:** Patient switching and session-specific record access to keep fictional patient information separated.
- **Activity Tracking:** In-session logs for reviewing simulated care actions.
- **Automated Testing:** Python tests and GitHub Actions workflows for checking application functionality.

## Technologies Used

**Language:** Python

**Frontend & Framework:** Streamlit

**AI Integration:** Google Gemini API, record retrieval

**Healthcare Data:** JSON, FHIR-style resources, public FHIR sandbox

**APIs & Integrations:** REST APIs, HTTP requests, Google Maps links

**Development Tools:** Git, GitHub, GitHub Actions, Python unittest

**Deployment:** Streamlit Community Cloud

## Screenshots

### Patient Dashboard

![PatientPilot AI - Dashboard](Screenshot%202026-11-02%20005620.png)

### Patient Chat and Records

![PatientPilot AI - Chat and Records](Screenshot%202026-11-02%20005645.png)

### Care Actions Workflow

![PatientPilot AI - Care Actions](Screenshot%202026-11-02%20005731.png)

## What I Learned

Working on PatientPilot gave me more hands-on experience with Python application development, API integration, handling structured data, and building interactive interfaces.

One of the interesting challenges was keeping the chatbot's responses connected to the selected patient's records rather than relying entirely on AI-generated answers.

I also spent time working with session state, testing different workflows, organizing the application into separate modules, and deploying it so other people could try it directly in a browser.

## Important Note

PatientPilot AI is a personal portfolio project built for learning and demonstration purposes.

All patient information used in the application is fictional or synthetic. Care actions are simulated and do not send real appointment requests, prescription requests, or insurance transactions.

The application is not a medical service and should not be used for medical decisions or processing private patient information.

---

**Created by [Dwit Patel](https://github.com/dwitdev)**

**[Try PatientPilot AI](https://patientpilot-ai-dwit.streamlit.app/)**
