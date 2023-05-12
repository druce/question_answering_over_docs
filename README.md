# question_answering_over_docs
Question answering with ChatGPT and LlamaIndex and Langchain over your own docs

- qa.ipynb: Langchain

- qa_llama.ipynb: LlamaIndex and Pinecone for vector storage

- qa_llama-hf-chroma.ipynb: LlamaIndex, Chroma for local storage, and Huggingface model (runs slow)

- 10kAnalysis.ipynb: [LlamaIndex 10k example updated to reflect 0.6 refactor](https://betterprogramming.pub/llamaindex-deep-lake-for-financial-statement-analysis-954f2b789c8e
)

You can run 10k question answering in colab. I recommend forking the repo and then running a URL like https://colab.research.google.com/github/druce/question_answering_over_docs/blob/main/10kAnalysis_colab.ipynb (substitute your own GitHub account for 'druce'). You will need to provide your own API key from [OpenAI](https://platform.openai.com/).  You can run the URL shown above and it will pull the code from this repo. However if multiple people are running they will run on the same instance and I think that might cause problems and possibly expose API keys.
