# Claude Skills Documentation Index

## Categories

### README
**File:** `README.md`
**Pages:** 1 (122 lines)

Complete overview of Claude Skills including:
- What are skills and how they work
- Example skills by category
- Document skills (source-available)
- Usage across platforms (Claude Code, Claude.ai, API)
- Creating basic skills
- Partner skills

## Quick Links

- What are skills → `README.md` (line 1-9)
- Example skills list → `README.md` (line 24-45)
- Document skills → `README.md` (line 47-56)
- Claude Code setup → `README.md` (line 58-78)
- Claude.ai usage → `README.md` (line 80-84)
- Claude API → `README.md` (line 86-88)
- Creating a skill → `README.md` (line 90-117)
- Partner skills → `README.md` (line 119-122)

## Topics Covered

### Getting Started
- What skills are
- How skills work
- Platform availability
- Installation methods

### Example Skills by Category

**Creative & Design:**
- Algorithmic art generation
- Canvas design
- Slack GIF creation

**Development & Technical:**
- HTML artifacts builder
- MCP server creation
- Webapp testing

**Enterprise & Communication:**
- Brand guidelines
- Internal communications
- Theme factory

**Meta Skills:**
- Skill creator guide
- Template skill

### Document Skills (Advanced)
- DOCX (Word documents)
- PDF (PDF manipulation)
- PPTX (PowerPoint presentations)
- XLSX (Excel spreadsheets)

### Creating Skills
- Basic structure (folder + SKILL.md)
- YAML frontmatter requirements
- Markdown instructions
- Template usage

### Platform Integration
- Claude Code plugin marketplace
- Claude.ai skills interface
- Claude API integration
- Cross-platform portability

## Skill Structure

```
skill-name/
├── SKILL.md           # Required: Main instructions
├── references/        # Optional: Documentation
├── scripts/           # Optional: Helper scripts
└── assets/            # Optional: Resources
```

## YAML Frontmatter

```yaml
---
name: skill-name
description: Clear description of what the skill does
---
```

## External Resources

- **Support Articles:**
  - What are skills?
  - Using skills in Claude
  - Creating custom skills

- **Blog Posts:**
  - Equipping agents with Agent Skills

- **API Documentation:**
  - Skills API Quickstart
  - Creating skills via API

## License

Example skills: Apache 2.0 (open source)
Document skills: Source-available (reference only)
