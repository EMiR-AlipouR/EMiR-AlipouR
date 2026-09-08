from pathlib import Path

content = """# 👋 Hey, I'm EMiR

### 💻 Frontend Developer · Computer Engineering Student

I'm a Computer Engineering student passionate about **Web Development** and modern JavaScript technologies.

Currently, I'm focused on building real projects and improving my skills with **React, Next.js, and modern web technologies**.

---

## 🚀 About Me

- 🎓 Computer Engineering Student

- 💻 Frontend Developer

- 🌱 Currently learning **Next.js & Full-Stack Development**

- ⚡ Interested in building modern, responsive web applications

- 🧠 Always learning and experimenting with new technologies

- 🎯 Goal: Become a skilled **Full-Stack Developer**

---

## 🛠️ Tech Stack

### Frontend

<p>

  <img src="https://skillicons.dev/icons?i=html,css,js,react,nextjs,tailwind" />

</p>

### Tools & Workflow

<p>

  <img src="https://skillicons.dev/icons?i=git,github,vscode,npm" />

</p>

---

## 📚 Currently Learning

```text

Next.js

   ↓

API Routes & REST APIs

   ↓

Server Components

   ↓

Database

   ↓

Authentication

   ↓

Full-Stack Development

```

I'm currently focusing on understanding how the **frontend, server, APIs, and database** work together to build complete applications.

---

## 🚀 Featured Projects

### 📝 Mini TodoList API

A small full-stack TodoList project built with **Next.js**.

**What I practiced:**

- REST API

- CRUD Operations

- GET / POST / PUT / PATCH / DELETE

- Dynamic Routes

- Catch-all Routes

- Server Components

- Server-side concepts

🔗 [View Repository](https://github.com/EMiR-AlipouR/NextMiniTodo-api)

---

### 🍔 NextFood

A recipe website built with **Next.js & Tailwind CSS** while learning modern React and Next.js concepts.

**What I practiced:**

- Next.js App Router

- React

- Tailwind CSS

- API integration

- Dynamic filtering

- Responsive UI

---

## 📈 My Learning Journey

```text

HTML

 ↓

CSS

 ↓

JavaScript

 ↓

React

 ↓

Tailwind CSS

 ↓

Next.js

 ↓

APIs & Backend

 ↓

Database

 ↓

Full-Stack 🚀

```

Still learning. Still building. Still improving.

---

## 🎯 2026 Goals

- [x] Learn HTML & CSS

- [x] Learn JavaScript

- [x] Learn React

- [x] Learn Tailwind CSS

- [x] Start Next.js

- [x] Build my first Next.js API

- [ ] Learn Databases

- [ ] Learn Authentication

- [ ] Build larger full-stack projects

- [ ] Become job-ready as a Full-Stack Developer

---

## 📊 GitHub Stats

<p align="center">

  <img src="https://github-readme-stats.vercel.app/api?username=EMiR-AlipouR&show_icons=true&theme=transparent&hide_border=true" height="170"/>

  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EMiR-AlipouR&layout=compact&theme=transparent&hide_border=true" height="170"/>

</p>

---

## 🤝 Let's Connect

<p align="center">

  <a href="https://github.com/EMiR-AlipouR">

    <img src="https://img.shields.io/badge/GitHub-EMiR--AlipouR-black?style=for-the-badge&logo=github"/>

  </a>

</p>

---

<p align="center">

  <b>💻 Build. Learn. Improve. Repeat. 🚀</b>

</p>

"""

path = Path("/mnt/data/README.md")

path.write_text(content, encoding="utf-8")

print(path)
