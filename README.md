# 🏋️‍♀️ FitLife App: Requirements Analysis & System Design

![Project Status](https://img.shields.io/badge/Status-Design_Phase-blue)
![Course](https://img.shields.io/badge/Course-CSE251_Software_Engineering-brightgreen)
![Institution](https://img.shields.io/badge/Institution-Alamein_International_University-maroon)

This repository contains the comprehensive software design documentation, user requirements analysis, and system architecture for a proposed mobile fitness application. The project was developed as part of the **Software Engineering (CSE251)** course at **Alamein International University (AIU)** during the Fall 2025 semester.

---

## 📖 Table of Contents
1. [Project Overview](#-project-overview)
2. [Market & User Research](#-market--user-research)
3. [Proposed Features & System Modules](#-proposed-features--system-modules)
4. [Monetization Strategy](#-monetization-strategy)
5. [UI/UX & Notification Strategy](#-uiux--notification-strategy)
6. [Repository Contents](#-repository-contents)
7. [Team Members](#-team-members)

---

## 🚀 Project Overview

The objective of this project is to conceptually engineer a holistic, user-centric mobile fitness application. Rather than assuming user needs, the design process was strictly data-driven. It began with a thorough requirements elicitation phase, analyzing data from 145 surveyed respondents to identify core demographic behaviors, primary fitness challenges, and demanded features.

This repository serves as a showcase of the early phases of the software development life cycle (SDLC), highlighting requirement engineering, data-driven feature prioritization, and system architecture design.

---

## 📊 Market & User Research

A detailed survey of 145 individuals provided the foundational data for our software requirements. Full numerical data can be found in the `Analysis Report.pdf`.

### Target Demographic Insights
- **Age**: The user base is heavily skewed towards young adults, with a mean age of **22.6 years** and a median of **19 years**.
- **Fitness Level**: The majority identify as having an **Intermediate** fitness level (48.9%), closely followed by **Beginners** (40.7%). Advanced users represent a small minority.
- **Device Preference**: **83.4%** of users prefer smartphones for health tracking, while 36.6% also utilize wearable devices (smartwatches).

### Core Motivations & Roadblocks
- **Primary Goals**: Users are primarily motivated by **General Health Improvement (60.7%)** and **Weight Loss (45.5%)**. Muscle gain serves as a secondary motivator (34.5%).
- **Major Challenges**:
  - **Lack of Time (62.8%)**: The most significant barrier.
  - **Lack of Motivation (31.7%)**: The second highest barrier.
  - **Lack of Knowledge & Meal Access (24.1% each)**.

---

## ✨ Proposed Features & System Modules

Driven directly by our user research, the system architecture prioritizes the following core modules:

### 1. Exercise Tracking & Guidance (Core Module)
*Requested by 50.3% of users.*
- **Features**: Tailored workout routines catering primarily to Beginners and Intermediates.
- **Time-Efficiency**: Focus on quick, high-intensity workouts to combat the "Lack of Time" challenge reported by 62.8% of users.

### 2. Personalized Nutrition Engine
*Requested by 48.3% of users; 86.9% showed strong willingness to use tailored meal suggestions.*
- **Features**: Algorithm-driven meal plans based on user preferences and goals.
- **Calorie Tracking**: Integrated macro/calorie tracking (demanded by 40.7% of users) to support weight loss goals.

### 3. Gamification & Engagement System
*Supported by 80% of respondents.*
- **Features**: Achievement badges, streaks, and community leaderboards.
- **Purpose**: Directly engineered to solve the "Lack of Motivation" challenge.

### 4. Live Coaching & Premium Support
*75.9% expressed interest in this feature.*
- **Features**: Direct chat/video access to certified fitness experts and doctors. 

---

## 💰 Monetization Strategy

The application includes a tiered freemium model based on pricing sensitivity analysis:
- **Free Tier**: Basic exercise tracking and limited meal suggestions.
- **Premium Tier (Under $5 - $10/month)**: **86.9%** of users are willing to pay $10 or less per month. The premium tier will include the Gamification system, advanced analytics, and full Personalized Nutrition.
- **Pro Tier ($10 - $20+/month)**: Includes access to the Live Coaching module. (Targeted at the ~13% willing to pay higher premiums).

---

## 🔔 UI/UX & Notification Strategy

- **Notification Frequency**: The system will allow flexible notification settings. 49% of users prefer daily notifications (e.g., daily challenges, habit tracking), while 26.2% prefer weekly summaries. 
- **Platform Focus**: The UI is optimized strictly for **Mobile (iOS/Android)** given the 83.4% smartphone preference, with secondary API endpoints planned for Wearable integration (Apple Watch / WearOS).

---

## 📁 Repository Contents

- 📄 **`Analysis Report.pdf`**: The raw survey data, detailed numerical analysis, statistical breakdowns, and data visualizations that drove the project's requirements.
- 📄 **`Software Project report.pdf` / `.docx`**: The comprehensive software engineering design document. This includes the system architecture diagrams, UML use-case diagrams, sequence diagrams, and technical requirement specifications.

---

## 👥 Team Members

This project was collaboratively designed by the following students:
- **Tasneem Ibrahim Hassan Mohamed Taha** (Project Manager)
- **Abdulrahman Hamby Khalil Shehata Harb**
- **Rokia Islam Elsayed Hussein Elsayed Ali**
- **Mariam Mohamed Sobhy Mohamed Othman**
- **Raghad Mohamed Ahmed Mohamed Abu Rafai**

**Instructor:** Dr. Islam El-gedawy  
**Institution:** Alamein International University (AIU) - Faculty of Computer Science and Engineering (CSE)

---
*Note: This repository currently contains software architecture, requirements engineering, and UI/UX design documentation. It does not contain executable source code.*
