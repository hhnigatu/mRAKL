# mRAKL: Multilingual Retrieval-Augmented Knowledge Graph Construction for Low-Resourced Languages.

### Code and Data for our ACL (Findings) 2025 paper.

Authors: **Hellina Hailu Nigatu,**  Min Li, Maartje ter Hoeve, Saloni Potdar, Sarah E. Chasins

[paper]()


Knowledge Graphs represent real-world entities and the relationships between them. Multilingual Knowledge Graph Construction ({\proj}) refers to the task of automatically constructing or predicting missing entities and links for knowledge graphs in a multilingual setting. In this work, we reformulate the mKGCC task as a Question Answering (QA) task and introduce mRAKL: a Retrieval-Augmented Generation (RAG) based system to perform mKGCC. We achieve this by using the head entity and linking relation in a question, and having our model predict the tail entity as an answer. Our experiments focus primarily on two low-resourced languages: Tigrinya and Amharic. We experiment with using higher-resourced languages Arabic and English for cross-lingual transfer. With a BM25 retriever, we find that the RAG-based approach improves performance over a no-context setting. Further, our ablation studies show that with an idealized retrieval system, {\system} improves accuracy by 4.92 and 8.79 percentage points for Tigrinya and Amharic, respectively.

