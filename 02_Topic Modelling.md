# Topic Modelling
NLP technique used to create structured data from a collection of unstructured data. Enables businesses to learn the hidden semantic patterns portrayed by a text corpus and automatically identify the topics that exist inside it.
For example, a topic modeling algorithm may be deployed to determine whether the contents of a document imply it’s an invoice, complaint, or contract.

Two popular topic modeling approaches are LSA and LDA. 

Where LSA assumes words with similar meanings will appear in similar documents, LDA assumes documents are made up of words that aid in determining the topics.

### Latent Dirichlet Allocation:

LDA assumes each document consists of a combination of topics, and each topic consists of a combination of words. It then approximates probability distributions of topics in a given document and of words in a given topic. For example:

Document 1: Topic1 = 0.33, Topic2 = 0.33, Topic3 = 0.33
Topic 1: Product = 0.39, Payment = 0.32, Store = 0.29
