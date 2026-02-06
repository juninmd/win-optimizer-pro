# AGENTS.md

## Project: WinOptimizer Pro

### Context for Agent Jules
WinOptimizer Pro is a Windows utility designed to handle system-level optimizations that typically require administrative privileges. The architecture follows an Electron + Python hybrid model.

### Technical Guidelines
- **Python Backend:** Use `uv` for dependency management. Core logic for file system and process management lives here.
- **Electron Frontend:** React-based UI. Use `pnpm` for npm packages.
- **Security:** Always validate system commands. Avoid shell injection.
- **Permissions:** Some tasks (like fixing folder permissions) will require elevation (UAC).

### Handover Status
- [x] Project directory initialized.
- [x] Initial documentation (README, ROADMAP, AGENTS) created.
- [ ] implementation_plan.md drafted.
- [ ] Git repository initialized and pushed to GitHub.

### Next Steps for Jules
1. Bootstrapping the Electron + Python boilerplate.
2. Implementing the first optimization module: Cache Cleaner.
3. Setting up the GitHub Actions pipeline.
