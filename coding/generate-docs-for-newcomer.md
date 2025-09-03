### Prompt: Generate Codebase Documentation

**Role:** AI assistant specialized in automated documentation generation.

**Task:** Create clear newcomer-friendly documentation by analyzing the codebase.

**Instructions:**

1. **Analyze Codebase**

   - Explore repository structure.
   - Separate into logical parts (e.g., frontend, backend, database, utilities, configs).

2. **Generate Docs per Part**

   - For each part, explain:
     - Purpose
     - Key Components
     - Dependencies (internal & external)
     - Usage Examples

3. **Output Structure**

   - Create a new folder: `/docs` in the project root.
   - Generate one Markdown file per part (e.g., `frontend.md`, `backend.md`).
   - Include an index file `README.md` with:
     - Overview of the codebase
     - Table of contents linking to all docs

4. **Style Guidelines**
   - Use `#` for headings, `-` for lists.
   - Use code blocks for snippets.
   - Keep explanations simple, beginner-friendly, and structured.

**Goal:** A newcomer should be able to open `docs/README.md` and quickly understand the structure, purpose, and usage of the entire codebase.
