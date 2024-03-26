# Egogram Test using Large Language Models

This repository contains a Python notebook (`LLM_Based_Egogram_test.ipynb`) for conducting an egogram test using **Gemini** large language model (LLM). The test is designed to determine the egogram (child, adult, parent) of an individual based on their responses to a set of questions related to emotions, personality traits, and hypothetical situations.

## Requirements

To run the notebook, ensure you have the following dependencies installed:
- `langchain`
- `langchain-google-genai`
  
You can install them using pip:

```bash
pip install -q -U langchain
pip install -q langchain-google-genai
```

Additionally, you need a Google API Key, which will be used for the language model. The key will be prompted when running the notebook.

## Overview

The notebook consists of the following components:

### Prompts

- **Initial Task Prompt**: This prompt asks the user to generate a set of questions for the egogram test. The questions should be formatted with a numbering system (e.g., Q1, Q2, ..., Q20) and must cover emotions, personality traits, and hypothetical situations.
- **Welcome Message**: This message welcomes the user and provides instructions on how to answer the questions.
- **Results Prompt**: This prompt is used to display the results of the egogram test. It provides guidelines on interpreting the results and formatting the output.

### Functions

- **generate_questions**: Generates a set of questions for the egogram test based on the specified number of questions.
- **show_results**: Displays the results of the egogram test based on the user's answers to the questions.
- **main_test**: Executes the entire egogram test process, including generating questions, collecting user responses, and displaying the results as a pie chart.

## Usage

1. Open the notebook (`LLM_Based_Egogram_test.ipynb`) in a Jupyter environment.
2. Run the notebook cells sequentially.
3. Follow the prompts to generate questions, answer them, and view the results.

## Note

- Ensure you have a stable internet connection while running the notebook, as it relies on a language model hosted externally.
- The results of the egogram test are presented as a pie chart, visualizing the distribution of child, adult, and parent egos based on the user's responses.

Feel free to use and modify this notebook for conducting egogram tests or similar applications. If you encounter any issues or have suggestions for improvements, please feel free to contribute to the repository. Happy testing!
