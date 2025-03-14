# Smart India Hackathon Workshop
# Date:14.03.2025
## Register Number:212224040082
## Name:DIVYA LAKSHMI M
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1. Role-Based Access System
   
🔹 Admin Panel → Manage vacancies, interviewers, and questions

🔹 Interview Panel (Experts) → Select/customize questions, rate responses

🔹 Candidates → Participate in AI-driven/mock/live interviews


2. Smart Questioning System
 
-> AI-Powered Question Selection:

Ice-breaking → General discussion → Techno-managerial questions

Adaptive difficulty based on candidate performance

Questions fetched dynamically from job-specific database

-> Question Types:


Multiple-Choice Questions (MCQs)

Descriptive/Text-based Answers

Scenario-based / Problem-Solving

Behavioral Questions (HR-based)

-> Question Relevance Matching:


NLP-based expertise analysis to ensure questions align with the candidate’s background

3️. AI-Powered Response Evaluation

-> Candidate Answer Analysis:

Natural Language Processing (NLP) & Machine Learning evaluate clarity, relevance, depth
AI checks grammar, coherence, and logical reasoning

Experts rate responses for accuracy
-> Scoring System:


Weighted AI Score + Expert Score

Real-time feedback for improvement

-> Live AI Feedback:


## Proposed Solution / Architecture Diagram
![WhatsApp Image 2025-03-14 at 09 17 14_3ad08423](https://github.com/user-attachments/assets/0c0a34b5-eac5-49bd-8fbc-b1173b1aafc7)


## Use Cases
![WhatsApp Image 2025-03-14 at 09 17 05_a68521ef](https://github.com/user-attachments/assets/b48486d7-0c05-4fb3-a1bb-6264a866b139)

## Technology Stack
Frontend: React.js / Angular / Vue.js

Backend: Node.js / Django / Flask

Database: MySQL / PostgreSQL / MongoDB

AI/NLP: OpenAI API, Google NLP, IBM Watson

Video Integration: WebRTC / Zoom SDK


## Dependencies
react-router-dom → For navigation in React

axios → For handling API requests

socket.io-client → For real-time communication

tailwindcss → For styling the UI

chart.js → For interview performance graphs

