# 👋 Hey, I'm Cory

**AI Security Researcher** focused on agentic AI hardening, MCP security, and embedded device research.

## 🔬 What I Work On

- **MCP Security** — Building tools to audit Model Context Protocol server configurations for security issues
- **Agentic AI Hardening** — OWASP Agentic Applications 2026, prompt injection, supply chain attacks
- **Embedded Device Research** — Kindle jailbreak research, Chromium sandbox escape

## 🛠️ Projects

| Project | Description |
|---------|-------------|
| [mcp-scanner](https://github.com/memyselfandaiandai/mcp-scanner) | Python CLI tool that audits MCP server configurations for security issues — auth gaps, hardcoded secrets, prompt injection, SSRF, command injection, tool shadowing. 8 check categories, 21+ rules, SIEM export (CEF/LEEF/Syslog/NDJSON/CSV/W3C), SARIF output |
| [mcp-scanner-gui](https://github.com/memyselfandaiandai/mcp-scanner-gui) | Desktop GUI for mcp-scanner built with Tauri + Python. Drag-and-drop config scanning, severity filtering, multi-format export |

## 📊 Security Coverage

- **8 check categories**: Authentication, Secrets, Transport, Prompt Injection, Permissions, SSRF, Command Injection, Tool Shadowing
- **OWASP Agentic 2026 mapping**: ASI01–ASI07
- **SIEM export**: CEF, LEEF, Syslog RFC 5424, NDJSON, CSV, W3C
- **SARIF 2.1.0**: GitHub Advanced Security compatible
- **v2 checks**: Supply chain (unpinned packages, typosquatting, npx -y), toxic flow detection, resource poisoning, prompt template poisoning, system prompt leakage, output sanitization, rug pull detection

## 📫 Connect

- GitHub: [@memyselfandaiandai](https://github.com/memyselfandaiandai)

---

*Built with 🔒 by OWL*
