# GitHub Classroom AI Grader
After students completed their test or exercise, sometimes teachers must review it one by one and give them the mark. The unit test approach does not work if students cannot submit the runnable code, so it is better to use AI to access their answers and give the objective mark to them.
Using Large Language modle including Azure Open AI and Google Cloud Vertex AI to score and comment programming practical test.

## How to use it?

1. Fork this repo and Create a CodeSpace.
2. Open extract_answer.ipynb and update the first cell. The output will be student_answer.xlsx which will check any student submit commit codes after the deadline.
3. update the .env for Azure Open AI.
4. Run gcp_vertex_ai_grader.ipynb and azure_openai_grader.ipynb and please follow the notebook instruction.
5. Run human_review.ipynb and it generates the excel for human review as LLM must not always 100% correct.
6. Upload the GitHub.xlsx for student ID and GitHub Repo name mapping, run generate_score_report.ipynb.
