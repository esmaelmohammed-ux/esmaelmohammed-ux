# Hi there, I'm Esmael Mohammed 👋
<!-- Animated SVG hero -->
<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="160" viewBox="0 0 1000 160" preserveAspectRatio="xMidYMid meet" role="img" aria-labelledby="title desc">
  <title id="title">Esmael Mohammed - Fullstack Developer</title>
  <desc id="desc">Animated header: greeting, role and university</desc>

  <rect width="100%" height="100%" fill="#0f1724"/>
  <g transform="translate(40,40)">
    <text x="0" y="36" font-family="Inter, Arial, sans-serif" font-size="30" fill="#e6eef8">Hi, I'm <tspan fill="#7dd3fc">Esmael Mohammed</tspan> 👋</text>

    <!-- Animated sub-lines (fade in one after another) -->
    <text x="0" y="72" font-family="Inter, Arial, sans-serif" font-size="16" fill="#bcd8f6" opacity="0">
      Information Science — 3rd year · Haramaya University
      <animate attributeName="opacity" from="0" to="1" begin="0.6s" dur="0.8s" fill="freeze" />
    </text>

    <text x="0" y="96" font-family="Inter, Arial, sans-serif" font-size="16" fill="#bcd8f6" opacity="0">
      Fullstack Developer · React · Node · Django · PostgreSQL
      <animate attributeName="opacity" from="0" to="1" begin="1.4s" dur="0.8s" fill="freeze" />
    </text>

    <!-- Simple animated dots (activity / "I'm active" indicator) -->
    <g transform="translate(760,30)">
      <circle cx="0" cy="0" r="6" fill="#60a5fa">
        <animate attributeName="cy" values="0;10;0" dur="1s" repeatCount="indefinite" />
        <animate attributeName="opacity" values="1;0.5;1" dur="1s" repeatCount="indefinite" />
      </circle>
      <circle cx="20" cy="0" r="6" fill="#fb7185">
        <animate attributeName="cy" values="0;12;0" dur="1s" begin="0.15s" repeatCount="indefinite" />
        <animate attributeName="opacity" values="1;0.5;1" dur="1s" begin="0.15s" repeatCount="indefinite" />
      </circle>
      <circle cx="40" cy="0" r="6" fill="#fbbf24">
        <animate attributeName="cy" values="0;14;0" dur="1s" begin="0.3s" repeatCount="indefinite" />
        <animate attributeName="opacity" values="1;0.5;1" dur="1s" begin="0.3s" repeatCount="indefinite" />
      </circle>
    </g>
  </g>
</svg>

---

About Me
- 🎓 Third-year Information Science student at Haramaya University
- 💻 Fullstack developer — building web apps with a focus on clean UI and scalable backends
- 🌱 Learning and experimenting with modern JavaScript, Python, and cloud deployment
- 🔭 Interested in web performance, UX, and data-driven applications

Skills
- Frontend: React, Next.js, HTML5, CSS3, Tailwind CSS, SASS
- Backend: Node.js, Express, Django, REST APIs
- Databases: PostgreSQL, MongoDB
- Tools: Git, Docker, Vercel, Heroku
- Languages: JavaScript (ES6+), TypeScript, Python

Featured Projects
- Project Name — Short description of what it does, key technologies.
  - Example: TaskFlow — a productivity app with React + Node + PostgreSQL. (Add repo link)

- Project Name — Short description, features & impact.
  - Example: UniPortal — student portal built with Django + React. (Add repo link)

How I Work
- I prioritize readable, maintainable code and great UX.
- I prefer component-driven development, test-first features and continuous deployment.
- Open to collaboration and mentorship — I learn fast and enjoy building things that solve real problems.

Get in touch
- GitHub: https://github.com/esmaelmohammed-ux
- Email: esmael.mohammed@example.com (replace with your preferred contact)
- LinkedIn: https://www.linkedin.com/in/esmael-mohammed (optional: add your actual profile)

Animated README tips
- The SVG at the top is live and self-contained — you can edit colors, text, and animation timings directly in this file.
- If you want richer animations, consider adding animated GIF demos of apps (host them in /assets or use GitHub releases to store media).
- Use GitHub Actions to automatically update stats or an animated GIF (e.g., record a short demo and push to the README on release).

Quick copy-paste templates

- Project card template:
```md
### Project Name
Short one-line summary.

Built with: `React`, `Node.js`, `PostgreSQL`  
Live: https://your-app.vercel.app · Repo: https://github.com/yourname/project-name

Key features:
- Feature 1
- Feature 2
- What I learned: performance optimization, auth flows, db design
```

- Contact badge (example):
```md
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/esmael-mohammed)
```

If you'd like, I can:
- customize the SVG hero's colors and animation to match your personal brand,
- generate ready-to-use project cards for your top 3 repos,
- and produce a small animated demo GIF template you can run locally and embed.

Would you like me to customize the header colors and create project cards from your GitHub repos?
