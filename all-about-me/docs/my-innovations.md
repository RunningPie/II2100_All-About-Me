# The AI-Powered Public Health Vending Machine

<img src="https://raw.githubusercontent.com/RunningPie/II2100_All-About-Me/refs/heads/main/all-about-me/docs/img/my_innovations_infographic.png" alt="Visual infographic defining the features of the AI-Powered Health Kiosk" height="40">

## System Architecture: The PUDAL Control Cycle
The core innovation is an AI-Powered Public Health Vending Machine designed to execute the PUDAL (Perception, Understanding, Decision, Action, Learning) cycle autonomously. This is not a passive vending machine; it is an intelligent clinical node.

Perception (Sensors): The kiosk is equipped with a multi-modal sensor array, including FDA-cleared peripherals for blood pressure, SpO2, and temperature. Crucially, it integrates Computer Vision using depth sensors (AutoDepth) to analyze minor injuries. This allows the machine to "see" a wound, calculate its dimensions, and characterize tissue type (e.g., granulation vs. slough) without human intervention.

Understanding & Decision (The AI Mind): The "brain" of the system utilizes a GAMENet (Graph Augmented Memory Networks) architecture. This advanced NLP model processes the patient’s self-reported symptoms and vital signs, cross-referencing them with anonymized electronic health records (EHR) and drug interaction databases. The innovation here is the system’s ability to triage: it distinguishes between a minor ailment (treatable on-site) and an emergency (requiring immediate referral), acting as a safe, automated gatekeeper.

Action (Robotic Dispensing): Unlike telemedicine apps, this machine performs a physical action. It features a robotic dispensing unit capable of delivering Over-the-Counter (OTC) medications, first aid supplies, and "smart bandages" that monitor healing. This closes the care loop instantly, diagnosis and treatment happen in one session.

## The "Energy" and "Heart" Modules: Sustainability and Education
To ensure the system is a true "Mahakarya Rekayasa" (Masterpiece of Engineering), the design integrates the PSKVE Engine (Product, Service, Knowledge, Value, Environmental).

Environmental Energon (Power): To solve the "Last Mile" problem in off-grid locations, the innovation includes a Solar-Plus-Storage power system. Similar to [the "Telemedan" project](https://www.telemedan.org/), this allows the kiosk to operate independently of unstable local grids, ensuring 24/7 reliability which is critical for emergency triage.

Value & Knowledge (Education): The machine is designed to be a pedagogical tool. Utilizing the idle time during dispensing or triage, the screen delivers targeted health education (Health Promotion). If a user buys diabetes test strips, the AI generates a personalized "nudge", a short, interactive video on blood sugar management, tailored to the user's literacy level. This transforms a transaction into a learning moment, directly improving community health literacy.

Federated Learning (Privacy): To protect "Homocordium" (trust), the system uses Federated Learning. Patient data remains on the local edge device; only the mathematical model updates are shared to the cloud. This ensures the collective intelligence of the network improves without ever exposing sensitive personal data, addressing privacy concerns that often derail digital health projects.