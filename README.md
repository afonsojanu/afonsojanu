<h1 align="center">Afonso Januário</h1>
<p align="center">Backend Developer & AI Engineer · Master's in Computer Engineering (AI) @ ISCTE</p>

<p align="center">
<a href="https://www.linkedin.com/in/afonsojanu"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

### About

I'm pursuing a Master's in Computer Engineering at ISCTE (specializing in AI), and I'm a Teaching Assistant there for the Bachelor's Introduction to Programming in Python course. I currently work as a backend developer at **Typeble**, where I design and build REST APIs, backend services and database architecture in Python. I've also interned in software development at **Capgemini Engineering**, and done a security-focused internship (vulnerability assessment, in-scope pentesting, exploit development) at **CyberS3C**.

Outside of work, I dig through real open-source codebases — C, C++, Python, JS — looking for bugs nobody's caught yet, then fix them properly: reproduce first, write a test that fails on the old code and passes on the new one, verify against the project's own suite before opening anything. It's the fastest way I've found to actually get better at reading production code instead of toy projects.

I've also won hackathons and led small technical teams along the way.

### Experience

| | | |
|---|---|---|
| **2026 – now** | Backend Developer, **Typeble** (startup) | Python — REST APIs, backend services, database architecture, system design, performance optimization |
| **2026 – now** | Teaching Assistant, **ISCTE** | *Introduction to Programming in Python* |
| **2026** | Software Development Intern, **Capgemini Engineering** | Implementation, testing and improvement of applications in a team-based workflow |
| **2024** | Cybersecurity, **CyberS3C** | Vulnerability assessment, in-scope pentesting, exploit development, led small teams, delivered training |

### Education

- **MSc, Computer Engineering** (in progress) — ISCTE, Lisbon · specializing in Artificial Intelligence
- **BSc, Computer Engineering** (final year) — ISTEC, Lisbon · CGPA 16/20 (~3.7/4.0)
- **CTeSP, Mobile Device Development** — ISTEC, Lisbon · CGPA 16/20 (~3.7/4.0)

### A few open-source fixes I'm proud of

All merged into the project's own codebase, not just opened and forgotten:

| Project | What was actually wrong |
|---|---|
| [moment.js](https://github.com/moment/moment/pull/6442) | `locale('__proto__')` silently corrupted the library's global locale registry for every other consumer |
| [Duktape](https://github.com/svaarala/duktape/pull/2587) | Heap-buffer-overflow in the embeddable JS engine's string-cache scanner, found with AddressSanitizer |
| [libexpat](https://github.com/libexpat/libexpat/pull/1354) | The XML parser that ships inside CPython itself accepted a malformed declaration version it should have rejected |
| [Python-Markdown](https://github.com/Python-Markdown/markdown/pull/1631) | Quadratic-time regex backtracking in reference-link parsing — a real ReDoS, not a style nitpick |
| [Gunicorn](https://github.com/benoitc/gunicorn/pull/3718) | Unneeded filesystem checks were breaking abstract-namespace Unix sockets — merged by the maintainer directly |
| [Assimp](https://github.com/assimp/assimp/pull/6832) | Heap-buffer-overflow reading MD2 model skin names |

Full history on the [pull requests tab](https://github.com/pulls?q=is%3Apr+author%3Aafonsojanu+is%3Amerged) — these six just stuck with me.

### Stats

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=afonsojanu&show_icons=true&hide_title=true&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=afonsojanu&layout=compact&hide_border=true" alt="Top languages" />
</p>
<p align="center">
<img src="https://streak-stats.demolab.com/?user=afonsojanu&hide_border=true" alt="GitHub streak" />
</p>

### What I reach for

**Backend:** Python · .NET · JavaScript/TypeScript · REST API design
**AI/ML:** currently specializing in this through my master's at ISCTE
**Also build with:** React · React Native · Flutter
**Security:** vulnerability assessment, pentesting basics
**Tools:** Docker (mostly for sanitizer builds), Git

**Languages:** Portuguese (native) · English (B1) · Spanish (B2)

### Outside of code

Gym, cooking, and whatever game I'm currently too invested in.

<p align="center"><sub>Always happy to talk about a weird bug — <a href="https://www.linkedin.com/in/afonsojanu">reach out on LinkedIn</a>.</sub></p>
