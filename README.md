<div id="header" align="center">
  <img src="https://media.giphy.com/media/QDjpIL6oNCVZ4qzGs7/giphy.gif" width="400"/>
  <h1>
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=800&size=28&pause=300&color=00AEEF&center=true&vCenter=true&width=800&lines=Hey%2C+I'm+Kostya+%F0%9F%91%8B;Full-Stack+JavaScript+Developer;JavaScript+%7C+TypeScript+%7C+NestJS+%7C+React" 
    alt="Typing SVG" 
  />
    <div id="badges">
    <a href="https://www.linkedin.com/in/konstantin-barilo-333974290/">
      <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=inspire&logoColor=white" alt="LinkedIn Badge"/>
    </a>
    <a href="https://x.com/kostabarilo12">
      <img src="https://img.shields.io/badge/Twitter-black?style=for-the-badge&logo=x&logoColor=white&lfbel=twitter" alt="X Badge"/>
    </a>
    <a href="https://t.me/kostianchick">
      <img src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Badge"/>
    </a>
  </div>
  </h1>  
</div>

### 😉 About Me 

I am a Full-Stack Developer.
- 🎓 graduate of BSUIR
- ⚡ 1,5+ years of full-stack engineering experience
- 🏅 calisthenics fan
- 📧 how to reach me: *kostabarilo12@gmail.com*
- 📃 [CV](./CV.pdf)


### 🛠️ Languages & Tools I Use

<div align="center">
  <img src="https://skillicons.dev/icons?i=html,css,js,ts,nodejs" />
  <img src="https://skillicons.dev/icons?i=bun,nest,rxjs,react,next" />
  <img src="https://skillicons.dev/icons?i=tailwind,redux,vite,vitest" />
  <img src="https://skillicons.dev/icons?i=docker,postgres,mongo,redis,rabbitmq" />
  <img src="https://skillicons.dev/icons?i=git,vscode,postman,figma,linux" />
</div>

<!--  -->
<!-- Giutub Stats -------------------------------->
<!--  -->

<!--### 📊 GitHub Stats

<div align="center">
  <table>
    <tr>
      <td>
        <img src="http://github-profile-summary-cards.vercel.app/api/cards/stats?username=TarhunchiKKK&theme=transparent" alt="Stats" />
      </td>
      <td>
        <img src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=TarhunchiKKK&theme=transparent" alt="Stats" />
      </td>
    </tr>
    <tr>
      <td colspan="2">
        <img src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=TarhunchiKKK&theme=transparent" alt="Stats" />
      </td>
    </tr>
  </table>
</div>-->

### 🍓 My Custom Library

[nestjs-multi-limiter](https://www.npmjs.com/package/nestjs-multi-limiter) - production-grade, race-condition safe rate limiting module for the [NestJS](https://nestjs.com/) framework (Node.js). 

<p align="center">
<a href="https://github.com/tarhunchikkk/nestjs-multi-limiter/actions/workflows/ci.yml"><img src="https://github.com/tarhunchikkk/nestjs-multi-limiter/actions/workflows/ci.yml/badge.svg" alt="CI" /></a>
<a href="https://github.com/tarhunchikkk/nestjs-multi-limiter/actions/workflows/e2e.yml"><img src="https://github.com/tarhunchikkk/nestjs-multi-limiter/actions/workflows/e2e.yml/badge.svg" alt="E2e" /></a>
<a href="https://github.com/tarhunchikkk/nestjs-multi-limiter/actions/workflows/codeql-analysis.yml"><img src="https://github.com/tarhunchikkk/nestjs-multi-limiter/actions/workflows/codeql-analysis.yml/badge.svg" alt="CodeQL Analysis" /></a>
<a href="https://biomejs.dev/"><img src="https://img.shields.io/badge/code_style-XO-60a5fa.svg" alt="Code Style" /></a>
<a href="https://biomejs.dev/"><img src="https://img.shields.io/badge/styled_with-Biome-60a5fa.svg" alt="Formatter" /></a>
<a href="https://www.npmjs.com/package/nestjs-multi-limiter"><img src="https://img.shields.io/npm/l/nestjs-multi-limiter.svg" alt="Package License" /></a>
</p>

- **🛠️ Tech Stack:** TypeScript, NestJS, reflect-metadata, Redis, Lua, Bun Test Runner, GitHub Actions, Turborepo, Biome
- **🎨 Key Features:**
  - **5 Core Algorithms**: _Fixed Window_, _Token Bucket_, _Sliding Window Counter_, _Sliding Window Log_ and _Leaky Bucket_.
  - **Runtime Configuration:** The system of options factories allows dynamically configure limits at runtime per request context (e.g., based on JWT user roles or pricing tiers).
  - **Driver-Agnostic Storage:** Redis integration is completely decoupled from specific npm packages (like `ioredis` or `node-redis`).   
  - **Race-Condition Safe**: Powered Redis storage by execution <a href="https://www.lua.org/">Lua</a> scripts, preventing race conditions in multi-instant deployments.
  - **Redis Failure Handling:** _Fail-Open_, _Fail-Close_ and _Fail-Fast_ strategies
  - **Protocol Agnosticism:** Ability to implement custom key extractors and error factories allows you to integrate the library with any protocol.
  - **Swagger Integration:** Native integration with [@nestjs/swagger](https://www.npmjs.com/package/@nestjs/swagger) pacakge with ability to customize metadata in Swagger docs.
- **🏗️ Status:** ✅ Ready

[👉 See Repo](https://github.com/TarhunchiKKK/nestjs-multi-limiter)


<!--  -->
<!-- Calypso -------------------------------->
<!--  -->

<!-- 
### 🍓 Featured Pet-Project

**Calypso** — Virtual whiteboard tool that lets you easily sketch diagrams (clone of [Miro](https://miro-landing.vercel.app/) board editor).

- **🛠️ Tech Stack:** TypeScript, React, TailwindCSS, NestJS, Microservices
- **🎨 Key Features:**
  - Multiple node types: stickers, arrows, text nodes, shapes, medias, formattable documents and drawings
  - Multiple node actions: dragging, resizing, editing, styling, etc.
  - Arrows binding (even when related nodes are moving or resizing)
  - Cancellation (Undo/Redo) and exchange buffer (Copy/Paste/Cut)
  - Window shifting and zooming, endless board
- **🧪 Challenge:** No state managers and drag-n-drop libraries
- **🏗️ Status:** 🛠 In Development / ✅ Ready

[👉 View Code](https://github.com/TarhunchiKKK/calypso) -->
