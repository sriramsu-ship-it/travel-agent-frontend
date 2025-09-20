# Contributing Guidelines

Thank you for considering contributing to **AI Travel Agent MVP**!  
We keep things lightweight but structured so development stays clean and fast.

---

## 🔀 Branching Strategy
We use a **3-branch strategy**:

- **main** → Production (auto-deploys)
- **dev** → Staging/test integration
- **feature/*** → Individual features or bugfixes

Workflow:
1. Create a new branch from `dev`:  
   ```bash
   git checkout dev
   git pull origin dev
   git checkout -b feature/your-feature-name
