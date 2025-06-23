# Pramod's – Next.js Starter Template

A minimal, modern, and developer-friendly **Next.js starter template** built for fast development with **React 19**, **Tailwind CSS v4**, **TypeScript**, and **commit conventions** powered by **Husky** and **Commitlint**. This is customized for internal or educational project scaffolding at **Pramod**.

---

## 🚀 Tech Stack & Versions

| Tool               | Version       | Description                                      |
|--------------------|---------------|--------------------------------------------------|
| **Next.js**        | 15.3.4        | React-based full-stack framework                |
| **React**          | ^19.0.0       | Latest UI library version                       |
| **Tailwind CSS**   | ^4            | Utility-first modern CSS framework              |
| **TypeScript**     | ^5            | Static typing for scalable JS development       |
| **ESLint**         | ^9            | Linting tool for maintaining code quality       |
| **Husky**          | latest        | Git hooks for pre-commit checks                 |
| **Commitlint**     | ^19.8.1       | Enforce commit message convention               |

---

## 📁 Folder Structure

```bash
.
├── public/                 # Static assets
├── src/                   # Source files
│   ├── pages/             # Next.js pages (Routing)
│   ├── components/        # Reusable UI components
│   ├── styles/            # Tailwind and global styles
├── .eslintrc.json         # ESLint configuration
├── tailwind.config.ts     # TailwindCSS config
├── tsconfig.json          # TypeScript config
├── package.json           # Project config & dependencies
```

---

## ✅ Features

- ✅ Fully ready with **React 19 + Next.js 15**
- ✅ **Tailwind CSS 4** for fast UI development
- ✅ **TypeScript support** by default
- ✅ **Commit linting** using Conventional Commits
- ✅ **Pre-configured ESLint** for clean code
- ✅ **Git hooks** using Husky for reliable commits
- ✅ Minimal boilerplate to focus on coding
- ✅ Works with `app` or `pages` directory

---

## 🛠️ Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/nextjs-starter.git
cd nextjs-starter
```

### 2. Install dependencies

```bash
npm install
```

### 3. Run in development mode

```bash
npm run dev
```

### 4. Build for production

```bash
npm run build
```

### 5. Start the production server

```bash
npm start
```

---

## 🔍 Scripts Overview

| Command     | Purpose                                  |
|-------------|-------------------------------------------|
| `dev`       | Start Next.js dev server with Turbopack   |
| `build`     | Compile and build production app          |
| `start`     | Start Next.js production server           |
| `lint`      | Run ESLint across your codebase           |
| `prepare`   | Used by Husky to install Git hooks        |

---

## 🧩 Commit Convention

This project follows **Conventional Commits** with custom commit rules powered by `@commitlint` and `Husky`.

### ✅ Allowed Commit Types

- `feat` – A new feature
- `fix` – A bug fix
- `docs` – Documentation-only changes
- `style` – Code style changes (formatting, etc.)
- `refactor` – Code changes that don't add features or fix bugs
- `perf` – Performance improvements
- `test` – Adding or fixing tests
- `build` – Changes to build system or dependencies
- `ci` – Changes to CI configuration
- `chore` – Miscellaneous changes (not affecting source/test)
- `revert` – Reverting a previous commit

### 📋 Commit Message Rules

- ✅ Type must be one of the allowed types and **lowercase**
- ✅ Type may optionally include a scope: `type(scope): subject`
- ✅ Subject must be in **sentence case** (only the first word capitalized)
- ❌ Subject must **not be empty**
- ⚠️ Maximum commit header length: **100 characters**

---

### ✅ Valid Examples

```bash
feat: Add student login page
fix: Resolve navbar responsiveness issue
docs: Update usage instructions in README
style: Reformat all CSS files
refactor(core): Simplify dashboard component
perf(images): Optimize PNG assets
test(api): Add test cases for login endpoint
chore: Update project dependencies
```

### ❌ Invalid Examples

```bash
Fix: add login button                # ❌ Type must be lowercase
feat:                               # ❌ Subject must not be empty
feat: add Login button              # ❌ Subject must be in sentence case
feat(): add support for something   # ❌ Empty scope (remove or name it)
feat(login): Add Login Function     # ❌ Subject must be in sentence case, not Title Case
```

---

All commits are checked automatically by **Husky** and **Commitlint** before being accepted.


---

## 🌐 Live Demo

You can deploy this template using **Vercel**, **Netlify**, or any Next.js compatible platform.

---

## 📌 License

This project is licensed for educational and personal use.

---

## ✍️ Author

Made with ❤️ by **Pramod Laha**
