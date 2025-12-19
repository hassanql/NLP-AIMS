# SemEval-2026 Task 9: Data-Centric Polarization Detection (POLAR)

This repository contains the implementation for our submission to **SemEval-2026 Task 9**. The project focuses on detecting and classifying socio-political polarization in text across three levels of granularity for both English and Arabic.

##  Global Rankings
* **1st Place Globally**: Arabic Manifestation Identification (Subtask 3)
* **2nd Place Globally**: Arabic Type Classification (Subtask 2)
* **3rd Place Globally**: English Type Classification (Subtask 2)
* **3rd Place Globally**: English Manifestation Identification (Subtask 3)

---

##  Repository Structure

The notebooks are organized by task and language. Each notebook includes the preprocessing, training, and evaluation steps used in the competition.

### Subtask 1: Binary Polarization Detection
*Goal: Distinguishing polarized content from neutral text.*
* **subtask_1_en.ipynb**: Final implementation for English binary classification.
* **subtask_1_ar.ipynb**: Final implementation for Arabic binary classification.
* **subtask_1_synthetic_data_generation.ipynb**: Code used to generate synthetic training data via LLMs for this task.

### Subtask 2: Polarization Type Classification
*Goal: Multi-label classification of polarization topics (Political, Racial, Religious, etc.).*
* **subtask_2_en.ipynb**: Final implementation for English multi-label type classification.
* **subtask_2_ar.ipynb**: Final implementation for Arabic multi-label type classification.
* **subtask_2_synthetic_data_generation.ipynb**: Code used to generate synthetic training data for the type classification task.

### Subtask 3: Manifestation Identification
*Goal: Identifying rhetorical strategies (Vilification, Dehumanization, Lack of Empathy, etc.).*
* **subtask_3_en.ipynb**: Final implementation for English rhetorical manifestation identification.
* **subtask_3_ar.ipynb**: **[1st Place Solution]** Final implementation for Arabic rhetorical manifestation identification.
* **subtask_3_en_failed_attempts.ipynb**: A record of experimental architectures and configurations for English Subtask 3 that were tested but not used in the final submission.

---

## Environment & Usage
These notebooks are intended to be run in a GPU-accelerated environment (e.g., Google Colab). 
* **Frameworks**: PyTorch, Transformers (Hugging Face), Scikit-learn.
* **Hardware**: Tested on NVIDIA T4 GPU

