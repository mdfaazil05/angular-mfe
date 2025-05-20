# 🚀 Coexisting Angular Microfrontends

**Tech Stack:** Angular + [single-spa](https://single-spa.js.org) + [single-spa-layout](https://single-spa.github.io/single-spa.js.org/docs/layout-overview/)

This repository showcases a **microfrontend architecture using Angular**, where multiple Angular apps (or micro-apps) work together seamlessly in a single-page application. It's built using `single-spa`, which means you can later extend it with React, Vue, or any other framework if needed.

Perfect for developers looking to get started with Angular-based microfrontends with minimal setup.

---

## 🧠 About the Project

* Combines **multiple Angular apps** into a single user experience
* Enables **independent development and deployment** of each microfrontend
* Utilizes `single-spa` and `single-spa-layout` for orchestration and routing
* Great for **team-based architecture** — each team can own and manage its own Angular app
* Includes four apps in this mono-repo:

  * `root-html-file` (shell app)
  * `navbar`
  * `app1`
  * `app2`

> 💡 In real-world setups, each app should ideally live in its own repository for better team autonomy.

---

## 💽 Running the Project Locally

You can either **run all apps at once** or **develop one microfrontend at a time** (recommended for better performance and developer experience).

---

### Clone the repo

```bash

git clone https://github.com/mdfaazil05/angular-mfe

cd angular-mfe

```

### 🧪 Run All Apps Locally

If you'd like to spin up the entire system locally:

```bash
# Terminal 1
cd root-html-file
npm install
npm start
```

```bash
# Terminal 2
cd app1
npm install
npm start
```

```bash
# Terminal 3
cd app2
npm install
npm start
```

```bash
# Terminal 4
cd navbar
npm install
npm start
```

Then open your browser and go to:
📅 **[http://localhost:4200](http://localhost:4200)**

> You can change ports in the `index.html` of `root-html-file` by editing the **Import Map**.

---

## 🛠️ Why This Repo is Useful

* Great starting point for **Angular devs looking to adopt microfrontend architecture**
* Minimal setup, well-documented, and easy to extend
* Clone & run with ease – **ideal for onboarding developers quickly**
* Encourages **modular codebases** for larger teams or enterprise apps

---

> ✅ Anyone interested in working with Angular-based microfrontends can **clone this repo and get started in minutes**. Whether you're building a proof of concept or structuring a scalable architecture, this project gets you up and running fast.
