⚡ VibeCheck — AI-Powered UX/UI Website Analyzer
📋 Table of Contents
App Overview & Problem Solved
Live Deployment
Features List
AI Feature & System Prompt
Tools, Services & AI Models
App Screenshots
How to Run Locally
Creator & Owner
🎯 App Overview & Problem Solved
What is VibeCheck?
VibeCheck is an intelligent visual audit platform designed to evaluate website designs instantly. By uploading a screenshot or entering a live URL, VibeCheck leverages multimodal artificial intelligence to analyze key user experience (UX) and user interface (UI) principles, delivering professional, structured feedback in seconds.

The Real Problem It Solves
Early-stage founders, independent developers, and students often build functional web applications but struggle with UI design, visual balance, contrast compliance, and call-to-action (CTA) placement. Professional UI/UX design audits from agency consultants are expensive and slow, while automated CSS linters fail to assess aesthetic balance or user perception.

Who It Is For
Frontend Developers & SaaS Founders: Who want instant, actionable feedback before launching products to public users.
UI/UX Designers: Looking for a second perspective on layout hierarchy, accessibility contrast, and typography scale.
Students & Product Creators: Seeking fast design audits to refine showcase projects and portfolio applications.
🌐 Live Deployment
The application is deployed and live for public use:

👉 Clickable Live URL: https://vibe-check-zainab-aqeel.netlify.app/

✨ Features List
[x] Dual Input Analysis Engine: Flexible analysis via image upload (PNG, JPG, WebP) or live website URLs.
[x] Undeployed Localhost Fallback Detection: Smart popup modal that alerts users if a URL points to localhost or an undeployed link, guiding them to upload a screenshot instead.
[x] Multimodal AI UI Audit: Automated evaluation covering visual hierarchy, typography scaling, whitespace distribution, color harmony, and accessibility contrast.
[x] Actionable CSS Fixes: Generates direct, high-impact CSS tweaks and copy-pasteable recommendations to quickly elevate visual appeal.
[x] Interactive About Modal: Dedicated creator showcase detailing project mission and owner attribution.
[x] Responsive Mobile Navigation Menu: Compact navigation drawer built with Lucide React icons for smooth responsive mobile and desktop viewports.
[x] Dark-Mode Optimized UI: Clean, modern dashboard styled with glassmorphism and Tailwind CSS gradients.
🤖 AI Feature & System Prompt
What the AI Feature Does
The core AI engine accepts a visual representation of a web layout (either uploaded directly by the user or captured from a live site) and processes the image using vision-enabled Large Language Models (LLMs). It outputs a structured design audit card breaking down strengths, usability flaws, accessibility warnings, and high-priority visual improvements.

Instructions / System Prompt Behind the AI
The AI operates on the following strict system instructions:


You are an expert Principal UI/UX Architect and Accessibility Specialist. Your job is to perform a meticulous visual design audit on the provided website screenshot.

Analyze the image across the following 5 core design pillars:
1. Visual Hierarchy & Composition: Focal point clarity, hero section layout, and cognitive clutter evaluation.
2. Typography & Readability: Font pairings, heading-to-body scaling, line heights, and readability contrast.
3. Color Palette & Brand Consistency: Primary/secondary color harmony, brand identity cohesion, and high-contrast CTA visibility.
4. Spacing & Grid Alignment: Alignment consistency, padding/margin balance, and effective whitespace utilization.
5. Quick Wins & CSS Enhancements: 3 high-impact, actionable design recommendations with exact CSS code snippets.



Output Guidelines:
- Keep the tone constructive, clear, and professional.
- Format output into structured sections using bold headers and bullet points.
- Prioritize actionable design tweaks that yield maximum visual improvement.

🛠️ Tools, Services & AI Models

Category

Technology / Service

Framework

Next.js (React 18 App Router)

Language

TypeScript

Styling

Tailwind CSS

Icons

Lucide React

AI Vision Model

Google Gemini 1.5 Flash Vision API / Multimodal LLM

Deployment / Hosting

Netlify

Version Control

Git & GitHub

📸 App Screenshots
1. Landing Page & Hero Section
VibeCheck main landing page with headline, dual-input toggle, and modern dark layout.

2. Interactive About Modal
Interactive modal window displaying project information and owner attribution for Zainab Aqeel.

3. Navigation Header & UI Analyzer Workflow
Responsive navigation header and live AI-powered UI audit report generated from a screenshot upload.

(Note: Replace image paths above with your exact relative paths or GitHub repository asset links)

💻 How to Run Locally
Follow these instructions to run VibeCheck on your local development machine.

Prerequisites
Node.js (v18.0.0 or higher)
npm or yarn
Step-by-Step Setup
Clone the repository:
Bash
git clone https://github.com/zainabaqeel17/Vibecheck-Website-UI-UX-analyzer
cd vibecheck
Install project dependencies:
Bash
npm install
Configure Environment Variables:
Create a .env.local file in the root directory and add your AI Vision API key:
Code snippet
NEXT_PUBLIC_AI_API_KEY=your_gemini_or_openai_api_key_here
Start the local development server:
Bash
npm run dev
Open in browser:
Open your browser and navigate to http://localhost:3000.
👩‍💻 Creator & Owner
Zainab Aqeel

Software Engineer & Creator of VibeCheck

Live Project: https://vibe-check-zainab-aqeel.netlify.app/
Mission: Making modern UI/UX design audits fast, accessible, and hassle-free for creators everywhere.
📄 License
This project is licensed under the MIT License — see the LICENSE file for details.
