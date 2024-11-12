## Coreference Resolution
Coreference resolution is the task of finding all expressions that refer to the same entity.

“My mom is the best!”, said Hamza, “She wakes me up, makes me healthy food then she lets me eat junk food”.

- Entities: “Hamza”, “my mom”.
- Expressions which refer to “Hamza”: “My”, “me”, “me”, “me”.
- Expressions which refer to “my mom”: “She”, “she”.

### Use Cases
- In the context of this project, Coreference Resolution could be best used in order to enrich downstream topic modeling by replacing references with the same entity in order to better model the actual meaning of the text. This increases the Tf-Idf of generalized entities and it removes ambiguous words that are meaningless for classification.
- Another use-case would be to use the Coreferenced text data as additional features, along with Named Entity Recognition tags, in any classification approach. A one-hot-encoded version of unique entities can be used as input to factorization machines or other approaches for spare modeling.

### Packages
NeuralCoref, Stanford NLP, Apache Open NLP, and Allennlp.

