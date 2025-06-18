# 🚀 Portfolio Website Revamp – Project Plan

I've had a portfolio site up for a while — it works, but it's due for an upgrade. The goal is to rebuild it from the ground up with full-stack functionality: dynamic content, proper API structure, better form handling, and a modernized frontend. This project will also help sharpen my backend and deployment workflows.

This project tracks everything — PRs, features, experiments, and commits.

---

## 📂 Project Summary

- **Methodology:** Agile (Scrum)
- **Sprints:** 3–4 (1 week each)
- **Tracking Format:** Jira-style Epics → Stories → Subtasks
- **Deployment Target:** Netlify (frontend), Spring Boot + PostgreSQL (backend)

---

## 🔵 Epic 1: Technical Discovery & Requirements

**Goal:** Define the problem, audit the existing portfolio, and lay the architectural foundation.

### Stories:
- `REQ-1`: Audit current portfolio site
- `REQ-2`: Gather feature requirements and wishlist
- `REQ-3`: Finalize tech stack and deployment tools
- `REQ-4`: Design high-level system architecture
- `REQ-5`: Break down backlog into epics/stories

### Deliverables:
- Architecture diagram
- Requirements doc
- Initial GitHub repo + project structure
- First PR: `spike/001-portfolio-revamp-requirements`

---

## 🟢 Epic 2: Backend API – Spring Boot Service

**Goal:** Build scalable backend services to power dynamic content and handle form submissions.

### Stories:
- `API-1`: Spring Boot project with Maven
- `API-2`: Configure PostgreSQL + schema for projects & contacts
- `API-3`: Build REST endpoints:
  - `GET /projects`
  - `POST /contact`
  - `POST /newsletter-optin`
- `API-4`: Add input validation and error handling
- `API-5`: Set up H2 for dev/testing
- `API-6`: Integrate Spring Mail for SMTP

### Deliverables:
- Backend server with API endpoints
- PostgreSQL schema + H2 support
- Contact form integration via email
- Postman collection for testing

---

## 🟠 Epic 3: Frontend – ReactJS UI

**Goal:** Rebuild frontend with React, integrating APIs and improving UX/UI.

### Stories:
- `FE-1`: Initialize React app (Yarn + Router)
- `FE-2`: Build base pages: Home, Projects, Contact, About
- `FE-3`: Integrate project listing via backend API
- `FE-4`: Create contact form with Yup validation
- `FE-5`: Integrate WhatsApp CTA (react-whatsapp-button)
- `FE-6`: Add newsletter form via `use-mailchimp-form`
- `FE-7`: Optimize layout for mobile and accessibility

### Deliverables:
- Functional, responsive React frontend
- API integration for dynamic data
- Validated contact + newsletter forms

---

## 🟣 Epic 4: CI/CD, Deployment & Environment Management

**Goal:** Deploy the application and set up continuous integration pipelines.

### Stories:
- `DEVOPS-1`: Set up `.env` configs for local/staging/prod
- `DEVOPS-2`: Deploy frontend to Netlify with GitHub auto-build
- `DEVOPS-3`: (Optional) Configure GitHub Actions for lint/test
- `DEVOPS-4`: Monitor Netlify build status
- `DEVOPS-5`: Secure SMTP and Mailchimp keys

### Deliverables:
- Live website (Netlify)
- Secure deployment environment
- CI/CD setup

---

## 🟡 Epic 5: Final QA & Documentation

**Goal:** Polish the app, finalize documentation, and perform QA.

### Stories:
- `QA-1`: Run Lighthouse audit (performance, accessibility, SEO)
- `QA-2`: Manually test all API endpoints
- `QA-3`: Test UI across browsers/devices
- `QA-4`: Write README and developer guide
- `QA-5`: (Optional) Write blog/devlog about the revamp

### Deliverables:
- Final test reports
- Complete project documentation
- Optional blog post

---

## 📅 Timeline (Tentative)

| Sprint | Focus Area                    |
|--------|-------------------------------|
| Week 1 | Discovery + Requirements       |
| Week 2 | Backend Setup + API Endpoints |
| Week 3 | Frontend UI + API Integration |
| Week 4 | Form Handling + Mailchimp     |
| Week 5 | QA + Final Deployment         |

---

## ✅ Success Criteria

- Portfolio hosted live with Netlify
- Dynamic project data from backend API
- Functional contact form (email via SMTP)
- Integrated Mailchimp and WhatsApp contact options
- Mobile-first, fast-loading, accessible UI
- Fully version-controlled with GitHub PRs

---

## 🌐 Production Link

Coming soon: [https://rm's_portfolio.netlify.app](#)

