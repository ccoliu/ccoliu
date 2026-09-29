<h1 align="center">Chia-Cheng Liu</h1>
<h3 align="center">Email: frgnd5433@gmail.com</h3>
<div align="center">

[![LeetCode Stats](https://leetcard.jacoblin.cool/ccoliu?hide=ranking&width=500&height=200&theme=dark&font=Anek%20Malayalam)](https://leetcode.com/u/ccoliu/)

</div>

<h2 align="left">About Me</h2>
<p align="left">
  Software engineer with a CS degree from Taiwan Tech. I build backend and systems software — distributed task scheduling, LLM agent orchestration, embedded/BMC simulation — and do deep-learning research on cross-domain few-shot learning.
</p>

<h2 align="left">Education</h2>
<div display="flex" justify-content="space-between">
<h3 font-weight="bold">National Taiwan University of Science and Technology (Taiwan Tech)</h3>
<h4>Bachelor of Science, Computer Science and Information Engineering</h4>
<p>Sep. 2019 - Jun. 2025</p>
<p>Data Structures, Object-Oriented Programming, Compiler Design, Operating Systems, Data Science, Applied AI</p>
</div>

<h2 align="left">Technical Skills</h2>

<h4 align="left">Programming Languages:</h4>
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" title="C" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" title="C++" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg" alt="C#" title="C#" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" title="Java" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" title="Python" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" width="40" height="40" />
</p>

<h4 align="left">Backend &amp; Web:</h4>
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="FastAPI" title="FastAPI" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" title="React" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" title="Tailwind CSS" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" alt="HTML5" title="HTML5" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg" alt="CSS3" title="CSS3" width="40" height="40" />
</p>

<h4 align="left">Data &amp; AI:</h4>
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/redis/redis-original.svg" alt="Redis" title="Redis" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" alt="PyTorch" title="PyTorch" width="40" height="40" />
</p>

<h4 align="left">Tools &amp; Platforms:</h4>
<p align="left">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" alt="Git" title="Git" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/githubactions/githubactions-original.svg" alt="GitHub Actions" title="GitHub Actions" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" title="Docker" width="40" height="40" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" title="Linux" width="40" height="40" />
</p>

<h2 align="left">Projects</h2>

<h3 align="left">
  <a href="https://github.com/ccoliu/Codoctopus" target="_blank">Codoctopus</a> 🐙
</h3>
<p align="left">
  A provider-neutral agent orchestration framework. Give it a goal and it decomposes the goal into a verified task DAG, then runs each step with agents that can actually act — read and write files, run shell commands and tests, and make HTTP requests. Works with Anthropic, OpenAI, Gemini, Ollama, or any OpenAI-compatible gateway, and ships with a CLI, a Python SDK, and a React web GUI.
</p>
<p align="left"><i>Python · asyncio · Pydantic · FastAPI · React · TypeScript</i></p>
<p align="center">
  <img src="CodoctopusDemo.gif" alt="Codoctopus Demo GIF" width="800" height="400"/>
</p>

<h3 align="left">
  <a href="https://github.com/ccoliu/coworkify" target="_blank">Coworkify</a>
</h3>
<p align="left">
  A distributed task scheduling and execution platform inspired by Apache Airflow and Celery. Supports the full task lifecycle, priority queues, delayed and cron-based scheduling, retries with exponential backoff, DAG workflows with a drag-and-drop visual builder, Redis sliding-window rate limiting, and real-time status push over WebSocket.
</p>
<p align="left"><i>FastAPI · Celery · PostgreSQL · Redis · React · Docker Compose</i></p>
<p align="center">
  <img src="coworkifypreview.png" alt="Coworkify workflow run with conditional branches" width="800"/>
</p>

<h3 align="left">
  <a href="https://github.com/ccoliu/mini-bmc" target="_blank">mini-bmc</a>
</h3>
<p align="left">
  A self-contained simulator of a server BMC (Baseboard Management Controller): a <code>poll()</code>-based C daemon that simulates sensors and fault injection, with a DMTF Redfish REST API on top. Every response is validated against the official Redfish schemas in CI, and the C code is tested with Unity under ASan/UBSan. No hardware required — just <code>docker compose up</code>.
</p>
<p align="left"><i>C11 · Python · FastAPI · Redfish · Docker · GitHub Actions</i></p>

<h3 align="left">
  <a href="https://github.com/ccoliu/FeatureSR" target="_blank">FeatureSR</a>
</h3>
<p align="left">
  Research on feature-level super-resolution for vision-language cross-domain few-shot learning. Upsamples ViT patch tokens from 14×14 to 28×28 with a cross-resolution consistency loss, built on cycle-consistent vision-language alignment (CC-CDFSL). Improves 5-way 5-shot accuracy on all four benchmarks (EuroSAT, CropDiseases, ISIC 2018, ChestX), +1.15% on average.
</p>
<p align="left"><i>Python · PyTorch · CLIP · LoRA</i></p>

<h2 align="left">Earlier Projects</h2>

<h4 align="left">
  <a href="https://github.com/ccoliu/Minesweeper" target="_blank">Minesweeper</a>
</h4>
<p align="left">
  The classic game: uncover every block that doesn't hide a mine.
</p>
<p align="center">
  <img src="minesweeperpreview.png" alt="Minesweeper preview"/>
</p>

<h4 align="left">
  <a href="https://github.com/ccoliu/Chess" target="_blank">Chess</a>
</h4>
<p align="left">
  A two-player chess game, played on the board until one side's king is captured.
</p>
<p align="center">
  <img src="chesspreview.png" alt="Chess preview"/>
</p>
