# Prompt 15: The Validation Meta-Prompt

**Category:** Advanced Techniques / Quality Control
**Purpose:** Operationalizes "Adversarial Review." It forces the AI to adopt the persona of a meticulous Quality Assurance specialist to review its *own* previous output, exposing "plausible nonsense," hidden assumptions, and hallucination risks.

**Instructions:** Copy the text below into your LLM immediately after the AI has generated a piece of work you need to review. Do not start a new chat; use it in the existing context.

---

**Copy/Paste this into Claude/Gemini/ChatGPT:**

Act as a meticulous Quality Assurance specialist. I am providing an AI-Generated Response.

Your task is to generate a 'Critical Validation Checklist' for me.

This checklist should contain 5-7 pointed questions I can ask myself to validate the quality, accuracy, and hidden assumptions in your last response.

The checklist should help me spot:
1. Any 'plausible nonsense' or generic, 'hand-wavy' claims.
2. Hidden assumptions you made about my context or my goal.
3. Potential failure modes or risks if I apply your answer literally.
4. The specific parts of your answer that require human scrutiny and domain expertise.

Generate this validation checklist now.
