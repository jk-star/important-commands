# React Important Commands

A quick reference guide for commonly used React, Vite, npm, and Git commands.

---

## 1. Check Node.js and npm

```bash
node -v
npm -v
```

Check installed Node.js and npm versions.

---

## 2. Create a React Project

### Using Vite (Recommended)

```bash
npm create vite@latest my-react-app
```

Or directly with React + JavaScript:

```bash
npm create vite@latest my-react-app -- --template react
```

---

## 3. Go Inside Project

```bash
cd my-react-app
```

---

## 4. Install Dependencies

```bash
npm install
```

Short form:

```bash
npm i
```

---

## 5. Start Development Server

```bash
npm run dev
```

Usually opens the application at:

```text
http://localhost:5173
```

---

## 6. Stop Development Server

Press:

```text
Ctrl + C
```

---

## 7. Build React Project

```bash
npm run build
```

Creates the production build inside:

```text
dist/
```

---

## 8. Preview Production Build

```bash
npm run preview
```

---

# NPM Commands

## Install a Package

```bash
npm install package-name
```

Example:

```bash
npm install axios
```

---

## Install a Development Dependency

```bash
npm install package-name --save-dev
```

Short form:

```bash
npm i package-name -D
```

Example:

```bash
npm i eslint -D
```

---

## Remove a Package

```bash
npm uninstall package-name
```

Example:

```bash
npm uninstall axios
```

---

## Check Installed Packages

```bash
npm list
```

Top-level packages only:

```bash
npm list --depth=0
```

---

## Update Packages

```bash
npm update
```

---

## Check Outdated Packages

```bash
npm outdated
```

---

# Common React Packages

## React Router

Install:

```bash
npm install react-router-dom
```

Common imports:

```jsx
import {
  BrowserRouter,
  Routes,
  Route,
  Link,
  NavLink,
  useNavigate,
  useParams
} from "react-router-dom";
```

---

## Axios

Install:

```bash
npm install axios
```

Import:

```jsx
import axios from "axios";
```

GET request:

```jsx
axios.get("/api/users");
```

POST request:

```jsx
axios.post("/api/users", data);
```

---

## Sass

Install:

```bash
npm install sass
```

Then use `.scss` files:

```text
App.scss
style.scss
```

---

## Tailwind CSS

Install:

```bash
npm install tailwindcss @tailwindcss/vite
```

---

# React Project Useful Commands

```bash
npm run dev
```

Runs the development server.

```bash
npm run build
```

Creates the production build.

```bash
npm run preview
```

Previews the production build.

```bash
npm install
```

Installs project dependencies.

```bash
npm install package-name
```

Installs a new package.

```bash
npm uninstall package-name
```

Removes a package.

---

# Git Commands for React Project

## Initialize Git

```bash
git init
```

## Check Status

```bash
git status
```

## Add All Files

```bash
git add .
```

## Commit

```bash
git commit -m "Initial React project"
```

## Add Remote Repository

```bash
git remote add origin https://github.com/username/repository.git
```

## Push

```bash
git push -u origin main
```

## Pull

```bash
git pull origin main
```

## Clone React Project

```bash
git clone https://github.com/username/repository.git
```

---

# React Project Folder Structure

```text
my-react-app/
│
├── node_modules/
├── public/
│
├── src/
│   ├── assets/
│   ├── components/
│   ├── pages/
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
│
├── .gitignore
├── index.html
├── package.json
├── package-lock.json
└── vite.config.js
```

---

# Important Files

## package.json

Contains:

- Project information
- Dependencies
- Scripts
- Version information

Example:

```json
{
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview"
  }
}
```

---

# Troubleshooting Commands

## Delete node_modules

### Windows CMD

```cmd
rmdir /s /q node_modules
```

### PowerShell

```powershell
Remove-Item -Recurse -Force node_modules
```

---

## Delete package-lock.json

### Windows CMD

```cmd
del package-lock.json
```

### PowerShell

```powershell
Remove-Item package-lock.json
```

---

## Reinstall Dependencies

```bash
npm install
```

---

## Clean Reinstall

### macOS/Linux/Git Bash

```bash
rm -rf node_modules package-lock.json
npm install
```

### Windows PowerShell

```powershell
Remove-Item -Recurse -Force node_modules
Remove-Item package-lock.json
npm install
```

---

# Quick Cheat Sheet

| Task | Command |
|---|---|
| Check Node | `node -v` |
| Check npm | `npm -v` |
| Create React project | `npm create vite@latest` |
| Install packages | `npm install` |
| Start project | `npm run dev` |
| Build project | `npm run build` |
| Preview build | `npm run preview` |
| Install package | `npm install package-name` |
| Remove package | `npm uninstall package-name` |
| Check packages | `npm list --depth=0` |
| Check outdated | `npm outdated` |
| Git status | `git status` |
| Git add | `git add .` |
| Git commit | `git commit -m "message"` |
| Git push | `git push` |
| Git pull | `git pull` |
| Git clone | `git clone URL` |

---

# Most Important Commands to Remember

```bash
npm create vite@latest
npm install
npm run dev
npm install package-name
npm uninstall package-name
npm run build
npm run preview
```
