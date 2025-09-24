Namaste ICD-11 API Demo

A demonstration project that integrates NAMASTE (Ayush Terminology Service) with ICD-11 (International Classification of Diseases, 11th Revision).
It simulates how clinicians can:

Search traditional medicine (Ayurveda, Siddha, Unani) diagnoses.

Map them to ICD-11 biomedical + TM2 codes.

Generate FHIR Condition resources for digital health records.

Visualize aggregated data in a National Morbidity Dashboard.

🚀 Features

Clinician Portal: Search NAMASTE diagnoses and map to ICD-11 codes.

FHIR Resource Generator: Creates dual-coded FHIR Condition resources.

Simulated ABHA Login: Simple ABHA ID + OTP entry.

Patient Record Simulation: Add diagnoses to a patient record.

Analytics Dashboard:

Stats on logged diagnoses

Top 5 conditions

Heatmap of Indian states

🛠️ Tech Stack

Frontend: HTML, TailwindCSS, Chart.js

Mock Data: NAMASTE terms + ICD-11 codes (JSON in JS)

No Backend Needed: Fully client-side demo (can be extended with APIs)

📦 Getting Started

Clone the repository:

git clone https://github.com/your-username/namaste-icd11-api.git
cd namaste-icd11-api


Open the project:
Just double-click app.html or open it in a browser.

👉 No server setup required.

📖 How to Use

Login Simulation

Enter ABHA ID (12-3456-7890-1234) and OTP (123456).

Click Login via OTP.

Clinician Portal

Search by NAMASTE term or keyword (e.g., fever, jwara, amavata).

Select a diagnosis.

Map to ICD-11 biomedical and TM2 codes.

Generate a FHIR Condition Resource.

Add it to the patient record.

Analytics Dashboard

See total cases, system-wise counts, and hotspots.

View Top 5 diagnoses in a bar chart.

Explore geographic distribution via the India map.

📌 Demo Screenshot

(Add your screenshot here, e.g. ![screenshot](screenshot.png))

📌 Roadmap

 Connect to live NAMASTE terminology API

 Fetch real ICD-11 entities via WHO APIs

 Add backend for persistence (Flask/Django/FastAPI)

 Enable authenticated clinician workflows

🤝 Contributing

Fork the repo

Create a branch (feature/new-idea)

Commit changes

Push and create a PR

📜 License
