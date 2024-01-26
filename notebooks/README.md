Goal of the project
Thanks to this project I had the opportunity to try some open-source llms such as mistral and llama2. The challenge was to check their prediction capabilities, though we know they are optimized more for reasoning tasks rather than database consulting tasks. I managed to play with different prompt engineering techniques and to generate some improvements from the naive attempts.


Folders of the project
* data: contains the questions-answers used with the models.

* notebooks:
    - Creating_questions_dataset: to prepare the dataset for the initial test
    - Collecting_model_responses: script to get the answers from the models
    - Analyzing_model_responses: evaluation of the responses of the initial test
    - Prompt_optimization: which techniques I tried to improved results
    - RAG_optimization: code used to improve results with mistral.
    - Fine_tuning_models: step-by-step explanation on how to perform fine-tuning of the models.
