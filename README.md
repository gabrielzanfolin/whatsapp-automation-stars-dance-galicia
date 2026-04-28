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
- [cite_start]**Backend/API:** Hosted on **Render**, handling the core logic and integrations[cite: 55].
- [cite_start]**Real-time Database:** **Firebase** was used to manage the list of schools and their contact information[cite: 55].
- [cite_start]**Audio Pipeline:** - Integration with **CloudConvert API** to ensure high-quality `.ogg` (WhatsApp compatible) format[cite: 56].
    - [cite_start]**Supabase Storage** to host the files and generate secure public URLs[cite: 56].
- [cite_start]**Communication:** **Twilio API** for automated messaging delivery[cite: 57].

## 📸 System Preview
*(Place for your screenshots or a GIF showing the interface)*

> **Note:** The source code for this project is private due to client confidentiality and data protection (GDPR). [cite_start]This repository serves as documentation of the technical architecture and implementation.
