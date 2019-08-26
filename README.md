Experimenting with Language Model outputs as Document Embeddings
================================================================

Document embeddings (like Doc2vec) provide a way to calculate document similarity by translating a document into a few-hundred-dimensional vector. With these vectors, you can calculate how similar two documents are with cosine similarity or other metrics.

This is really handy for exploring large documents, as we did at the [Quartz AI Studio for the Mauritius Leaks](https://qz.com/1670632/how-quartz-used-ai-to-help-reporters-search-the-mauritius-leaks/).

Fast.ai's transfer-learning approach to language modeling is really neat and we thought: could we make document embeddings from that?

We tried... but **it didn't work**.
