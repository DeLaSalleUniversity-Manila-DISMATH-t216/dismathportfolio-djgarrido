# dismathportfolio-djgarrido

#Week 1
- An introduction to DISMATH was discussed. I am absent by that time but still managed to ask my classmates for the lesson.

 | Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
 | :-----: |:-------:|:-----:| :-------: | :-------: |
 | ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
 | ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
 | v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
 | ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |

#Week 2 
- What I've learned is that the truth table is important in proving statements.
- The truth table must be memorized and understood to be able to be mastered.
- A declarative sentence is the structure required for a proposition. 
- I've learned about the terms negation, conjunction, disjunction, exclusive or, biconditional and implications.

 | Laws | Logical Equivalences |
 | :-----: |:-------:|
 | Identity Laws | p v F = p; p ∧ T = p |
 | Domination Laws | p v T = T; p ∧ F = F |
 | Negation Laws | p v ¬p = T; p ∧ ¬p = F |
 | Double Negation Law | ¬(¬p) = p |
 | Idempotent Laws | p v p = p; p ∧ p = p |
 | Commutative Laws | p v q = q v p; p ∧ q = q ∧ p |
 | Associative Laws | (p v q) v r = p v (q v r) |
 | Distributive Laws | p v (q ∧ r) = (p v q) ∧ (p v r) |
 | De Morgan's Laws | ¬(p ∧ q) = ¬p v ¬q |
 | Absorption Laws | p v (p ∧ q) = p; p ∧ (p v q) = p |
 
#Week 3
- I've learned that by using logical statements, you can prove statements.
- Truth and Validity are different things.
- Conclusions are dependent on the premises.
- There are differences in the quantifiers.
- Rules of Inference were taught.
- Knowing if an argument is a fallacy or not is important.

#Week 4
- I've learned that there are different types of proofs like the direct proof and its types.
- I also have learned on when and how a type of proof should be used.
- Proof by contraposition and contradiction are indirect methods of proof.
- Vacuous and Trivial proofs were also discussed.

#Week 5
- One must show that assuming the negation of a premise is true leads to a contradiction when it comes to proof of contradiction. We have tested different conditions and premises using the proof of contradiction.
- In this proof, according to Sir Arthur Conan Doyle, "When you have eliminated all which is impossible, then whatever remains, however improbable, must be the truth."
- It is a combination of a direct and indirect proof when it comes to proof of equivalence.

#Week 6
- We are taught the basics of MIT App Inventor.
- Additional lessons about functions were taught. Tricky exercises about the topic were given.

#Week 7
- Functions and its types and properties were discussed.
- Functions have three types: 
 - One-to-one function
 - Onto function
 - One-to-one correspondence.
- One-to-one function, also known as injective, is a fuction that always assigns a value to each domain only once.
- Onto funtion, also known as surjective, is a function in which all its codomains have a designated value.
- One-to-one function, also known as bijective, is a combination of an injective and surjective function.
 
#Week 8
- Algorithms. Tricky but exciting.
- max() funtion was introduced.
- Pseudocodes were taught. How to make it and how to create it. 
- Building an algorithm requires a precondition, procedure and postcondition.
 
#Week 9
- Linear and binary search were analyzed and we made a pseudocode for each search algorithm.
- Bubble sort and Insertion sort were also analyzed and the are really very different in the construction and way of sorting.
- The greedy algorithm and some coin algorithm were explained.
- Growth of functions and the Big-O notation was introduced.
- There are witnesses in growth of functions which are constants called C and k.

#Week 10
- Growth of functions have broadened to Big-theta and Big-omega.
- Big-omega is the lower bound to a function.
- Big-theta is the combination of big-O and big-omega (from my own understanding)
- Time complexity is the number of operations an algorithm takes. It is hard to know the time complexity of an algorithm.

#Week 11 
- Graph Theory. Easier but trickier. 
- This is easier because all you have to do is count and use your imagination to manipulate the graphs which makes it trickier.
- A graph consists of edges and vertices.
- Degree is the number of edges connected to a vertex.
- Path is finishing a certain path once.
- Circuit is like a path but going back to the initial.
- An Euler Circuit is when you run through all the edges and comes back to the initial edge.
 - Note: All nodes have even degrees.
- An Euler Path is when you run through all the edges without coming back to the initial edge.
 - Note: Exactly two nodes must be odd.
- A Hamilton Circuit is when you run through all the vertices coming back to the initial vertex.
- A Hamilton Path is when you run through all the vertices without coming back to the initial vertex.
- If two graphs have similar number of nodes, they are isomorphic.
- Planar graphs do not have any edge that crosses with each other.
- Nonplanar graphs can be known through Kuratowski's theorem which states that it must have a subgraph homeomorphic to a K3,3 or a K5 graph.

#Week 12
- We discussed further about graphs.
- To color graphs, two adjacent edges must be of a different color.
- Chromatic number is the least number of colors that can be assigned to a graph. 
- Planar graphs follow the Four Color Theorem meaning it can only have a chromatic number of at most four.
- Nonplanar graphs may have higher chromatic numbers.
- A tree is a graph with no circuits. Parts/Terminology for a tree:
 - Roots
 - Parent
 - Child
- More trees creates a forest.
- Leaves are infertile because they don't have children.
- M-ary trees are trees that have m number of children at each node.
 - if it is a 2-ary tree, it is called a binary tree. If 3, then triary. If 1000000, just 1000000-ary tree. :)))
