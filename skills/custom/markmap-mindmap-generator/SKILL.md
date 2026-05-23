---
name: markmap-mindmap-generator
description: Generate beautiful mindmaps from templates using Markmap. Use this skill when you need to visualize structures, plans, architectures, or strategies as interactive mindmaps.
license: Complete terms in LICENSE.txt
---

# Markmap Mindmap Generator

This skill enables Manus to create professional mindmaps using the Markmap library. It supports multiple templates for different use cases, custom sections, and various themes.

## Capabilities

- **Template-based Generation**: Use built-in templates for Novels, System Architecture, Executive Reports, Technical Reports, AI Skills, Planning, and Strategy.
- **Customization**: Add custom sections and levels to any mindmap.
- **Visual Enhancements**: Include code blocks, tables, and images in the mindmap.
- **Interactive Export**: Export mindmaps as standalone HTML files with interactive features.

## Templates

| Template | Use Case |
|----------|----------|
| `novel` | Story structure, narrative planning |
| `system_arch` | Software architecture, system design |
| `exec_report` | Executive summary, business reports |
| `tech_report` | Technical documentation, research |
| `ai_skill` | AI/ML skills mapping, learning path |
| `planning` | Project planning, timeline |
| `strategy` | Business strategy, strategic planning |

## Usage

### Generating a Mindmap
Use the `mmg` CLI tool to generate mindmaps:
```bash
mmg --type planning --html --theme dark
```

### Adding Custom Sections
```bash
mmg --type system_arch --add "API:Login,Register,Logout"
```

## Bundled Resources
- **`scripts/`**: CLI and generator logic.
- **`templates/`**: YAML templates for various mindmap types.
