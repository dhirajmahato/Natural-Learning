# Natural Language Processing
focuses on the interaction between computers and human language.
### FLOW
1. Data Cleaning
2. Tokenization
3. Vectorization
4. Model development
### Basic Terminology
- **Cleaning Stop Words**: e.g., "the," "and," "in" since they don't carry meaning
- **Stemming and Lemmatization**": reduce words to their base or root form
- **Part-of-Speech Tagging (POS)** :

This is for extracting information from sentence.
sentence is usually composed of subject+verb+object/ verb +object.
sentence needs **Part of speech (POS) Tagging**.

Parts of speech: http://www.grammarinenglish.com/
1.noun, 
2.pronoun, 
3.verb, 
4.adverb, 
5.adjective, 
6.conjunction, 
7.preposition, and 
8.interjection.

Standford POS Tagger can identify these and more demo link:https://parts-of-speech.info/
Adjective
Adverb
Conjunction
Determiner
Noun
Number
Preposition
Pronoun
Verb

General Tricks to identify these:
1. is it an article? These are a short list. There will almost always be a noun to the right of an article, but there may be adverbs and adjectives in between.
2. is it a pronoun? A longer but still manageable list
3. does it end in ly? It is probably an adverb but some non-adverbs also end in ly.
4. does it end in ing? It may be a gerund or participle (forms of a verb) but other words also end in ing.
5. does it end in s’ ? It is likely a noun
6. does it end in ‘s ? It is either a noun as in 5, or a contraction of the verb is, usually connected to a pronoun.
There are a few more contractions using apostrophes and these usually mark verbs
7. does it end in er or est and does the sense of the sentence make a comparison? Then these words may be adjectives. There are many non-adjective words that end this way.
These are the easy ones. This list will rarely allow you to identify all the parts of speech in a typical sentence. After this, you need to look at the function of each word in the sentence and determine the matching part of speech. This process is called parsing.
Bonus trick but you will not see it often: if it is the only word after a semicolon and before a comma, it is a conjunction.

POS tag List https://www.ling.upenn.edu/courses/Fall_2003/ling001/penn_treebank_pos.html
CC | Coordinating conjunction |
CD | Cardinal number |
DT | Determiner |
EX | Existential there |
FW | Foreign word |
IN | Preposition or subordinating conjunction |
JJ | Adjective |
JJR | Adjective, comparative |
JJS | Adjective, superlative |
LS | List item marker |
MD | Modal |
NN | Noun, singular or mass |
NNS | Noun, plural |
NNP | Proper noun, singular |
NNPS | Proper noun, plural |
PDT | Predeterminer |
POS | Possessive ending |
PRP | Personal pronoun |
PRP$ | Possessive pronoun |
RB | Adverb |
RBR | Adverb, comparative |
RBS | Adverb, superlative |
RP | Particle |
SYM | Symbol |
TO | to |
UH | Interjection |
VB | Verb, base form |
VBD | Verb, past tense |
VBG | Verb, gerund or present participle |
VBN | Verb, past participle |
VBP | Verb, non-3rd person singular present |
VBZ | Verb, 3rd person singular present |
WDT | Wh-determiner |
WP | Wh-pronoun |
WP$ | Possessive wh-pronoun |
WRB | Wh-adverb |

- **Named Entity Recognition/ entity chunking** : Its actually a tagger similar to Part of Speech Tagger called NER tagger which classifies words into predefined categories like person, organisation, place, cities, dates etc. Further: It helps in extracting features from text which could further be processed to make classifying for documents. Giving answer to user query? [usecases](https://www.kdnuggets.com/2018/12/introduction-named-entity-recognition.html)
  - *semanticly equivalent sentences generators , paraphasing*

- **Tokenization** : breaking down text into individual words
- **Vectorization/word embedding**:like Word2Vec and FastText represent words as vectors in high-dimensional spaces, capturing semantic relationships between words. 
- **Sentiment Analysis** : Model development
  
## Packages
### NLTK


















[src](https://towardsdatascience.com/basic-concepts-of-natural-language-processing-nlp-models-and-python-implementation-88a589ce1fc0)

