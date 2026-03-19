# UX Directives — Claude Skill

> A Claude skill that applies the **UX Directives** to any design task — audits, new product design, interaction critique, and AI-mediated interface evaluation.

**Author: [Aleh Haiko](https://github.com/alehhaiko)**

---

## What is this?

This is a **Claude Project Skill** authored by **[Aleh Haiko](https://github.com/alehhaiko)** that turns Claude into a senior UX practitioner fluent in the *UX Directives* — a doctrine of Human-Centered Systems Engineering.

When this skill is active in your Claude Project, Claude will:

- **Audit designs** against all 9 chapters of the Blue Book, citing directive numbers and severity levels
- **Guide new product design** by surfacing the right constraints before you build
- **Critique single decisions** with directive-backed rationale, not personal opinion
- **Evaluate AI interfaces** using Chapter 9 — a dedicated framework for AI-mediated interaction

---

## The 9 Chapters of the Blue Book

| # | Chapter | Governs |
|---|---------|---------|
| 1 | **Human Cognition & Behavior** | Attention, cognitive load, recognition, mental models, learnability, simplicity |
| 2 | **Information Architecture & Wayfinding** | Information hierarchy, discoverability, navigation, progressive disclosure |
| 3 | **Interaction Mechanics & Agency** | Affordances, direct manipulation, feedback loops, efficiency, Fitts's Law |
| 4 | **System Behavior & Workflow Logic** | Defaults, anticipation, error prevention, recovery, latency |
| 5 | **Visual Communication** | Visual hierarchy, contrast, readability, accessibility, information density |
| 6 | **Consistency & Coherence** | Consistency, conventions, patterns, design system integrity |
| 7 | **Trust, Safety & Responsibility** | Consent & control, transparency, error communication, data integrity |
| 8 | **Adaptation & Evolution** | Continuity, scalability, observability, validation |
| 9 | **AI-Mediated Interaction** | Human oversight, automation consent, explainability, trust calibration, graceful failure |

---

## How to Install

### Step 1 — Create a Claude Project

Go to [claude.ai](https://claude.ai), create a new **Project**, and open its settings.

### Step 2 — Add the Skill

1. In your Project settings, go to **Skills** (or **Custom Instructions**)
2. Upload `SKILL.md` from this repository
3. Optionally, upload the full **Blue Book of UX Directives** as a project knowledge document so Claude can cite specific directive numbers

### Step 3 — Start a conversation

Ask Claude to review a design, audit a flow, or guide a new feature — it will automatically apply the Blue Book framework.

---

## Example Prompts

```
Review this onboarding flow and audit it against UX Directives.
```

```
We're designing a dashboard with AI-generated recommendations. 
What UX directives should govern this feature?
```

```
Here's a screenshot of our checkout page. What do you think?
```

```
Evaluate this error message design against the Blue Book.
```

---

## How the Skill Works

When triggered, Claude:

1. **Identifies the task type** (audit, new design, single decision, AI interface)
2. **Searches project knowledge** for the relevant directive chapters
3. **Evaluates systematically** using Key Heuristics and Success Indicators
4. **Classifies findings** by severity: 🔴 Critical · 🟡 Major · 🟢 Minor
5. **Cites directives by number** (e.g., *Directive 44/03*)
6. **Pairs every critique with a recommendation**

---

## Key Principles

- **The system is responsible**, not the user. Errors, confusion, and inefficiency are design failures.
- **Defaults are behavioral commitments**, not placeholder values.
- **Accessibility is equal task capability** — not optional accommodation.
- **Attention must be earned** — every interruption must justify its cognitive cost.
- **Aesthetic restraint is functional** — visual noise is a usability defect.
- **AI behavior must remain understandable, controllable, and trustworthy.**
- **Design debt is a system risk** — inconsistencies must be tracked and refactored.

---

## Repository Structure

```
UX-directives-skills/
├── README.md              ← Landing page with install guide & examples
├── SKILL.md               ← The actual skill file users upload to Claude
├── LICENSE                ← MIT License
├── .gitignore
└── .github/
    └── ISSUE_TEMPLATE/
        └── feedback.md    ← Issue template for directive feedback
```

---

## Contributing

The UX Directives is a living doctrine. If you have feedback on specific directives, encounter edge cases, or want to propose additions to any chapter, please open an issue using the feedback template.

Pull requests are welcome for:
- Clarifications to the SKILL.md trigger logic
- New example prompts
- Documentation improvements

---

## Author

**Aleh Haiko** — Human-Centered Systems Engineering practitioner and author of the UX Directives.

- Website: [alehhaiko.com](https://www.alehhaiko.com)
- GitHub: [@alehhaiko](https://github.com/alehhaiko)

---

## License

MIT — see [LICENSE](./LICENSE)
