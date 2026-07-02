# RemoMed - Remote Patient Telehealth & Interactive Clinical Records

https://tiny-haupia-9e09ea.netlify.app/ 

RemoMed is a highly aesthetic, responsive, and secure telemedicine portal designed specifically for modern medical practitioners. It bridges the gap between digital laboratory networks, patient self-monitoring, and virtual clinic management, allowing doctors to comprehensively care for their patients remotely without requiring physically repetitive in-person visits.

The system is optimized for doctors to easily track patient medical histories, view direct-to-patient lab reports (sent from prominent laboratory networks like Asiri Labs, Durdens, and Lanka Hospitals), write digital prescriptions, and conduct interactive tele-consultations all from a single window.

🌟 Core System Workflows

┌────────────────────────┐      ┌────────────────────────┐      ┌────────────────────────┐
│   Laboratory Tests     │ ───> │  SMS Sent to Patient   │ ───> │ Patient Syncs to Port. │
│ (Asiri, Lanka, Durdens)│      │   (With secure PDF)    │      │  (Instantly received)  │
└────────────────────────┘      └────────────────────────┘      └────────────────────────┘
                                                                            │
                                                                            ▼
┌────────────────────────┐      ┌────────────────────────┐      ┌────────────────────────┐
│  Interactive Vitals   │ <───  │ Telehealth / Live Chat │ <───  │  Doctor Portal View    │
│  (Sugar, BP, O2, Chol) │      │  (Video & SMS Console) │      │ (PDF Viewer & Metrics) │
└────────────────────────┘      └────────────────────────┘      └────────────────────────┘


Seamless SMS-to-Portal Document Sync: Patients get their laboratory tests done at localized diagnostic centers. Since lab systems deliver official PDFs directly to patients' smartphones via secure SMS links, RemoMed intercepts or enables direct client-to-doctor document syncing.

Clinical Document Verification: The doctor receives authentic lab PDFs directly in the patient file database. An interactive PDF reader parses these documents to display biological reference ranges, highlighting alarming parameters with visual "Alert Flags."

Continuous Physiological Monitoring: Rather than viewing a single test result in isolation, the doctor views automated longitudinal charts plotting vital parameters (Blood Glucose, Blood Pressure, SpO2, and Cholesterol) tracked over time to spot clinical deviations.

Immediate Treatment Decisions: The physician can initiate a high-definition video consult, text secure clinical advice via SMS, or draft a digital prescription (Rx) to be texted to the patient's phone instantly.

🎨 Liquid Glass Design Philosophy

Clinician burnout and digital screen fatigue are real problems. RemoMed solves this with a customized, doctor-focused visual grammar:

Eye-Pleasing Light Aesthetics: Replaces harsh high-contrast dark modes or generic hospital-white canvases with soft, low-intensity pastel teals, mints, and light blues.

Translucent Glassmorphic Containers: Semi-transparent glass panes (backdrop-filter: blur(20px)) float on top of an organic background, reducing visual noise and dividing information into natural mental silos.

Ambient Fluid Blobs: Animated background meshes gently pulsate in the background to provide a calming, non-distracting screen depth, easing stress during long clinical shifts.

Slate Typography Scale: Utilizing premium sans-serif typography (Plus Jakarta Sans & Inter) styled in dark slate shades to prioritize optimal reading legibility over harsh blacks.

🚀 Key Features

Secure Practitioner Entrance: Integrated splash-screen loader leading into a secure Doctor Access Login simulation.

Adaptive Specialty Module: Allows any medical practitioner to customize their title and adapt their active specialty (e.g., Dermatologist, General Physician, Cardiologist, Endocrinologist, Pediatrician).

Smart Patient Directory: Instant search query bar mapping names, IDs, or contact details, featuring real-time clinical triage indicators (Stable, Warning, Critical).

Active Clinical Console:

Digital Prescription (Rx) Editor allowing instantaneous SMS distribution to patients.

Document Center compiling received laboratory PDFs with simulated document viewers.

Integrated Telemedicine Hub: Fully interactive, responsive video & voice tele-calling simulator alongside a live SMS messenger pane.

Multi-Parameter Tracking Graphs: Beautiful line charts powered by Chart.js tracking dynamic physiological trends across multiple months.

🛠️ Technology Stack

Structure: Single File Architecture (HTML5)

Styling: Tailwind CSS (Fluid Layouts & Glassmorphic variables)

Icons: Lucide Icons (Modern line iconography)

Charts: Chart.js (Canvas-based responsive vector tracking graphs)

Typography: Google Fonts (Plus Jakarta Sans & Inter)

💻 Installation & Quickstart

Because RemoMed is built on a highly optimized, client-side Single File Architecture, getting it running is incredibly simple:

Clone this repository:

git clone https://github.com/your-username/remomed-portal.git


Navigate to the project folder:

cd remomed-portal


Open index.html directly in any web browser (Chrome, Safari, Edge, Firefox):

# On macOS
open index.html

# On Windows / Linux
double-click index.html in your file explorer


Login Credentials (Simulated):

Email: dr.chalukya@remomed.lk

Password: Any secure key combinations (Pre-filled)

### screenshots 

<img width="1917" height="914" alt="Screenshot 2026-07-02 151054" src="https://github.com/user-attachments/assets/ac928a5a-53c9-4ac2-9c56-723db1c6be9a" />

<img width="1917" height="916" alt="Screenshot 2026-07-02 151111" src="https://github.com/user-attachments/assets/178d3582-952e-4a19-be74-6050f44dd212" />

<img width="1917" height="911" alt="Screenshot 2026-07-02 151202" src="https://github.com/user-attachments/assets/96858fa1-4ebf-4c52-a0c4-3e9f0f5ceeac" />

<img width="1917" height="915" alt="Screenshot 2026-07-02 151804" src="https://github.com/user-attachments/assets/72e8fac2-fbe2-423f-8c7e-e24b5c92be22" />
