# Backend Documentation

Welcome to the CodeThe5 backend documentation. Start here to get onboarded.

---

## 🚦 Getting Started (Start Here)

| Document | Description | Time |
|----------|-------------|------|
| **[Zero to Deploy (Onboarding)](./ONBOARDING.mdx)** | **Read this first!** Setup, dev loop, and deployment guide. | 20 min |
| **[Introduction](./INTRODUCTION.md)** | What the backend does, tech stack overview | 5 min |
| **[Development](./DEVELOPMENT.mdx)** | Detailed day-to-day workflows and patterns | 20 min |

---

## Technical Guides

| Document | Description |
|----------|-------------|
| **[Architecture](./ARCHITECTURE.mdx)** | System design, module breakdown, security layers |
| **[Quickstart](./QUICKSTART.mdx)** | Concise setup guide for experienced devs |

---

## Quick Reference

### Start Development

```bash
cd functions
source venv/bin/activate
firebase emulators:start
```

### Run Tests

```bash
cd functions
pytest
```

---

## Documentation Map

```
docs/backend/
├── README.md           # This file
├── ONBOARDING.mdx      # Zero-to-hero guide
├── INTRODUCTION.md     # System overview
├── DEVELOPMENT.mdx     # Workflows & patterns
├── ARCHITECTURE.mdx    # Technical deep dive
└── QUICKSTART.mdx      # Fast setup summary
```
