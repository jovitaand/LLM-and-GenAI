# Project Title: Leveraging NotebookLM for Ethical AI Analysis

This repository contains a Jupyter Notebook that explores the capabilities of Google's NotebookLM in analyzing ethical considerations within AI applications. Specifically, we focus on NotebookLM's strengths and limitations in examining issues like statistical bias and societal impacts in AI systems, using ProPublica's "Machine Bias" article as a case study.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Strengths and Limitations](#strengths-and-limitations)
- [Example Case Study](#example-case-study)
- [Contributing](#contributing)
- [License](#license)

## Overview
NotebookLM is a tool developed by Google that enables users to interact with structured data, articles, and even videos to extract and infer insights. This project aims to investigate NotebookLM's utility in evaluating AI's ethical dimensions, particularly in detecting issues like bias and autonomy, and in assessing the transparency of machine learning systems.

## Features
- **Information Retrieval:** Extracts key points from structured information and provides high-level summaries of complex topics.
- **Contextual Understanding:** Demonstrates contextual comprehension, making it useful for initial reviews or brief explanations of AI ethics.
- **Reflective Insights:** Highlights the limitations of AI models in understanding nuanced ethical debates and the need for human oversight.

## Installation
To run this project, you will need to install the required libraries. Clone the repository and run:

```bash
pip install -r requirements.txt
```
> **Note:** You may need access to Google's NotebookLM, as this project uses its platform for inference.

## Usage
1. Clone the repository.
2. Install the required dependencies.
3. Run the `Coding_Lab3.ipynb` notebook in a Jupyter environment. This notebook demonstrates the interaction with NotebookLM and provides commentary on the ethical considerations and insights generated.

## Strengths and Limitations
This project reveals both the potential and limitations of NotebookLM when dealing with ethical AI topics.

- **Nuance in Ethical Debate:** While NotebookLM can identify statistical bias in AI systems, it struggles to explore deeper social implications without further prompt-specific training. It tends to miss the subtle ethical aspects unless specifically guided.

- **Complex Reasoning:** The model excels at retrieving facts but has limitations in reasoning through contentious or subjective topics. While it handles information recall well, it may fall short in engaging with advanced ethical reasoning.

## Example Case Study: "Machine Bias"
Using ProPublica's ["Machine Bias"](https://www.propublica.org/article/machine-bias-risk-assessments-in-criminal-sentencing) as a case study, this project demonstrates how NotebookLM processes and interprets issues related to bias in machine learning models used for risk assessments. The notebook includes reflections on the model's ability to identify statistical biases while also noting areas where it requires additional input to capture social and ethical nuances.

## Contributing
Contributions are welcome! Please open an issue first to discuss what you would like to change. For significant changes, please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more information.

