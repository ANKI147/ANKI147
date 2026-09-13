# Ankit More

**Backend & Systems Software Engineer**

Pune, Maharashtra, India

I build C++ collector services for a production vehicle-data platform at **Sonatus**, working on real-time ingestion, concurrency, observability, and reliability on embedded Linux. I also own the logging and tracing framework used to investigate field failures.

Alongside systems engineering, I build multi-agent AI applications and real-time backend services. My interests sit behind the API: how data moves, how services behave under load, and how failures are diagnosed.

[LinkedIn](https://www.linkedin.com/in/ankitmore147/) | [Email](mailto:workwithankitmore@gmail.com) | [Projects](https://github.com/ANKI147?tab=repositories) | [ML Account](https://github.com/LuffyG7)

## Featured Projects

### [Atelier - AI Fashion CFO](https://github.com/ANKI147/atelier-fashion-cfo)

An image-to-costing application that coordinates four AI agents to analyze garments, research fabric and retail prices, and estimate profitability.

**Python | Google ADK | Gemini | Google Search | SerpAPI | Streamlit**

- Parallel sourcing and market research, followed by bounded optimization.
- Python cost calculations, per-run margin targets, and offline regression tests.
- Web interface and CLI, with documented assumptions and limitations.

**My focus:** sequential, parallel, and capped-loop orchestration over shared agent state, plus streamed CLI events, tool-call tracing, and state dumps for debugging agent handoffs.

[![Atelier checks](https://github.com/ANKI147/atelier-fashion-cfo/actions/workflows/ci.yml/badge.svg?branch=agents_v2)](https://github.com/ANKI147/atelier-fashion-cfo/actions/workflows/ci.yml)

[Explore the code](https://github.com/ANKI147/atelier-fashion-cfo) | [Architecture](https://github.com/ANKI147/atelier-fashion-cfo/blob/agents_v2/ARCHITECTURE.md)

<details>
<summary>Interface preview</summary>

![Atelier interface with a garment image and analysis settings](https://raw.githubusercontent.com/ANKI147/atelier-fashion-cfo/agents_v2/images/dashboard.png)

Local interface preview, not a live analysis result. Analysis requires Gemini and SerpAPI credentials; costs and material identification are estimates.

</details>

### [Scalable Chat Service](https://github.com/ANKI147/scalable-chat-service)

A real-time messaging backend and browser client with MongoDB persistence and delivery acknowledgments after successful storage.

**JavaScript | Node.js | Express | Socket.IO | MongoDB | Docker Compose**

- Validated messages, bounded history replay, and per-connection throttling.
- Reconnection handling, deduplicated messages, and a responsive browser client.
- Socket-level tests, real MongoDB persistence checks, and a container build in CI.

[![Chat checks](https://github.com/ANKI147/scalable-chat-service/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ANKI147/scalable-chat-service/actions/workflows/ci.yml)

[Explore the code](https://github.com/ANKI147/scalable-chat-service) | [Self-hosting setup](https://github.com/ANKI147/scalable-chat-service#self-hosting)

<details>
<summary>Desktop and mobile previews</summary>

![Scalable Chat desktop interface](https://raw.githubusercontent.com/ANKI147/scalable-chat-service/main/docs/chat-desktop.png)

[View the mobile interface](https://github.com/ANKI147/scalable-chat-service/blob/main/docs/chat-mobile.png).

Local demonstration with test messages. This is a single-instance public-room project, not a benchmarked production-scale service.

</details>

## Experience

### Sonatus | Software Engineer

**June 2025 - Present | Pune, India**

- Build and maintain C++ collector services for concurrent, real-time vehicle signal streams across multiple vehicle variants.
- Own the LOG & TRACE framework: telemetry capture, log generation and collection, system tracing, and core-dump handling.
- Tune concurrency and resource usage on constrained embedded-Linux targets, diagnose cross-service defects, and extend automated test and CI coverage.

### Accenture | Application Developer Intern

**February 2025 - June 2025**

Delivered automation utilities and chatbot integration on client projects; achieved P2 proficiency in Adobe Experience Manager.

### Society for Data Science | Machine Learning Engineer Intern

**March 2024 - August 2024**

Built a generative-AI-augmented OCR pipeline for printed and handwritten text, with preprocessing, feature selection, and model tuning. Co-authored the resulting IEEE PuneCon 2024 paper.

## Earlier Machine Learning Work

[Churn Prediction](https://github.com/LuffyG7/churn-prediction): a notebook exploring bank-customer churn through data analysis, preprocessing, and logistic regression. This earlier learning project lives on my [LuffyG7 account](https://github.com/LuffyG7).

## Technical Focus

| Area | Technologies and Practices |
| --- | --- |
| Core languages | C++ (11/17), Python, SQL, JavaScript; also Rust, Java, Bash |
| Systems and concurrency | Embedded Linux, POSIX, multithreading, IPC, D-Bus, sockets, shared memory |
| Backend and data | Node.js, Express, Socket.IO, Protocol Buffers, MQTT, MySQL, MongoDB |
| Observability | Structured logging, DLT, tracing, telemetry, GDB, core-dump analysis |
| Applied AI and ML | Google ADK, Gemini, LLM orchestration, multi-agent systems, pandas, scikit-learn |
| Build and quality | CMake, GoogleTest/GMock, pytest, Jenkins, GitHub Actions, Docker, Kubernetes |

## Research & Education

**Publication:** Co-author of "Extracting Valuable Insights from Handwritten Feedback," IEEE PuneCon 2024.

**Army Institute of Technology, Pune** | B.E. in Computer Engineering | 2021-2025

GPA: **8.5/10**. Coursework includes operating systems, databases, distributed systems, computer networks, information security, and data structures and algorithms.

## Highlights

- **500+** algorithm problems solved across LeetCode, Codeforces, CodeChef, and HackerRank.
- **CodeChef:** peak rating 1532. **HackerRank:** 5-star Problem Solving.
- **Runner-up:** Innerve7 Hackathon.
- **PMSS scholarship:** four consecutive years.
- **Certifications:** Google Cybersecurity and Network Security (2024); Machine Learning, Internshala Trainings.

## Connect

Reach me on [LinkedIn](https://www.linkedin.com/in/ankitmore147/) or at [workwithankitmore@gmail.com](mailto:workwithankitmore@gmail.com) for backend, systems, and applied AI opportunities.