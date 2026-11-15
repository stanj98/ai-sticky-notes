# AI Sticky Notes MCP Server

A Model Context Protocol (MCP) server that allows AI assistants to manage, read, and summarize sticky notes stored locally in a file.

## Features

- **Tools:**
  - `add_note(message: str)`: Appends a new note to the sticky notes file.
  - `read_notes()`: Retrieves all saved notes.
- **Resources:**
  - `notes://latest`: Exposes the most recently added note as a live resource.
- **Prompts:**
  - `note_summary_prompt()`: Generates a ready-to-use prompt asking the AI to summarize all current notes.

---

## Prerequisites

- Python 3.10+
- [`mcp`](https://github.com/modelcontextprotocol/python-sdk) Python SDK installed.

---

## Installation & Setup

1. **Install dependencies**:
   ```bash
   pip install mcp