# The D.I.S.T. Framework

**A repeatable method for deconstructing professional roles and redesigning them for human-AI workflow symbiosis.**

## Overview

Artificial intelligence is a universal solvent for knowledge work. It is systematically breaking down the stable container of tasks, skills, and responsibilities that has defined "jobs" for decades.

The **D.I.S.T. Framework** is a method for navigating this dissolution. It allows you to stop treating your job as a solid block and start seeing it as a collection of elements, enabling you to separate the mechanical cognitive tasks (Silicon) from the human responsibilities (Carbon).

This repository contains the core protocols, prompts, and templates required to execute this framework.

## The Framework

The methodology follows four phases:

### 1. DISSOLVE (The Audit)
**Break the rigid role into liquid elements.**
Most professionals rely on memory to estimate workload, which is unreliable. The Dissolve step asks for tracking work with granular fidelity to reveal the friction often ignored. Use the prompt to analyze your actual time log.
* **Goal:** Create a raw log of discrete task entries.
* **Prompt:** `prompts/02-work-analysis.md`
* **Template:** `templates/01-audit-log.md`

### 2. ISOLATE (The Sort)
**Separate the Silicon from the Carbon.**
Sort every item into two primary lists. Use the prompt to sort the list and identify opportunities:
* **Silicon (AI-Ready):** Tasks that follow known patterns with structured data (e.g., data entry, report generation).
* **Carbon (Human Responsibility):** Tasks that require judgment, ambiguity navigation, and relational trust (e.g., negotiation, strategic interpretation).
* **Prompt:** `prompts/03-silicon-carbon-sort.md`

### 3. SYNTHESIZE (The Blueprint)
**Architect the new workflow.**
Don't just automate; redesign how value is created. Design collaboration patterns where AI handles execution and humans provide validation and judgment. Use the prompt to draft new workflows.
* **Common Patterns:**
    * *AI Executes, Human Validates* (Data processing)
    * *Human Guides, AI Assists* (Drafting and design)
    * *Iterative Co-Creation* (Complex problem solving)
* **Prompt:** `prompts/04-workflow-redesign.md`

### 4. TITRATE (The Test)
**Treat the workflow as an experiment.**
Run the new workflow as a time-boxed sprint. Measurement is non-negotiable. If the orchestration takes longer than the drudgery, abandon it. If it works, adopt it as the new baseline. Use the prompt to test the results to improve outcome quality.
* **Prompt:** `prompts/07-sprint-design.md`
* **Template:** `templates/02-sprint-plan.md`

## Repository Contents

This repository is organized to help you run a "Personal Launch Plan" sprint:

* `/prompts` - The specific LLM prompts (compatible with Claude, Gemini, ChatGPT) to assist with each phase of the framework.
* `/templates` - Markdown templates for tracking your Audit and Titration sprints.
* `/guide` - Detailed descriptions of the four phases.

## Usage

1.  Use the templates in `/templates` to log your work week and test for new workflow efficiency and aligned outcomes.
2.  Use the prompts in `/prompts` to analyze your data and design your new role.

## Contributing

The D.I.S.T. Framework is a living protocol. 

* **Have a better prompt?** If you've refined a prompt that works better than the current version, feel free to open a Pull Request to contribute to the project.
* **Found a bug?** If a prompt is consistently hallucinating on a specific model (Claude vs GPT), please open an Issue.

## Origin & Context

This framework is derived from the book **Agile Symbiosis** by Michael Janzen.

While this repository provides the *how* (the operational tools), the book provides the *why*—covering the economic context of the "Automation Headwind" vs. the "Augmentation Tide", organizational strategies for leaders, and the path to collective agency.

* **Book:** [Agile Symbiosis](https://agilesymbiosis.com)
* **Free PNA Version:** 
* **Author:** Michael Janzen
* **License:** The D.I.S.T. process definitions and prompts in this repository are released under the [MIT License](LICENSE).

---

*"The choice isn't whether AI will transform your work. The choice is whether you will be The Passenger or The Navigator in that transformation."* — Agile Symbiosis
