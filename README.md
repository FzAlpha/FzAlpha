<a href="https://github.com/FzAlpha">
  <img src="signature.svg" alt="Hritabrata Bardhan" />
</a>

**Systems & Software Developer** · B.Tech CSE at ITER, Siksha 'O' Anusandhan · Class of 2029

I build software close to the metal: C++, Linux internals and algorithms, and lately the backends that sit on top of them.

<p>
  <a href="https://portfolio-beige-six-oxsb0gllne.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white" alt="Portfolio">
  </a>
  <a href="https://www.linkedin.com/in/hritabrata-bardhan-12b498365/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://leetcode.com/u/Fz_Alpha_07/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black" alt="LeetCode">
  </a>
  <a href="mailto:hritabratabardhan13579@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

### About

I learn how operating systems work by building the parts most people never see: shells, process managers and state engines. I also configure and maintain my own Linux system. Lately that has grown into backends. I've built a modular C++ server framework, an API over SQLite, and a Postgres rewards platform where every table sits behind row-level security.

- Daily driver: **Arch Linux / EndeavourOS** with a custom **Hyprland** setup scripted in Lua and Bash.
- Comfortable with POSIX syscalls, process lifecycles, signals and debugging with GDB.
- Practising DSA in public on LeetCode: 269 problems solved, with a best streak of 64 days.

### Selected Work

| Project | What it is | Stack |
| :-- | :-- | :-- |
| **[Rewards Platform](https://github.com/FzAlpha/loyalty-app)**<br><sub>Backend · Client work</sub> | Backend for a loyalty app built to a client spec: digital stamp cards, offers, partner businesses and staff tools. It has 14 schema modules with deny-by-default row-level security, and all writes go through `SECURITY DEFINER` RPCs. 17 pgTAP test files run in CI, and there are 9 Edge Functions plus a mirrored FastAPI server. | PostgreSQL · Supabase · TypeScript · Python · pgTAP |
| **[AlgoVault](https://github.com/FzAlpha/algo-vault)**<br><sub>Full stack</sub> | A personal vault for coding-practice solutions. A C++ HTTP server over SQLite with 14 token-authenticated REST endpoints syncs stats from LeetCode's GraphQL API and draws a practice heatmap in the browser. | C++17 · SQLite · REST · JavaScript |
| **[CentralPlatform](https://github.com/FzAlpha/api_network_system)**<br><sub>C++ backend</sub> | A modular C++23 server framework. Modules register with a manager that starts them in order and tears them down in reverse, and errors are returned as `std::expected` values. HTTP runs on Crow + Asio, storage on SQLite. *Early in development.* | C++23 · Crow · SQLite · Docker |
| **[NovaShell](https://github.com/FzAlpha/custom-linux-shell)**<br><sub>OS internals</sub> | A small Unix shell in modern C++. It uses `fork` / `execvp` / `waitpid` for external commands, `dup2`-based output redirection, and signal handling so that Ctrl+C stops the child, not the shell. | C++23 · POSIX · Signals |
| **[Velvané](https://website-checker-lmdx.vercel.app/)**<br><sub>Web design</sub> | A studio showcase of ten complete websites, each in a different style (minimal, luxury, neo-brutal, liquid glass, retro cyber, immersive 3D…), plus three sites that blend them. Includes a canvas sketchbook that redraws ink drawings stroke by stroke. | React · TypeScript · Canvas · Motion |
| **Manufacturer Catalogue**<br><sub>Web · Client work (private)</sub> | A B2B site for a garment and uniform manufacturer: a product catalogue plus a quote request form with file uploads, delivered to the sales team by email. | Next.js · TypeScript · Tailwind · Nodemailer |

<sub>Earlier work: [log-Manager](https://github.com/FzAlpha/log-Manager) · [chat-program](https://github.com/FzAlpha/chat-program)</sub>

### Tech Stack

<table>
  <tbody>
    <tr>
      <td align="left" valign="middle" width="160"><b>Languages</b></td>
      <td align="left" valign="middle">
        <img src="https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white" alt="C++">
        <img src="https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black" alt="C">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python">
        <img src="https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white" alt="Java">
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" alt="TypeScript">
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" alt="JavaScript">
        <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white" alt="Bash">
        <img src="https://img.shields.io/badge/Lua-2C2D72?style=flat&logo=lua&logoColor=white" alt="Lua">
      </td>
    </tr>
    <tr>
      <td align="left" valign="middle" width="160"><b>Backend & Data</b></td>
      <td align="left" valign="middle">
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white" alt="PostgreSQL">
        <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white" alt="Supabase">
        <img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" alt="SQLite">
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI">
      </td>
    </tr>
    <tr>
      <td align="left" valign="middle" width="160"><b>Web</b></td>
      <td align="left" valign="middle">
        <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB" alt="React">
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white" alt="Next.js">
        <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">
        <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white" alt="HTML5">
        <img src="https://img.shields.io/badge/CSS-663399?style=flat&logo=css&logoColor=white" alt="CSS">
      </td>
    </tr>
    <tr>
      <td align="left" valign="middle" width="160"><b>Systems & Tools</b></td>
      <td align="left" valign="middle">
        <img src="https://img.shields.io/badge/Arch_Linux-1793D1?style=flat&logo=archlinux&logoColor=white" alt="Arch Linux">
        <img src="https://img.shields.io/badge/EndeavourOS-7F3FBF?style=flat&logo=endeavouros&logoColor=white" alt="EndeavourOS">
        <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white" alt="Ubuntu">
        <img src="https://img.shields.io/badge/Hyprland-00A69C?style=flat&logo=hyprland&logoColor=white" alt="Hyprland">
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker">
        <img src="https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white" alt="CMake">
        <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" alt="Git">
        <img src="https://img.shields.io/badge/Neovim-57A143?style=flat&logo=neovim&logoColor=white" alt="Neovim">
        <img src="https://img.shields.io/badge/GDB-A42E2B?style=flat&logo=gnu&logoColor=white" alt="GDB">
      </td>
    </tr>
  </tbody>
</table>

### Activity

<table align="center" border="0" cellpadding="0" cellspacing="0">
  <tr>
    <td align="center" valign="top">
      <img src="https://github-readme-stats.shion.dev/api?username=FzAlpha&show_icons=true&theme=github_dark&count_private=true&hide_border=true" alt="GitHub Stats" height="165" />
    </td>
    <td align="center" valign="top">
      <img src="https://github-readme-stats.shion.dev/api/top-langs/?username=FzAlpha&layout=compact&theme=github_dark&langs_count=6&hide_border=true" alt="Top Languages" height="165" />
    </td>
  </tr>
</table>

<p align="center">
  <a href="https://leetcode.com/u/Fz_Alpha_07/">
    <img src="https://leetcard.jacoblin.cool/Fz_Alpha_07?theme=dark&font=Inter&ext=heatmap" alt="LeetCode Stats" />
  </a>
</p>

<img src="https://github.com/FzAlpha/FzAlpha/raw/output/github-snake-dark.svg" alt="Contribution Snake" width="100%" />

### Contact

The fastest way to reach me is [email](mailto:hritabratabardhan13579@gmail.com). You can also find me on [LinkedIn](https://www.linkedin.com/in/hritabrata-bardhan-12b498365/) or on Discord as `fz_alpha_1`.
