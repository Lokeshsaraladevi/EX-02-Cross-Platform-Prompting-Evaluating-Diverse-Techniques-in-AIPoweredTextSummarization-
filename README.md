# EX-02: Cross-Platform Prompting – Evaluating Diverse Techniques in AI-Powered Text Summarization

## Overview

This project evaluates the effectiveness of different prompting techniques across multiple AI platforms for the task of technical text summarization. The experiment compares how various large language models (LLMs) generate summaries of a research article on **"The Basics of Blockchain Technology"** using different prompt engineering strategies.

The objective is to identify which combination of AI platform and prompting technique produces the most accurate, coherent, and student-friendly summaries for undergraduate learners.

---

## Aim

To evaluate and compare the effectiveness of prompting techniques:

- Zero-Shot Prompting
- Few-Shot Prompting
- Chain-of-Thought Prompting
- Role-Based Prompting

across different AI platforms:

- ChatGPT
- Google Gemini
- Claude
- Microsoft Copilot

for the task of text summarization.

---

## Scenario

As a member of an educational content curation team, the objective is to summarize a technical research article on **Blockchain Technology** into concise, easy-to-understand summaries suitable for undergraduate students.

Each AI platform receives the same article but with different prompting strategies, and the generated summaries are evaluated based on quality and usability.

---

## Prompting Techniques Evaluated

### 1. Zero-Shot Prompting
The model is asked to summarize the article without any examples or additional guidance.

### 2. Few-Shot Prompting
The model is provided with example summaries before generating the final summary.

### 3. Chain-of-Thought Prompting
The model is encouraged to reason step-by-step before producing the final summary.

### 4. Role-Based Prompting
The model is assigned the role of a professional educational content curator to generate a student-friendly summary.

---

## AI Platforms Compared

- ChatGPT
- Google Gemini
- Claude
- Microsoft Copilot

---

## Evaluation Criteria

Each generated summary was evaluated using the following metrics:

- Accuracy
- Coherence
- Simplicity
- Response Speed
- User Experience (UX)

Scores were assigned on a 5-point scale.

---

## Results Summary

| Prompting Technique | Best Performing Platform | Average Score |
|--------------------|--------------------------|--------------|
| Zero-Shot | ChatGPT | **4.4 / 5** |
| Few-Shot | ChatGPT | **4.4 / 5** |
| Chain-of-Thought | ChatGPT | **4.6 / 5** |
| Role-Based | ChatGPT | **4.6 / 5** |

---

## Overall Findings

- **ChatGPT** consistently produced the most accurate, coherent, and student-friendly summaries.
- **Microsoft Copilot** ranked second with clear and readable responses.
- **Google Gemini** generated technically correct summaries but tended to use a textbook-style approach.
- **Claude** provided detailed and research-focused summaries but often included critical analysis, making them less suitable for undergraduate learners.

Among the prompting techniques:

- **Role-Based Prompting** produced the most engaging and simplified summaries.
- **Chain-of-Thought Prompting** generated the most detailed and logically structured responses.
- **Few-Shot Prompting** improved consistency compared to Zero-Shot prompting.
- **Zero-Shot Prompting** delivered satisfactory summaries with minimal prompt engineering.

---

## Technologies Used

- ChatGPT
- Google Gemini
- Claude AI
- Microsoft Copilot
- Markdown
- GitHub

---

## Repository Structure

```
EX-02-Cross-Platform-Prompting/
│
├── README.md
├── Experiment_Report.pdf
├── Prompt_Outputs/
│   ├── Zero_Shot.md
│   ├── Few_Shot.md
│   ├── Chain_of_Thought.md
│   └── Role_Based.md
└── Evaluation_Tables.md
```

---

## Learning Outcomes

After completing this experiment, learners will be able to:

- Understand different prompt engineering techniques.
- Compare responses from multiple AI platforms.
- Evaluate AI-generated summaries using standard quality metrics.
- Identify suitable prompting strategies for educational content generation.
- Analyze the strengths and limitations of modern large language models.

---

## Conclusion

This experiment demonstrates that prompt engineering significantly influences the quality of AI-generated summaries. While all four AI platforms successfully summarized the blockchain article, **ChatGPT consistently achieved the highest overall performance**, particularly when using **Role-Based** and **Chain-of-Thought Prompting**. These techniques produced summaries that were accurate, well-structured, easy to understand, and highly suitable for undergraduate students. The study highlights the importance of selecting the right prompting strategy to maximize the effectiveness of AI-powered text summarization.

---

## Author

**Name:** Lokesh S

**Register Number:** 212224060134

---
