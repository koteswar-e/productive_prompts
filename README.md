# Productive Prompts
-- Prompt Engineering redefined

# 💡 Socratic Mentor Prompt for Algorithm Problem Solving

This prompt is designed to turn an AI into a **non-answering Socratic mentor** for a coding problem (like those on LeetCode). The goal is to facilitate the user's independent discovery of the solution by providing validation for correct ideas and challenging flawed assumptions through targeted questions. The mentor **never** gives the solution or explicit steps.

---


### 🌟 General-Purpose Socratic Mentor Prompt: Refining Thinking

You are a supportive, non-answering mentor for the user as they solve the following LeetCode problem. Your sole goal is to facilitate the user's independent discovery of the solution by validating their correct thinking and challenging their flawed assumptions. The user must perform all logic, indexing, and coding themselves.

### 🚫 Core Constraints & Non-Negotiables

* **NO ANSWERS:** DO NOT provide the final code, the full function body, the explicit algorithm steps, or any specific formulas (e.g., index calculations, recurrence relations).
* **MANDATE: Socratic Method:** Your primary response mechanism for any user-proposed logic must be a **targeted question** that forces the user to identify and fix their own mistake or deepen their understanding. Never state the correct next step or piece of logic.
* **MANDATE: Analysis on Request:** You will only analyze or correct syntax/implementation errors (in code or pseudocode) when the user explicitly submits a draft and requests a review.

--+++--++++++----++++++---++++++++---+++++---

Here's the prompt formatted for direct paste into a markdown file:


# Prompt for NotebookLM

Analyze the uploaded book/PDF and apply the Pareto Principle (80/20 rule) to extract the most impactful and actionable insights. Focus on identifying the 20% of concepts that will deliver 80% of the results.

Please provide:

## 1. Complete Executive Summary
Provide a comprehensive summary of the entire book covering:
- The author's main thesis and purpose
- Key arguments and supporting evidence presented
- The structure and flow of ideas throughout the book
- Major conclusions and takeaways
- Overall context and significance of the work

(This should be thorough enough to understand the full scope of the book, not just a few sentences)

## 2. Top Actionable Tips & Tricks (ONLY from the uploaded source)
Extract 5-10 immediately implementable strategies, techniques, or practices directly from this book. For each tip:
- Provide a clear, specific action step as described in the book
- Explain WHY it matters according to the author
- Include direct references, quotes, and page numbers from the book
- Give the EXACT examples and case studies mentioned in the book showing how this was applied
- DO NOT add external examples - use only what's in the uploaded document

## 3. High-Impact Concepts (with source references)
Identify the 3-5 most critical ideas or frameworks from the book that represent the core 20% of content delivering 80% of value. For each:
- Provide a detailed explanation as presented in the book
- Cite specific passages, examples, and page numbers from the book
- Include the author's own practical application advice from the text
- Reference any frameworks, models, or systems exactly as described in the source

## 4. Practical Implementation Plans (sourced from the book)
Create step-by-step action plans based solely on the guidance provided in the uploaded book:
- Daily actions recommended by the author
- Weekly practices mentioned in the text
- Monthly goals suggested in the book
- Include specific chapter/page references for each recommendation

## 5. Quick Wins (from the source)
List 5-7 things I can do TODAY or THIS WEEK based exclusively on the book's teachings:
- Each must be directly stated or clearly implied in the book
- Include exact page numbers and quotes supporting each quick win
- Reference the specific examples or case studies from the book that demonstrate these wins

## 6. Real Examples & Case Studies (from the uploaded document)
Summarize all the key examples, case studies, stories, and real-world applications that the author includes in the book:
- Who was involved
- What they did
- What results they achieved
- Page numbers and chapter locations

## 7. Key Quotes & References
Provide 10-15 of the most powerful, memorable quotes from the book with exact page numbers/locations and context for each quote

## 8. Chapter-by-Chapter Actionable Breakdown
For each major chapter or section:
- Main concept covered
- Key actionable takeaway
- Specific page references

---

**CRITICAL REQUIREMENT**: Every tip, example, practical plan, and piece of advice must come directly from the uploaded source. Do not add external information, general knowledge, or examples from other sources. If the book doesn't provide certain types of information, clearly state that rather than supplementing with external content.

Format everything for easy scanning and implementation. Prioritize practical application based on what the author specifically recommends. Always include specific references (page numbers, chapter names, or direct quotes) to support each point so I can verify and dive deeper if needed.
