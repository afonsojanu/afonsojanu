<h1 align="center">Afonso Januário</h1>
<p align="center">CS master's student who spends most of his free time reading other people's C, C++, Python and JS codebases until something breaks — then fixing it properly.</p>

<p align="center">
<a href="https://www.linkedin.com/in/afonsojanu"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://github.com/afonsojanu"><img src="https://img.shields.io/github/followers/afonsojanu?style=flat-square&label=Followers&color=blue" alt="Followers"></a>
</p>

---

### About

I got into this almost by accident: I started picking real bugs out of open-source issue trackers to get better at reading production code instead of toy projects, and it turned into a habit. Most of what I do now is the same loop every time — find something that's actually broken, reproduce it myself before touching anything, fix it, and prove the fix with a test that fails on the old code and passes on the new one.

Before this I built mobile and web apps professionally (Flutter, React, Node.js) during an internship at **Cybers3c** (Mar–Aug 2024).

**Education:** MSc in Computer Science (in progress) · CTESP in Mobile Device Development (2022–2024)

### A few fixes I'm proud of

These are all merged into the project's own codebase, not just opened and forgotten:

| Project | What was actually wrong |
|---|---|
| [moment.js](https://github.com/moment/moment/pull/6442) | `locale('__proto__')` silently corrupted the library's global locale registry for every other consumer of the library |
| [Duktape](https://github.com/svaarala/duktape/pull/2587) | Heap-buffer-overflow in the embeddable JS engine's string-cache scanner, found with AddressSanitizer |
| [libexpat](https://github.com/libexpat/libexpat/pull/1354) | The XML parser (the one that ships inside CPython itself) accepted a malformed declaration version it should have rejected |
| [Python-Markdown](https://github.com/Python-Markdown/markdown/pull/1631) | Quadratic-time regex backtracking in reference-link parsing — a real ReDoS, not just a style nitpick |
| [Gunicorn](https://github.com/benoitc/gunicorn/pull/3718) | Unneeded filesystem checks were breaking abstract-namespace Unix sockets — merged by the maintainer directly |
| [Assimp](https://github.com/assimp/assimp/pull/6832) | Heap-buffer-overflow reading MD2 model skin names |

Full history is on the [pull requests tab](https://github.com/pulls?q=is%3Apr+author%3Aafonsojanu+is%3Amerged) — these six are just the ones that stuck with me.

### Stats

<p align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=afonsojanu&show_icons=true&hide_title=true&hide_border=true&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=afonsojanu&layout=compact&hide_border=true" alt="Top languages" />
</p>
<p align="center">
<img src="https://streak-stats.demolab.com/?user=afonsojanu&hide_border=true" alt="GitHub streak" />
</p>

### What I reach for

**Comfortable reading and fixing:** C · C++ · Python · JavaScript/TypeScript
**Build with:** React · React Native · Flutter · Node.js/Express
**Tools:** Docker (mostly for spinning up sanitizer builds), Git, VS Code

### Outside of code

Gym, cooking, and whatever game I'm currently too invested in.

<p align="center"><sub>Always happy to talk about a weird bug — <a href="https://www.linkedin.com/in/afonsojanu">reach out on LinkedIn</a>.</sub></p>
