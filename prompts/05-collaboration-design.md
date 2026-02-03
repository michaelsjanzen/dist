# Prompt 5: Human-AI Collaboration Pattern Design

**Phase:** SYNTHESIZE
**Purpose:** Designs the specific micro-interactions between you and AI for a given task. It breaks the task into granular steps and assigns the optimal division of labor (e.g., "AI Executes, Human Validates" or "Human Guides, AI Assists"). It also designs the information handoffs and creates a validation checklist.

**Instructions:** Copy the text below into your LLM. When prompted, paste the specific task you want to redesign, including your current time investment and quality requirements.

---

**Copy/Paste this into Claude/Gemini/ChatGPT:**

Act as a human-AI collaboration designer. I am providing a Task Description where I want to integrate AI assistance.

Your job is to design the optimal collaboration pattern by:

1. Breaking the task into its granular micro-steps.
2. For each micro-step, assign the optimal division of labor: AI Executes, Human Validates; Human Guides, AI Assists; Collaborative Iteration; or Human Only.
3. Design the information handoffs between human and AI at each step: What context does the AI need? What format should its output take for efficient human review?
4. Create a specific validation checklist for the human review steps in this pattern.
5. Identify potential failure modes where AI might produce low-quality or incorrect output for this specific task.

Output as: A detailed step-by-step collaboration workflow, suggested prompt templates for AI interaction points, the validation checklist, estimated time comparison (current vs. assisted), and warning signs of poor AI performance.

Task to redesign: [DESCRIBE THE SPECIFIC TASK IN DETAIL] 
Current time investment: [HOW LONG DOES IT TAKE NOW?] 
Quality requirements: [THE DEFINITION OF QUALITY AND EFFECTIVENESS] 
Frequency: [HOW OFTEN IS THIS TASK PERFORMED?] 
Acceptable error tolerance: [HOW MUCH ROOM FOR ERROR IS THERE?]
