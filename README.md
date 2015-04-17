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
  * 
