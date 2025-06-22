# Task 2: Prompt Design Experiment

## AI Model Used
GPT-4 (ChatGPT)

## Topic Chosen
**Quantum Entanglement** – a complex concept in quantum physics.

---

## Prompt Experiments

### 1. Zero-Shot Prompt

**Prompt:**  
Explain quantum entanglement.

**AI Response Summary:**  
Quantum entanglement is a phenomenon in which two particles become linked such that the state of one instantly determines the state of the other, even across large distances.

**Analysis:**  
-  Clear definition.
-  Lacks context, step-by-step reasoning, or analogies.

---

### 2. Few-Shot Prompt

**Prompt:**  
Here are examples of scientific explanations:  
1. *Photosynthesis is the process by which plants convert sunlight, water, and CO₂ into energy.*  
2. *Newton’s First Law states that an object in motion stays in motion unless acted upon by an external force.*  
Now, explain quantum entanglement.

**AI Response Summary:**  
Quantum entanglement occurs when two particles interact in a way that their states become dependent. Measuring one reveals information about the other, even when separated by large distances.

**Analysis:**  
-  Mimics the structure of examples.
-  Improves readability.
-  Still not deeply explanatory.

---

### 3. Chain-of-Thought Prompt

**Prompt:**  
Let’s reason step-by-step:  
1. What are quantum particles?  
2. How can two become related?  
3. What does it mean for their states to be linked?  
4. How does measurement affect one and the other?  
Now explain quantum entanglement.

**AI Response Summary:**  
Entangled particles share a state even when separated. If one is measured, the other's state is instantly known. This is due to their shared quantum system. It challenges classical physics and supports new technologies like quantum computing.

**Analysis:**  
-  Most detailed and pedagogical.
-  Supports gradual understanding.
-  Requires longer prompts.

---

## Conclusion

| Prompt Type       | Clarity | Depth | Ease of Use | Best Use Case                   |
|------------------|--------|-------|-------------|----------------------------------|
| Zero-Shot        | ★★★☆☆  | ★★☆☆☆ | ★★★★★      | Fast explanations                |
| Few-Shot         | ★★★★☆  | ★★★☆☆ | ★★★★☆      | General education                |
| Chain-of-Thought | ★★★★★  | ★★★★★ | ★★☆☆☆      | In-depth learning and reasoning  |

---

## Key Takeaways
- **Zero-shot** is great for speed but not depth.
- **Few-shot** improves tone and clarity through examples.
- **Chain-of-thought** excels in step-by-step logic and depth but needs well-crafted prompts.
