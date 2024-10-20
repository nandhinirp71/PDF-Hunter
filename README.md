# SemantiChunk

In this project, text is split into sentences that are converted vectors through an embedding model. Similarity is measured between each pair of consecutive sentences. If sentences are too similar, as defined by a threshold, additional chunks are created. We can ensure that if any two consecutive sentences are too different from one another, additional chunks can be created. In theory, this will allow us to achieve better results during retrieval within our RAG system.
