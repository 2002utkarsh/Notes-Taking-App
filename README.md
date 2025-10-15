# Notes Taking App (Notion Clone)

A modern, React-based note-taking application inspired by Notion, designed for intuitive organization and seamless productivity.  
The app combines a dynamic front-end with AWS-powered backend services and local storage support for offline flexibility.

---

## Overview

The **Notes Taking App** replicates the essential functionality of Notion — enabling users to **create**, **edit**, and **organize** notes and tasks in a clean, responsive interface.  
It integrates **React** for the user interface, **AWS** for cloud-based operations, and **Local Storage** for temporary offline persistence.

The goal is to deliver a lightweight yet scalable productivity tool that demonstrates robust front-end engineering and cloud integration practices.

---

## Features

- **Dynamic Note Management**  
  Create, edit, delete, and organize notes in a structured and efficient way.

- **Responsive React Front-End**  
  Built entirely with React to ensure a fast, interactive, and adaptive user experience.

- **AWS Cloud Integration**  
  - **Cognito** for user authentication and session management  
  - **S3** for secure storage of note data and assets  
  - Scalable and fault-tolerant backend architecture

- **Local Storage Support**  
  Enables temporary note saving for users who are offline or not logged in.

- **Minimal & Intuitive Design**  
  Clean UI that emphasizes productivity and ease of navigation.

---

## Getting Started

### Prerequisites

Before running the project, ensure you have:
- **Node.js (v16 or higher)**
- **npm** or **yarn**
- Access to **AWS** (S3, Cognito, and related IAM permissions)

---

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/notes-taking-app.git
cd notes-taking-app
