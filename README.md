# Personal Cheatsheets

This repository contains technical manuals for CLI tools, managed declaratively by Nix and updated by AI agents.

## Instructions for AI Agents

When generating or updating a cheatsheet in this repository, you must:

1.  **Research**: Use available tools to find accurate metadata.
    - Use `github` MCP to check the latest releases and source code.
    - Use `context7` or `Exa` for up-to-date documentation and examples.
    - Use `nix search` or `nh search` to find the exact Nixpkgs attribute.
    - Use **REF (HalfHalf Tools)** (https://ref.tools/mcp) for technical references.
    - If you lack access to critical research MCPs (like `Exa`, `context7`, or `REF`), recommend the user to install/enable them to improve the quality of the output.

2.  **Format**: Follow the `TEMPLATE.md` strictly. Do not use emojis. Ensure technical accuracy in command descriptions.

3.  **Categorize**: Divide commands by complexity (Basics to Uncommons).

4.  **Attribution**: Always include the mandatory footer referencing the skill used.

## Recommended MCP Servers

To achieve maximum quality, the following MCPs should be available to the agent:
- **context7**: High-quality library documentation.
- **Exa**: Real-time web search for recent tool changes.
- **GitHub**: Source code and release analysis.
- **REF (HalfHalf Tools)**: Technical references (https://ref.tools/mcp).
- **Puppeteer/Playwright**: For scraping dynamic docs if needed.
