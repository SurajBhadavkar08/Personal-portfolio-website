# Portfolio
Personal portfolio website built with React + Vite. Demonstrates basic SPA routing with nested routes for the About section (Skills, Education, Experience).

## Features
- React + Vite
- react-router-dom for top-level and nested routing
- Components: Home, About (with nested Skills, Education, Experience), Contact, Portfolio
- Simple responsive UI with gradient cards and hover effects

## Project structure (important files)
- src/
  - App.jsx            — main router + navbar
  - main.jsx           — app entry
  - Home.jsx
  - About.jsx          — nested routes + sub-navigation
  - Skills.jsx
  - Education.jsx
  - Experience.jsx
  - Contact.jsx
  - Portfolio.jsx
  - Navbr.jsx / CSS files
- index.html
- vite.config.js
- package.json (project metadata & scripts)

## Requirements
- Node.js 16+ and npm (Windows)

## Install & run (Windows)
1. Open PowerShell or Command Prompt and go to the project root:
```cmd
cd C:\Users\suraj\Desktop\Portfolio

Steps to run the project on Windows (short):

Verify Node/npm
node -v
npm -v

Node 16+ recommended.

cd C:\Users\suraj\Desktop\Portfolio

3a. If package.json exists, install deps:
npm install

3b. If package.json is missing, create a Vite React project (this will generate package.json), or use the package.json you already added:
npm create vite@latest . -- --template react
npm install

4.(Optional) install recommended extras:
npm install react-router-dom react-bootstrap bootstrap react-icons axios

5.Start dev server
npm run dev

6.Build / preview
npm run build
npm run preview
