# Contributing to MCP Korea Documentation

Thank you for your interest in contributing to MCP Korea documentation! This guide will help you understand how to contribute effectively.

## 📋 Table of Contents

- [Getting Started](#getting-started)
- [Documentation Standards](#documentation-standards)
- [Submission Process](#submission-process)
- [Style Guide](#style-guide)
- [Review Process](#review-process)

## 🚀 Getting Started

1. Fork this repository
2. Create a new branch for your documentation (`git checkout -b docs/your-topic`)
3. Write your documentation following our standards
4. Submit a pull request

## 📝 Documentation Standards

### Wiki Articles (`/wiki/`)

All wiki articles must include frontmatter:

```yaml
---
title: "Article Title in Korean"
description: "Brief description in Korean"
tags: ["tag1", "tag2"]
author: "Your Name"
date: "YYYY-MM-DD"
---
```

### MCP Documentation (`/mcp/`)

Each MCP should have its own directory with:
- `README.md` - Overview and installation
- `configuration.md` - Configuration options
- `examples.md` - Usage examples
- `api.md` - API reference (if applicable)

Example structure:
```
/mcp/mcp-name/
├── README.md
├── configuration.md
├── examples.md
└── api.md
```

### Guides (`/guides/`)

Guides should be practical tutorials with:
- Clear objectives
- Prerequisites
- Step-by-step instructions
- Code examples
- Troubleshooting section

## 📤 Submission Process

1. **Check Existing Documentation**: Ensure your topic isn't already covered
2. **Follow Templates**: Use provided templates when available
3. **Test Your Examples**: All code examples must be tested and working
4. **Include Images**: Add relevant screenshots to `/images/` directory
5. **Submit PR**: Create a pull request with a clear description

## 📖 Style Guide

### Language
- Primary language: Korean
- Technical terms: Use English terms commonly used in Korean tech community
- Code comments: English

### Formatting
- Use GitHub Flavored Markdown
- Headers: Use proper hierarchy (H1 for title, H2 for main sections)
- Code blocks: Specify language for syntax highlighting
- Links: Use relative links for internal documentation

### Code Examples

```javascript
// Good example - includes context and explanation
const mcp = new MCP({
  name: 'example-mcp',
  version: '1.0.0'
});

// 연결 초기화
await mcp.connect();
```

### Images
- Format: PNG or WebP preferred
- Naming: `kebab-case-description.png`
- Location: `/images/[category]/`
- Alt text: Required for all images

## 🔍 Review Process

1. **Initial Review**: Maintainers check for completeness and standards compliance
2. **Technical Review**: Verify technical accuracy and test examples
3. **Language Review**: Check Korean language quality and clarity
4. **Final Approval**: Merge to main branch and auto-sync to website

## ✅ Checklist

Before submitting your PR, ensure:

- [ ] Documentation follows the style guide
- [ ] All code examples are tested
- [ ] Images are properly formatted and placed
- [ ] Frontmatter is complete and accurate
- [ ] No broken links
- [ ] Korean language is clear and professional

## 🤝 Getting Help

If you need help:
- Check existing documentation for examples
- Open an issue for questions
- Join our community discussions

## 📜 License

By contributing, you agree that your contributions will be licensed under the same license as the main project.

---

Thank you for helping make MCP Korea documentation better! 🎉