# Smart India Hackathon Workshop
# Date:12-03-2025
## Register Number:212224040195
## Name:MohamedRafi-R
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1.Virtual Interview Panel (Boardroom Simulation) 3D avatars of interviewers for a realistic experience. Multiple interviewer roles (HR, Technical, Managerial, etc.). Speech-enabled AI interviewers to ask questions dynamically.
2.AI-Driven Questioning System Initial ice-breaking questions, then in-depth technical/managerial queries. Personalized questions based on the candidate's domain expertise. Adaptive questioning – changes based on candidate responses.
3.Candidate Response Analysis Supports voice-based and text-based responses. AI evaluates response relevance, clarity, and confidence. Speech-to-text conversion for analysis and scoring.
4.Real-Time Scoring & Feedback Assigns a relevance score based on question and answer matching. Provides instant feedback on strengths & weaknesses. AI-generated report on interview performance.
5.Data & Analytics Dashboard for Recruiters Tracks candidate performance over multiple interviews. Identifies biases in questions and responses. ML-powered hiring recommendations.
6.Gamification Elements (Optional) Time-based challenges to simulate real-world pressure. Performance badges & leaderboard to encourage improvement.


## Proposed Solution / Architecture Diagram
![image](https://github.com/user-attachments/assets/c4f82778-3965-4b8e-940b-741206d873c3)


## Use Cases
![image](https://github.com/user-attachments/assets/6af0ee2f-38b6-4607-9dd6-003461480a4e)


## Technology Stack

1.Frontend: React.js, Next.js, Three.js (for 3D UI), WebRTC (real-time video).
2.Backend: Node.js with Express.js or FastAPI (Python) for APIs & business logic.
3.AI/ML: OpenAI GPT (question generation), TensorFlow/PyTorch (response evaluation), Deepgram/Whisper (speech-to-text).
4.Database: PostgreSQL (structured data), MongoDB (unstructured logs), VectorDB (AI training data).
5.Cloud & DevOps: AWS/GCP, Docker, Kubernetes, CI/CD (Jenkins/GitHub Actions).


## Dependencies

  1.Manpower Cost: ₹2-3 crore (~₹10-15 lakh per developer for 12-18 months).
  2.Cloud Infrastructure: ₹20-30 lakh (AWS/GCP services, storage, compute, and AI APIs).
  3.AI & Speech Processing APIs: ₹10-15 lakh (OpenAI, Deepgram, Google STT).
  4.Software & Licensing: ₹5-10 lakh (3D UI tools, security, DevOps tools).
  5.Miscellaneous (Testing, Maintenance, Support): ₹10-15 lakh.

