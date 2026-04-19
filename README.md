# EduPulseAppEduPulse AI | Smart Learning Companion
EduPulse AI is an intelligent academic management and tutoring platform designed to bridge the gap between static Learning Management Systems (LMS) and active, AI-driven student engagement. This project was developed as part of the ISM 6225 coursework at the University of South Florida.

🚀 Project Vision
Modern technical coursework—covering topics like Deep Learning, Big Data, and Advanced SQL—requires more than just a document repository. EduPulse acts as a force multiplier for students by transforming raw syllabus data into an interactive, personalized learning journey.

✨ Key Features
🤖 AI-Driven Tutoring
Integrated with Botpress, the platform features a custom-grounded AI assistant. Unlike general-purpose LLMs, this bot is grounded in a specific Assignments Database, providing 24/7 context-aware support for deadlines, topics, and difficulty levels while mitigating hallucinations through RAG-based logic.

📊 Actionable Analytics
A comprehensive dashboard built with Chart.js that translates academic data into visual stories:

Grade Distribution: Identifying class success trends.

Topic Interest: Mapping student queries to specific curriculum modules.

Engagement Over Time: Tracking longitudinal interaction spikes.

Course Difficulty Profile: Multidimensional radar analysis of course rigor.

🛠️ Assignment Management (CRUD)
A robust administrative interface that allows for the full lifecycle of assignment management. Using Browser LocalStorage, the prototype demonstrates real-time creation, reading, updating, and deletion of deliverables with high data integrity.

🌐 API Integration
A dedicated Computer Science Quiz showcase that demonstrates real-time data fetching from the OpenTDB REST API. This feature utilizes asynchronous JavaScript (fetch, async/await) and dynamic UI rendering to provide instant academic reinforcement.

🛠️ Tech Stack
Frontend: HTML5, CSS3 (Glassmorphism UI), Bootstrap 5

Logic: Vanilla JavaScript (ES6+), LocalStorage API

AI: Botpress (Autonomous Nodes & Knowledge Bases)

Visualization: Chart.js

API: Open Trivia Database (REST API)

📂 Project Structure
├── index.html          # Landing Page & Hero Carousel
├── assignments.html    # CRUD Interface for Assignment Management
├── visuals.html        # Chart.js Learning Analytics Dashboard
├── test.html           # External API Quiz Showcase
├── mybot.html          # Botpress Chatbot Integration Page
├── about.html          # Project Documentation & Logical Data Model
└── assets/             # Images and Static Resources

📐 Data Model
The application is built on a structured relational foundation:

Users & Courses: 1:N relationship tracking instructors and their respective courses.

Course Content: Linking courses to specific assignments.

Interaction Logs: Tracking student engagement with the AI Tutoring sessions.

👤 Author
Prince Praveen Lead Developer & Data Scientist M.S. in Business Analytics & Artificial Intelligence, USF



Bash
git add README.md
git commit -m "Add professional README documentation"
git push origin main
This README highlights your transition from a static prototype to an AI-integrated platform, making it a strong piece for your professional portfolio.