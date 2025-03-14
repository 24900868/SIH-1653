# Smart India Hackathon Workshop
# Date:13.03.2025
## Register Number: 212224230148
## Name: Mahalakshmi.M
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
```
User Roles and Authentication:

Experts (Interviews) who create and evaluate interview questions and responses.
Candidates who provide their responses to interview questions.
Admin (optional) to manage users, data, and overall system settings.
Questionnaire Management:

Question Bank: A database of pre-defined questions based on job roles or expertise levels. The system should allow categorization of questions by area of expertise (e.g., technical, managerial).
Dynamic Question Generation: Experts should be able to choose relevant questions for a particular candidate based on their expertise or job level. The system should be able to suggest appropriate questions based on the candidate's profile.
Ice-Breaking Questions: A set of predefined questions to start the interview.
Response Evaluation:

Grading of Responses: Experts should be able to grade the relevance and quality of the candidate's responses.
Quantitative Scoring: The system should allow experts to provide scores for both the questions' relevance and the quality of the candidate's response.
Real-Time Interview Simulation:

Interactive Interface: A real-time interface where the interviewer can ask questions, and the candidate can submit responses.
Audio/Video Support: If needed, the system can include real-time video or audio chat for the interview process.
Scoring and Analytics:

Question Relevance Scoring: The relevance of the questions asked during the interview should be scored based on the candidate’s expertise and the job profile.
Response Relevance Scoring: The quality and relevance of the responses should be evaluated by experts, with feedback provided.
Overall Candidate Score: The total score based on both question and response relevancy, which helps in assessing the candidate’s knowledge and suitability for the position.
Candidate Profile:

Detailed Profiles: Information about the candidates, including their qualifications, job experience, skills, and areas of expertise. This helps experts choose appropriate questions.
Personalized Question Bank: The system should be able to filter and recommend questions based on the candidate's profile.
Reporting:

Interview Reports: After the interview, experts can generate detailed reports that show the candidate’s performance, including scores for question relevance, response quality, and overall suitability.
Candidate Feedback: Feedback can be provided to the candidate on their performance.
```
## Proposed Solution / Architecture Diagram

![Screenshot 2025-03-14 060612](https://github.com/user-attachments/assets/61e44d66-a308-4de7-b6a2-be9a50a899c3)


## Use Cases

![Screenshot 2025-03-14 060842](https://github.com/user-attachments/assets/b7b08bca-dc8d-4d2e-9e01-f318b13a880a)


## Technology Stack
```
Frontend (User Interface)
Framework: React.js / Angular / Vue.js
Styling: Tailwind CSS / Bootstrap / Material UI
Real-Time Interaction: WebRTC (for video interviews), Socket.io (for real-time updates)
Backend (Server & APIs)
Language: Node.js (Express.js) / Python (Django, Flask)
REST API / GraphQL: Express.js / Django REST Framework / Apollo GraphQL
Authentication: OAuth 2.0, JWT
Database (Storage & Management)
Relational DB: PostgreSQL / MySQL (for structured data)
NoSQL DB: MongoDB (for flexible document storage)
Cache: Redis (for fast data access)
AI & Machine Learning (Scoring & Evaluation)
NLP Models: BERT / OpenAI GPT / spaCy (for answer evaluation)
Text Similarity & Relevance: TF-IDF, Word2Vec
ML Frameworks: TensorFlow / PyTorch / Scikit-Learn
Deployment & DevOps
Cloud Platforms: AWS (EC2, S3, Lambda) / Google Cloud / Azure
Containerization: Docker, Kubernetes
CI/CD: GitHub Actions, Jenkins
Logging & Monitoring: Prometheus, Grafana
Security & Compliance
Data Encryption: TLS/SSL, AES-256
Access Control: Role-Based Access Control (RBAC)
Compliance: GDPR, ISO 27001
```

## Dependencies
```
Dependencies for Web-Based Selector-Applicant Simulation Software
Frontend Dependencies
React.js / Angular / Vue.js – Frontend framework
Tailwind CSS / Bootstrap / Material UI – UI styling
Axios / Fetch API – API communication
WebRTC / Socket.io – Real-time video and chat functionality
Redux / Zustand (React) – State management
Backend Dependencies
Express.js (Node.js) / Django / Flask – Web framework for API development
Socket.io – Real-time communication
JWT / Passport.js – Authentication & authorization
Bcrypt.js / Argon2 – Password hashing
Cors – Cross-origin resource sharing
Dotenv – Environment variable management
Database & Storage Dependencies
PostgreSQL / MySQL – Relational database
MongoDB / Mongoose – NoSQL database (if needed)
Redis – Caching for fast response times
Cloudinary / AWS S3 – Media storage (for interview recordings)
AI & NLP Dependencies
spaCy / NLTK – Natural Language Processing
TensorFlow / PyTorch – Machine Learning framework
OpenAI GPT / BERT – AI-based answer evaluation
Scikit-Learn – Text similarity & ML scoring
DevOps & Deployment Dependencies
Docker / Kubernetes – Containerization
GitHub Actions / Jenkins – CI/CD automation
Nginx / Apache – Web server for hosting
Prometheus / Grafana – Logging & monitoring
```
