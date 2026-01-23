# LLM System Design – DeepLearning.AI Course Labs

This repository contains my completed labs from a DeepLearning.AI short course on designing and evaluating LLM-powered applications (taught by Andrew Ng and team).

The goal of these labs was to move beyond simple prompting and learn how to build **reliable, safe, and evaluable** LLM systems.

## What I implemented

Across the notebooks, I worked on:

- **Tokenization & LLM behavior**
  - Explored how tokenization affects model behavior (e.g., why it struggles to reverse certain words like "lollipop").
- **Prompting & chain-of-thought**
  - Used chain-of-thought reasoning to improve intermediate reasoning steps.
  - Split complex tasks into subtasks using **chain prompts**.
- **Safety & input/output checks**
  - Evaluated user inputs for quality and safety.
  - Added guardrails to check and filter model outputs before returning them to users.
- **Evaluation & monitoring**
  - Set up simple evaluation pipelines for LLM responses.
  - Monitored system performance over time and iterated on prompts and settings.

## Notebooks

All course notebooks are under `notebooks/`:

- `L1_tokenization.ipynb` – tokenization and basic LLM behavior
- `L2_prompting.ipynb` – basic prompting strategies
- `L3_chain_of_thought.ipynb` – chain-of-thought reasoning
- `L4_task_decomposition.ipynb` – splitting tasks into subtasks with chain prompts
- `L5_safety_and_moderation.ipynb` – basic safety and content checks
- `L6_evaluation.ipynb` – evaluating LLM outputs
- `L7_monitoring.ipynb` – monitoring system performance over time
- `L8_improving_prompts.ipynb` – prompt iteration and refinement
- `L9_capstone.ipynb` – combining the above into a small end‑to‑end system
- `L10_custom_prompt_evaluation.ipynb` – **my own extension**: comparing different prompt strategies (directive, structured, few-shot, chain-of-thought) using a custom evaluation rubric

## How this fits my profile

This course complements my work in:

- **ML & DL:** Python, PyTorch, TensorFlow, computer vision (YOLO, OpenCV)
- **LLM systems:** designing prompts, safety checks, evaluation and monitoring
- **Applied AI:** building systems that are not just "clever prompts" but reliable applications

I plan to build on these labs in my own projects by:
- Adding custom evaluation metrics,
- Integrating LLM chains into small demo apps,
- Combining LLM components with my existing CV and ML pipelines.

---

> Note: These labs are based on DeepLearning.AI's course materials. This repo is for educational purposes only.
