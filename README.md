# taskflow-assistant (archived)

**This repository has moved.** The TaskFlow work assistant (MCP server, Claude Code plugin and Claude Desktop chat skill) now lives in the TaskFlow repo, under [`assistant/`](https://github.com/nevridge/TaskFlow/tree/main/assistant), so an API change and its matching MCP change ship and are tested in one PR.

- Setup and install: [`assistant/README.md`](https://github.com/nevridge/TaskFlow/blob/main/assistant/README.md)
- Issues and changes: [nevridge/TaskFlow issues](https://github.com/nevridge/TaskFlow/issues)
- Why it moved: [#32](https://github.com/nevridge/taskflow-assistant/issues/32) and [nevridge/TaskFlow#397](https://github.com/nevridge/TaskFlow/issues/397)

Open issues were transferred to nevridge/TaskFlow on 2026-11-04, and the full history was carried over in nevridge/TaskFlow#425. This repository is read-only.

**If you installed the plugin from a clone of this repo**, re-point the marketplace at the TaskFlow clone:

```powershell
claude plugin marketplace remove taskflow-assistant
claude plugin marketplace add <path-to-TaskFlow>\assistant
claude plugin install taskflow-assistant@taskflow-assistant
```
