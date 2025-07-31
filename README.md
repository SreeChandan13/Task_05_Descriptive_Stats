# Task_05_Descriptive_Stats

## Project Overview
[cite_start]This project, "Research Task 5: Descriptive Statistics and Large Language Models," is an exploration of how Large Language Models (LLMs) like ChatGPT, Co-Pilot, or Claude handle and interpret data from a small public dataset[cite: 4]. [cite_start]The core task is to provide a dataset to an LLM and challenge it to answer natural language questions about the data[cite: 4]. [cite_start]The primary focus is not just on getting a correct answer, but on understanding the LLM's process, its limitations, and the prompt engineering required to achieve accurate results[cite: 10, 16, 17].

## Objectives
- [cite_start]To provide a large language model with a public dataset and ask it to answer natural language questions[cite: 4].
- [cite_start]To use prompt engineering to guide the LLM to correctly answer questions, particularly more probing ones that require defining a measure of quality[cite: 10, 12, 13].
- [cite_start]To validate the LLM's answers against the original dataset to ensure accuracy[cite: 13].
- [cite_start]To document the experience, including instances where the LLM failed, what prompts were used, and the nature of the failure[cite: 17].
- [cite_start]To explore the LLM's capability to produce visualizations directly from the data[cite: 21].

## Repository Contents
- `readme.md`: This file, providing an overview of the project.
- `prompts.txt`: A file containing the natural language questions asked of the LLM.
- `scripts/`: A directory that may contain scripts for generating basic statistics for validation purposes.
- `findings.md`: A summary of the interactions with the LLM, including its responses, an analysis of its successes and failures, and any visualizations it produced.
- [cite_start]**Note:** The original dataset file should **not** be included in this repository[cite: 28].

## How to Use
1.  [cite_start]**Obtain the Dataset:** Access the SU Women’s Lacrosse data (or a similar public dataset) from the source link[cite: 5, 6, 8].
2.  [cite_start]**Select an LLM:** Choose a large language model like ChatGPT, Co-Pilot, or Claud[cite: 4].
3.  **Prompt the LLM:** Copy the contents of the prompts file and interact with the LLM, providing the dataset and asking the questions.
4.  **Document Findings:** Record the LLM's responses and your analysis in a `findings.md` file. [cite_start]Document what worked, what failed, and the prompt engineering techniques you used[cite: 16, 17].
5.  [cite_start]**Validate:** Use a separate script or your own manual analysis to validate the LLM's answers against the dataset[cite: 13, 14].

## Summary of Findings
_This section is a placeholder to be filled out after completing the research task. It will include a detailed account of the LLM's performance, highlighting its ability to handle straightforward statistical queries versus its struggles with complex, interpretive questions._

-   **Successes:** The LLM was generally successful in answering direct, factual questions that required simple data retrieval or calculations (e.g., total goals, overall record).
-   **Challenges:** The LLM struggled with more complex, probing questions. [cite_start]These required a defined measure of quality or an interpretive leap that the model could not make without explicit instructions[cite: 12, 13, 20]. [cite_start]For example, questions like "Who was the most improved player?" or making causal recommendations based on the data proved difficult[cite: 12, 19].
-   **Visualizations:** The LLM's ability to produce visualizations was... _(To be completed based on your findings)_.

## Source Dataset
-   **Dataset:** Syracuse University Women’s Lacrosse, Combined Team Statistics (as of May 26, 2023)
-   **Link:** `https://s3.us-east-2.amazonaws.com/sidearm.nextgen.sites/suathletics.com/documents/2023/2/14/2023Stats.pdf?timestamp=20230527030432`
