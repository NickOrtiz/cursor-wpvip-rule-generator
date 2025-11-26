Analyze the project structure, architecture, languages, and frameworks in the current workspace. 
Using that information, generate a complete set of Cursor Rules in .mdc format following the current Cursor rule schema with the four rule types: 
- always
- auto-select 
- agent 
- manual

Rules should be split into separate .mdc files, each optimized for relevance and readability.

Ensure:
- Rules follow Cursor’s recommended structure.
- No redundant or conflicting rules.
- Keep rules modular (e.g., one file each for project overview, code style, folder-specific rules, framework conventions, API contracts, naming conventions, and testing practices).
- Use concise but explicit guidance.
- Prioritize rules that improve refactoring, debugging, generating new code, and multi-file reasoning.

Output ONLY valid rule file contents and filenames. Do not explain.
