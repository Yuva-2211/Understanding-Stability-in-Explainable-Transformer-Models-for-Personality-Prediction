# What Makes Personality Prediction Stable?
## An Explainable Transformer-Based Study

This repository provides the implementation for the research paper:

**“What Makes Personality Prediction Stable? An Explainable Transformer-Based Study”**

The project investigates personality trait prediction from conversational text using transformer-based language models, with an emphasis on **prediction stability**, **explainability**, and **robustness** beyond accuracy-centric evaluation.

---

##  Research Overview

Personality prediction from text has gained attention with the adoption of transformer models. However, existing work often focuses primarily on predictive accuracy, overlooking the **stability** and **reliability** of model behavior under linguistic variation.  
This work addresses this gap by combining:

- Multi-output regression for Big Five personality traits  
- Token-level explainability using SHAP  
- Robustness analysis via contextual and structural text perturbations  

The study demonstrates that stable personality predictions emerge from **distributed contextual representations**, rather than isolated lexical cues.

---

##  Key Features

- Transformer-based multi-output regression model (Big Five traits)
- Minimal text preprocessing to preserve conversational language
- SHAP-based token-level explainability
- Stability evaluation using:
  - Synonym-based contextual perturbations
  - Sentence-level structural perturbations


---

## Repository Structure

| Folder/File | Description |
| :--- | :--- |
| **model/** | Contains Model and config.yaml. |
| **results/** | Stores generated figures, plots, and evaluation metrics. |
| **src/** | Contains the main analysis and modeling workflow in `notebook.ipynb`. |
| **requirements.txt** | List of Python dependencies required to run the project. |

Here is the raw Markdown code for your README.md. You can copy and paste this directly into your file.

Markdown
# Project Name

A brief description of your project and what it aims to achieve.

---

##  Getting Started

1. Installation
Ensure you have Python installed. Clone this repository and install the dependencies:

`Bash`

`pip install -r requirements.txt`



2. Configuration
Before running the code, adjust the parameters in model/configs.yaml. This file allows you to change the model behavior (like learning rates or file paths) without touching the code.

3. Usage
Navigate to the src/ directory and open the notebook:

Bash
jupyter notebook src/notebook.ipynb

4.  Outputs
All visual outputs and performance summaries will be automatically saved to the results/ folder for easy access and reporting.

----

## Dataset

The dataset consists of conversational text from Reddit paired with continuous Big Five personality trait scores.
Due to privacy and licensing considerations, the dataset is not included in this repository.

----
## Ethical Notice

This project is intended for research purposes only.
Predicted personality traits reflect statistical patterns learned from text and do not constitute psychological or clinical assessments.
The models should not be used for high-stakes decision-making.

----
## Research Supervision

This research was conducted under the guidance of:

### Dr. R. Satyta Janaki
Department of Artificial Intelligence and Machine Learning
Takshashila University, Tamil Nadu, India

## Author

### Dhaipullay Yuva Shankar Narayana
Department of Artificial Intelligence and Machine Learning
Takshashila University, Tamil Nadu, India

----
## License

This repository is released for academic and research use.


---

