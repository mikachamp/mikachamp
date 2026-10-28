# Hi, I'm Mika

I make things in two worlds: metal and plastic on the shop floor, JavaScript on the screen. CNC routing, 3D printing and CAD on one side. AI agents, web and 3D on the other. Most of what I enjoy sits where the two meet, like a web page that explodes a part the way a machinist would, or an agent that knows a feed rate from a frame rate.

## What I'm building right now

- **Mika OS.** A personal AI operations system: one orchestrator, role agents that wake up per task, and an Obsidian vault that is both the task board and the memory. Agents stop at "review". I am the only one who can say "done".
- **web-lab.** Three.js and scroll-driven pages. Gyro Winder builds to a single HTML file that opens from disk and runs offline, with reduced motion and fps checks.
- **concept-sites.** Concept sites for local businesses, work in progress.
- **A double-element GT wing** for my own car: designed in Fusion 360 with an AI assistant connected over MCP, planned as printed ASA shells on an aluminium skeleton, for a Bambu Lab H2D.
- **A course project in machine learning.** A dog-breed classifier: 120 breeds, 10,222 images, best validation accuracy 78.1%. Fine-tuning the base model dropped it to about 45%, and I kept that in the write-up.

## Repo map

| Repo | In one line |
|---|---|
| [mika-os](https://github.com/mikachamp/mika-os) | Orchestrator + role sub-agents + Electron app. Task queue with lock files and leases, a review pipeline, human approval gates. |
| [mika-os-knowledge-base](https://github.com/mikachamp/mika-os-knowledge-base) | The Obsidian vault as a second brain and agent control plane, as a reusable template. |
| [web-lab](https://github.com/mikachamp/web-lab) | My web and 3D demos, with the techniques, tests and mistakes written down. |
| [concept-sites](https://github.com/mikachamp/concept-sites) | Concept sites for local businesses. Work in progress. |
| [dog-breed-identification](https://github.com/mikachamp/dog-breed-identification) | Course project: image classification across 120 dog breeds. |

Start with **mika-os** if you want the engineering, **web-lab** if you want something to look at.

## Toolbox

| Area | What I use |
|---|---|
| Web and 3D | JavaScript, TypeScript, Three.js, Vite, Web Audio |
| Agents and apps | Node.js, Express, PM2, Electron, Obsidian, Claude and Gemini, local models via LM Studio / llama.cpp |
| Testing | Headless Chrome with `puppeteer-core`, `node --test` |
| ML | Python, TensorFlow / Keras, MobileNetV2 |
| Making | Fusion 360, CNC routing, 3D printing (ASA, PLA) |

## How I work

- Facts come from files, not vibes. Anything an agent writes must cite its source.
- Test it for real: 1440 px and 390 px, no console errors, no sideways scroll, reduced motion, real GPU.
- Small, reversible steps. Write the decision down before changing the code.
- I write down what broke. The projects here have a "what went wrong" section, because that is where the learning is.

## Fun fact

My task board is a folder of text files, and my "agents" are not allowed to publish, push, send, delete or spend anything. Three agents can work at once; a fourth waits its turn in the queue.
