### Saurav Jha

I build AI agents and RAG pipelines, and the harness that keeps them honest.
Tool calling, memory, guardrails, evals, and a cost line on every request.

Software Engineer at **Bug0**, where the agents I build write, run and repair
end-to-end test suites on their own. Before that, six production apps and the
real-time systems underneath them.

[![srvjha.in](https://img.shields.io/badge/srvjha.in-9A5405?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyBmaWxsPSJ3aGl0ZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiBpZD0ibWRpLXdlYiIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBkPSJNMTYuMzYsMTRDMTYuNDQsMTMuMzQgMTYuNSwxMi42OCAxNi41LDEyQzE2LjUsMTEuMzIgMTYuNDQsMTAuNjYgMTYuMzYsMTBIMTkuNzRDMTkuOSwxMC42NCAyMCwxMS4zMSAyMCwxMkMyMCwxMi42OSAxOS45LDEzLjM2IDE5Ljc0LDE0TTE0LjU5LDE5LjU2QzE1LjE5LDE4LjQ1IDE1LjY1LDE3LjI1IDE1Ljk3LDE2SDE4LjkyQzE3Ljk2LDE3LjY1IDE2LjQzLDE4LjkzIDE0LjU5LDE5LjU2TTE0LjM0LDE0SDkuNjZDOS41NiwxMy4zNCA5LjUsMTIuNjggOS41LDEyQzkuNSwxMS4zMiA5LjU2LDEwLjY1IDkuNjYsMTBIMTQuMzRDMTQuNDMsMTAuNjUgMTQuNSwxMS4zMiAxNC41LDEyQzE0LjUsMTIuNjggMTQuNDMsMTMuMzQgMTQuMzQsMTRNMTIsMTkuOTZDMTEuMTcsMTguNzYgMTAuNSwxNy40MyAxMC4wOSwxNkgxMy45MUMxMy41LDE3LjQzIDEyLjgzLDE4Ljc2IDEyLDE5Ljk2TTgsOEg1LjA4QzYuMDMsNi4zNCA3LjU3LDUuMDYgOS40LDQuNDRDOC44LDUuNTUgOC4zNSw2Ljc1IDgsOE01LjA4LDE2SDhDOC4zNSwxNy4yNSA4LjgsMTguNDUgOS40LDE5LjU2QzcuNTcsMTguOTMgNi4wMywxNy42NSA1LjA4LDE2TTQuMjYsMTRDNC4xLDEzLjM2IDQsMTIuNjkgNCwxMkM0LDExLjMxIDQuMSwxMC42NCA0LjI2LDEwSDcuNjRDNy41NiwxMC42NiA3LjUsMTEuMzIgNy41LDEyQzcuNSwxMi42OCA3LjU2LDEzLjM0IDcuNjQsMTRNMTIsNC4wM0MxMi44Myw1LjIzIDEzLjUsNi41NyAxMy45MSw4SDEwLjA5QzEwLjUsNi41NyAxMS4xNyw1LjIzIDEyLDQuMDNNMTguOTIsOEgxNS45N0MxNS42NSw2Ljc1IDE1LjE5LDUuNTUgMTQuNTksNC40NEMxNi40Myw1LjA3IDE3Ljk2LDYuMzQgMTguOTIsOE0xMiwyQzYuNDcsMiAyLDYuNSAyLDEyQTEwLDEwIDAgMCwwIDEyLDIyQTEwLDEwIDAgMCwwIDIyLDEyQTEwLDEwIDAgMCwwIDEyLDJaIiAvPjwvc3ZnPg==&logoColor=white)](https://srvjha.in) [![blogs.srvjha.in](https://img.shields.io/badge/blogs.srvjha.in-1f2328?style=flat-square&logo=rss&logoColor=F2A33C)](https://blogs.srvjha.in) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyBmaWxsPSJ3aGl0ZSIgcm9sZT0iaW1nIiB2aWV3Qm94PSIwIDAgMjQgMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0iTTIwLjQ0NyAyMC40NTJoLTMuNTU0di01LjU2OWMwLTEuMzI4LS4wMjctMy4wMzctMS44NTItMy4wMzctMS44NTMgMC0yLjEzNiAxLjQ0NS0yLjEzNiAyLjkzOXY1LjY2N0g5LjM1MVY5aDMuNDE0djEuNTYxaC4wNDZjLjQ3Ny0uOSAxLjYzNy0xLjg1IDMuMzctMS44NSAzLjYwMSAwIDQuMjY3IDIuMzcgNC4yNjcgNS40NTV2Ni4yODZ6TTUuMzM3IDcuNDMzYy0xLjE0NCAwLTIuMDYzLS45MjYtMi4wNjMtMi4wNjUgMC0xLjEzOC45Mi0yLjA2MyAyLjA2My0yLjA2MyAxLjE0IDAgMi4wNjQuOTI1IDIuMDY0IDIuMDYzIDAgMS4xMzktLjkyNSAyLjA2NS0yLjA2NCAyLjA2NXptMS43ODIgMTMuMDE5SDMuNTU1VjloMy41NjR2MTEuNDUyek0yMi4yMjUgMEgxLjc3MUMuNzkyIDAgMCAuNzc0IDAgMS43Mjl2MjAuNTQyQzAgMjMuMjI3Ljc5MiAyNCAxLjc3MSAyNGgyMC40NTFDMjMuMiAyNCAyNCAyMy4yMjcgMjQgMjIuMjcxVjEuNzI5QzI0IC43NzQgMjMuMiAwIDIyLjIyMiAwaC4wMDN6Ii8+PC9zdmc+&logoColor=white)](https://linkedin.com/in/srvjha02) [![@J_srv001](https://img.shields.io/badge/%40J__srv001-1f2328?style=flat-square&logo=x&logoColor=white)](https://x.com/J_srv001) [![Email](https://img.shields.io/badge/Email-1f2328?style=flat-square&logo=gmail&logoColor=EA4335)](mailto:jhasaurav0209001@gmail.com)

---

### Now

- Building AI agents at Bug0 that generate, execute and repair Playwright suites through LLM tool calling, with self-healing tests that regenerate when DOM or selectors drift.
- Writing up whatever I take apart, at [blogs.srvjha.in](https://blogs.srvjha.in). 27 articles so far.
- Going deeper on retrieval evaluation. Measuring a pipeline honestly is harder than building one.

---

### Selected work

| | What it is | |
|---|---|---|
| **[pragatiLM](https://github.com/srvjha/pragatiLM)** | A research notebook that answers only from your sources, with a locator on every claim. Five query variants per turn, reciprocal rank fusion at k&nbsp;=&nbsp;60, and CRAG-style grading that retries below 6 and refuses below 3. | [live](https://pragati.srvjha.in) |
| **[Yugati](https://github.com/srvjha/yugati)** | A Gmail and Calendar agent on the OpenAI Agents SDK. Prompt-injection classifier and PII filter running alongside generation, per-request token and cost logging, 51 tests in CI, paid in INR. | [live](https://yugati.in) |
| **[NoteCast](https://github.com/srvjha/Notionary-LLM)** | PDFs, articles and YouTube into one Qdrant index, with every answer anchored to the chunk it came from. | [live](https://notecast.srvjha.in) |
| **[CodeWarriors](https://github.com/srvjha/codewarriors)** | DSA practice platform. Untrusted submissions run on Judge0 across Cloudflare Workers and GCP, never on the app server. | [live](https://codewarriors.srvjha.in) |
| **[FormCraft](https://github.com/srvjha/form-builder)** | Form builder with 14 field types, a 50-step undo history and response analytics, typed end to end over tRPC. | [live](https://formcraft.srvjha.in) |

---

### Stack

| | |
|---|---|
| **Retrieval** | RAG, HyDE, query rewriting, reciprocal rank fusion, reranking, semantic chunking, CRAG self-correction, hit-rate and MRR evals |
| **Guardrails** | Prompt-injection classification, PII filtering, structured outputs, per-request token and cost accounting |
| **Agents** | ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=data:image/svg%2Bxml;base64,PHN2ZyBmaWxsPSJ3aGl0ZSIgcm9sZT0iaW1nIiB2aWV3Qm94PSIwIDAgMjQgMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0iTTIyLjI4MTkgOS44MjExYTUuOTg0NyA1Ljk4NDcgMCAwIDAtLjUxNTctNC45MTA4IDYuMDQ2MiA2LjA0NjIgMCAwIDAtNi41MDk4LTIuOUE2LjA2NTEgNi4wNjUxIDAgMCAwIDQuOTgwNyA0LjE4MThhNS45ODQ3IDUuOTg0NyAwIDAgMC0zLjk5NzcgMi45IDYuMDQ2MiA2LjA0NjIgMCAwIDAgLjc0MjcgNy4wOTY2IDUuOTggNS45OCAwIDAgMCAuNTExIDQuOTEwNyA2LjA1MSA2LjA1MSAwIDAgMCA2LjUxNDYgMi45MDAxQTUuOTg0NyA1Ljk4NDcgMCAwIDAgMTMuMjU5OSAyNGE2LjA1NTcgNi4wNTU3IDAgMCAwIDUuNzcxOC00LjIwNTggNS45ODk0IDUuOTg5NCAwIDAgMCAzLjk5NzctMi45MDAxIDYuMDU1NyA2LjA1NTcgMCAwIDAtLjc0NzUtNy4wNzI5em0tOS4wMjIgMTIuNjA4MWE0LjQ3NTUgNC40NzU1IDAgMCAxLTIuODc2NC0xLjA0MDhsLjE0MTktLjA4MDQgNC43NzgzLTIuNzU4MmEuNzk0OC43OTQ4IDAgMCAwIC4zOTI3LS42ODEzdi02LjczNjlsMi4wMiAxLjE2ODZhLjA3MS4wNzEgMCAwIDEgLjAzOC4wNTJ2NS41ODI2YTQuNTA0IDQuNTA0IDAgMCAxLTQuNDk0NSA0LjQ5NDR6bS05LjY2MDctNC4xMjU0YTQuNDcwOCA0LjQ3MDggMCAwIDEtLjUzNDYtMy4wMTM3bC4xNDIuMDg1MiA0Ljc4MyAyLjc1ODJhLjc3MTIuNzcxMiAwIDAgMCAuNzgwNiAwbDUuODQyOC0zLjM2ODV2Mi4zMzI0YS4wODA0LjA4MDQgMCAwIDEtLjAzMzIuMDYxNUw5Ljc0IDE5Ljk1MDJhNC40OTkyIDQuNDk5MiAwIDAgMS02LjE0MDgtMS42NDY0ek0yLjM0MDggNy44OTU2YTQuNDg1IDQuNDg1IDAgMCAxIDIuMzY1NS0xLjk3MjhWMTEuNmEuNzY2NC43NjY0IDAgMCAwIC4zODc5LjY3NjVsNS44MTQ0IDMuMzU0My0yLjAyMDEgMS4xNjg1YS4wNzU3LjA3NTcgMCAwIDEtLjA3MSAwbC00LjgzMDMtMi43ODY1QTQuNTA0IDQuNTA0IDAgMCAxIDIuMzQwOCA3Ljg3MnptMTYuNTk2MyAzLjg1NThMMTMuMTAzOCA4LjM2NCAxNS4xMTkyIDcuMmEuMDc1Ny4wNzU3IDAgMCAxIC4wNzEgMGw0LjgzMDMgMi43OTEzYTQuNDk0NCA0LjQ5NDQgMCAwIDEtLjY3NjUgOC4xMDQydi01LjY3NzJhLjc5Ljc5IDAgMCAwLS40MDctLjY2N3ptMi4wMTA3LTMuMDIzMWwtLjE0Mi0uMDg1Mi00Ljc3MzUtMi43ODE4YS43NzU5Ljc3NTkgMCAwIDAtLjc4NTQgMEw5LjQwOSA5LjIyOTdWNi44OTc0YS4wNjYyLjA2NjIgMCAwIDEgLjAyODQtLjA2MTVsNC44MzAzLTIuNzg2NmE0LjQ5OTIgNC40OTkyIDAgMCAxIDYuNjgwMiA0LjY2ek04LjMwNjUgMTIuODYzbC0yLjAyLTEuMTYzOGEuMDgwNC4wODA0IDAgMCAxLS4wMzgtLjA1NjdWNi4wNzQyYTQuNDk5MiA0LjQ5OTIgMCAwIDEgNy4zNzU3LTMuNDUzN2wtLjE0Mi4wODA1TDguNzA0IDUuNDU5YS43OTQ4Ljc5NDggMCAwIDAtLjM5MjcuNjgxM3ptMS4wOTc2LTIuMzY1NGwyLjYwMi0xLjQ5OTggMi42MDY5IDEuNDk5OHYyLjk5OTRsLTIuNTk3NCAxLjQ5OTctMi42MDY3LTEuNDk5N1oiLz48L3N2Zz4=&logoColor=white) ![Anthropic](https://img.shields.io/badge/Anthropic-1f2328?style=flat-square&logo=anthropic&logoColor=white) ![MCP](https://img.shields.io/badge/MCP-1f2328?style=flat-square&logo=modelcontextprotocol&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Drizzle](https://img.shields.io/badge/Drizzle-1f2328?style=flat-square&logo=drizzle&logoColor=C5F74F) |
| **Backend** | ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Express](https://img.shields.io/badge/Express-1f2328?style=flat-square&logo=express&logoColor=white) ![Fastify](https://img.shields.io/badge/Fastify-1f2328?style=flat-square&logo=fastify&logoColor=white) ![tRPC](https://img.shields.io/badge/tRPC-2596BE?style=flat-square&logo=trpc&logoColor=white) |
| **Interface** | ![Next.js](https://img.shields.io/badge/Next.js-1f2328?style=flat-square&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-1f2328?style=flat-square&logo=react&logoColor=61DAFB) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white) ![TanStack Query](https://img.shields.io/badge/TanStack%20Query-FF4154?style=flat-square&logo=reactquery&logoColor=white) ![Framer Motion](https://img.shields.io/badge/Framer%20Motion-0055FF?style=flat-square&logo=framer&logoColor=white) ![Three.js](https://img.shields.io/badge/Three.js-1f2328?style=flat-square&logo=threedotjs&logoColor=white) |
| **Delivery** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-1f2328?style=flat-square&logo=vercel&logoColor=white) |

---

### Writing

Mostly about the layer underneath: how a model turns a message into an answer,
how systems behave once load stops being theoretical, and what the protocols
everyone uses are really doing.

- [What Actually Happens When You Send a Message to ChatGPT?](https://blogs.srvjha.in/posts/what-actually-happens-when-you-send-a-message-to-chatgpt)
- [How OIDC and OAuth Actually Work Under the Hood](https://blogs.srvjha.in/posts/how-oidc-and-oauth-actually-works-under-the-hood)
- [Your Data Is Not Actually Stored in a Database](https://blogs.srvjha.in/posts/your-data-is-not-actually-stored-in-a-database)
- [The Thundering Herd Problem in Distributed Systems](https://blogs.srvjha.in/posts/thundering-herd-problem)

[All 27 articles →](https://blogs.srvjha.in)

---

Open to Applied AI Engineer roles.
Reach me at [jhasaurav0209001@gmail.com](mailto:jhasaurav0209001@gmail.com).
