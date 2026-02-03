# The D.I.S.T. Framework

**A repeatable method for deconstructing professional roles and redesigning them for human-AI workflow symbiosis.**

## Overview

Artificial intelligence is a universal solvent for knowledge work. It is systematically breaking down the stable container of tasks, skills, and responsibilities that has defined "jobs" for decades.

The **D.I.S.T. Framework** is a method for navigating this dissolution. It allows you to stop treating your job as a solid block and start seeing it as a collection of elements, enabling you to separate the mechanical cognitive tasks (Silicon) from the human responsibilities (Carbon).

This repository contains the core protocols, prompts, and templates required to execute this framework. If you want to test the framework without using your own data, use `prompts/00-test-data-generator.md` to create a realistic dummy data sandbox.

## The Framework

The methodology follows four phases:

### 1. DISSOLVE (The Audit)
**Break the rigid role into liquid elements.**
Most professionals rely on memory to estimate workload, which is unreliable. The Dissolve step asks for tracking work with granular fidelity to reveal the friction often ignored. 
* **Goal:** Create a raw log of discrete task entries and analyze the gap between official scope and actual work.
* **Prompt:** `prompts/01-comprehensive-job-analysis.md`
* **Prompt:** `prompts/02-work-week-analysis.md`
* **Template:** `templates/01-audit-log.md`

### 2. ISOLATE (The Sort)
**Separate the Silicon from the Carbon.**
Sort every item into two primary lists based on pattern-recognition and risk.
* **Silicon (AI-Ready):** Tasks that follow known patterns with structured data (e.g., data entry, report generation).
* **Carbon (Human Responsibility):** Tasks that require judgment, ambiguity navigation, and relational trust (e.g., negotiation, strategic interpretation).
* **Prompt:** `prompts/03-silicon-carbon-sort.md`

### 3. SYNTHESIZE (The Blueprint)
**Architect the new workflow.**
Don't just automate; redesign how value is created. Design collaboration patterns where AI handles execution and humans provide validation and judgment.
* **Goal:** Blueprint a new Symbiotic Workflow and map specific micro-steps for the Human-AI handoff.
* **Prompt:** `prompts/04-workflow-redesign.md`
* **Prompt:** `prompts/05-collaboration-design.md`
* **Prompt:** `prompts/06-alternative-approach.md`

### 4. TITRATE (The Test)
**Treat the workflow as an experiment.**
Run the new workflow as a time-boxed sprint. Measurement is non-negotiable. If the orchestration takes longer than the drudgery, abandon it. If it works, adopt it as the new baseline.
* **Goal:** Launch a controlled experiment with strict validation guardrails and run a retrospective.
* **Prompt:** `prompts/07-sprint-design.md`
* **Prompt:** `prompts/08-retrospective.md`
* **Prompt:** `prompts/15-validation.md`
* **Template:** `templates/02-sprint-plan.md`

## Repository Contents

This repository is organized to help you run a "Personal Launch Plan" sprint:

* `/prompts` - The specific LLM prompts (compatible with Claude, Gemini, ChatGPT) to assist with each phase of the framework.
* `/templates` - Markdown templates for tracking your Audit and Titration sprints.
* `/guide` - Detailed descriptions of the four phases.

## Origin & Context

This framework is derived from the book **Agile Symbiosis** by Michael Janzen.

While this repository provides the *how* (the operational tools), the book provides the *why*—covering the economic context of the "Automation Headwind" vs. the "Augmentation Tide", organizational strategies for leaders, and the path to collective agency.

* **Book:** [Agile Symbiosis](https://agilesymbiosis.com)
* **Free PNA Version:** [Agile Symbiosis OS](https://agilesymbiosis.com/pna-edition)
* **Author:** Michael Janzen
* **License:** The D.I.S.T. process definitions and prompts in this repository are released under the [MIT License](LICENSE).
