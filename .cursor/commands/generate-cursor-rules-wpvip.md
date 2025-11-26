You are generating a complete set of Cursor Rule files for this workspace.
First, deeply analyze the workspace’s languages, frameworks, file structure, naming conventions, dependencies, build system, and WordPress theme/block architecture.

Use this analysis to produce a fully modernized, production-grade set of Cursor rules tailored to:

1. WordPress VIP coding standards
2. 10up / Fueled WordPress engineering best practices
3. Modern WordPress block theme development
4. Gutenberg best practices (custom blocks, patterns, variations)
5. React/JSX in block development
6. PHP architecture conventions (namespacing, autoloading, separation of concerns)
7. Theme.json usage and responsive typography systems
8. Accessibility and performance guidelines core to VIP + 10up
9. Modern asset build pipelines (esbuild, webpack, Vite, or whatever exists)
10. Code review expectations on enterprise WP builds

RULESET REQUIREMENTS:
- Use the updated Cursor rule schema.
- Produce modular `.mdc` files organized by topic.
- Use the four modern rule types: always, auto-select, agent, manual.
- Do not merge unrelated rules into single files.
- Remove redundancy and contradictions.
- Include guidance only if it fits the workspace’s tech stack.
- Ensure all rules help Cursor produce production-quality code and safe refactors.

GENERATE THE FOLLOWING FILES (if relevant to the project):

1. project-overview.mdc  
   - Dependencies summary  
   - Framework notes  
   - Architectural overview  

2. wordpress-vip-standards.mdc  
   - Escaping  
   - Sanitization  
   - Query performance  
   - No direct DB writes  
   - No remote requests without VIP approval  
   - Enqueue patterns  
   - VIP PHPCS conventions  

3. php-best-practices.mdc  
   - Namespacing  
   - File structure  
   - Class patterns  
   - Separation of concerns  
   - Template architecture (partial patterns, template parts)  

4. gutenberg-blocks.mdc  
   - Block.json conventions  
   - Editor/frontend parity  
   - theme.json usage  
   - A11y rules  
   - Allowed variations + patterns  
   - Inline vs external scripts  
   - Block scaffolding expectations  

5. theme-json.mdc  
   - Responsive typography  
   - Custom properties strategy  
   - Media queries  
   - Fluid type rules  
   - Using theme.json variables in CSS  

6. javascript-react.mdc  
   - React patterns for blocks  
   - Component reuse  
   - Hooks conventions  
   - File organization  
   - Testing expectations (if applicable)  

7. performance.mdc  
   - Lighthouse goals  
   - Lazy loading  
   - Script enqueueing  
   - Render blocking minimization  
   - Query optimization  

8. accessibility.mdc  
   - 10up A11y checklist points  
   - ARIA guidance  
   - Color contrast  
   - Content structure expectations  

9. code-style.mdc  
   - VIP PHPCS  
   - ESLint conventions  
   - Prettier / formatting expectations  
   - Naming conventions  

10. refactoring-guidance.mdc  
   - Safe refactor patterns  
   - Multi-file updates  
   - Detecting dead code  
   - Handling legacy patterns  

11. folder-specific-rules.mdc  
   - Create rules for each folder in the workspace  
   - Tailor rules to what the codebase contains  

When generating:
- Use concise, enforceable language.  
- Omit explanations and meta commentary.  
- Output only valid `.mdc` file contents and filenames.  
