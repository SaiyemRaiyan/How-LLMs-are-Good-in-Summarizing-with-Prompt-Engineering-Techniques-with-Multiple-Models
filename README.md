
# How LLMs are good in summarizing ft Prompt Engineering, RAG and Dspy

   ![1_VQmaXe3vWq-fL_t7aDmtfg](https://github.com/user-attachments/assets/86bb378d-d001-4257-90ad-9ffc77b34f4d)


This project aims to generate summaries from long text using LLM models and RAG prompt engineering technique. Initially, we tried the whole summarization process using Microsoft/phi-2 model. This model is a small LLM model and to generate better summary from this model we used RAG technique which helps the model to generate better summaries using vectors to relate context. We tried some other LLM models like llama, sentence-transformers/all-mpnet-base-v2, etc. LangChain & ChromaDB library used to generate the embedding or vector of the context. The project is tested with the meeting data (script) and CNN-Dailymail-News Dataset from Kaggle. The summaries are evaluated with readability scores from the renowned editors. The project evaluated some models to make a conclusion regarding these models.This project aims to create summaries from long texts using Large Language Models (LLMs) and the Retrieval Augmented Generation (RAG) technique. Initially, we used the Microsoft/phi-2 model, a smaller LLM, to summarize the text. However, to improve the quality of the summaries, we applied the RAG technique, which enhances the model's performance by using vectors to better understand and relate to the context of the text.
We also experimented with other LLM models, such as Llama and sentence-transformers/all-mpnet-base-v2, to see how they performed in summarization tasks. To generate the vectors (or embeddings) that represent the context, we used the LangChain and ChromaDB libraries, and dspy techniques.
                      ![image](https://github.com/user-attachments/assets/0a0a0d68-be5e-4c05-808a-3733b321e2f5)


The project was tested using meeting transcripts and the CNN-Dailymail-News dataset from Kaggle. We evaluated the summaries using readability scores from well-known text editors. By comparing the performance of different models, we aimed to draw conclusions about their effectiveness in summarization tasks.
    ![image](https://github.com/user-attachments/assets/8fa891bc-1f0b-43c9-b080-6e972b90c034)


   ![Results Comparison Picture](https://github.com/user-attachments/assets/68d3747f-090e-49f4-a314-5908ce096036)
