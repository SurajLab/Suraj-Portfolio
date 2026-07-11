# Suraj Agrawal — Portfolio Website

A personal portfolio website built with **React** and **Vite**, featuring animated pages (via Framer Motion) for showcasing projects, skills, certificates, and a resume, plus a working contact form.

## About the Project

This is a single-page application (SPA) with client-side routing. Each section of the portfolio lives on its own route/page:

- **Home** – animated intro, profile photo, typing effect, and quick links to social profiles (GitHub, LinkedIn, Gmail, WhatsApp, Instagram)
- **About** – short bio and development interests
- **Projects** – showcase of projects with tech stack tags, live demo and source code links
- **Skills** – interactive visualization of languages, frameworks, and tools known
- **Certificates** – gallery of certifications with image previews
- **Blog** – space for articles/posts
- **Resume** – embedded and downloadable PDF resume
- **Contact** – validated form (name, email/phone, subject, message) that sends messages via EmailJS
- **404 page** for unknown routes

## Project Structure

```
Suraj-Portfolio/
├── index.html               # HTML entry point
├── vite.config.mjs          # Vite build configuration
├── package.json             # Dependencies & npm scripts
├── public/                  # Static assets (images, certs, resume.pdf)
└── src/
    ├── main.jsx              # React app entry point
    ├── App.jsx                # Route definitions, navbar & footer
    ├── index.css              # Global styles
    ├── components/
    │   └── Navbar.jsx         # Site navigation bar
    ├── CSS/                   # Page-specific stylesheets
    └── pages/
        ├── Home.jsx
        ├── About.jsx
        ├── Projects.jsx
        ├── Skills.jsx
        ├── Certificates.jsx
        ├── Blog.jsx
        ├── Resume.jsx
        ├── Contact.jsx
        └── NotFound.jsx
```

## Tech Stack

| Category | Technology |
|---|---|
| Framework | React 18 |
| Build tool | Vite 5 |
| Routing | React Router DOM v6 |
| Animation | Framer Motion |
| Icons | React Icons, Lucide React |
| Data viz | D3.js |
| Contact form | EmailJS (emailjs-com) |
| Styling | Plain CSS |

## Getting Started

### Prerequisites
- Node.js (v16+) and npm installed

### Setup & Run

```bash
# Clone the repository
git clone https://github.com/SurajLab/Suraj-Portfolio.git
cd Suraj-Portfolio

# Install dependencies
npm install

# Start the development server (http://localhost:5173)
npm run dev

# Build for production (output goes to dist/)
npm run build

# Preview the production build locally
npm run preview
```

### Note on Contact Form
The contact form uses EmailJS. To make it functional in your own deployment, set your own EmailJS service ID, template ID, and public key inside `src/pages/Contact.jsx`.

## Author
**Suraj Agrawal** — BCA Student, Aspiring Full Stack Developer
- GitHub: [@SurajLab](https://github.com/SurajLab)
- LinkedIn: [suraj404](https://www.linkedin.com/in/suraj404)
