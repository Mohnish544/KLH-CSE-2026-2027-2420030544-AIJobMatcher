<<<<<<< HEAD# AI-Powered Resume/Job Matcher + Application Tracker

## Team Members

* Member 1 — ID: 2420030544 - Alaparthy Mohnish
* Member 2 — ID: 2420030265 - Pedireddi Sandeep
* Member 3 — ID: 2420030199 - Leela Krishna Likith Raj

## Supervisor

**Supervisor Name:** MRS.K.BHAVYA VARMA

## Abstract

Job seekers routinely apply to dozens of positions without knowing whether their resume actually matches a given job description, leading to wasted effort and low interview conversion rates. This project proposes an AI-assisted Job Application Tracker that combines a Kanban-style application pipeline (Applied, Interview, Offer, Rejected) with an integrated resume-to-job-description matching engine. Users upload their resume and paste a target job description; the system extracts key skills and keywords from both, computes a similarity score, and highlights missing or weak skill matches before the user applies. Each tracked application stores its match score alongside its pipeline status, enabling an analytics dashboard that correlates match quality with real outcomes such as interview conversion. The system is built using React.js for the frontend, Firebase (Authentication, Firestore, Storage, Hosting) for backend services, Git and GitHub with GitHub Actions for version control and continuous integration/deployment, and Jira for Agile sprint-based project management. Firestore security rules enforce that users can only access their own data, addressing basic secure-coding practices. The resulting system demonstrates practical application of Agile development, DevOps automation, and lightweight AI/NLP techniques to solve a genuine, everyday problem faced by job seekers.

Following Adaptive Software Engineering principles, the project is developed using Agile/Scrum practices for iterative, sprint-based development, DevOps-driven CI/CD pipelines for reliable and automated delivery, and secure coding practices to protect user data throughout the development lifecycle. Version control is managed through Git and GitHub using a feature-branch workflow, with GitHub Actions automating testing and deployment to Firebase Hosting on every merge to the main branch. Project progress is tracked through a Jira Scrum board, with work organized into epics, sprints, and user stories to reflect real-world Agile team practices. Together, these elements make the project a practical demonstration of adaptive, iterative, and security-conscious software engineering applied to a genuine, everyday problem.

[ASE_ABSTRACT.docx](https://github.com/user-attachments/files/31134610/ASE_ABSTRACTdocx.docx)

###
## Project Structure

```
CareerForge/
├── src/        # Application source code (React frontend, Firebase functions, matching engine)
├── docs/       # Project documentation (architecture, sprint plans, meeting notes, diagrams)
├── data/       # Sample/reference data (sample resumes, sample job descriptions) or data source references
├── results/    # Experiment/test outputs (match-score samples, evaluation results, screenshots)
├── reports/    # Formal deliverables (abstract, project report, presentation exports)
├── .gitignore
└── README.md
```

## Tech Stack
- **Frontend:** React.js
- **Backend/Cloud:** Firebase (Authentication, Firestore, Storage, Hosting)
- **Version Control & CI/CD:** Git, GitHub, GitHub Actions
- **Project Management:** Jira (Agile/Scrum)

## Current Phase Status

**Phase:** Initial Development

* [x] Project repository created
* [x] Project setup completed
* [ ] Core implementation
* [ ] Testing
* [ ] Final documentation
* [ ] Deployment

**Status:** In Progress
>>>>>>> f0a11c220330b687b1d4bb60a5e9cc3027800b41
