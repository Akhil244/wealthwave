# 🚀 Next.js Project Starter

This is a **[Next.js](https://nextjs.org/)** project bootstrapped using [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app). It follows a modular architecture for scalability, performance, and developer experience.

---

## 🏗️ Project Architecture

![Project Architecture](https://github.com/user-attachments/assets/8c19c2a0-16a9-4773-aab4-84cb3082980e)

This diagram outlines the architectural design of the project including core directories, components, and API routes.

**Highlights:**
- Modular structure with `app/`, `components/`, and `api/`
- Page-based routing
- Centralized layout configuration
- Reusable and scalable component design
- Font optimization via `next/font`

---

## ⚙️ Getting Started

Follow these steps to run the development server:

### 1. Install dependencies

npm install
# or
yarn
# or
pnpm install
# or
bun install

## 2. Start the development server

npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev

Visit http://localhost:3000 to view the app in your browser.

Project Structure

.
├── app/                # Next.js app directory (pages, layout, routing)
│   ├── page.tsx        # Main landing page
│   └── layout.tsx      # App layout wrapper
├── components/         # Shared React components
├── public/             # Static assets (images, icons, etc.)
├── styles/             # Global styles and CSS modules
├── app/api/            # API routes (backend functions)
├── next.config.js      # Next.js configuration
└── README.md           # Project documentation

Fonts & Optimization
This project uses next/font for automatic optimization and loading of Google Fonts. The Inter font is used by default.
