# ROADMAP - WinOptimizer Pro

## Phase 1: Foundation & Infrastructure (WIP)
- [ ] Initialize project with Electron and Python (uv).
- [ ] Implement secure IPC bridge between Frontend and Python backend.
- [ ] Create basic Dashboard UI.

## Phase 2: Core Optimization Features
- [ ] **Cache Cleaning:**
    - [ ] System Temporary files.
    - [ ] Browser caches (Chrome, Firefox, Edge).
    - [ ] Windows Update cache.
- [ ] **Startup Management:**
    - [ ] List current startup entries (Registry & Startup folder).
    - [ ] Enable/Disable toggle for entries.

## Phase 3: Advanced System Tools
- [ ] **Process Optimization:**
    - [ ] Identify high-resource processes.
    - [ ] One-click "Game Mode" optimizer.
- [ ] **Security Analysis:**
    - [ ] Integration with process scanning to identify suspicious parent-child relationships.
    - [ ] Check process signatures.
- [ ] **Permission Fixer:**
    - [ ] Recursive permission reset for common "Locked" folders.

## Phase 4: UI/UX & Polish
- [ ] Modern, dark-themed dashboard.
- [ ] Real-time system resource monitoring.
- [ ] Task scheduling for automatic cleaning.

## Phase 5: Release & Distribution
- [ ] Package for Windows (Portable & Installer).
- [ ] GitHub Actions for CI/CD.
