# Cursor WPVIP Rule Generator

A modular, workspace-aware system for generating **Cursor Rules** tailored to enterprise-grade WordPress development.  
This repository provides two Cursor command definitions that analyze the current workspace and output a complete set of `.mdc` rule files that follow:

- WordPress VIP coding standards  
- 10up + Fueled engineering conventions  
- Modern block theme + Gutenberg patterns  
- React/JSX block development guidelines  
- PHP architecture and namespacing discipline  
- theme.json responsive typography strategies  
- Accessibility, performance, and code review expectations  

This tool is intended for **production WordPress engineering environments**, especially those using complex block themes, custom Gutenberg blocks, and strict VIP PHPCS constraints.

---

## Features

- **`.cursor/commands/` integration**  
  Cursor automatically discovers these commands and exposes them as slash commands.

- **Workspace-aware rule generation**  
  Both commands analyze:
  - folder layout  
  - PHP architecture  
  - JS/React block code  
  - theme.json structure  
  - build tools  
  - naming patterns  
  - VIP + 10up conventions  

- **Generates modular `.mdc` rulepacks**, including:
  - project-overview.mdc  
  - wordpress-vip-standards.mdc  
  - php-best-practices.mdc  
  - gutenberg-blocks.mdc  
  - theme-json.mdc  
  - javascript-react.mdc  
  - performance.mdc  
  - accessibility.mdc  
  - code-style.mdc  
  - refactoring-guidance.mdc  
  - folder-specific-rules.mdc  

- **Optimized for Cursor’s modern rule schema**  
  Each file separates `always`, `auto-select`, `manual`, and `agent` rules.

---

## Included Commands

### `generate-cursor-rules.md`
Generates a full rule set based on the workspace, producing modular `.mdc` rule files following Cursor’s recommended structure.

### `generate-cursor-rules-wpvip.md`
An advanced command that generates a production-grade WPVIP/10up/Fueled ruleset with deep analysis and topic-specific `.mdc` files.

---
