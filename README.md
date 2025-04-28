# 📚 College Enquiry Chatbot (Website Embedded)

This project is a **College Enquiry Chatbot** built using **Dialogflow CX** and embedded on the college website to assist students with queries related to admissions, courses, placements, and facilities.

---

## 🚀 Tech Stack Used:
- **Dialogflow CX** (Google Cloud) — Chatbot backend
- **Dialogflow CX Data Store** — Knowledge retrieval from official admission brochure PDF
- **Dialogflow Messenger** — Embedded chatbot frontend for website
- **HTML + CSS + JavaScript** — For integration with college website

---

## 🛠️ Features:
- Admission process brochure PDF integrated through Dialogflow **Data Store** for smart answer retrieval.
- Custom **intents** created for FAQs like eligibility, admission procedure, documents required, etc.
- Embedded chatbot widget into college website using **Dialogflow Messenger**.
- Spacebar scrolling issue fixed using **custom JavaScript patch**.
- No separate React/Flask server — all integration handled through **website HTML** directly.

---

## 🗂️ Project Structure:

```plaintext
college-chatbot/
├── website-integration-snippet/
│    └── index.html (or chatbot-integration.html)
├── documentation/ (optional)
├── README.md

📥 How Integration Works:
Create Dialogflow CX Agent

Upload Admission Brochure PDF to Data Store

Create custom intents and responses

Embed chatbot using <df-messenger> tag on college website

Fix input issues (e.g., spacebar) using custom JavaScript



🔗 Dialogflow CX Agent

Handles dynamic knowledge search via PDF

Also answers manual FAQs through intents

Integrated via Dialogflow Web Messenger


