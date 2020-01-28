# MLExperiments

Collection of State-of-the-Art for real world Machine Learning Use Cases.
Since shallow models (e.g. SVM and logistic regression) are no state-of-the-Art anymore, they wont be captured here anymore.
Further only NLP tasks that have the capability to have direct real world impact for SME will be captured. Topics that have a stronger focus on NLP research are out of scope.


## Natural Language Processing

| NLP-Task | relevant | Description |
|---------|:------:|-------------|
| Automatic speech recognition | :x: | automatically recognizing speech |
| CCG | :x: | linguistically expressive grammar formalism |
| Common sense | :x: | enable model to answer questions that go beyond a provided text (model shoud e.g. use world knowledge) |
| Constituency parsing | :x: | creating a parse tree that represents syntactic sentence structure |
| Coreference resolution | :x: | clustering mentions in text that refer to the same underlying real world entities |
| Dependency parsing | :x: |  extracting a dependency parse of a sentence that represents its grammatical structure and defines the relationships between words within the sentence |
| Dialogue | :heavy_check_mark: | design of conversational agents (siri, cortana), chatbots etc.|
| Domain adaptation | :heavy_check_mark: | enable a model to perform well in another domain (e.g. other kind of text that the model was trained on) = Transfer Learning? |
| Entity linking | :heavy_check_mark: | extract entities from text (e.g. recognize name of celebrity) and disambiguate them to correct entry in knowledge base |
| Grammatical error correction | :bulb: | correcting different kinds of errors in text such as spelling, punctuation, grammatical, and word choice errors |
| Information extraction | :heavy_check_mark: | Information extraction is the process of extracting specific (pre-specified) information from textual sources. One of the most trivial examples is when your email extracts only the data from the message for you to add in your Calendar. |
| Language modeling | :x: | task of predicting the next word or character in a document. |
| Lexical normalization | :bulb: | process of reducing words to their roots (stemming, lemmatization)  |
| Machine translation | :heavy_check_mark: | translate text or speech from one language to another|
| Missing elements | :x: | deals with things that are meant, but not explicitly mentioned in a text |
| Multi-task learning | :x: | training a model on several tasks with the aim that in generalizes better on the specific original task |
| Multi-modal | :x: | Combining several modalitites text, speed, image) to improve model performance  |
| Named entity recognition | :heavy_check_mark: | automatically detect and extract entites (person names, organizations, cities etc.) |
| Natural language inference | :heavy_check_mark: | determine if one given statement (premise) semantically entails another given statement |
| Part-of-speech tagging | :x: | assigning word category to word (noun, verb etc.)|
| Question answering | :heavy_check_mark: | building systems that automatically answer questions posed by humans in a natural language |
| Relation prediction | :x: | recognizing a named relation between two named semantic entities (e.g. for data in graph dbs) |
| Relationship extraction | :bulb: | extracting semantic relationships from text, which usually occur between two or more entities. ("Paris is in France" - relationship: "is in") |
| Semantic textual similarity | :heavy_check_mark: | determining how similar two pieces of texts are |
| Semantic parsing | :x: | converting a natural language utterance to a machine-understandable representation of its meaning |
| Semantic role labeling | :x: | assigns labels to words or phrases in a sentence that indicate their semantic role in the sentence |
| Sentiment analysis | :heavy_check_mark: | identify whether the expressed option of a text is positive, negative oder neutral |
| Shallow syntax | :x: | analysis of a text on the level of the syntactic structure of the text |
| Simplification | :x: | modifying the content and structure of a text in order to make it easier to read and understand, while preserving its main ide |
| Intent Detection and Slot Filling | :bulb: | task of interpreting user commands/queries by extracting the intent and the relevant slots (=basis of chatbots) |
| Stance detection | :heavy_check_mark: | identify type of attitude that is expressed as reaction to a claim made by a primary actor   |
| Summarization | :heavy_check_mark: | technique to shorten long pieces of text |
| Taxonomy learning | :x: | hierarchically classifying concepts in an automatic manner from text corpora |
| Temporal processing | :x: | e.g identify which date a docuement was created, or in which orders events are mentioned withing a docuement |
| Text classification | :heavy_check_mark: | assign a text to one or more categories |
| Word sense disambiguation | :x: | the same word can have different meaning depending on its context(e.g the word "bank" - riverside or financial bank, WSD helps ro resolve such word ambiguities|
