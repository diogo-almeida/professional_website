---
# Date this page was created.
date: 2018-08-26T00:00:00Z

title: "Sentence Processing"

tags:
- Sentence Processing
---

Sentences contain dependency relations between words at a linearly unbounded distance. For instance, in the second sentence below, it is understood that the word _what_ is somehow linked to the verb (_sing_), namely, by referring to its original direct object (_a song_):

* The boy sang a song
* _What_ did the boy sing ___ ?

This relationship between _what_ and the verb of the sentence (_sing_) is impossible to predict from linear order alone, as sentences can theoretically grow indefinitely large:

* _What_ did the boy sing ___ ?
* _What_ did the boy that the girl likes sing ___? 
* _What_ did the boy that the girl likes to see at school everyday sing ___?

This fact is used to motivate, at a theoretical level, a series of language-specific operations acting on linguistic representations, such as _Movement_. From a language processing perspective, linearly unbounded dependencies constitute a challenge for the parser, as information about the first element of the dependency needs to remain accessible in memory for an unpredictable duration of time without preventing the processing of the rest of the sentence. How these linguistic facts and their language processing consequences are connected is still a matter of debate. 

Some propose an architecture in which at least _some_ of the long distance relationships are processed by language-specific mechanisms that are fairly independent from the rest of the memory system. One such proposal is that the processing of _Movement_ operations rely on specialized neural circuitry, located in Broca’s area.

Others propose that it is possible to account for long distance dependencies by relying on independently motivated general working memory mechanisms. One such proposal proposes to reduce highly systematic errors in the comprehension and production of subject-verb agreement (agreement attraction) – another potentially linearly unbounded long distance dependency – to probabilistic side effects of this general working memory system. For instance, in the pair of sentences below: 

* _The key_ to the cabinets _is_ on the table.
* _The key_ to the cabinets _are_ on the table.

In the both sentences, the subject (_the key_) is singular, and thus requires a singular form of the verb (_is_). However, systematic errors are observed sentences like the second one, even though the verb is _plural_, both in comprehension and production. One of the proposed reasons for this phenomenon is the presence of a plural noun (_the cabinets_) intervening between the subject and the verb, which disrupts the memory retrieval mechanism responsible for checking whether the verb carries the correct agreement form.

My lab investigates the connection between long distance dependencies and the working memory system by investigating both types of claims, as well as other phenomena related to how sentences are processed in real-time.
