# Wasiq Bashir — Personal Portfolio

> **Building the Engineer I'm Becoming.**

A personal portfolio website for **Wasiq Bashir**, a Software Engineering student focused on building a strong foundation in software development while moving toward **full-stack development, cloud computing, and DevOps**.

The site is designed as a visual, editorial-style portfolio rather than a conventional developer template. It combines bold typography, personal photography, motion, interactive sections, and a clear engineering-learning narrative.

---

## ✨ Overview

This portfolio presents:

- A cinematic introduction and personal identity
- A visual gallery built around personal photography
- A concise personal/about section
- Current technical capabilities and learning areas
- Selected software projects and GitHub repositories
- A progression timeline showing the engineering journey
- Current areas of exploration
- A **Code → Application → Server → Container → Cloud → Automation** direction
- Education and academic foundations
- Public GitHub work
- A contact section
- Responsive design and motion effects

The portfolio intentionally presents learning honestly: it focuses on **progress, projects, and direction** rather than claiming expertise prematurely.

---

## 🎯 Personal Positioning

The portfolio is built around this direction:

**Software Engineering Student → Full-Stack Development → Cloud & DevOps → Cloud Engineering**

Current areas of focus include:

- Programming fundamentals
- C++
- Object-Oriented Programming
- Data Structures & Algorithms
- HTML & CSS
- JavaScript
- DOM and browser interaction
- Responsive web development
- Git & GitHub
- Backend exploration
- Linux
- Cloud computing
- DevOps concepts
- Databases
- Future cloud engineering

---

## 🧩 Featured Projects

The current portfolio showcases six projects:

| # | Project | Focus |
|---|---|---|
| 01 | **Momenta** | HTML, CSS, Vanilla JavaScript |
| 02 | **Netflix UI Clone** | Responsive UI, Flexbox, CSS Grid |
| 03 | **JavaScript DOM Playground** | DOM, events, forms, interaction |
| 04 | **JavaScript Practice Toolkit** | JavaScript fundamentals and validation |
| 05 | **JS Fundamentals Login UI** | UI, DOM, regex, validation |
| 06 | **C# New Project** | C# / .NET learning |

The portfolio deliberately describes these as learning and development work rather than overstating their scope.

---

## 🎨 Design Philosophy

The visual identity combines:

- Editorial web design
- Cinematic photography
- Minimal interface design
- Large display typography
- Monospace technical labels
- Dark and light section transitions
- Subtle gradients and borders
- Smooth scroll/reveal animations
- Personal photography
- Interactive hover states

### Visual direction

The design language can be summarized as:

**Editorial × Engineering × Photography**

The goal is to make the portfolio feel personal and memorable while still communicating technical credibility.

---

## ⚙️ Tech Stack

### Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- CSS
- HTML

### UI & Interaction

- Lucide React
- Radix UI components
- Framer Motion
- Wouter
- React Hook Form
- TanStack React Query
- Sonner

### Development

- Node.js
- PNPM
- TypeScript
- Git
- GitHub

### Project Environment

- Replit-compatible workspace
- Vite development server
- PNPM workspace structure

---

## 📁 Project Structure

```text
wasiq-bashir-portfolio/
│
├── artifacts/
│   │
│   ├── api-server/
│   │   └── src/
│   │
│   ├── mockup-sandbox/
│   │   └── src/
│   │
│   └── wasiq-bashir-portfolio/
│       │
│       ├── public/
│       │   ├── favicon.svg
│       │   ├── robots.txt
│       │   ├── wasiq-portrait.png
│       │   ├── wasiq-red.jpg
│       │   ├── wasiq-stairs.png
│       │   ├── wasiq-suit.png
│       │   └── wasiq-tree.png
│       │
│       └── src/
│           ├── components/
│           ├── hooks/
│           ├── lib/
│           ├── pages/
│           ├── App.tsx
│           ├── index.css
│           └── main.tsx
│
├── lib/
│   ├── api-client-react/
│   └── api-spec/
│
├── package.json
└── .replit
```

---

## 🖥️ Main Sections

### Hero

Introduces Wasiq with:

- Name and identity
- Software Engineering positioning
- Full-stack/cloud/DevOps direction
- Personal portrait
- Animated entrance
- Pointer-based visual movement

### Visual Index

A horizontally moving visual gallery using personal photographs and abstract system-thinking visuals.

### About

Explains the transition from programming fundamentals toward software engineering and scalable systems.

### Building

Presents the development mindset and technical foundation.

### Selected Work

Displays six projects with their:

- Project number
- Category
- Description
- Technologies
- GitHub repository

### Journey

A progression from:

```text
Foundation
    ↓
C++
    ↓
OOP
    ↓
DSA
    ↓
Git / GitHub
    ↓
HTML / CSS
    ↓
JavaScript
    ↓
DOM
    ↓
Responsive Development
    ↓
Web Projects
    ↓
Backend Exploration
    ↓
Linux
    ↓
Cloud
    ↓
DevOps
    ↓
Future Cloud Engineering
```

### Currently Exploring

Interactive topics covering:

- Cloud computing
- DevOps
- Linux
- Full-stack development
- Databases
- Software engineering
- Data Structures & Algorithms

### Cloud Direction

A visual engineering pipeline:

```text
CODE
  ↓
APPLICATION
  ↓
SERVER
  ↓
CONTAINER
  ↓
CLOUD
  ↓
AUTOMATION
```

### Education

Current academic foundation:

**Bachelor's in Software Engineering**  
University of Management and Technology (UMT)  
Lahore, Pakistan

### Public Code

Highlights selected GitHub repositories and provides access to the complete GitHub profile.

### Contact

Provides LinkedIn and GitHub contact paths.

The current contact form performs local validation and does **not** send email because the portfolio does not currently have a connected email/backend service.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have:

- Node.js
- PNPM

The project is configured as a PNPM workspace.

### Install dependencies

From the project root:

```bash
pnpm install
```

### Start development

The portfolio application is located at:

```text
artifacts/wasiq-bashir-portfolio
```

Run:

```bash
cd artifacts/wasiq-bashir-portfolio
pnpm dev
```

The Vite configuration expects the `PORT` and `BASE_PATH` environment variables.

For a local setup, for example:

```bash
PORT=5000 BASE_PATH=/ pnpm dev
```

On Windows PowerShell:

```powershell
$env:PORT="5000"
$env:BASE_PATH="/"
pnpm dev
```

---

## 🏗️ Production Build

From the portfolio directory:

```bash
pnpm build
```

To preview the production build:

```bash
pnpm serve
```

The workspace also provides root-level build and type-check commands.

```bash
pnpm typecheck
pnpm build
```

---

## 🔍 Type Checking

Run:

```bash
pnpm typecheck
```

This checks the TypeScript code without emitting compiled files.

---

## 🌐 GitHub

GitHub profile:

**https://github.com/cyber-Horcrux**

Selected repositories:

- **Momenta:** https://github.com/cyber-Horcrux/My-Project
- **Netflix UI Clone:** https://github.com/cyber-Horcrux/netflix-ui-clone
- **JavaScript DOM Playground:** https://github.com/cyber-Horcrux/javascript-dom-playground
- **JavaScript Practice Toolkit:** https://github.com/cyber-Horcrux/javascript-practice-toolkit
- **JS Fundamentals Login UI:** https://github.com/cyber-Horcrux/js-fundamentals-login-ui
- **C# New Project:** https://github.com/cyber-Horcrux/CSharp-New-Project

---

## 💼 Connect

### LinkedIn

https://www.linkedin.com/in/wasiq-bashir-712139399/

### GitHub

https://github.com/cyber-Horcrux

### Instagram

https://www.instagram.com/the_haji_/

---

## 🛣️ Roadmap

The portfolio is intended to evolve alongside the developer.

### Current

- Strengthen JavaScript
- Improve DSA
- Build more frontend projects
- Learn React
- Explore backend development
- Improve Git/GitHub workflow

### Next

- Node.js
- APIs
- Databases
- Linux
- Docker
- Cloud platforms
- CI/CD

### Future Direction

- AWS / cloud architecture
- Terraform
- Kubernetes
- Advanced DevOps
- Production deployments
- Scalable full-stack systems
- Cloud engineering

---

## 📌 Future Improvements

Planned improvements may include:

- [ ] Connect the contact form to a real email service
- [ ] Add live project demos
- [ ] Add detailed project case studies
- [ ] Add real project screenshots to project cards
- [ ] Add cloud architecture diagrams
- [ ] Add GitHub API-powered repository data
- [ ] Add certifications
- [ ] Add downloadable CV
- [ ] Add more full-stack projects
- [ ] Add cloud-deployed projects
- [ ] Add Docker and CI/CD demonstrations
- [ ] Add accessibility refinements
- [ ] Improve SEO and metadata
- [ ] Add analytics

---

## 📱 Responsive Design

The website is designed to adapt across:

- Desktop
- Laptop
- Tablet
- Mobile

Navigation, typography, images, cards, grids, and interactive sections are adjusted for smaller screens.

Reduced-motion preferences are also considered for users who prefer less animation.

---

## 🔐 Notes

This is a personal portfolio project and is continuously evolving.

Some sections represent **learning goals and future direction**, not completed professional expertise.

The portfolio intentionally uses the idea:

> **Progression, not completion.**

---

## 👨‍💻 Author

**Wasiq Bashir**

BS Software Engineering Student  
Aspiring Full-Stack Developer  
Future Cloud & DevOps Engineer

**Lahore, Pakistan**

---

## 📄 License

This project is intended as a personal portfolio.

The source code can be used for learning and reference, but personal photographs, branding, identity, and portfolio content should not be reused without permission.

---

<p align="center">
  <strong>Building the Engineer I'm Becoming.</strong>
</p>
