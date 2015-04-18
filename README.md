# CoolPapers
List of cool academic papers I've read with summaries

# [A Few Useful Things to Know About Machine Learning] (http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)

# [GloVe: Global Vectors for Word Representation] (http://www-nlp.stanford.edu/projects/glove/glove.pdf)

# [Parsing Natural Scenes and Natural Language with Recursive Neural Networks] (http://www-nlp.stanford.edu/pubs/SocherLinNgManning_ICML2011.pdf)

# [From Frequence to Meaning: Vector Space Models of Semantics] (http://www.jair.org/media/2934/live-2934-4846-jair.pdf)

# [Semi-Supervised Recursive Autoencoders for Predicting Sentiment Distributions] (http://www.socher.org/uploads/Main/SocherPenningtonHuangNgManning_EMNLP2011.pdf)

# [A Joint Model of Language and Perception for Grounded Language Learning] ( )

* Task of extracting representations of language tied to physical world
* New grounded concepts from a set of scenes containing only sentences, images, and indications of what objects being referred to
* System includes: 
  * *Semantic parsing model* 
    * Defines distribution over logical meaning representations for each given sentence
  * Set of visual attribute classifiers for each possible object in scene
  * Joint model learning mapping from logical constants in logical form to set of visual attribute classifiers
  * Extracted depth and RGB values from images as features (shape and color attributes)

# [Learning Distributions over Logical Forms for Referring Expression Generation] ()
  * Efficiently find fraction of referring expressions for scenes that are used; estimate associated likelihoods
  * Learn probability distribution over set of logical expressions that select a target set of objects in a world state
  * Model as globally normalized log-linear model using features of logical form *z*
  * Distinction for plural entities in generated logical forms
  * globally optimized log-linear model, conditioned on state S and set of target objects G
  * Three kinds of features: logical expression structure features, situated features, and a complexity feature
  * learning two models--one for a global logical form for world-state model; and one learning a series of classifiers for each 
  * learn codebooks and associated sparse codes

#[A Game-Theoretic Approach to Generating Spatial Descriptions] ()
  * Generate spatial references to objects where listener much accurately identify object described by the speaker
  * Given target, speaker generates utterance according to a distribution, listener generates guess according to another distribution and both agents get a utility of 1 iff the guess matches the target
  * Train log-linear model for speaker and listener respectively
  * 
