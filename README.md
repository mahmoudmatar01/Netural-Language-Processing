## NLP (Netural Language Processing)

- NLP : is a subfield of linguistics, computer science, Ai, and Human language.

- The goal is acomputer capable of unferstanding the contetn of documents.

- Challenges in natural language processing frequently involve speech, recognition, natural-language understanding, and natural-language generation.

- Methods :- Rules , Statistics, and Neural Networks.

- Rule :- designed by symbolic methods, ex the hand coding of a set of rules.

- More recent system based on machine learing algorithm have many adv over hand-produced rules.

- The learing procedures used during machine learing automatically focus ont he most common cases.

- When writing rules by hand it is often not at all ovious where the effort should be directed.

- System based on automatically learing the rules can be made more accurate simple by supplying more input data. 

- System based on handwritten rules can only be made more accurate by increasing the complextiy of the rules which is a much difficult task.

- for Preprocessing in NLP pipelines, e.g tokenization, or postprocessing and transforming the output of NLP piplelines, e.g for knowledge extraction from syntactic pares.

- Corpus : is the set of documents.

- Neural Networks : a mojor drawback of statistical methods is that they require elaborate feature engineering .

- Since 2015 ,the field has thus largely abandoned statistical methods and shifted to neural networks .

- Popular techiques include the use of word embedding to capture semantic properties of words, and an inceade in end-to-end learing of a higher level task instead of relying on a pipeline of separate intermediate tasks .

------------------- Common NLP Tasks (Applications) -------------------

## Text and speech processing :

### OCR (Optical char recognition) :- 
given an image representing printed text, determine the corresponding text.

### Speech recognition :-
given a sound clip of a person or peaople speaking, determine the textual representation of the speech.

### Speech segmentation :-
given a sound clip of a person or peaople speaking, separate it into words. 
Subtask of speech recognition.

### Text to speech :-
given a text, transform those units a spoken representation.

### Word segmentation (Tokenization) :-
separate a chunk of continuous into separate words.


## Morphological analysis :

### Lemmatization :-
The task of removing inflectional endings only and returning the base dictionary form of a word which is also known as a lemma.

### Morphological segmentation :-
Separate words into individual morphemes identify the class of the morphemes.

### Part-Of-Speech tagging :- 
given a sentence ,determine the part of speech for each word.

### Stemming :-
the process of reducing inflected words to a base form
("close" will be the root for "closed", "closing", "close" etc) stemming yields similar results as lemmatization.


## Syntactic analysis :

### Grammar induction :- 
generate a formal grammar that describes a language's syntax.

### Parsing :-
detemine the parse tree of a given sentence.
there are two primary types of parsing : Dependency Parsing focuses on the relationships between words in a sentence - Constituency Parsing focuses on building out the parse tree using a probabilistic context free grammar


##  Lexical Semtantics : 

### Lexical Semtantics :-
what is the computational meanig of individual words in context?

### Distributional semantics :-
How can we learn sematic representations from data ?

### Named entity recognition (NER) :- 
given a stream text ,determine which items in the text map to prper names such as people or places, ans what the type o each such name is (e.g person, location, organization).

### Sentiment analysis :-
Extract subjective information usually from a set of documents, often usinf online reviews to determine "polarity" about specific objects.

### Terminology extraction :- 
automatically extract relevant terms from a given corpus

### Word-sense disambiguation (WSD) :- 
Many words have more than one meaning : we have to select the meaning which makes the most sense in context .

### Entity linking :-
Many words --Typically proper names-- refer to named entities ; here we have to select the entity which is refered to in context.


## Relational Semantics :

### Relational extraction :-
given a chunk of text, identify the relationships amnong named entities.

### Semantic Parsing :-
given a piece of text , produce a formal representation of its semantics either as a graph or in accordance with a logical formalism.

### Semantic role labelling :-
given a single sentence, identify and disambiguate semantic predicates,then identify and classify the frame elements.

------------------- There are a lot of applications in NLP -------------------

## RMM :-
is the relative measure of meaning 

## Token :- 
is any block of text,sentence,phrase or word

## N :-
is the number of tokens being analyzed

## PMM :- 
is the probable measure of meanig based on  acorpora

## D :- 
is the location of the token along the sequence of N-1 tokens

## PF :-
is the probability function specfiic to a language 

