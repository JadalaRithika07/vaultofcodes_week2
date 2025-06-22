# Task 1: Advanced Prompt Engineering Techniques

## Introduction
Prompt engineering involves crafting inputs (prompts) to guide the behavior and output of AI language models like GPT-3.5 and GPT-4. This task explores three key techniques used to enhance the model's performance: **Zero-Shot**, **Few-Shot**, and **Chain-of-Thought** prompting.

---

## 1. Zero-Shot Prompting

###  Definition
Zero-shot prompting refers to giving the AI a task **without any examples** — the model must rely entirely on its pretraining knowledge.

###  Example
**Prompt:**  
> "Translate the following English sentence into French: 'I am learning AI.'"

**AI Output:**  
> "J'apprends l'intelligence artificielle."

###  Applications
- Quick fact retrieval
- Language translation
- Summarization
- Straightforward tasks with well-defined outcomes

###  Limitations
- May misinterpret ambiguous tasks
- Less effective for multi-step reasoning or novel formats

---

## 2. Few-Shot Prompting

###  Definition
Few-shot prompting includes **a few relevant examples** in the prompt to show the AI how to respond to a specific task.

###  Example
**Prompt:**
> Q: What is the capital of France?  
> A: Paris  
> Q: What is the capital of Germany?  
> A: Berlin  
> Q: What is the capital of Italy?  
> A:

**AI Output:**  
> Rome

###  Applications
- Custom formatting
- Domain-specific tasks
- Mimicking writing style or tone

###  Limitations
- Prompt length constraints
- Requires carefully chosen examples

---

## 3. Chain-of-Thought Prompting

###  Definition
Chain-of-thought (CoT) prompting involves adding **step-by-step reasoning** in the prompt to help the AI solve complex problems or explain its answers.

###  Example
**Prompt:**  
> "If there are 3 apples and you eat 1, how many are left? Let's think step by step."

**AI Output:**  
> "There were 3 apples. You ate 1. 3 - 1 = 2 apples are left."

###  Applications
- Math and logic problems
- Scientific explanations
- Legal or multi-step decision-making

###  Limitations
- Requires verbose prompts
- Can generate unnecessary or incorrect steps if not well-structured

---

## Conclusion

| Technique           | Best For                        | Strengths                          | Weaknesses                        |
|--------------------|----------------------------------|------------------------------------|-----------------------------------|
| Zero-Shot Prompting | Quick tasks, general knowledge  | Simple, fast                       | Lacks context, prone to errors    |
| Few-Shot Prompting  | Pattern-specific tasks          | Customizable, controls output style| Requires careful example crafting |
| Chain-of-Thought    | Complex reasoning, explanations | Deep understanding, stepwise logic | Long prompts, may over-explain    |

These techniques are foundational tools in prompt engineering that enable more accurate, context-aware, and reliable interactions with large language models.

