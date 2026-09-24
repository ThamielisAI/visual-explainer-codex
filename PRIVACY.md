# Privacy

Visual Explainer is a local Codex plugin. The skill reads files from the workspace when the user asks for a visual explanation and writes generated HTML files to the local output directory described in `skills/visual-explainer/SKILL.md`.

The bundled MCP server sends an image-generation prompt to Google's Gemini API only when the user explicitly invokes one of its image tools and provides `NANOBANANA_GEMINI_API_KEY` or `GEMINI_API_KEY`. The repository does not operate a separate hosted backend, collect analytics, or store user content remotely. Generated image files are written to the local temporary directory reported by the MCP tool.

Users should review Google's current Gemini API privacy terms for requests made with their own API key. This document describes the behavior of this repository and is not legal advice.
