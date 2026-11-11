# 🚀 Universal AI App Architect & Blueprint Engine

> A standardized, intelligent multi-chat framework for bootstrapping, architecting, and incrementally building production applications with AI coding assistants.

---

## 📂 Architecture Overview

```
ROOT/
├── Generalised app decisions and requirements/   <-- [READ-ONLY MASTER BLUEPRINT & ENGINE]
│   ├── 00_MASTER_AI_INSTRUCTIONS.txt            <-- Decisions Chat master playbook
│   ├── APP_DEVELOPMENT_FLOW_TEMPLATE.txt        <-- Tracking card & checkbox template
│   ├── technical requirements documents(TRD)/   <-- Framework matrix & library presets
│   ├── UI implementation/                       <-- Component-first design extraction
│   ├── Common Ux implementation/                <-- User journeys, states & permissions
│   ├── App features implementation/             <-- Module -> Phase -> Step hierarchy
│   └── product requirements documnets(PRD)/     <-- PRD discovery template
│
└── decisions for this app/                      <-- [TARGET DIRECTORY: GENERATE DECISIONS HERE]
    └── APP_DEVELOPMENT_FLOW.txt                 <-- Generated during Decisions Chat
```

---

## 🔄 How the Multi-Chat Workflow Works

### 1. Decisions Chat (Brain & Architecture)
1. Point your AI assistant to this repository.
2. The AI asks **4 quick starter questions**:
   - What are you building?
   - What framework & language?
   - What architecture? (e.g. Feature-First MVVM)
   - Path to UI design files or app working process document.
3. The AI outputs a **names-only tech stack short list** for your approval.
4. Upon confirmation, the AI generates:
   - `decisions for this app/APP_DEVELOPMENT_FLOW.txt` (with progress checkboxes `[ ]`).
   - 5 ready-to-copy prompts for separate implementation chats.

---

### 2. Implementation Chats (Execution Chats)
Never build the entire app in one chat. Open a new chat for each phase:

| Phase | Target Chat | Responsibility |
| :--- | :--- | :--- |
| **Plan 1** | `Impl Chat 01` | **UI Components**: Build all reusable atoms, inputs, buttons, cards from design |
| **Plan 2** | `Impl Chat 02` | **UI Pages**: Assemble pre-made components into full screen layouts |
| **Plan 3** | `Impl Chat 03` | **Data Layer**: DTOs, API services, local DB, repository implementations |
| **Plan 4** | `Impl Chat 04` | **Domain Layer**: Pure entities, repository interfaces, usecases |
| **Plan 5** | `Impl Chat 05` | **Presentation Layer**: ViewModels & binding to UI pages (fully functional) |

*(Each chat updates its corresponding `[ ]` to `[x]` in `APP_DEVELOPMENT_FLOW.txt` when verified.)*

---

## ⚡ Global Usage

### Option A: Use as GitHub Template
Click **"Use this template"** on GitHub to start a new application repository with this blueprint pre-installed.

### Option B: Clone into Any Project
```bash
git clone https://github.com/Nehal-Ahmmed/app-architect-blueprint.git .
```
