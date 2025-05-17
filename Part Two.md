## Part Two, Statistical Learning

Chapter Nine of the book entitled “Knowledge Graphs,” by Kejriwal, Mayank et al., discusses how statistical learning is applied in creating knowledge graphs. In one of the lectures of the Northwestern University MSDS program with Dr. Chaturvedi at the helm, I learned that statistical learning and machine learning greatly overlap—the two are almost the same thing. Three key aspects of Chapter Nine will be discussed: (1) statistical learning, (2) first order logic, and (3) Markov Logic. 

(1) Statistical learning is used in knowledge graphs to extract “named entities, relationships, or events.” According to Chapter Nine, the models extract the information and assign a threshold percentage (e.g., .6) to the “relevance” of the information. Moreover, the models use weak results to improve performance. Although the following is not stated in the book, this appears to be the use of algorithms that are similar to gradient boosting machines. Moreover, according to the book, collective output is used by the algorithms. This appears to be similar ensemble methods that are popular in statistical learning (and machine learning). 

(2) Additionally, first order logic is used in the creation of knowledge graphs. First order logic is extremely precise and uses the rules of symbolic logic (e.g., negation, conjunction, disjunction, equivalence, and so on). Building a model based solely on these rules would algorithm extremely lengthy and will be overfit to a specific source of information. That means that it would not function well when it is scaled to the World Wide Web. 

(3) Therefore, a buffer is needed to make the model more robust and useful when it is applied at scale. Markov Logic can be used as the needed buffer. Markov Logic makes the model more useful. So, instead of completely disregarding information that is not an exact fit, the model classifies it as “less probable;” there might be some sort of ranking that is used (e.g., a percentage ranking). 

In sum, statistical learning methods are used for pattern recognition and ranking. The combination of the above discussed practices makes an algorithm more robust and for that reason more useful when it is applied at scale, especially when applied to the World Wide Web.

**Reference**

Kejriwal, Mayank, Craig A. Knoblock, and Pedro Szekely. 2021. Knowledge Graphs: Fundamentals, Techniques, and Applications. Cambridge, MA: MIT Press. [ISBN-13: 978-0262045094]
