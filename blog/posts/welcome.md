---
date: 2025-01-20
authors:
  - scttfrdmn
categories:
  - Announcements
  - Platform Updates
---

# Welcome to ResearchComputing

Welcome to the ResearchComputing blog! I'm excited to introduce a unified platform for modern research computing that makes cloud-based scientific computing accessible, efficient, and cost-effective.

<!-- more -->

## What is ResearchComputing?

ResearchComputing is an integrated ecosystem of tools designed to support the entire research computing lifecycle:

- **🧫 petri** - Research-focused AWS account management
- **🔷 prism** - Interactive cloud workspaces
- **🔬 lens** - Lab notebook environments (Jupyter, RStudio, VSCode)
- **⚛️ atom** - Cloud-native HPC platform
- **🚢 cargoship** - Enterprise data archiving
- **🐋 orca** - Kubernetes-to-AWS burst computing

## Why Another Platform?

Over the past few years, I've worked with dozens of research groups struggling with cloud computing. Common pain points include:

- **Complexity**: AWS is powerful but overwhelming for researchers
- **Cost**: Unpredictable costs and difficulty optimizing spending
- **Performance**: Generic cloud setups miss significant performance gains
- **Integration**: Tools don't work together seamlessly

ResearchComputing addresses these challenges by providing:

1. **Simplified UX** - Complex infrastructure, simple user experience
2. **Cost Transparency** - Know costs before running workloads
3. **Optimized Performance** - Architecture-specific builds (AMD, Intel, ARM)
4. **Integrated Workflow** - Tools designed to work together

## Cloud-Native Philosophy

Traditional HPC involves managing physical clusters - purchasing hardware, managing queues, dealing with downtime. Cloud-native HPC takes a different approach:

- **Elastic**: Scale from 1 to 1000 cores instantly
- **Containerized**: Reproducible environments
- **Serverless**: No cluster management overhead
- **Cost-Optimized**: Pay only for what you use

This isn't just lifting existing HPC tools to the cloud - it's rethinking HPC for the cloud era.

## ATOM: The Fundamental Unit

I'm particularly excited about [atom](https://atomhpc.io) - our cloud-native HPC platform. The name captures our philosophy: atoms are fundamental units of matter, and atom is the fundamental unit of cloud computing for researchers.

Key features:

- **Architecture-Optimized**: Builds for AMD EPYC, Intel Xeon, ARM Graviton with 2-3x performance gains
- **Application-Agnostic**: Platform for any scientific application (GEOS-Chem, Gaussian, WRF, VASP, ORCA)
- **Cost-Efficient**: Spot instances, priority queues, automatic architecture selection

Starting with GEOS-Chem atmospheric chemistry and expanding to quantum chemistry, weather modeling, and beyond.

## What's Next

Over the coming months, I'll be sharing:

- **Architecture deep-dives** - How each tool works
- **Performance benchmarks** - Real numbers from actual workloads
- **Cost optimization** - Strategies to reduce cloud spending
- **Integration patterns** - How tools work together
- **Case studies** - Real research groups using the platform

## Get Involved

All ResearchComputing projects are open source:

- **GitHub**: [@scttfrdmn](https://github.com/scttfrdmn)
- **Twitter**: [@scttfrdmn](https://twitter.com/scttfrdmn)

Questions? Ideas? Open an issue or discussion on GitHub. Want to contribute? Check out our contributing guides.

## Stay Tuned

The next post will dive into atom's container architecture and why architecture-specific optimization matters for HPC workloads.

Subscribe via RSS or follow on Twitter to stay updated!

---

*Have questions about ResearchComputing? Open a [GitHub Discussion](https://github.com/scttfrdmn/atom/discussions) or reach out on [Twitter](https://twitter.com/scttfrdmn).*
