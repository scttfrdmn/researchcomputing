# ResearchComputing

**A unified platform for modern research computing**

[researchcomput.ing](https://researchcomput.ing)

## Overview

This repository contains the landing page and documentation for the ResearchComputing ecosystem - an integrated suite of tools for cloud-based research computing.

## Ecosystem Projects

- **[petri](https://github.com/scttfrdmn/petri)** - Research-focused AWS account management
- **[prism](https://github.com/scttfrdmn/prism)** - Interactive cloud workspaces
- **[lens](https://github.com/scttfrdmn/lens)** - Lab notebook environments (Jupyter, RStudio, VSCode)
- **[atom](https://github.com/scttfrdmn/atom)** - Cloud-native HPC platform
- **[cargoship](https://github.com/scttfrdmn/cargoship)** - Enterprise data archiving
- **[orca](https://github.com/scttfrdmn/orca)** - Kubernetes-to-AWS burst computing

## Documentation

This site is built with [MkDocs](https://www.mkdocs.org/) and [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

### Local Development

```bash
# Install dependencies
pip install mkdocs-material mkdocs-minify-plugin

# Serve locally
mkdocs serve

# Build static site
mkdocs build
```

### Blog

The blog is integrated using the [MkDocs Material blog plugin](https://squidfunk.github.io/mkdocs-material/plugins/blog/).

Blog posts go in `blog/posts/` with frontmatter:

```markdown
---
date: 2025-01-20
authors:
  - scttfrdmn
categories:
  - Platform Updates
---

# Post Title

Post content...
```

## Contributing

Contributions welcome! To suggest changes:

1. Fork this repository
2. Make your changes
3. Submit a pull request

## License

Documentation is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

---

**Questions?** Open an [issue](https://github.com/scttfrdmn/researchcomputing/issues) or [discussion](https://github.com/scttfrdmn/atom/discussions).
