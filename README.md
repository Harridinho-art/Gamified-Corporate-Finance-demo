# Architecting a Gamified Corporate Finance Engine

## 🎯 The Objective
To design and build a self-sustaining gamified assessment engine that bridges complex educational content with automated behavioral rewards. This project demonstrates the ability to integrate separate systems (an LMS and a logic engine) to drive user engagement and test advanced BCom-level principles.

## 🛠️ The Tech Stack
* **CMS:** WordPress (Local Environment)
* **Logic & Economy Engine:** GamiPress
* **Assessment Engine:** Tutor LMS

## 🎬 System Demonstration
*(The user completes a high-level BCom audit. The system automatically verifies the score and instantly awards 500 "Capital," triggering a badge reward).*

[https://youtu.be/f15foHmo0w8]

---

## 🏗️ Architecture & Blueprints
Building this required engineering a custom digital economy and linking it to an external learning management system. Here is how the logic was constructed:

### 1. The Economy Structure (Points & Progression)
Instead of generic points, I created a custom currency called **"Capital."** Users start with the rank of **Sole Trader**. By accumulating Capital through successful audits, they trigger automated promotions to higher tiers.

[<img width="907" height="661" alt="Gamipress screenshot 2" src="https://github.com/user-attachments/assets/58e22ac9-01a6-42b1-b477-096c8bd4ae59" />
]

[<img width="907" height="503" alt="Gamipress screenshot 3" src="https://github.com/user-attachments/assets/36115c48-88fc-4793-98fe-3c04b373028e" />
]

### 2. The Logic Engine (The "Plumbing")
This is the core "If/Then" logic that connects Tutor LMS to GamiPress. The system actively monitors the user's progress and only fires the reward sequence when a specific condition is met.
* **Logic Formula:** *IF* User Completes "Q1 Financial Audit" *THEN* Award 500 Capital *AND* Unlock "First Audit Passed" Badge.

[<img width="917" height="592" alt="Gamipress screenshot 1" src="https://github.com/user-attachments/assets/99211c93-9c09-4ad3-bdc6-06ec5e2654eb" />
]

### 3. Subject Matter Expertise (The Assessments)
The assessment module tests genuine corporate finance knowledge, covering concepts such as CAPM, the DuPont framework, and NPV.

[<img width="877" height="767" alt="Gamipress screenshot 4" src="https://github.com/user-attachments/assets/c21a4ffd-cafa-4160-903b-6e29f208af62" />
]
