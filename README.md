# WhatsApp Automation & Feedback Platform | Stars Dance Galicia 🚀

This is a professional case study of a full-stack solution developed for the international event **Stars Dance Galicia** (Ourense, Spain).

## 📝 The Problem
Judges at large-scale events often struggle with manual feedback delivery. The goal was to eliminate the delay and complexity of sending individual audio evaluations to multiple schools via WhatsApp.

## 🛠️ The Solution
I built a web-based platform that allows judges to:
1. Select a specific school from a verified list.
2. Record audio feedback directly in the browser.
3. Automatically convert and send the audio to the school's WhatsApp in seconds.

## 🏗️ Technical Architecture
- **Backend/API:** Hosted on **Render**, handling the core logic and integrations.
- **Real-time Database:** **Firebase** was used to manage the list of schools and their contact information.
- **Audio Pipeline:** Integration with **CloudConvert API** to ensure high-quality `.ogg` (WhatsApp compatible) format.
- **Storage:** **Supabase Storage** to host the files and generate secure public URLs.
- **Communication:** **Twilio API** for automated messaging delivery.

## 📸 System Preview
*(Place for your screenshots or a GIF showing the interface)*
<img width="1440" height="900" alt="Captura de Tela 2026-04-28 às 01 55 27" src="https://github.com/user-attachments/assets/5b37da22-bbea-4e2e-899f-14528378c9bb" />
<img width="1440" height="900" alt="Captura de Tela 2026-04-28 às 01 55 36" src="https://github.com/user-attachments/assets/704e1dd0-1411-45a7-85f5-5656cf79d593" />
<img width="1440" height="900" alt="Captura de Tela 2026-04-28 às 01 55 45" src="https://github.com/user-attachments/assets/eb3ce638-a1d9-448f-a75c-ea08ac4cc17c" />
<img width="1440" height="900" alt="Captura de Tela 2026-04-28 às 01 55 54" src="https://github.com/user-attachments/assets/a947609d-fec4-42dc-9f73-0f5db8436417" />
<img width="1440" height="900" alt="Captura de Tela 2026-04-28 às 01 56 30" src="https://github.com/user-attachments/assets/19626e81-729d-4465-bbd1-0457a9725e00" />
<img width="997" height="579" alt="Captura de Tela 2026-04-28 às 02 04 54" src="https://github.com/user-attachments/assets/5c5271e9-c1aa-4ed9-8bd1-df26c496ffb5" />


> **Note:** The source code for this project is private due to client confidentiality and data protection (GDPR). This repository serves as documentation of the technical architecture and implementation.
