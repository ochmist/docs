# Backend Documentation

Welcome to the CodeThe5 backend documentation. Start here to get onboarded.

---

## Getting Started

| Document | Description | Time |
|----------|-------------|------|
| **[Introduction](./INTRODUCTION.md)** | What the backend does, tech stack overview | 5 min |
| **[Quickstart](./QUICKSTART.md)** | Set up your development environment | 15 min |
| **[Development](./DEVELOPMENT.md)** | Day-to-day workflows, testing, debugging | 20 min |

---

## Deep Dives

| Document | Description |
|----------|-------------|
| **[Architecture](./ARCHITECTURE.md)** | System design, module breakdown, security layers |
| **[Onboarding (Extended)](./ONBOARDING.md)** | Alternative comprehensive guide |

---

## Quick Reference

### Start Development

```bash
cd functions
source venv/bin/activate
firebase emulators:start  # Run from project root
```

### Run Tests

```bash
cd functions
pytest
```

### Deploy

```bash
firebase deploy --only functions
```

---

## Documentation Map

```
docs/backend/
├── README.md           # This file
├── INTRODUCTION.md     # System overview
├── QUICKSTART.md       # Environment setup
├── DEVELOPMENT.md      # Daily workflows
├── ARCHITECTURE.md     # Technical deep dive
└── ONBOARDING.md       # Extended onboarding guide
```
