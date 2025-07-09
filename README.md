# ⚡ Vite Tailwind Starter Kit

**Vite Tailwind Starter Kit** is a CLI tool that instantly scaffolds a modern Vite + React + Tailwind CSS project complete with optional React Router and Lucide Icons—using just one command.

It automates all the boring setup work and gives you a beautifully styled, production-ready boilerplate so you can jump right into building.

---

## 🚀 Features

- Sets up **Vite** with **React**
- Configures **Tailwind CSS v4**
- Updates **tailwind.config.js** and **index.css** automatically
- Optional **React Router v6+** with starter routes
- Optional **Lucide Icons** (lightweight, customizable SVG icons)
- Cleans up default Vite boilerplate
- Generates responsive components with Tailwind classes
- Minimal, developer-friendly file structure
- Supports **npm**, **pnpm**, **yarn**, and **bun** package managers
- Automatically **opens the browser** to `http://localhost:5173` after starting the project (optional)
- Generates a `.gitignore` with common defaults

---

## 📦 Installation

Install the CLI globally:

```bash
npm install -g vite-tailwind-starter-kit
```

---

## 🛠 Usage

Run the CLI to scaffold a new project:

```bash
vite-tailwind
```

Then follow the prompts:

```
√ Enter your project name ... vite-tailwind-v4-app
√ Do you want to install react-router-dom? ... yes (if you want, otherwise type N)
√ Do you want to install lucide-react icons? ... yes (if you want, otherwise type N)
```

After setup completes, you'll see this message:

```
Tailwind CSS v4 with Vite plugin setup complete! Run the following commands to start your project:
```

Now run:

```bash
cd vite-tailwind-v4-app
npm install
npm run dev
```

💥 Boom! Your project is up and running at localhost:

```bash
http://localhost:5000/
```

---

## 🤪 What It Does

1. Creates a Vite + React project with your provided name
2. Installs and configures:
   - `tailwindcss v4`
   - `react-router-dom` _(if selected)_
   - `lucide-react` _(if selected)_
3. Generates:
   - `App.jsx` — with responsive layout and Tailwind utilities
   - `App.jsx` — if routing is selected
   - Example pages — `Home`, `About`, with navigation in `App.jsx`
   - Integrated Lucide icons — if selected

---

## 📁 Project Structure

```
my-app/
├── node_modules/
├── public/
│   └── vite.svg
├── src/
│   ├── assets/
│   │   └── react.svg
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   ├── main.jsx
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── vite.config.js
└── README.md
```

---

## 🙌 Credits

<a href="https://x.com/megh_bari" style="display: inline-flex; align-items: center; gap: 8px; text-decoration: none;">
    <img src="https://github.com/megh-bari.png?size=40" alt="avatar" width="32" height="32" style="border-radius: 50%;" />
    <span> Creator</span>
  </a>

---

## 🫱🏻‍🫲🏻 Contributor:

[![avatar](https://github.com/iamvkr.png?size=40)](https://github.com/iamvkr)

---

## 📜 License

[MIT](./LICENSE)

---

## 🎉 Happy Hacking!

Got ideas to make this starter even better? PRs welcome or drop your thoughts at [@megh_bari](https://x.com/megh_bari) ✨
