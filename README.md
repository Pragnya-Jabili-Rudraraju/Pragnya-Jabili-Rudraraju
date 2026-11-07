# Hi, I'm Pragnya 👋

BCA student in India building backend-focused, full-stack software. I like systems where correctness, security and clear boundaries matter, and I'm currently looking for **Software Engineering internships** (backend / full-stack).

## What I'm building

### [Insight](https://github.com/<username>/insight): AI-assisted pull request review

A read-only GitHub PR reviewer that combines **deterministic AST analysis** with **LLM review**, then validates every AI finding against the real diff before showing it. Insight never writes to GitHub.

- Parses changed JS/JSX/TS/TSX with `@babel/parser` and runs structural rules (dynamic code execution, hardcoded secrets, unsafe TLS, removed exports, changed function signatures)
- Sends LLMs a redacted, bounded context and accepts only schema-validated, evidence-backed findings
- Express REST API with GitHub OAuth, CSRF protection, encrypted token storage and signed webhook verification
- 59 backend tests (Jest + Supertest) and a controlled evaluation harness that reports precision, recall and false-positive rate

`Node.js` · `Express 5` · `MongoDB / Mongoose` · `Zod` · `Babel parser` · `React 19 + Vite` · `Jest`

## Tech stack

| | |
|---|---|
| **Languages** | JavaScript |
| **Backend** | Node.js, Express, REST API design, session auth, GitHub OAuth |
| **Frontend** | React, Vite, HTML, CSS |
| **Database** | MongoDB, Mongoose |
| **AI / LLM** | Structured JSON outputs, provider adapters (OpenAI, Anthropic, Gemini, Groq), prompt-injection-aware prompting |
| **Code analysis** | Abstract syntax trees, static analysis rules |
| **Testing & tools** | Jest, Supertest, ESLint, Git, GitHub |

## Currently working on

- Data structures and algorithms (daily practice, solutions will be published in a public repo)
- Connecting Insight's React frontend to its backend API
- Deepening the MERN stack and system design fundamentals

## Connect

- GitHub: [@Pragnya-Jabili-Rudraraju](https://github.com/Pragnya-Jabili-Rudraraju)
