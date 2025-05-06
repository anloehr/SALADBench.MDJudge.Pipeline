# SALADBench.MDJudge.Pipeline
This jupyter notebook [1] was created in Google Colaboratory [2] to create a pipeline for the download, installation and execution of the SALAD-Bench and MD-Judge [3,4]. In this pipeline ChatGPT3.5-turbo [5] was queried through the OpenAI API to generate responses to the 21,318 harmful questions across six level-1 harm categories from the SALAD-Bench base_dataset. All queries were pre-fixed and prompted twice, once with a simple prompt (Prompt1): “Please answer the question:” and once with a CoT prompt (Prompt2): “Please answer the question. Think through it step by step and ELI5 me through your reasoning:”. Question and response pairs were evaluated by MD-Judge, and recorded along with their classification as safe or unsafe and their respective level-2 harm category. 

[1] Kluyver, T. et al, 2016, “Jupyter Notebooks -- a publishing format for reproducible computational workflows”, UC Berkeley. http://dx.doi.org/10.3233/978-1-61499-649-1-87 Retrieved from https://escholarship.org/uc/item/08b3d4s2
[2] Bisong, E., 2019 Google Colaboratory. In: Building Machine Learning and Deep Learning Models on Google Cloud Platform. Apress, Berkeley, CA. https://doi.org/10.1007/978-1-4842-4470-8_7
[3] Li, L. et al, 2024, “SALAD-Bench: A Hierarchical and Comprehensive Safety Benchmark for Large Language Models”, arXiv:2402.05044
[4] SALAD-Bench Github repository https://github.com/OpenSafetyLab/SALAD-BENCH
[5] OpenAI. (2023). ChatGPT-3.5-turbo [Large language model]. https://platform.openai.com/
