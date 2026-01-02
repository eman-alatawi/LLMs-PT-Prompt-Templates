# Prompt Templates for LLM Behavioral Evaluation

This repository contains the generalized prompt templates developed to evaluate **Large Language Model (LLM) behavior** in autonomous and semi-autonomous penetration testing (PT) workflows.

These templates were designed and validated during **Phase I: Prompt Engineering Research and LLM Behavioral Evaluation** and are referenced in the associated research paper.

---

## Available Prompt Templates

### 1. Structured Reasoning Prompt Template

**File:** `structured_prompt.txt`

This template enforces strict task decomposition, explicit behavioral constraints, and structured (JSON) outputs to ensure reproducibility and deterministic orchestration.


### 2. Reflective Adaptive Prompt Style

**File:** `reflective_prompt.txt`

This prompt emphasizes self-evaluation, error detection, and corrective reasoning to improve robustness in long-horizon execution sequences.


### 3. Interactive Role-Dialogue Prompt Style

**File:** `interactive_prompt.txt`

This template improves interpretability through a mentor–apprentice dialogue model and is suitable for Human-in-the-Loop (HITL) or training-oriented workflows.


### 4. Benchmark-Oriented Evaluation Prompt Style

**File:** `benchmark_prompt.txt`

This prompt is designed for structured experimentation and cross-model comparison by enforcing standardized logging and step-by-step execution records.

