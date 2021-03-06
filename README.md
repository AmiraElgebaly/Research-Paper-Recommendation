# Research-Paper-Recommendation
### Problem formulation
Researchers spend a lot of their time reading scientific papers. Finding the right papers is a time-
consuming process, since it requires skimming through many irrelevant papers until the right one
is found. To reduce the time required to achieve this task, we aim to develop a research paper
search engine, where the user can use a certain paper as a query, and the system returns the top
most similar papers.

### Methodology
First of all, we construct a database of scientific papers from different disciplines. We then
extract features from them, and build a dictionary of unique identifiers of papers along with their
corresponding features. There are a variety of features that could be extracted to represent the
text, some are simple like TF-IDF and n-gram models, while others are more complex like
transformers. We aim to try both and choose the most appropriate of them. When a presents a
query paper, we perform the same feature extraction, and rank the papers in our database
according to how similar they are to the query paper. The user can provide feedback about which
recommended paper where actually similar, and use the relevant papers along with the query
paper to refine the search results.
