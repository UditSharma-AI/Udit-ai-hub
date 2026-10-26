# Udit Sharma | AI Learning Hub

*Learn. Practice. Recall. Apply.*

Interactive study notes for **Machine Learning**, **Deep Neural Networks**, **Deep Reinforcement Learning**, **Natural Language Processing**, **Software Engineering for Machine Learning**: 66 sessions, each with

- **Simple Learning**: plain-language explanation, steps, an interactive demo, a real-world example and a quick check
- **Technical Deep Dive**: equations, derivations, worked examples, complexity, verified Python code
- **Split view** that keeps both in sync
- **Interview prep** (beginner, intermediate, advanced, with a simulation mode), **quizzes**, **flashcards** with spaced repetition, and a **coverage report**

Site address (set at export time; check it after deploying): https://udit-ai-hub.vercel.app

## How it works

A static site: `index.html` (the whole app) plus `content/**.json` (one folder per session). No build step and no server; progress is saved in the visitor's browser. It works offline after the first visit and can be installed as an app.

## Deploy

- **Vercel / Netlify / Cloudflare Pages**: import this repository; framework preset "Other" (no build command, output directory = repository root).
- **GitHub Pages**: Settings → Pages → Deploy from branch → `main` / root.
