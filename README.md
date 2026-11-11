# 👋 Hey, I'm Mayank Sahu

<div align="center"> <a href="https://git.io/typing-svg"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=Full+Stack+Developer;MERN+Stack+%7C+Next.js+%7C+TypeScript;Building+Scalable+Web+Applications;Frontend+Engineering+%7C+Backend+Development;Turning+Ideas+Into+Digital+Products" alt="Typing SVG" /> </a> <br/> <a href="https://mayank-sahu-dev.vercel.app"> <img src="https://img.shields.io/badge/Portfolio-Visit%20Website-0EA5E9?style=for-the-badge&logo=vercel&logoColor=white" /> </a> <a href="https://www.linkedin.com/in/mayank-sahu-ou"> <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /> </a> <a href="https://github.com/Deadshot-45"> <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" /> </a> <img src="https://komarev.com/ghpvc/?username=Deadshot-45&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile views" /> </div>
🚀 About Me
I'm a Full-Stack Developer passionate about building modern, responsive, and scalable web applications.

Currently working as a Frontend Intern at Lincpay, contributing to product development, reusable UI components, and scalable frontend solutions.

I enjoy working across the development lifecycle, from designing interactive user interfaces to developing backend APIs, integrating databases, and implementing authentication.

💻 Building full-stack applications using React, Next.js, Node.js, and Express.js.
⚡ Developing reusable components and RESTful APIs.
🔐 Working with authentication, authorization, and application security.
🗄️ Exploring database optimization, caching, and scalable backend architecture.
🎨 Interested in modern UI/UX, animations, and web performance.
🌱 Continuously learning and improving my engineering skills.
🛠️ Tech Stack
Frontend Development
<p align="left"> <img src="https://skillicons.dev/icons?i=html,css,js,ts,react,next,redux,tailwind,bootstrap,jquery" /> </p>
Backend Development
<p align="left"> <img src="https://skillicons.dev/icons?i=nodejs,express" /> </p>
Database & ORM
<p align="left"> <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,prisma" /> </p>
Tools & Platforms
<p align="left"> <img src="https://skillicons.dev/icons?i=git,github,vscode,postman,vercel,npm,docker" /> </p>
💼 Featured Projects
<table> <tr> <td width="50%" valign="top">
💬 iMessage
A real-time chat application inspired by Apple's iMessage, featuring a modern messaging experience and cloud-native architecture.

Highlights

Real-time communication
Modern messaging interface
TypeScript-based development
Tech: TypeScript

View Repository →

</td> <td width="50%" valign="top">
🛍️ Vault Vogue Lite
A modern fashion e-commerce storefront built with Next.js and TypeScript.

Highlights

Product browsing
Authentication pages
Shopping cart UI
Reusable components
Tech: Next.js · TypeScript · Tailwind CSS

Frontend Repository →

</td> </tr> <tr> <td width="50%" valign="top">
⚙️ E-commerce Backend
A backend API for the Vault Vogue e-commerce application.

Highlights

Secure authentication
Product management
Cart handling
Order processing
RESTful APIs
Tech: Node.js · Express.js · TypeScript

View Repository →

</td> <td width="50%" valign="top">
🌐 Personal Portfolio
A personal portfolio showcasing my development skills, experience, and projects through a responsive interface.

Highlights

Responsive UI
Modern design
Interactive components
Tech: React · Tailwind CSS · Vite

View Repository →

</td> </tr> </table>
📊 GitHub Statistics
<div align="center"> <img width="49%" src="https://github-readme-stats.vercel.app/api?username=Deadshot-45&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" /> <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Deadshot-45&layout=compact&theme=tokyonight&hide_border=true" />
<br/><br/>

<img width="70%" src="https://streak-stats.demolab.com?user=Deadshot-45&theme=tokyonight&hide_border=true" /> </div>
🐍 Contribution Activity
<div align="center"> <img src="https://raw.githubusercontent.com/Deadshot-45/Deadshot-45/output/github-contribution-grid-snake.svg" alt="GitHub contribution snake animation" /> </div>
🤝 Let's Connect
<div align="center">
I'm always open to connecting with developers, collaborating on interesting projects, and exploring new opportunities.

<a href="https://mayank-sahu-dev.vercel.app">Portfolio</a> ·
<a href="https://www.linkedin.com/in/mayank-sahu-ou">LinkedIn</a> ·
<a href="https://github.com/Deadshot-45">GitHub</a>

<br/><br/>

Thanks for visiting my profile! ⭐

<i>Code. Build. Learn. Repeat.</i>

</div>
<div align="center">
© 2026 Mayank Sahu

</div></WritingBlock>
Configure your contribution snake animation

Keep the GitHub Actions workflow in .github/workflows/snake.yml:

<CodeBlock language="yaml" editable> name: Generate Contribution Snake
on:
schedule:
- cron: "0 0 * * *"
workflow_dispatch:
push:
branches:
- main

permissions:
contents: write

jobs:
generate:
runs-on: ubuntu-latest

steps:
  - name: Generate Snake
    uses: Platane/snk@v3
    with:
      github_user_name: Deadshot-45
      outputs: |
        dist/github-contribution-grid-snake.svg

  - name: Deploy Snake
    uses: crazy-max/ghaction-github-pages@v3.1.0
    with:
      target_branch: output
      build_dir: dist
    env:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
</CodeBlock>
