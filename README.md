# -Advanced-Prompt-Engineering-Techniques-using-large-language-models-such-as-GPT-3.5-and-GPT-4.

This repository contains my analysis and experimentation on Advanced Prompt Engineering Techniques using large language models such as GPT-3.5 and GPT-4.

 Task 1: Research and Summarize
In this task, I explored three advanced prompting strategies used in modern language models:
1.Zero-shot Prompting
2.Few-shot Prompting
3.Chain-of-Thought Prompting

Task 2: Design and Experiment
Objective:
Test and compare the performance of zero-shot, few-shot, and chain-of-thought prompting strategies on a math word problem.

Prompt Topic:
“A train travels 60 miles in 1.5 hours. What is its average speed?”
Prompt Variants and Observations:
Zero-shot Prompt:

Direct question. The model often gives the correct answer but doesn't explain the process.

✅ Fast but ❌ lacks transparency.

Few-shot Prompt:

Provides examples of similar problems before the question.

✅ Accurate with format consistency, but ❌ doesn’t explain steps.

Chain-of-Thought Prompt:

Prompts the model to explain its reasoning step by step.

✅ Most effective for logic clarity and learning use cases.

📊 Conclusion
Prompt Type	Accuracy	Reasoning	Best For
Zero-shot	Medium	❌	Common/straightforward tasks
Few-shot	High	❌	Format-based consistency
Chain-of-Thought	High	✅	Reasoning, math, explanations
