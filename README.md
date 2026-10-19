<!-- GitHub profile README · Kevin · 2026 -->
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=195&section=header&color=0:0B1220,100:2563EB&text=KEVIN&fontColor=FFFFFF&fontSize=55&fontAlignY=35&desc=Full-Stack%20Development%20%7C%20Backend%20Engineering%20%7C%20Applied%20AI&descAlignY=56&descSize=17" alt="Kevin — Full-Stack Development, Backend Engineering and Applied AI" />

### Full-Stack Developer · Backend-Focused Engineer · Exploring Applied AI

*Building thoughtful interfaces, reliable backend systems, and practical software products.*

[![GitHub](https://img.shields.io/badge/GitHub-kazakov7-111827?style=flat-square&logo=github&logoColor=white)](https://github.com/kazakov7)
[![AURORA](https://img.shields.io/badge/Live-AURORA-2563EB?style=flat-square&logo=vercel&logoColor=white)](https://auroratravel.vercel.app/)
[![ELIF BOOK STORE](https://img.shields.io/badge/Live-ELIF%20BOOK%20STORE-0D9488?style=flat-square&logo=googlechrome&logoColor=white)](https://elif-book.store/)
![Visitors](https://komarev.com/ghpvc/?username=kazakov7&style=flat-square&color=64748b)

</div>

---

## About Me

I'm **Kevin**, a full-stack developer based in South Korea, with a particular interest in **backend architecture, end-to-end application development, and applied machine learning**.

I build beyond static interfaces: authentication, role-based access, database modeling, booking workflows, real-time communication, payment integrations, admin tools, and deployment.

- **Frontend:** Responsive interfaces, application state, API integration, and product-focused UI.
- **Backend:** NestJS/Express, GraphQL/REST, validation, guards, access control, and business logic.
- **Data:** MongoDB schemas, Mongoose, aggregations, indexing concepts, and data consistency.
- **Infrastructure:** AWS EC2, Vercel, PM2, Docker workflows, environments, and debugging.
- **AI learning:** Python, data analysis, computer vision, PyTorch, and local LLM experimentation.

> I care about how a system works **behind** the interface just as much as how it looks.

## Selected Projects

### ✈️ AURORA — End-to-End Travel Marketplace

**A multi-role travel platform connecting travelers, hotel partners, and tour operators.**

[![Live Website](https://img.shields.io/badge/Live%20Demo-Explore%20AURORA-2563EB?style=flat-square&logo=vercel&logoColor=white)](https://auroratravel.vercel.app/)

**Product capabilities**

- Hotel and property listings, destination discovery, and tour packages.
- Traveler, hotel-agent, tour-agent, and administrator workflows.
- Property availability, reservations, booking status transitions, and cancellation rules.
- Stripe payment integration, webhook processing, and refund handling.
- Real-time direct/global chat, notifications, follows, likes, and community content.
- Ratings, reviews, activity metrics, ranking logic, and admin management.
- Authentication and authorization, including password and supported social-login flows.
- Multilingual user interface and responsive layouts.

**Engineering highlights**

- **NestJS + GraphQL** application organized into domain modules, DTOs, guards, decorators, pipes, and interceptors.
- **MongoDB + Mongoose** schemas, aggregation pipelines, relationships, filtering, and pagination.
- **Booking integrity:** availability checks, pending reservations, expiration rules, and atomic inventory operations where required.
- **Payment reliability:** webhook-based state transitions and idempotent processing patterns.
- **Real-time communication:** WebSocket chat and event-driven user updates.
- **Deployment:** Next.js frontend on Vercel; backend hosted on AWS EC2 with PM2 and MongoDB Atlas.

`Next.js` · `TypeScript` · `NestJS` · `GraphQL` · `MongoDB` · `Mongoose` · `Apollo Client` · `WebSocket` · `Stripe` · `AWS EC2` · `Vercel`

<details>
<summary><b>Architecture at a glance</b></summary>

```text
Next.js / React UI
        │
        ▼
   Apollo Client ────── WebSocket client
        │                       │
        ▼                       ▼
 NestJS GraphQL API       Real-time chat
        │
        ├── Authentication / authorization
        ├── Members / agents / destinations
        ├── Hotels / tours / bookings
        ├── Payments / webhook handlers
        ├── Community / notifications
        └── MongoDB Atlas (Mongoose)

Hosting: Vercel (web) + AWS EC2 (API)
```

</details>

### 📚 ELIF BOOK STORE — Full-Stack Book Discovery Platform

**A responsive bookstore experience with a customer-facing catalog and an EJS-based admin panel.**

[![Live Website](https://img.shields.io/badge/Live%20Demo-Explore%20ELIF-0D9488?style=flat-square&logo=googlechrome&logoColor=white)](https://elif-book.store/)

- Book discovery with categories, filters, search, and detailed product pages.
- Shopping basket and wishlist interactions.
- Member authentication and profile features.
- Ratings and book engagement features.
- Server-rendered admin dashboard for **book catalog and user management**.
- Create/edit book details, availability, stock, pricing, descriptions, and images.
- Express REST backend with MongoDB/Mongoose data models.

`React` · `TypeScript` · `Redux Toolkit` · `Node.js` · `Express` · `REST API` · `MongoDB` · `Mongoose` · `EJS` · `Material UI`

> The admin showcase focuses on catalog and user management; no completed order-management system is claimed.

### 🧪 RoadVision AI — Korean Traffic Sign Recognition

**In progress · Computer Vision / Applied Machine Learning**

Developing an image-classification workflow for **South Korean traffic signs**, with multilingual descriptions in Korean, Uzbek, and English.

**Learning and implementation focus:**

- Building and validating image datasets with consistent class-to-label mappings.
- OpenCV image processing and webcam capture.
- PyTorch `Dataset`, `DataLoader`, transforms, batching, and augmentation.
- MobileNetV2 transfer learning, custom training loops, and model checkpoints.
- Matplotlib evaluation plots and image-based inference.
- A planned React + FastAPI interface for recognizing signs and explaining their meaning.

`Python` · `OpenCV` · `PyTorch` · `Torchvision` · `MobileNetV2` · `Matplotlib` · `React` · `FastAPI`

> Training, evaluation, and any accuracy figures will be reported only after testing a real licensed Korean traffic sign dataset.

---

## Technical Toolbox

### Languages & Web Fundamentals

![JavaScript](https://img.shields.io/badge/JavaScript-111827?style=flat-square&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=3178C6)
![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=3776AB)
![HTML5](https://img.shields.io/badge/HTML5-111827?style=flat-square&logo=html5&logoColor=E34F26)
![CSS3](https://img.shields.io/badge/CSS3-111827?style=flat-square&logo=css3&logoColor=1572B6)

### Frontend Engineering

![React](https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-111827?style=flat-square&logo=nextdotjs&logoColor=white)
![Redux Toolkit](https://img.shields.io/badge/Redux%20Toolkit-111827?style=flat-square&logo=redux&logoColor=764ABC)
![Apollo Client](https://img.shields.io/badge/Apollo%20Client-111827?style=flat-square&logo=apollographql&logoColor=9B63E4)
![Material UI](https://img.shields.io/badge/Material%20UI-111827?style=flat-square&logo=mui&logoColor=007FFF)
![Styled Components](https://img.shields.io/badge/styled--components-111827?style=flat-square&logo=styledcomponents&logoColor=DB7093)
![Vite](https://img.shields.io/badge/Vite-111827?style=flat-square&logo=vite&logoColor=646CFF)

### Backend & API Engineering

![Node.js](https://img.shields.io/badge/Node.js-111827?style=flat-square&logo=nodedotjs&logoColor=5FA04E)
![NestJS](https://img.shields.io/badge/NestJS-111827?style=flat-square&logo=nestjs&logoColor=E0234E)
![Express](https://img.shields.io/badge/Express-111827?style=flat-square&logo=express&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-111827?style=flat-square&logo=graphql&logoColor=E10098)
![REST API](https://img.shields.io/badge/REST%20APIs-111827?style=flat-square)
![WebSockets](https://img.shields.io/badge/WebSockets-111827?style=flat-square)
![Socket.IO](https://img.shields.io/badge/Socket.IO-111827?style=flat-square&logo=socketdotio&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-111827?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI%20(Learning)-111827?style=flat-square&logo=fastapi&logoColor=009688)

### Data, Cloud & Development Tools

![MongoDB](https://img.shields.io/badge/MongoDB-111827?style=flat-square&logo=mongodb&logoColor=47A248)
![Mongoose](https://img.shields.io/badge/Mongoose-111827?style=flat-square)
![Atlas](https://img.shields.io/badge/MongoDB%20Atlas-111827?style=flat-square&logo=mongodb&logoColor=47A248)
![Redis](https://img.shields.io/badge/Redis%20(Exploring)-111827?style=flat-square&logo=redis&logoColor=DC382D)
![AWS](https://img.shields.io/badge/AWS%20EC2-111827?style=flat-square&logo=amazonec2&logoColor=FF9900)
![Vercel](https://img.shields.io/badge/Vercel-111827?style=flat-square&logo=vercel&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=2496ED)
![PM2](https://img.shields.io/badge/PM2-111827?style=flat-square)
![Git](https://img.shields.io/badge/Git-111827?style=flat-square&logo=git&logoColor=F05032)
![GitHub](https://img.shields.io/badge/GitHub-111827?style=flat-square&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-111827?style=flat-square&logo=postman&logoColor=FF6C37)
![Stripe](https://img.shields.io/badge/Stripe-111827?style=flat-square&logo=stripe&logoColor=635BFF)

### Applied AI & Data Science — Actively Learning

![NumPy](https://img.shields.io/badge/NumPy-111827?style=flat-square&logo=numpy&logoColor=4DABCF)
![Pandas](https://img.shields.io/badge/Pandas-111827?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-111827?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-111827?style=flat-square&logo=opencv&logoColor=5C3EE8)
![PyTorch](https://img.shields.io/badge/PyTorch-111827?style=flat-square&logo=pytorch&logoColor=EE4C2C)
![MobileNetV2](https://img.shields.io/badge/MobileNetV2-111827?style=flat-square)
![Ollama](https://img.shields.io/badge/Ollama-111827?style=flat-square)

Currently exploring **computer vision, image classification, model training and inference, local LLMs, embeddings, and AI-assisted development**.

---

## Engineering Interests

| Area | What I work on |
|:--|:--|
| **Backend architecture** | Modular services, validation, DTOs, guards, decorators, interceptors, domain boundaries |
| **Authentication & security** | JWT, password hashing, OAuth flows, RBAC, CORS, rate limiting, protected endpoints |
| **Database design** | MongoDB schemas, aggregation pipelines, filtering, pagination, references, atomic updates |
| **Business workflows** | Booking availability, state transitions, payment webhooks, refunds, idempotency |
| **Real-time systems** | WebSocket-based chat, messaging, notifications, connection handling |
| **Deployment & operations** | Linux/EC2, PM2, environment configuration, production debugging, frontend hosting |
| **Applied ML** | Data preparation, augmentation, CNN classification, PyTorch training and evaluation (in progress) |

## GitHub Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=kazakov7&show_icons=true&hide_border=true&theme=transparent&rank_icon=github" alt="GitHub activity stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=kazakov7&layout=compact&langs_count=8&hide_border=true&theme=transparent" alt="Top languages by public repository code" />

</div>

<sub>Activity cards are third-party widgets; language percentages represent repository code, not proficiency.</sub>

---

## Current Focus

```text
BUILD      → AURORA · travel marketplace architecture & reliability
IMPROVE    → TypeScript, NestJS, GraphQL & production debugging
LEARN      → Python, PyTorch, OpenCV & MobileNetV2
EXPLORE    → RoadVision AI · Korean traffic sign classification
PRACTICE   → Algorithms, system design & technical interviews
```

## Let's Connect

I'm interested in **full-stack and backend engineering opportunities**, meaningful collaborations, and software that solves real problems.

<div align="center">

[![GitHub](https://img.shields.io/badge/Explore%20my%20GitHub-111827?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kazakov7)
[![AURORA](https://img.shields.io/badge/Visit%20AURORA-2563EB?style=for-the-badge&logo=vercel&logoColor=white)](https://auroratravel.vercel.app/)
[![ELIF](https://img.shields.io/badge/Visit%20ELIF%20BOOK%20STORE-0D9488?style=for-the-badge&logo=googlechrome&logoColor=white)](https://elif-book.store/)

**Build real things. Understand the systems behind them. Keep improving.**

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=90&section=footer&color=0:0B1220,100:2563EB" alt="Footer wave" />

</div>
