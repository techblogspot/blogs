## TL;DR

- Plan before Act. Use a reasoning-capable model to plan, then switch to an accurate coding model to execute.
- Write specific prompts: objective, inputs/outputs, constraints, acceptance criteria, and tool boundaries.
- Define Cline Rules to enforce your workflow (e.g., “search for existing helpers before writing new code”, “update docs after changes”).
- Provide context via MCP servers (e.g., Context7 or your own) to expose APIs, microservices, and domain knowledge.
- Limitations: Context window size. Don’t expect full-repo migrations in one shot; chunk the work. Migration strategies are covered in a separate post—stay tuned.