# Top Tips for Getting Better Responses from LLMs

## 1. **Be Explicit About Requirements**
- State your goal clearly:  
  *“I want to generate a Python script that reads a CSV and plots a graph.”*
- Mention constraints:  
  *“It must be compatible with Python 3.8, and use only built-in libraries.”*

## 2. **Request Strict Documentation Adherence**
- Paste or link the documentation:  
  *“Use only the methods described in [this API doc](https://example.com/api).”*
- Phrase your request:  
  *“Strictly follow the documentation at this link—do not invent any methods.”*

## 3. **Ask for Step-by-Step Reasoning or Pseudocode First**
- Before asking for code:  
  *“Explain your reasoning step by step.”*  
  *“Show pseudocode before generating real code.”*
- For debugging:  
  *“Describe potential causes before suggesting fixes.”*

## 4. **Break Your Question into Sub-Tasks**
- Example:  
  *“First, generate the function signature. Next, show an example input/output. Finally, write the implementation.”*
- This helps the model organize the response.

## 5. **Request Justification or Source for Each Suggestion**
- Ask:  
  *“Cite the documentation for each function you use.”*  
  *“Explain why you chose this approach.”*

## 6. **Specify the Output Format**
- For code:  
  *“Output only the code, no explanation.”*  
  *“Wrap the code in triple backticks.”*
- For lists or summaries:  
  *“Make a bullet-point list.”*  
  *“Present the answer in tabular form.”*

## 7. **Limit the Scope**
- Narrow the focus:  
  *“Focus only on error handling.”*  
  *“Show only the part of code that reads the file.”*

## 8. **Ask for Alternatives or Trade-Offs**
- Example:  
  *“Suggest two ways to do this, and compare their pros and cons.”*

## 9. **Use Iterative Refinement**
- Start broad, then narrow:  
  *“Now improve performance.”*  
  *“Make it more readable.”*  
  *“Add comments.”*

## 10. **Be Direct About What Not To Do**
- Example:  
  *“Do not use external libraries.”*  
  *“Don’t include code for user input.”*

---

## Sample Power Prompts

- “Generate code only using methods in [this documentation](https://example.com/docs). For each method, cite the line or section.”
- “Give me a step-by-step plan before writing the code. Only proceed to code after I confirm the plan.”
- “Summarize the main limitations of this approach.”
- “List all assumptions you are making in your answer.”
- “If you are unsure, say so and ask me for clarification before guessing.”

---

## General Advice

- **Treat the LLM like a junior developer:**  
  Give clear instructions, ask for justifications, and review their work.
- **Iterate:**  
  If the first answer isn’t perfect, clarify, narrow, or redirect.
- **Always verify outputs yourself:**  
  LLMs can be wrong, so double-check especially for code or domain-specific advice.

---
