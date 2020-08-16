# Zeno’s paradox, countability, uncountability and the continuum hypothesis

S.K.Venkatesan

### Abstract

We show here that just like the resolution of Zeno’s paradox, contradiction between countability and uncountability can be resolved. Here it is shown that contradictions don’t exist in an ideal world, and that they
only arise due to elements in physical reality that challenge idealism. Contradictions gives rise to infinite hierarchies of classes and that these classes are distinguished better by scaling dimensions (Hausdorff measures), providing a new way to look at continuum hypothesis. We also show that the quantitative aspects of the problem of algorithmic complexity classes throws further light on these contradictions.

“Reason has always existed, but not always in a reasonable form” – Karl Marx

## Introduction

Contradictions are mills through which reality ebbs and flows. The right and left hand side exists as opposing manifestations. The fact that the
perfect symmetry of the left and right is broken is what establishes their distinction. If Earth is a perfect sphere, then there would not be rivers
and valleys that brings life to it. However, since the radius of the earth is almost a constant (to more than an accuracy of 99%), we are qualified to call it a sphere.

Contradictions are also a great source of changes to society and transitions from one form to another. Goliath was powerful when combat was direct physical conflict with hand-held weapons. When the giant Goliath calls David to come near him to fight him it is clear that only at that range that he can overcome David. David at the same time keeps his distance to deny him that opportunity and defeats him with his long-distance weapon. Inside the atomic nucleus such a conflict between the Goliath nuclear forces that operate only short distances release enormous amount of energy when it comes in conflict with the electrical repulsion
that operates at long distances as the size of the nucleus becomes sufficiently large, as in the case of Uranium or Plutonium nucleus, when it is bombarded with neutrons causes nuclear fission releasing enormous amount of energy in short time. At the other end of the spectrum when the gravitational forces crushes electrical repulsion in Hydrogen ions, the Goliath nuclear forces take over releasing enormous energy producing the energy of the sun. 

In this article we first consider classical Zeno’s paradox, countable infinity and uncountable infinities of higher order. We also show how
these Hegelian contradictions lead to an hierarchy of infinities. We then show that the so called uncountable numbers can in fact be counted as
well, using a close parallel with Zeno’s paradox, resulting in a serious fissure in continuum hypothesis and Gödel’s incompleteness theorem as well.

## Classical Hegelian hierarchy of infinities

We will begin with the classical Zeno’s paradox that is usually explained in terms of Achilles and the tortoise [Aristotle, 350 BCE].

## Zeno’s paradox

Classical Zeno’s paradox is illustrated by the story of the Achilles and the Tortoise. The paradox follows from the argument that if the tortoise
takes a lead, then each time Achilles reaches the place the tortoise was, the tortoise would have moved further away, and however fast the Achilles
chases the tortoise, it can never catch the tortoise, as each time the tortoise would have moved further away while Achilles is trying to catchup. We
will illustrate this in a much simpler way using the concept of recursive decimals:

$$ 0.99999 ··· = 1 $$

We know from this that there are infinite sequence of numbers, $0.9, 0.99, 0.999, ...$ that are bound above by the finite value 1.0. The finite
value 1.0 can be expressed by the infinite sequence of decimals represented by the above equation. Of course, there are many such infinite sequences
that approach 1.0, each with its own rhyme and rhythm. The fact that the infinite is contained in the finite value of 1.0 is indeed a paradox.
However, it depends on how we measure the bananas, by counting them or by weighing them. Although it takes infinite steps in an algorithm for
the Achilles in terms of number of zero-dimensional points, it is still finite in terms of length of time it takes for it to reach the tortoise. The paradox disappears once we weigh the bananas instead of counting them.

### Hegelian hierarchy of infinities in classical mathematics

Let us now consider the cardinality of a set as the number of elements in a set, for example, if

$$A = \{\text{dog, cat, horse, car, bus, train, aeroplane}\}$$

$$\#(A) = 7$$

Now consider the set of all subsets of $A$, symbolically written as the set, $2^A$ and in fact this notation for the power-set is justified by the relation,

$$\#(2^A) = 2^{\#(A)}$$

We would like point out that this process can continued indefinitely, i.e., we can construct power-set of a power-set or, in plain language, that there
can be a set of all subsets of the set of all subsets of a set etc., i.e.,

$$A, 2^A , 2^{(2^A)} , ...$$

The cardinality of natural numbers is denoted by &aleph;,

$$\aleph = \#(N)$$

Now consider the cardinality of the set of all real numbers between 0 and 1, i.e.,

$$c = \#([0, 1])$$

Just as the number of drops of water in a glass of water cannot be counted like a bunch of bananas, we intuitively know that the set of real numbers in [0,1] cannot be counted like natural numbers. We will prove this now. Let us represent all real numbers between 0 and 1 in terms of their binary representation in some counting order,

$$a_1 = 0.a_{11} a_{12} a_{13} a_{14} a_{15} = 0.01010···$$

$$a_2 = 0.a_{21} a_{22} a_{23} a_{24} a_{25} = 0.110010 ···$$

$$a_3 = 0.a_{31} a_{32} a_{33} a_{34} a_{35} = 0.101011 ···$$

$$···$$

By a diagonalization process discovered by Cantor we can construct a real number,

$$b = 0.100···$$

where $b$ is obtained by reversing the 0s and 1s of i-th digit of ai , such that,

$$b = 0.b_{11} b_{22} b_{33} b_{44} b_{55} ... ∉ {a_1,a_2,a_3,...}$$

leading to a contradiction. We would like to point out that this proof is quite similar to the proof used in Zeno’s paradox showing that the Hare never catches the Tortoise, so like Zeno’s paradox we will prove also its opposite in the next section. For now, in this section, however, we will assume that this proof is correct and proceed further to qualitative results, i.e.,

$$c = 2^{\aleph} $$

In order prove this consider the binary representation of real number in (0,1),

$$x = 0.010011001···$$

We now obtain the corresponding subset of natural numbers by considering all the index positions of "1" in the above binary representation, i.e.,

$$ S = \{2, 5, 6, 9, ...\} $$

Similarly for every subset of natural numbers we can construct a real number in (0,1). This implies a bijective mapping between the power-set
of natural numbers and the set (0,1), thus proving the result. QED

So finally we also have the result that we can construct an infinite hierarchies of infinities, i.e.,

$$\aleph, 2^{\aleph}, 2^{2^{\aleph}}, ...$$

## Paradox of countability and fissures in continuum hypothesis

Now, we will establish a new result, that contrary to classical mathematics, it is possible to count the real numbers in (0,1) in a orderly sequence. This establishes a contradiction between countability and uncountability. First, let us consider the binary representation of real numbers (0,1) using a tree-like representation (Figure 1).

Now let us count the binary numbers from top-down-left-right in Figure 1:


0.0, 0.1,

0.00, 0.01, 0.10, 0.11,

0.000, 0.001, 0.010, 0.011, 0.100, 0.101, 0.110, 0.111,

.........

By using Cantor’s arguments of diagonalization we get that the number, 

$$x = 0.11111111111111$$

is not in this counting sequence. However, contrary to this argument, we know Achilles will eventually catch-up, i.e., when the depth of the tree (which is now 3) reaches 14 (= 2 + 4 + 8), then the last entry in the right-bottom will be the number 0.11111111111111. What about the number 0.11111... , i.e., the number 1.0. Will it ever be reached in counting as it is an infinite sequence? The question posed is similar to the Zeno’s paradox, as we assume that counting takes equal amount of time. What if we count them very fast in parallel. Assuming that we count the items of the $i$-th generation within a speed of $r^i$ seconds, where $0 < r < 1$. The total time taken to count all of them will be,

$$\text{Total time taken} = \sum_{i=1}^{∞} r^i = r/(1−r)$$

which is a finite value. Here the crucial point is whether $i = ∞$ is included here or not. If the point at infinity is included in the set of natural numbers then the value $0.111111... = 1.0$ will also be reached in counting. Since the total time taken for the computer to finish computation is finite, we can assume that the point at infinity will be included as we cross that time. This is exactly how Zeno’s paradox was resolved. This proves that this tree like structure will approach all the real numbers as it penetrates its roots across the entire set of real numbers in (0,1). Almost the same idea applies also for the set of rational numbers of the form $p/q$, as they can be represented in a two-dimensional grid points $(p,q)$ and it can be counted in a zig-zag manner, starting at the top-left corner, similar to the tree structure here, but there the spatial distribution grows more like $n^2$, so it will take much more steps to converge to the real numbers than the tree algorithm which grows spatially as $2^n$.

One might argue that the point at infinity is just one point and how come this creates a one-to-one mapping from the set of natural numbers to the continuum. The point at infinity is a single converging point in time, but in the space of counting zero-dimensional points it maps to $2^{\aleph_0}$ , the continuum (that’s another reason why we counted them as a binary tree expansions, more as an expansion of sequence of finite power sets). So as a consequence we get the important result,



Similarly, if we consider multi-exponential trees, we obtain,

$$\aleph_0 = 2^{\aleph_0} = 2^{2^{\aleph_0}} = ...$$

At a philosophical level, we can say that in the ideal Platonic world, there is only one infinity (one truth and one god).
Paul Cohen [Chow, 2007] proved using the concept of forcing that a consistent set of axioms of set theory cannot prove or disprove continuum
hypothesis. Abstract ideas do perform an useful function of unifying various disparate concrete objects but as observed by Arnold [1998], they mostly do not yield any thing concrete by themselves.

In summary, we found that the idea of countability breaks down, so it cannot be used to classify levels of infinities and all the Hegelian infinities collapse to a single infinity in the Platonic world. However, the concept of continuum hypothesis still remains true in this new context where we will no more be counting bananas but instead weighing them. In the next section (Section 3) we will construct a counter example to continuum hypothesis using a new way of distinguishing infinities with Hausdorff measures or the concept of scaling dimensions.


## Decision problems


Although here we are only discussing about numbers and mathematics of set theory, these results have much greater implication in computer science as there are corresponding categorical mapping at higher levels that maps these domains to similar problems there. At an abstract level decision problems can considered as the function mappings,

$$f : A → {0, 1}$$

where $A ⊂ N$. So in essence a decision problem can be mapped to a real number. However, at the same time it can be shown that the set of algorithms or procedural programs are countable, as a Turing machine can be reduced to a natural number, a binary state of the computer. Putting these two facts together, we get the result that not all decision problems can be solved exactly by a computer as real numbers are uncountable. This how we also prove that the halting problem is unsolvable and also how Gödel proved his incompleteness theorem [Aaronsom, 2013]. Our results here question the exact validity of all those proofs without additional assumptions. It is quite clear that other assumptions about reality are required to make them valid.

In order to make this article self-contained we briefly indicate how the halting problem is related to the Zeno’s paradox, but for more details about the halting problem and it’s relation to the Gödel’s incompleteness theorem, please refer to lucid account by Aaronsom [2013]. The halting problem constructs the two legally disjoint categories, the finite and infinite, and finds a contradiction between them. Here we noticed in our earlier sections that, just as in Zeno’s paradox, the infinite of events is contained within a finite interval of time. In an ideal world it is possible to count an infinite of things in finite time and only by imposing some conditions that are borrowed from reality that we can establish such logically disjoint categories and then only a contradiction can be established.

Although it is recursion that is establishing contradiction between the finite and infinite, it is also recursion that is capable of producing the infinite by finite means. It is the disease that some times provides the cure, like in the case of inoculation that injects the disease causing agent itself with reduced virulence in order to fight the disease.

### Crucial assumption about reality that can restore validity of Cantor’s proof and Gödel’s proof

Additional elements from physical reality are required, in order to restore validity of Cantor’s proof on uncountability of the continuum [0,1] and also Gödel’s proof of incompleteness. In a previous section we established that the continuum can be counted, where the crucial step was that the $i$-th generation of binary fractions of length $2^i$ can be counted in a time of $r^i$ , where $0 < r < 1$. This value of $r$ is not possible in a real physical world. In the real physical world, we always have $r > 1$ (even when we consider Quantum computing), so we will not be able to count the continuum in finite time and so Cantor’s proof and the proof of incompleteness of Gödel remain correct, only if we add this crucial element from reality. Contradictions don’t exist in an ideal world, they only arise due to elements in physical reality that challenge our idealism.


## Cantor set and the continuum hypothesis

The continuum hypothesis states that there are no cardinal numbers between $\aleph$ and $2^{\aleph}$. We have shown in the earlier section that the argument of diagonalization is similar to the Zeno’s paradox and we know in practice that the Achilles will overtake the tortoise, i.e., that the continuum can be counted. This implies that all the hierarchy of Hegelian infinities collapse to one, so the continuum hypothesis can be reformulated in this new context as:

Is there a set $B$ with infinite points and a new measure of dimension, $μ$, such that, $μ(N) < μ(B) < μ(C)$ where $N$ is the set of natural numbers, $C$ is set of real numbers in the [0, 1]. We will now be constructing such a measure and the set $B$ as well. Let us now consider the Cantor set, $B$ , which can be obtained by recursively removing the middle one-third (but keeping the end points during the removal) of the set real numbers in [0,1]. Consider the sequence of sets,

$$B_1 = [0,1/3] ∪ [2/3,1],$$

$$B_2 = [0,1/9] ∪ [2/9,1/3] ∪ [2/3,7/9] ∪ [8/9,1],$$

$$...$$

defining the Cantor set to be,

$$B = \cap_{k=1}^{∞} B_k$$

In the above representation it seems as if the Cantor set can be represented as the disjoint union of countable sets. However, this is quite untrue, as the Cantor set is a totally disconnected nowhere dense set. So, it can only be written as the disjoint union of uncountable sets. This fallacy is due to the fact that countability of the finite-dimensional truncation of an uncountable set does not prove that the limiting set is countable, not that distinguishing between countable sets and uncountable sets is as easy as it was portrayed by classical mathematicians. Cantor set can also be symbolically written as a geometric set following the relation,

$$3 × C(0) = C(0) ∪ C(2/3)$$

Or to put in simply, when we scale the Cantor set by 3, we get two Cantor sets, i.e.,

$$3^D = 2$$

where $0 < D < 1$ is the scaling dimension of the Cantor set and from this relation we obtain $D = \log(2)/\log(3) ≈ 0.63$.
For example, we can see that natural numbers are 0-dimensional points in Euclidean space that don’t scale, while [0,1] scales linearly, a two-
dimensional square scales quadratically and, a cube grows to the cubic power etc. We can also prove easily that the Cantor set is uncountable. Consider the ternary representation of a real number in (0,1), i.e.,

$$x = 0.0102201 ···$$

The points in the Cantor sets will not have digit "1" in them, i.e., say,

$$x = 0.002022002···$$

This may seem erroneous as $0.1 ∈ C$ , but it should be noted that in the ternary representation, $0.1 = 0.0222...$, so there is an equivalent ternary representation without the digit "1" and which is what we will pursue as the ternary representation in this article. Similar to the proof involving binary representation of real numbers we can show that the Cantor set, C , is uncountable. Using a similar procedure we can also show that,

$$\#(C) = 2^{\aleph}$$

One then wonders how this is a counter example to the continuum hypothesis? The answer lies not in counting bananas but weighing bananas, as there is more geometric information in the Cantor set that is lost in counting rather than weighing them. It is this extra geometric information that is captured by the scaling dimension, which distinguishes it as a fractal object existing between 0-dimension and 1-dimension.

It also becomes apparent that the idea of countability is rather useless, as although the set of rational numbers are countable, they are dense in the set of real numbers and their effective scaling dimension is one and not zero. 

### Discrete versus continuum

The ideal way of mediating between the discrete and the continuum is by the use of Dirac distributions or the Heavside function.

Let us now consider Heavside function $H(x,A)$ corresponding to a set of discrete points in space $A$, i.e.,

$$H(x,A) =  1 \text{ if }x \in A$$

$$H(x,A) =  0 \text{ if }x \notin A$$

Let us now define,

$$H_\epsilon(x,A) = H(x,A) \ast \exp(-|x|^2/\epsilon^2)$$

Now consider the support of the function,

$$\mathrm{supp}(H_{\epsilon}(x,A)) = \{x | H_{\epsilon}(x,A) \ne 0\}$$

Define,

$$A^{\ast} = \lim_{\epsilon \rarr 0} \mathrm{supp}(H_{\epsilon}(x,A))$$

There are many discrete sets that obey the property,

$$A^{\ast} = A$$

for them there is hope. However, for sets that do not satisfy this property we will only consider it's regular equivalent $A^{\ast}$ rather than A.

In the case of the set of rational numbers we get,

$$Q^{\ast} = R$$

But for Cantor set $B$, we have,

$$B^{\ast} = B$$

It is possible to measure such sets with confidence.

Of course, there are pathological sets like the Vitali set,

$$V = R/Q$$

which are not even well-defined; in the sense that there are multiple avatars of this set possible and it is possible to define them as subsets of $[q_1,q_2]$ for any two distinct rationals $q_1, q_2$ that will remain untractable even for Lebesque measure. We will keep ourselves far way from those kinds of pathologies, however interesting they may be. The ockam razor for avoiding such sets is that these sets are not well-ordered sets and they do not have an associated metric that can uniquely define a metric distance between two points in the set. 

Of course, we invented all this mechanism to convince the audience that,

$$Q^{\ast} = R$$

and so,

$$\mu(Q) = 1$$

i.e., that they should be identified with $R$ rather than with the countable integers.

The method of indentifying rational numbers of the form $p/q$ with two-dimensional grid $(p,q)$ breaks the topological neighbourhood relationships, so in a sense it deconstructs it in different context misrpresenting it.

One of the essence of uncountability is the fact that one cannot find the next number in the ordered list and this fact is satisfied by both the set of rational numbers, $Q$ and the set of real numbers, $R$.

## NP vs P - the exact problem as a limiting case of approximate problem

In reality, mathematical idealizations are scale limits of real problems. Just as we cannot have a measuring scale of infinite length, these limiting problems are unrealistic abstractions, but they are useful to capture essence of some problems as a simplified cartoon sketch.

In our earlier sections we saw how the continuum hypothesis and set theory could be understood. In the same vein, let us consider a simple NP-complete problem, the [subset sum problem](https://en.wikipedia.org/wiki/Subset_sum_problem). The subset sum problem is the problem of indentifying a set of $N$ numbers in a given set that add-up to a given number $M$. It is easy to verify that they add-up to $M$, but difficult to find such numbers, especially that there is no solution whose effort estimate is polynomial in $N$ and so expected to be exponenetial in $N$. These problems are realted to the packing problem of finding if a given set of objects fit a bag, a problem that every travellor has enough experience to know that it is complex. In fact, every time we pack a bag we find that some thing is sticking out frustrating us so much that we sometimes off-load the bag and restart the packing again!

Now let us consider the approximate version of this problem and see how it is solved. We will give a rough sketch here, but for more details please refer to the [source](https://en.wikipedia.org/wiki/Subset_sum_problem#Polynomial_time_approximate_algorithm).

...

In the above approximate problem the introduction of an $\epsilon > 0$ managed to convert it into a problem of polynomial complexity, so the problem of NP-complexity class under the limit $\epsilon \to 0$ establishes the result NP=P. Howvever, we also expect that for the exact problem, $\text{NP}\ne \text{P}$ and that in fact that it can only be solved in an effort that grows as exponential of $N$ and not polynomial in $N$. This can also be established from another angle that if we look at the Talor series expansion of the exponetial function of $N$,i.e.,

$$
\exp(N) = 1 + N + \frac{N^2}{2!} + \frac{N^3}{3!} + \cdots 
$$

then it truncates to a polynomial but the limit is an exponential.


In order to establish that it remains a polynomial in $N$ we have to find an upper-bound on the degree of the polynomial $N$, so that it remains polynomial in the limiting process also. We will now consider sub-classes of problems that have these limiting properties.

Although this problem seems quite different from the problem of prime decomposition problem, it can transformed into a problem of prime deposition by mappiing of each number of the set into it's corresponding power of say 2, e.g., $n_i \to 2^{n_i}$ and treat the problem as factorization problem rather than a problem of sums. Of course, this is special subclass of the product decomposition problem. 












