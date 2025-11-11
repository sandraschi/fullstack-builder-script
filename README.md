# SOTA Fullstack App Builder

This repository showcases the AI-generated PowerShell script that scaffolds a production-ready fullstack application. The script was produced during a single agentic coding session in Cursor to demonstrate what automated tooling can create end-to-end.

## Highlights
- Generates React + TypeScript + Chakra UI frontend
- Builds FastAPI backend with PostgreSQL, Redis, and Prometheus wiring
- Emits Docker Compose, monitoring stack, and helper scripts
- Includes MCP server CLI documentation and Windows-safe Unicode handling

## Usage
```powershell
# Run from the directory where you want the new project folder
.
\new-fullstack-app.ps1 -AppName "MyApp" [-OutputPath "C:\Projects"]
# -OutputPath is optional; when omitted the script writes to the current directory.
```

> **Note**: The generator assumes Windows with Docker Desktop available. A fresh `docker-compose up` smoke test is recommended after generation to validate the scaffold.

## Provenance
- Script location: `new-fullstack-app.ps1`
- Source: AI-assisted session using Cursor
- Reference docs: `mcp-central-docs/FULLSTACK_BUILDER.md`

