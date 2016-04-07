What Are Literary Topics, Really? 
=================================


1. Topic Modeling
    * What is Topic Modeling, what are topics?
    * Topic Modeling in Literary Studies
    * The issue: non-thematic types of topics

2. What types of topics are there? An intuitive typology
    * The data: a topic model of 840 French novels, ca. 1840-2000
    * The topic model: 1000-word segments; lemmas; nouns-verbs-adjectives; 160 topics; 10000 iterations
    * Types of topics: themes, motives, setting, personnel, rhetorics; arts; meta-topics (also: character names; foreign words)

3. Reasons for this
    * Literary texts are non-expository: they treat their themes not explicitly, but implicitly and by way of concrete examples
    * Sure, Moby Dick is about "seafaring" and has a very high score in the "seafaring"-topic
    * But, really, Moby Dick is about the relation between man and nature and about the ambition of the individual

4. Consequences: non-thematic topics
    * In literary studies, we should not equate topics with themes
    * This doesn't mean topic modeling doesn't work in literary studies
    * Topic modeling opens up other aspects of literary texts to quantitative analysis as well
    * Literary studies are well-equipped to analyse these things
    * In fact, we could go back to non-expository prose and ask for rhetorical / meta-topics there as well! (feedback-loop from humanities to sciences!)

5. The big question: are there distinguishing, formal characteristics of the different types of topcis? 
    * The approach: first of all, accept my intuitive classification as a given (ok, bad first step) 
    * Generate features describing each topic: skewness; kurtosis; topic coherence; proportion of N, V, ADJ; average word length; overall topic score in model/collection;
    * Check correlations between the features, eliminate too strong correlations?
    * Check the distributions of the features per category
    * Can the formal features be used to classify topicsby category? (using multinomial logistic regression? or some other classifier)


