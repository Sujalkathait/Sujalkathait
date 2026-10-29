# Hi, I'm Sujal Kathait 👋

I am a software engineer focused on building secure, efficient, and scalable systems. My passion lies at the intersection of low-level systems programming, cybersecurity, and artificial intelligence. I enjoy breaking down complex problems into clean, modular, and production-quality architectures, while valuing clear communication, analytical problem-solving, and adaptability.

---

## 🛠️ About & Skills

**Interests:** Cybersecurity • C++ • Systems Programming • System Design • Software Engineering • AI • Networking

### 🧰 Technologies & Tools

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![DBMS](https://img.shields.io/badge/DBMS-4479A1?style=flat&logo=database&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

### 💡 Skills & Tools Defined

- **C++:** Systems programming, memory management, high-performance computing, and object-oriented design.
- **Python:** Backend service development, automation scripting, and AI/RAG system engineering.
- **TypeScript:** Type-safe full-stack application development and maintainable API architectures.
- **React:** Responsive, component-based user interfaces and state-driven frontend applications.
- **Flask:** Lightweight web microservices, routing, and RESTful API development.
- **DBMS:** Relational schema design, normalization (3NF), data integrity, ACID compliance, and query optimization.
- **Linux:** Operating system fundamentals, shell scripting, process management, and server administration.
- **Git:** Version control, collaborative branching workflows, and repository management.

---

## 🚀 Projects

### 1. [PortFlow](https://github.com/Sujalkathait/PortFlow)
- **Problem:** Maritime ports suffer from severe operational bottlenecks, high demurrage costs, and scheduling deadlocks when vessel berthing, crane allocation, and container dispatch are handled inefficiently.
- **Approach:** Developed a full-stack maritime operations platform powered by an in-memory OS scheduling simulator (FCFS, SJF, Priority, Round Robin) with concurrency control (Mutex locks for cranes, Counting Semaphores for berths, and Deadlock detection via Wait-For Graphs). Built with a dual API architecture (REST & Apollo GraphQL) and a normalized relational DBMS.
- **Tech Stack:** ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![DBMS](https://img.shields.io/badge/DBMS-4479A1?style=flat&logo=database&logoColor=white) ![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat&logo=graphql&logoColor=white)
- **Outcome:** A comprehensive port management system that eliminates resource conflicts, minimizes vessel turnaround time, and provides real-time operational visibility.

### 2. [High-Level Design (HLD)](https://github.com/Sujalkathait/high-level-design)
- **Problem:** Distributed systems and scalable architecture topics are frequently explained with dense academic jargon rather than clear, visual, and practical engineering guidance.
- **Approach:** Authored an open-source visual engineering guide breaking down real-world high-level architectures. Covers DNS routing, CDNs, load balancing (L4/L7, consistent hashing), caching strategies (Cache-Aside, Write-Through), stateless server tiers, message queues, and DBMS scaling (replication & sharding) through clear diagrams and case studies.
- **Tech Stack:** ![System Design](https://img.shields.io/badge/System_Design-007ACC?style=flat&logo=diagramsdotnet&logoColor=white) ![Distributed Systems](https://img.shields.io/badge/Distributed_Systems-FF6F00?style=flat) ![Architecture](https://img.shields.io/badge/Architecture-2ea44f?style=flat) ![DBMS](https://img.shields.io/badge/DBMS-4479A1?style=flat&logo=database&logoColor=white)
- **Outcome:** A modular, production-focused engineering blueprint for understanding distributed system patterns and acing system design interviews.

### 3. [FileShare](https://github.com/Sujalkathait/filesender) | [Live Demo](https://filesender-coral.vercel.app/)
- **Problem:** Transferring files securely across the web without exposing them to intermediate servers or relying on third-party cloud storage.
- **Approach:** Built a zero-knowledge encrypted file transfer system. Files are encrypted client-side in the browser before transmission, utilizing a stream-and-batch processing pipeline for up to 20 files per transfer.
- **Tech Stack:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![Web Crypto API](https://img.shields.io/badge/Web_Crypto_API-4CAF50?style=flat) ![WebRTC](https://img.shields.io/badge/WebRTC-FF5722?style=flat&logo=webrtc&logoColor=white)
- **Outcome:** A privacy-first, ephemeral file-sharing platform where decryption keys and plaintext files never touch the server disk or memory, complete with a self-destruct mechanism.

### 4. [DocMind RAG](https://github.com/Sujalkathait/docmind-RaG)
- **Problem:** Students need a private, offline, and cost-free way to query their lecture slides and handwritten notes without dealing with hallucinations from general LLMs.
- **Approach:** Engineered a 100% offline Retrieval-Augmented Generation (RAG) assistant. It uses a strict 30-rule pedagogical system prompt and local GGUF models to generate factual, syllabus-grounded answers and code dry runs.
- **Tech Stack:** ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white) ![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6600?style=flat) ![HuggingFace](https://img.shields.io/badge/HuggingFace-FF9D00?style=flat&logo=huggingface&logoColor=white) ![Local LLMs](https://img.shields.io/badge/Local_LLMs-6366F1?style=flat)
- **Outcome:** A highly efficient learning tool capable of step-by-step code tracing, marks-based exam answers, and memory visualization with zero API costs.

### 5. [Movie Ticket Booking System](https://github.com/Sujalkathait/MovieTicketBookingSystem)
- **Problem:** Understanding and demonstrating core object-oriented and low-level system design principles in a real-world scenario.
- **Approach:** Developed a robust, in-memory C++ console application mimicking a real cinema. Implemented modular architecture with separate services for pricing, polymorphic payments, seating layouts, and booking management.
- **Tech Stack:** ![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=c%2B%2B&logoColor=white)
- **Outcome:** A crash-resistant, cleanly architected system showcasing strong system design principles, robust error handling, and clean code separation.

---

## 📊 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=Sujalkathait&show_icons=true&hide_border=true&theme=transparent" alt="Sujal's GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Sujalkathait&hide_border=true&theme=transparent" alt="Sujal's GitHub Streak" />
  <br/>
  <br/>
  <img src="https://ghchart.rshah.org/3776AB/Sujalkathait" alt="Sujal's Contribution Graph" />
  <br/>
  <br/>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Sujalkathait/Sujalkathait/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Sujalkathait/Sujalkathait/output/github-contribution-grid-snake.svg">
    <img alt="Sujal's GitHub Contribution Grid Snake" src="https://raw.githubusercontent.com/Sujalkathait/Sujalkathait/output/github-contribution-grid-snake.svg">
  </picture>
</div>

---

## 🔗 Connect with me

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sujalkathait)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sujal-kathait-283b06322)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/6OvdD6swvO/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sujalkathait93@gmail.com)
