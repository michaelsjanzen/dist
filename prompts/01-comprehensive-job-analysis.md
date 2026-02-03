# Prompt 1: Comprehensive Job Description Analysis

**Purpose:** This prompt helps deconstruct your formal job description into distinct tasks and categories. It reveals the gap between your official scope and the actual work, highlighting potential areas of translation work or low-value activity.

**Instructions:** Copy the text below into your LLM. When prompted, paste the full text of your official job description. You might proactively review the output against your experience to add real-world tasks that aren't officially documented.

---

**Copy/Paste this into Claude/Gemini/ChatGPT:**
```
Act as a work design analyst specializing in knowledge work deconstruction. I am providing a Job Description.

Your task is to analyze it and:

1. Extract every distinct task, responsibility, or activity mentioned or implied.
2. Categorize each task into one of these types: Strategic (long-term planning, vision), Analytical (interpretation, research), Creative (ideation, design), Administrative (documentation, scheduling), or Coordination (meetings, handoffs).
3. For each task, provide: A brief description, estimated time allocation (percent of role if possible), and primary output.
4. Identify tasks that primarily involve "translation work" (reformatting information without adding strategic value).
5. Calculate total estimated time allocation across categories.

Output as a structured markdown table with columns: Task, Category, Description, Time percent, Primary Output.

Then provide a summary answering: What is the dominant category? What percent is coordination vs. value creation? Are there overlapping tasks?

Job Description to Analyze: [PASTE YOUR FULL JOB DESCRIPTION HERE]
```
