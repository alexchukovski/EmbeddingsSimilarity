This is a jypiter notebook that can be used to get embeddings using OpenAI for a string and then get the top K similar candidates for each string.
The input is a CSV file where at least one column has to be the text you want to get the embeddings for.
The outputs are two:
1) Numpy file with the generated embeddings
2) CSV with the original data and five columns with the top 5 similar entries.
