# poc-template-repo

This repository's workflow is designed for quick, simple proof-of-concept (PoC) and toy code development. The goal is to validate ideas rapidly and foster clear understanding—without unnecessary complexity.

## Table of Contents

- [Why Keep It Simple?](#why-keep-it-simple)
- [Embrace Simplicity](#embrace-simplicity)
- [Beware of Unnecessary Complexity](#beware-of-unnecessary-complexity)
- [Usage](#usage)
- [FAQ](#faq)

## Why Keep It Simple?

- **Faster iteration:** Modify, test, and pivot quickly.
- **Clearer insights:** Fewer moving parts mean you can easily see what works.
- **Easier debugging:** When issues arise, fix them quickly.

## Embrace Simplicity

For PoCs and toy code, focus on:

- **Skip the design patterns** - just make it work.
- **Hardcode values** instead of building configuration systems.
- **Copy-paste code** rather than creating reusable functions.
- **Use the most straightforward approach**, even if it's not "elegant".

## Beware of Unnecessary Complexity

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

**Why avoid abstractions and design patterns?**

Premature abstractions add complexity and slow down learning and iteration. In PoCs, clarity and speed matter most.

**What if I want to turn my PoC into production code?**

Once the idea is validated, start a new project or refactor with engineering best practices and abstractions as needed.

---

> Proof-of-concept code should be unapologetically simple. Validate ideas quickly, understand the problem space, and keep complexity at bay.

