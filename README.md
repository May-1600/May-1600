# Mayeul de Charentenay

I build practical AI applications and help people use them in their work. Based in Paris, I work as a Data Product Owner for AI at Orange alongside independent software projects and my ESSEC Global BBA.

At Orange, I have delivered AI training and introduced **300+ employees** to practical AI use with **Live Intelligence**, our internal AI tool. My technical work includes LLM evaluation, business applications, and workflows built with **Codex and Claude Code**.

## Selected work

### TBES business tools

Independent work with TBES, separate from my work on AstréIA:

- **Historical price matching:** built a workflow to find a relevant historical construction price schedule, assist with price filling, and export an Excel file for human review.
- **Reliability:** fixed excessive Excel parsing memory use in an isolated pilot. Measured cold-start peak fell from **8.24 GiB to approximately 316 MiB**; 58 tests passed and useful rows were preserved across 541 comparable files. This result applies to the pilot reader, not the original production reader.
- **CRM and access:** built business workflows and deployed a CRM pilot with permissions, persistent drafts, and isolated restore checks. Live email integration and business acceptance remain pending.

Client source code and business records are private. These descriptions present the engineering work without publishing client data.

### Public repositories

| Repository | What to look at |
| --- | --- |
| [Jarvis Vocal](https://github.com/May-1600/jarvis-vocal) | Python voice agent for macOS: speech recognition, intent routing, tool execution, persistent memory, and privacy boundaries. The public v0.1 baseline documents its test and evaluation setup. |
| [Edge AI Stack](https://github.com/May-1600/novo-box-stack) | Reusable Docker wiring and example workflows with n8n, Ollama, Qdrant, PostgreSQL, and Next.js. This is a public reference skeleton, distinct from private TBES applications; some examples use cloud services. |

## How I build

I use AI coding tools to turn business needs into small, verifiable changes. I work from the existing code and project context, review generated changes, test the affected workflow, and keep prepared, tested, deployed, and accepted states separate.

I am also building the internal CRM for **AstréIA**, a separate venture in development. The current work includes access control and end-to-end verification; it has not been deployed to production.

**Tools:** Python, TypeScript, React, Next.js, SQL, PostgreSQL, Docker, n8n, Ollama, Qdrant, MCP, Codex, Claude Code.

[LinkedIn](https://www.linkedin.com/in/mayeul-de-charentenay/) · [Email](mailto:mayeuldecharentenay@gmail.com)
