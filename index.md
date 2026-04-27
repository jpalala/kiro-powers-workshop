---
title: Home
layout: home
---

This repository provides a **minimalist, production-ready template** for building Jekyll-based documentation sites using he **Just the Docs** theme. 

At its core, this project leverages the `just-the-docs` Ruby gem—a premier theme specifically engineered for high-performance, searchable, and mobile-friendly documentation. 

By using a gem-based approach and a standard `Gemfile`, the site remains lightweight and easy to update. While it is pre-configured for seamless deployment via **GitHub Pages** (using GitHub Actions), the underlying Jekyll foundation means you can build, preview, and host it on any platform that supports static sites.

---

## Kiro.dev: The AI-Native Workflow

**Kiro.dev** is a next-generation development environment designed to move beyond the limitations of traditional code editors. While tools like Cursor focus on file-level AI chat, Kiro introduces **"Powers"**—a concept similar to Claude Skills—that allows you to install structured, reusable capabilities directly into your workflow.

Kiro is built on the philosophy that AI should understand your **system intent**, not just your syntax. It is significantly easier to use for AI-driven development because it prioritizes a "Design-First" approach, where your specifications drive the code generation, ensuring your architecture and implementation never drift apart.

### Kiro Powers
**Kiro Powers** is a design-first, AI-assisted development workflow built around reusable “powers” (skills) that operate on your codebase. Instead of manually editing files or issuing one-off prompts, you define structured capabilities that can interpret intent, modify code, and evolve your system.

### Philosophy
Kiro Powers is built on three principles:

1.  **Design First**: Start with specs—not code. Use Markdown specs, architecture diagrams (e.g., Mermaid), and clear system intent. Code is generated from design, not the other way around.
2.  **Powers over Prompts**: Ad-hoc prompts don’t scale. Powers are reusable, structured, and intent-driven. Instead of saying "refactor this file," you invoke `refactor-api-layer`.
3.  **Intent > Files**: Traditional tools operate at the file level. Kiro Powers operates at the system level (e.g., “add authentication” or “modularize the app”).

### What is a Power?
A Power is a structured capability that understands a goal, reads relevant context, and applies changes across the codebase. Think of it as a reusable, high-level AI instruction with scope.

#### Core Power Types
* **File Mutation**: Create, update, or delete files across the project.
* **Spec → Code**: Generate implementation directly from architectural design specs.
* **Intent Execution**: Apply high-level transformations across multiple layers.
* **Workflow Automation**: Automatically run scripts, tests, or linters after changes.
* **MCP (Optional)**: Integration with the Model Context Protocol for stateful, cross-project awareness.

### Workflows
* **Design-First (Recommended)**: Write a spec → Select a power → Execute via AI → Iterate.
* **MCP-Enhanced**: Connect to an MCP server to leverage extended memory and external tools for complex systems.

### Project Structure
```text
/specs/          # Design blueprints
/powers/         # Reusable AI instructions
/posts/          # Documentation and updates
```

### Defining a Power
Powers are typically written as structured Markdown:

> **# refactor-api-layer**
>
> **Goal:** Extract API logic into a service layer.
>
> **Steps:**
> 1. Identify route handlers.
> 2. Move business logic into `/services`.
> 3. Update imports.
> 4. Ensure tests pass.

### Why Kiro Powers?
Modern AI tools are powerful but unstructured. Kiro Powers introduces **consistency** and **reusability**. It turns "chatting with an AI" into a **composable development workflow**. It is best used when you want your design and code to stay perfectly aligned while reusing logic patterns across multiple projects.

