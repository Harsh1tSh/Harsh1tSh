<p align="center">
  <img src="assets/banner.svg" alt="Harshit Sharma: software engineer, backend, full-stack and applied ML" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/Harsh1tSh/unmix">
    <img src="https://readme-typing-svg.demolab.com?font=Inter&weight=500&size=20&duration=3000&pause=1000&color=C084FC&center=true&vCenter=true&width=680&lines=Hi%2C+I'm+Harshit+%F0%9F%91%8B;I+build+things+end+to+end%2C+from+models+to+pixels;Now+building+Unmix%3A+neural+audio+source+separation;Python+%C2%B7+TypeScript+%C2%B7+FastAPI+%C2%B7+React+%C2%B7+PyTorch" alt="Hi, I'm Harshit. I build things end to end, from models to pixels." />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/harshit-sharma-6b883a193/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://leetcode.com/u/Heptaa/"><img src="https://img.shields.io/badge/LeetCode-546%20solved%20%C2%B7%20peak%201955-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode: 546 solved, peak rating 1955" /></a>
  <a href="mailto:hepta1000@gmail.com"><img src="https://img.shields.io/badge/Email-me-8B5CF6?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

I build full-stack and applied-ML products from end to end: **Python/FastAPI** and **TypeScript/React** services, **PyTorch** model pipelines, GPU inference, and graphics and audio in the browser. I care about software that is tested, typed, secure, and fast on ordinary hardware.

- 🎓 Dual degree (B.Tech + M.Tech) in Computer Science, **NIT Hamirpur**
- 🐫 Previously community ambassador at **[CAMEL-AI](https://github.com/camel-ai/camel)** (multi-agent systems, MCP servers)
- 🎧 Currently building **[Unmix](https://github.com/Harsh1tSh/unmix)**, below

---

## 🎧 Featured: Unmix

**Pull a recording apart by source.** Talk over a song, or drop any clip, and neural models split it into voices, drums, bass, guitar, piano and the rest, separate your voice from the singer's, and transcribe the lyrics word by word. Free, open source, and it runs on your own machine.

<p align="center">
  <a href="https://github.com/Harsh1tSh/unmix">
    <img src="https://raw.githubusercontent.com/Harsh1tSh/unmix/main/docs/media/demo.webp" alt="Unmix: a recording becomes seven sound spheres, then nine stems you can hear one by one" width="85%" />
  </a>
</p>

- **Models:** BS-RoFormer, HT-Demucs and MossFormer2 for separation, Whisper for word-timed lyrics; the stems sum exactly back to the mix
- **Backend:** FastAPI job pipeline with live progress and automatic CUDA / DirectML / Apple / CPU selection with measured fallback (37x faster on a T4 GPU than on CPU)
- **Frontend:** sample-locked playback of every stem in Web Audio (hover a card to hear one source), a live mode over WebSockets, in-browser inference in WebAssembly, and a WebGL2 particle sphere at 60 fps
- **Quality:** 170+ automated tests and a full security review

<p align="center"><a href="https://github.com/Harsh1tSh/unmix"><b>→ github.com/Harsh1tSh/unmix</b></a></p>

---

## 🛠️ More things I've built

| Project | What it is | Built with |
|---|---|---|
| **[DataVisual](https://github.com/Harsh1tSh/datavisual)** · [live](https://harsh1tsh.github.io/datavisual/) | Design a database schema on a canvas and get versioned migration files for Supabase, PostgreSQL, MySQL and SQLite, each following that database's own rules. Imports existing migrations or SQL dumps, runs fully in the browser and never touches a live database. | JavaScript (no framework), SVG, PWA, PGlite, Playwright |
| **LyricLight** *(private for now)* | One photo + a song → a lyric video where the words sit behind the person and their light falls on the scene. Segmentation and depth models, WebGL compositing, H.264 encoded in the browser. | Python, FastAPI, BiRefNet, Depth Anything V2, React, WebGL, WebCodecs |
| **[Sky Skirmish](https://github.com/Harsh1tSh/sky-skirmish)** | A browser jetpack shooter with 4 modes, 12 weapons and bots, where every sprite and sound is generated in code: no asset files at all. | TypeScript, Vite |
| **[AI Project Planner](https://github.com/Harsh1tSh/AI-Project-Planner)** | A team of AI agents that turns a project idea into a technical architecture and a timeline. | Python, CAMEL-AI, Mistral, Streamlit |
| **[AutoMax](https://github.com/Harsh1tSh/Django_app)** | Full-stack car marketplace with token auth, role-based permissions and filtered search. | Django REST, React, PostgreSQL |

## 🌱 Open source

- **CAMEL-AI**: merged (#2773)
- **OWL** (CAMEL-AI's multi-agent assistant): merged a [community use-case example (#434)](https://github.com/camel-ai/owl/pull/434).

## 🐍 Contributions

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Harsh1tSh/Harsh1tSh/output/github-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/Harsh1tSh/Harsh1tSh/output/github-snake.svg" alt="A snake eating my contribution graph" width="100%" />
  </picture>
</p>

## 🧰 Tech I work with

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,js,go,cpp&perline=12" alt="Languages: Python, TypeScript, JavaScript, Go, C++" /><br/>
  <img src="https://skillicons.dev/icons?i=fastapi,django,nodejs,nestjs,react,nextjs,vite,tailwind&perline=12" alt="Frameworks: FastAPI, Django, Node.js, NestJS, React, Next.js, Vite, Tailwind" /><br/>
  <img src="https://skillicons.dev/icons?i=pytorch,sklearn,postgres,sqlite,mongodb,supabase&perline=12" alt="ML and data: PyTorch, scikit-learn, PostgreSQL, SQLite, MongoDB, Supabase" /><br/>
  <img src="https://skillicons.dev/icons?i=docker,aws,cloudflare,githubactions,linux&perline=12" alt="Infrastructure: Docker, AWS, Cloudflare, GitHub Actions, Linux" />
</p>

<p align="center"><sub>Also: ONNX Runtime, Whisper, Web Audio API, WebSockets, OpenAPI, Playwright, pytest, Vitest, multi-agent systems and MCP.</sub></p>

<p align="center"><i>Open to interesting problems and good teams. Say hi on <a href="https://www.linkedin.com/in/harshit-sharma-6b883a193/">LinkedIn</a>.</i></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:FF6B9A,50:C084FC,100:34D399&height=120&section=footer" alt="" width="100%" />
