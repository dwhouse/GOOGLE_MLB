# Google Machine Learning Bootcamp 2024
This repository is about the project “Gemma Sprint” that I worked on while participating in the Google Machine Learning Bootcamp. I will upload my fine-tuning of the Gemma2-2b-it model.

1. Project Title : Research in a Flash: fine-tuning gemma for paper summerization
2. Project Description : This project aims to leverage the power if the Gemma 2b model to create a specialized tool for academic paper summarization. By fine-tuning Gemma on a carefully curated dataset of scientific articles and their corresponding abstracts, we'll develop a model capable of distilling complex academic content into concise, informative summaries. This tool will assist researchers, students, and academics by providing quick insights into extensive research papers, saving time and effort in literature reviews and study preparation. The model will be implemented using Hugging Face's Transformers library and will be optimized for deployment on various platforms, making it accessible for desktop and cloud environments. By focusing on key domains such as medicine, computer science, and social sciences, the project will ensure that the summerization model is versatile and applicable across a wide range of academic fields.
3. Cause of gpu allocation and due-date issue, I had no choice but to sample 10,000 out of the 290,000 or so pieces of data I had and run the training.
4. With 8bit quantization and fine-tuning with qLoRA, I think it was a valuable experience to organize how to deal with the LLM model.

5. https://huggingface.co/dwhouse/gemma-2-2b-it-research-in-a-flash
6. https://colab.research.google.com/drive/1xiyWCnTzXmFFgD7CBL-jq8m2Mv29fg-M?usp=sharing

#GemmaSprint
