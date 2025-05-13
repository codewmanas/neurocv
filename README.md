<h1 align="center"> 🧠 NeuroCV – AI-Powered Resume Builder</h1>

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge\&logo=nextdotjs\&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=for-the-badge\&logo=tailwindcss\&logoColor=white)
![Shadcn UI](https://img.shields.io/badge/Shadcn_UI-black?style=for-the-badge\&logo=Vercel\&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge\&logo=vercel\&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge\&logo=postgresql\&logoColor=white)
![Drizzle ORM](https://img.shields.io/badge/Drizzle_ORM-3A0CA3?style=for-the-badge)
![React Query](https://img.shields.io/badge/TanStack_React_Query-FF4154?style=for-the-badge\&logo=reactquery\&logoColor=white)
![Hono](https://img.shields.io/badge/Hono-EE4B2B?style=for-the-badge)
![Gemini AI](https://img.shields.io/badge/Gemini_AI-4285F4?style=for-the-badge\&logo=google)
![Kinde](https://img.shields.io/badge/Kinde_Auth-5A4FCF?style=for-the-badge)
</div>

## 🚀 Overview

**NeuroCV** is a modern, AI-driven resume builder that enables users to effortlessly create, customize, and manage professional resumes. Designed with sleek UI components and powered by the latest web technologies, NeuroCV delivers a seamless and intelligent experience for crafting impactful resumes.

---

## 🌟 Features

* 🔐 **Authentication with Kinde** – Google Sign-In integration for easy access
* ➕ **Create Resumes** – Start a new resume with structured sections
* ✏️ **Edit Resumes** – Real-time WYSIWYG-style resume editing
* 🎨 **Theme Customization** – Choose from multiple color schemes
* 📸 **Resume Thumbnails** – Automatically generated preview image
* 🗨️ **Shareable Links** – Instantly share resumes via public links
* 🔎 **Search Trash Resumes** – Find and restore deleted resumes
* 📡 **Live Editing Support** – Real-time updates as you type
* 🔗 **Preview Mode** – View resume in printable/public format
* 👨‍💻 **PDF Download** – One-click PDF export
* 🤖 **AI-Powered Resume Generation** – Integrated with Gemini AI

---

## 🧰 Tech Stack

### Frontend

* **[Next.js 14](https://nextjs.org/)** – React framework for building modern web apps
* **[TailwindCSS](https://tailwindcss.com/)** – Utility-first CSS framework
* **[Shadcn UI](https://ui.shadcn.com/)** – Accessible UI components built with Radix

### Backend / API

* **[Hono](https://hono.dev/)** – Lightweight, ultra-fast web framework
* **[Drizzle ORM](https://orm.drizzle.team/)** – Type-safe SQL ORM for TypeScript
* **[Vercel PostgreSQL](https://vercel.com/postgres)** – Managed Postgres DB solution

### AI Integration

* **[Gemini AI](https://deepmind.google/technologies/gemini/)** – Smart text generation and resume optimization

### Auth

* **[Kinde](https://kinde.com/)** – Secure and scalable authentication with Google Sign-In

### Data Management

* **[TanStack React Query](https://tanstack.com/query/latest)** – Powerful tool for data fetching, caching, and syncing

### Deployment

* **[Vercel](https://vercel.com/)** – Hosting and CI/CD deployment platform

---

## 📂 Folder Structure

```bash
├── app
│   ├── (auth)
│   ├── (dashboard)
│   ├── (editor)
│   └── layout.tsx
├── components
│   ├── ui
│   ├── shared
│   └── resume
├── lib
│   ├── drizzle
│   ├── hooks
│   └── utils
├── pages/api
│   └── hono-endpoints
├── public
├── styles
├── types
└── vercel.json
```

---

## 🧪 Running Locally

1. Clone the repo

```bash
git clone https://github.com/codewmanas/neurocv.git
cd neurocv
```

2. Install dependencies

```bash
yarn install
# or
npm install
```

3. Setup environment variables

```bash
cp .env.example .env.local
# Add your Kinde, DB, Gemini, etc. keys
```

4. Start the dev server

```bash
yarn dev
```

---

## 📜 License

Licensed under the **MIT License**.

---

## 🙌 Acknowledgements

Thanks to all open-source tools and libraries that power **NeuroCV**, and the developers who made these amazing frameworks possible.

---

## 📧 Contact

Have feedback, suggestions, or want to contribute?

* Email: [your.email@example.com](mailto:manas.kolaskar@somaiya.edu)
* GitHub: [@yourusername](https://github.com/codewmanas)

---

> ✨ NeuroCV – Build smarter resumes, faster.
