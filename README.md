# PharmaGuardAI
PharmaGuard AI is an AI-powered web application that helps hospital pharmacists review prescriptions by identifying drug interactions, duplicate therapies, contraindications, dosage concerns, and patient safety risks. It provides fast, AI-assisted clinical recommendations to improve medication safety and support informed decision-making.
# 🏥 PharmaGuard AI

### AI-Powered Clinical Prescription Review Assistant for Hospital Pharmacists

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![Next.js](https://img.shields.io/badge/Next.js-15-black)
![React](https://img.shields.io/badge/React-19-blue)
![Firebase](https://img.shields.io/badge/Firebase-Orange)
![OpenAI-GPT--5.5-green](https://img.shields.io/badge/AI-GPT--5.5-green)

---

# Overview

**PharmaGuard AI** is an AI-powered web application developed to support **hospital pharmacists** in reviewing prescriptions more efficiently and safely. Pharmacists spend a significant amount of time manually checking prescriptions for drug-drug interactions, duplicate therapies, contraindications, dosage concerns, and high-risk medications. Existing clinical decision support systems are often expensive, require institutional subscriptions, or are not easily accessible to small hospitals and teaching institutions.

PharmaGuard AI provides an intelligent clinical review assistant that analyzes patient prescriptions and generates evidence-based recommendations within seconds. The application is designed to **assist—not replace—licensed healthcare professionals** by highlighting potential medication-related problems and improving workflow efficiency.

---

# Real Problem It Solves

Hospital pharmacists are responsible for ensuring that every prescription is safe before dispensing medications. Manual review is:

* Time-consuming
* Prone to human error
* Difficult during heavy workloads
* Dependent on expensive commercial software

PharmaGuard AI streamlines this process by providing an AI-assisted clinical review that helps pharmacists identify potential medication-related problems quickly while maintaining clinical judgment.

**Target Users**

* Hospital Pharmacists
* Clinical Pharmacists
* Pharmacy Students
* Pharmacy Interns
* Medical Residents

---

# Live Demo

🌐 **Live Application**

https://vercel.com/malee/pharmaguard-ai-tool/4nqzCkD9AcYwn7FwkJmr2XjZuhp8 
https://maleehabegum.app.n8n.cloud/assistant/ecf67f37-052d-4596-81b9-d502f72495de


---

# GitHub Repository

https://github.com/maleehameed-a11y/PharmaGuardAI.git

---

# Features

## User Authentication

* Secure Login
* User Registration
* Firebase Authentication

---

## Patient Information

* Patient Name
* Age
* Gender
* Diagnosis
* Allergies
* Renal Disease
* Hepatic Disease

---

## Prescription Entry

Users can enter multiple medications including:

* Drug Name
* Dose
* Frequency
* Route
* Duration

---

## AI Clinical Review

The AI analyzes prescriptions and identifies:

* Drug–Drug Interactions
* Duplicate Therapy
* Contraindications
* High-Risk Medications
* Dosage Concerns
* Allergy Risks
* Renal Dose Adjustments
* Hepatic Dose Adjustments
* Monitoring Recommendations
* Patient Counseling Points

---

## Severity Classification

Interactions are classified as:

🟢 Low Risk

🟡 Moderate Risk

🔴 Severe Risk

---

## Clinical Safety Score

Each prescription receives an overall assessment:

* Safe
* Needs Review
* High Risk

---

## Download Reports

Generate downloadable PDF reports containing:

* Prescription Summary
* Identified Issues
* Recommendations
* Clinical Notes

---

## Dashboard

* Total Prescriptions Reviewed
* Severe Alerts
* Moderate Alerts
* Saved Reports
* Recent Activity

---

## Saved History

Users can view previous prescription analyses and reports.

---

# AI Feature

The core feature of PharmaGuard AI is its AI-powered prescription review assistant.

The AI examines patient medications and produces a structured clinical report identifying potential medication-related problems along with evidence-based pharmacist recommendations.

Unlike a simple chatbot, the AI acts as a **clinical decision support assistant** specifically designed for hospital pharmacy workflows.

---

# System Prompt

```text
You are an experienced Clinical Pharmacist working in a tertiary care hospital.

Review every prescription carefully.

Identify:

1. Drug-drug interactions
2. Duplicate therapy
3. Contraindications
4. Dose-related concerns
5. Drug allergies
6. Renal impairment considerations
7. Hepatic impairment considerations
8. Monitoring recommendations
9. Patient counseling points

For every issue provide:

• Medication names
• Severity (Low, Moderate, Severe)
• Clinical explanation
• Recommended pharmacist action

If there is insufficient evidence, clearly state that.

Do not fabricate interactions.

Always remind users that AI recommendations do not replace professional clinical judgment.
```

---

# Example Workflow

1. Pharmacist logs into the application.
2. Enters patient information.
3. Adds prescribed medications.
4. Clicks **Analyze Prescription**.
5. AI reviews the prescription.
6. Results are displayed with severity levels and recommendations.
7. Pharmacist downloads or saves the report.

---

# Technology Stack

## Frontend

* React
* Next.js
* Tailwind CSS

## Backend

* Node.js
* Express.js

## Database

* Firebase Firestore

## Authentication

* Firebase Authentication

## AI

* OpenAI GPT-5.5 API *(or Google Gemini API)*

## Deployment

* Vercel

## Version Control

* GitHub

---

# Project Structure

```bash
pharmaguard-ai/
│
├── app/
├── components/
├── pages/
├── api/
├── firebase/
├── lib/
├── public/
├── styles/
├── README.md
├── package.json
└── .env.local
```

---

# Installation

Clone the repository.

```bash
git clone https://github.com/yourusername/pharmaguard-ai.git
```

Navigate into the project folder.

```bash
cd pharmaguard-ai
```

Install dependencies.

```bash
npm install
```

Run the development server.

```bash
npm run dev
```

Open your browser.

```
http://localhost:3000
```

---

# Environment Variables

Create a `.env.local` file and add the following:

```env
OPENAI_API_KEY=your_api_key

NEXT_PUBLIC_FIREBASE_API_KEY=

NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=

NEXT_PUBLIC_FIREBASE_PROJECT_ID=

NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=

NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=

NEXT_PUBLIC_FIREBASE_APP_ID=
```

---

# Screenshots

Add at least three screenshots before submission.

### 1. Login Page

`/screenshots/login.png`

---

### 2. Dashboard

`/screenshots/dashboard.png`

---

### 3. Prescription Entry Form

`/screenshots/prescription-form.png`

---

### 4. AI Clinical Review

`/screenshots/analysis.png`

---

### 5. PDF Report

`/screenshots/report.png`

---

# Future Improvements

* Laboratory value integration
* Electronic Health Record (EHR) integration
* Drug dosage calculator
* Medication reconciliation
* Barcode prescription scanning
* Voice-based prescription entry
* Multilingual support
* Offline hospital mode
* Clinical guideline integration
* Pharmacovigilance reporting

---

# Disclaimer

PharmaGuard AI is designed as a **clinical decision support tool**. It assists pharmacists by identifying potential medication-related problems but **does not replace professional medical judgment**. All recommendations should be verified by qualified healthcare professionals before clinical use.

---

# Author

**Maleeha Begum**

Pharmacology Researcher | AI in Healthcare | Clinical Decision Support Systems

---

# License

This project is licensed under the **MIT License**.

---

## Acknowledgments

Special thanks to the open-source community and the developers of React, Next.js, Firebase, Tailwind CSS, and OpenAI for providing the technologies that made this project possible.

This README is structured to match your assignment rubric and is suitable for a GitHub repository. Before submission, replace the placeholder GitHub and Vercel links with your actual URLs and add your application screenshots.
