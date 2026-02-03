# Phase 4: TITRATE (The Test)

> "Treating the new workflow as an experiment starts by formulating a hypothesis... Measurement is non-negotiable."

## The Concept
Titration is the careful measurement of effects. In this phase, you treat your synthesized workflow not as a permanent change, but as a prototype that requires testing.

## The Sprint Protocol
Run a "Personal Sprint" (typically 1 to 2 weeks) to test the new workflow.

### 1. Formulate a Hypothesis
Example: *"If I use AI to automate data pulling for the monthly forecast, I will reduce prep time by 60% and increase analysis time by 30%."*

### 2. Validation is Not Optional
You remain responsible for the output. The human in the loop is the "Editor-in-Chief".
* **Adversarial Review:** Actively attempt to break the AI's output. Assume it has hallucinated a fact or buried a logical error.
* **The Intern Check:** Treat the AI like a confident but inexperienced intern. You wouldn't sign their work without reading it.

### 3. The Decision
At the end of the sprint, review the data:
* **Abandon:** If the orchestration took longer than the drudgery.
* **Modify:** If the AI hallucinated but saved time (refine the prompt).
* **Adopt:** If you reclaimed time and maintained quality.

## The Tools
Use the open-source tools in this repository to execute this phase:

1. **Plan your Sprint:** Use `prompts/07-sprint-design.md` to define your hypothesis and risk mitigation plan, and track it using the `templates/02-sprint-plan.md` file.
2. **Enforce Adversarial Review:** Use `prompts/15-validation.md` to force the AI to act as a Quality Assurance specialist and expose hidden errors in its own output.
3. **Run the Retrospective:** At the end of the sprint, paste your tracking data into `prompts/08-retrospective.md` to determine whether to Adopt, Modify, or Abandon your new workflow.
