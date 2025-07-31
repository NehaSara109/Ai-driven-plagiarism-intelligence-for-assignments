# AI-Driven Plagiarism Checker for Assignments

This project is an intelligent, context-aware plagiarism detection tool developed using IBM Watsonx.ai Studio and the Granite Foundation Model. It helps academic institutions detect AI-generated or paraphrased assignments by analyzing submissions against historical student work and simulated instructor feedback.

---

## Problem Statement

Academic institutions face increasing difficulty in detecting nuanced forms of plagiarism, especially when assignments are paraphrased or generated using AI tools. This project solves the challenge by using an adaptive AI system that:

- Compares new submissions with historical assignments
- Simulates instructor reasoning to identify context mismatches
- Flags potential misconduct dynamically

---

## Features

- Upload and compare new assignment submissions
- Analyze against 3–5 historical student assignments
- Simulate instructor-style feedback using Granite LLM
- Flag suspicious content with reasoning
- Built using free IBM Cloud Lite services

---

## Technology Stack

| Tool/Service              | Purpose                                      |
|---------------------------|----------------------------------------------|
| IBM Watsonx.ai            | AI studio to run code and prompts            |
| Granite-13b-instruct-v2   | Large Language Model for reasoning           |
| Python 3.11               | Notebook runtime                             |
| Jupyter Notebook (.ipynb) | Code execution and result logging            |

---

## File Structure

- Granite_AI_Plagiarism_Checker.ipynb: Main notebook with code, prompts, and results
- README.md: Project description and usage guide

---

## How to Use

1. Open the notebook (.ipynb) in:
   - IBM Watsonx.ai Studio (recommended)
   - Google Colab or Jupyter Notebook (alternative)

2. Modify the past_submissions and new_submission variables with actual assignments

3. Run the notebook to get:
   - Match comparison results
   - Instructor-style explanation
   - Final suspicious/not suspicious verdict

---

## Requirements

- IBM Cloud account (Lite plan is free)
- Watsonx.ai project with granite-13b-instruct-v2 model

---

## Acknowledgements

- IBM Watsonx.ai for platform and model access
- IBM Granite Foundation Models for language understanding
