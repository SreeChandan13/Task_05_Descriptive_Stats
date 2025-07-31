# Task_05_Descriptive_Stats

## Project Overview
This project, "Research Task 5: Descriptive Statistics and Large Language Models," is an exploration of how Large Language Models (LLMs) like ChatGPT, Co-Pilot, or Claude handle and interpret data from a small public dataset. The core task is to provide a dataset to an LLM and challenge it to answer natural language questions about the data. The primary focus is not just on getting a correct answer, but on understanding the LLM's process, its limitations, and the prompt engineering required to achieve accurate results.

## Objectives
- To provide a large language model with a public dataset and ask it to answer natural language questions.
- To use prompt engineering to guide the LLM to correctly answer questions, particularly more probing ones that require defining a measure of quality.
- To validate the LLM's answers against the original dataset to ensure accuracy.
- To document the experience, including instances where the LLM failed, what prompts were used, and the nature of the failure.
- To explore the LLM's capability to produce visualizations directly from the data.

## Repository Contents
- `readme.md`: This file, providing an overview of the project.
- `prompts.txt`: A file containing the natural language questions asked of the LLM.

## How to Use
1.  **Obtain the Dataset:** Access the SU Women’s Lacrosse data (or a similar public dataset) from the source link.
2.  **Select an LLM:** Choose a large language model like ChatGPT, Co-Pilot, Gemini or Claud.
3.  **Prompt the LLM:** Copy the contents of the prompts file and interact with the LLM, providing the dataset and asking the questions.
4.  **Validate:** Use a separate script or your own manual analysis to validate the LLM's answers against the dataset.

## Summary of Findings
-   **Successes:** The LLM was generally successful in answering direct, factual questions that required simple data retrieval or calculations (e.g., total goals, overall record).
-   **Challenges:** The LLM struggled with more complex, probing questions. These required a defined measure of quality or an interpretive leap that the model could not make without explicit instructions. 

## Source Dataset
-   **Dataset:** Syracuse University Women’s Lacrosse, Combined Team Statistics (as of May 26, 2023)
-   **Link:** `https://s3.us-east-2.amazonaws.com/sidearm.nextgen.sites/suathletics.com/documents/2023/2/14/2023Stats.pdf?timestamp=20230527030432`
