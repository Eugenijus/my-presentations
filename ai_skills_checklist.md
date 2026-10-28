# AI & Agentic SDLC Skills Checklist

> **Purpose:** Team skill assessment for genAI and agentic SDLC adoption.
> **Columns when imported to Excel:** Category | Skill ID | Skill Name | Description | Level (1–4) | Notes

---

## Category 1: AI Foundations

| Skill ID | Skill Name | Description |
|----------|-----------|-------------|
| F-01 | AI Basics | Understands what AI is and how AI chat tools (e.g. ChatGPT) work at a conceptual level. |
| F-02 | Model Landscape Awareness | Knows major model families: Anthropic (Claude), OpenAI (GPT), Google (Gemini), and their key differences. |
| F-03 | Model Tier Understanding | Understands model tiers within a family (e.g. Haiku 4.5 = lightweight/fast, Sonnet 5 = balanced, Opus 5 = most capable) and when to choose each. |
| F-04 | Prompt Engineering | Knows how to write effective prompts: clear instructions, role framing, constraints, and output format. |
| F-05 | Context Engineering | Knows what context to add to a prompt (files, screenshots, code selections, URLs) to improve accuracy and relevance. |
| F-06 | AI-900 / AI Fundamentals Certification | Has completed Microsoft AI Fundamentals training and passed the AI-900 exam. See: [MS AI-900 Learning Path](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-fundamentals/) |
| F-07 | Accenture AI Training | Has completed internal Accenture AI training programme. |

---

## Category 2: AI-Assisted Development (IDE & CLI)

| Skill ID | Skill Name | Description |
|----------|-----------|-------------|
| D-01 | GitHub Copilot in IDE | Uses GitHub Copilot for code completion and chat inside VS Code or another IDE. |
| D-02 | Claude Code in IDE | Uses Claude Code extension inside VS Code or another IDE for agentic coding tasks. |
| D-03 | GPT / ChatGPT in IDE | Uses ChatGPT or OpenAI-based tools inside an IDE for code assistance. |
| D-04 | Claude CLI | Uses the Claude command-line interface (`claude`) for agentic tasks from the terminal. |
| D-05 | GitHub Copilot CLI | Uses GitHub Copilot in the terminal (`gh copilot`) for shell command suggestions and explanations. |
| D-06 | Plan Mode | Uses Plan (or "think first") mode to break down and stage complex implementations before executing. |

---

## Category 3: Custom Prompts & Skills (Reusable Instructions)

| Skill ID | Skill Name | Description |
|----------|-----------|-------------|
| P-01 | Custom Prompts / Commands | Creates reusable prompt templates (e.g. `.github/prompts/*.prompt.md` in VS Code Copilot; `/commands` in Claude Code) that are manually invoked by name. |
| P-02 | Agent Skills — Basic | Creates basic agent skills (e.g. `.github/skills/<name>/SKILL.md`) with a name and description so the agent auto-selects the skill based on context. |
| P-03 | Agent Skills — Advanced (Progressive Disclosure) | Structures skills with supporting folders (`scripts/`, `references/`, `assets/`) so the agent loads only what it needs, keeping the core SKILL.md lean. |

---

## Category 4: AI Services & APIs

| Skill ID | Skill Name | Description |
|----------|-----------|-------------|
| S-01 | AI Services in Application Code | Calls AI provider APIs (Anthropic, OpenAI, Azure AI, etc.) directly from project code rather than relying only on chat or CLI tools. |
| S-02 | OCR with AI (Gemini / Azure AI) | Uses Gemini Vision or Azure AI Vision / Document Intelligence to extract text and data from images or scanned documents. |
| S-03 | Figma MCP Integration | Uses the Figma MCP server so an AI agent can retrieve design data, reducing manual handoff effort and improving UI implementation accuracy. |

---

## Category 5: Agentic Workflows & Orchestration

| Skill ID | Skill Name | Description |
|----------|-----------|-------------|
| A-01 | Sub-agents & Orchestration Concepts | Understands how multi-agent systems work: orchestrator agents delegating tasks to specialist sub-agents. |
| A-02 | MCP (Model Context Protocol) | Understands what MCP is and can configure or consume MCP servers to give agents structured access to external tools and data. |
| A-03 | Spec-Driven Development | Uses specification-first development workflows (e.g. GitHub Speckit) where a written spec drives agentic implementation. |
| A-04 | Advanced Agentic Tools | Has hands-on experience with advanced agentic platforms (e.g. Automaker, LangGraph, CrewAI, or similar). |

---

## Category 6: AI-Powered Frontend & Rapid Prototyping

| Skill ID | Skill Name | Description |
|----------|-----------|-------------|
| UI-01 | v0 (Vercel) | Uses v0.dev to generate React / shadcn / Radix UI frontend code from natural language or design descriptions. |
| UI-02 | AI-Assisted UI from Design | Connects AI tooling to a design source (Figma, screenshots) to generate or scaffold UI code with higher fidelity. |

---

## Suggested Proficiency Scale (add as a column in Excel)

| Level | Label | Description |
|-------|-------|-------------|
| 0 | None | No awareness or experience. |
| 1 | Aware | Has heard of / read about it; not yet used it. |
| 2 | Beginner | Has tried it; can use it with guidance or documentation. |
| 3 | Practitioner | Uses it independently in real projects; comfortable with most scenarios. |
| 4 | Expert / Champion | Deep experience; can teach others and design workflows using this skill. |

---

## Notes

- **Prompt engineering and context engineering** (F-04, F-05) are expected to become the most critical skills as agentic SDLC matures — prioritise these in training.
- Skills marked with an external link (F-06) should have the certification URL preserved in the Excel sheet for reference.
- This checklist can be extended per team member by adding a `Person` column and repeating rows, or by creating one sheet per person.
