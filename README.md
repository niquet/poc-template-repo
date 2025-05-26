# poc-template-repo

This repository's workflow is designed for quick, simple proof-of-concept (PoC) and toy code development. The goal is to validate ideas rapidly and foster clear understanding—without unnecessary complexity.

## Table of Contents

- [Embrace Simplicity](#embrace-simplicity)
    - [Why Keep It Simple?](#why-keep-it-simple)
    - [Beware of Unnecessary Complexity](#beware-of-unnecessary-complexity)
- [Usage](#usage)
- [FAQ](#faq)

## Embrace Simplicity

> Simplicity is a great virtue but it requires hard work to achieve it and education to appreciate it. And to make matters worse: complexity sells better. — Edsger W. Dijkstra

- **Start with the simplest solution that could possibly work.**
- Don’t overthink or over-engineer.
- Make it work, make it right, then (maybe) make it fast.

For PoCs and toy code, focus on:

- **Skip the design patterns** - just make it work.
- **Hardcode values** instead of building configuration systems.
- **Copy-paste code** rather than creating reusable functions.
- **Use the most straightforward approach**, even if it's not "elegant".

### Why Keep It Simple?

- **Faster iteration:** Modify, test, and pivot quickly.
- **Clearer insights:** Fewer moving parts mean you can easily see what works.
- **Easier debugging:** When issues arise, fix them quickly.

### Beware of Unnecessary Complexity

Adding abstractions "just in case" can:

- Solve problems you don't have.
- Obscure what's really working.
- Hide the core insights you're trying to validate.

_Save the engineering excellence for when you know the idea is worth building properly._

## Usage

1. **Create a new repository from this template**

    Click "Use this template" on GitHub to start a new PoC project with this structure.

2. **Clone the repository and make your first commit**

    Push an initial commit to the default branch (`main`).

    This triggers a workflow that will automatically create a set of issues to guide your PoC process.

4. **Work through the issues**

    Follow the actionable issues to define purpose, scope, simplicity, iteration, communication, and discipline in your PoC.

4. **If you don’t want the issues created automatically:**

  - Before pushing your first commit, create a file named .github/issues_created in your repository.
  - This will prevent the workflow from creating the issues.
  - Alternatively, delete the workflow file in .github/workflows/ if you don’t want this automation at all.

---

## FAQ

**Why is simplicity so important in PoCs and toy code?**

Simplicity allows you to move fast, learn quickly, and avoid getting bogged down in details that don’t matter until you’ve validated your idea. Both Gergely Orosz and many experienced engineers on Hacker News agree: clarity and speed are more valuable than polish or abstraction at this stage.

**Isn’t abstraction and maintainability important?**

Yes—but only when you know the idea is worth building. For PoCs, extra abstraction often just adds confusion and slows you down. Focus on solving the problem at hand.

**What if I need to add complexity for correctness or learning?**

If complexity directly serves your learning goal or is necessary for correctness, add it deliberately and document why. Otherwise, defer it until you’ve validated the core concept.

**What about design patterns and reusable code?**

Skip them for PoCs. Hardcode values, copy-paste if you must, and keep everything as straightforward as possible. Save engineering excellence for later.

**How do I avoid over-engineering?**

Keep your checklist simple:

- Define clear goals.
- Build the simplest thing that works.
- Only add complexity when it’s absolutely necessary for learning or correctness.

**What if I want to turn my PoC into production code?**

Once the idea is validated, start a new project or refactor with best practices, abstractions, and maintainability in mind.

---

Remember...

> Proof-of-concept code should be unapologetically simple. Validate ideas quickly, understand the problem space, and keep complexity at bay.

