Download Link: https://assignmentchef.com/product/solved-mlcs-homework3-computable-c-e-and-not-computable-problems
<br>
<ol>

 <li>Computable, c.e. and not computable Problems</li>

</ol>

N.B. In the following we use (<em>ϕ<sub>i</sub></em>)<em><sub>i</sub></em><sub>∈<strong>N </strong></sub>to refer to a fixed programming system (model of computation). You can reason in terms of the one you prefer, be it Turing Machines (<em>M<sub>i</sub></em>)<em><sub>i</sub></em><sub>∈<strong>N</strong></sub>, the class C, Σ<sub>1</sub>-definable functions, or in terms of pseudo-code.

<strong>Exercise 1.1. </strong>Write down the sentence <em>F<sub>M </sub></em>associated as in the proof of Trakhtenbrot and Church’s Theorems to the Turing Machine described below, where the alphabet is {0<em>,</em>1}, # is the blank symbol, <em>q</em><sub>0 </sub>the intiial state, <em>q<sub>r </sub></em>the reject state. The machine <em>M </em>has the following transition function:

(<em>q</em><sub>0</sub><em>,</em>0) →7   (<em>q<sub>r</sub>,</em>#<em>,</em>+1)

(<em>q</em><sub>0</sub><em>,</em>1) 7→ (<em>q</em><sub>0</sub><em>,</em>#<em>,</em>+1)

(<em>q</em><sub>0</sub><em>,</em>#) 7→ (<em>q</em><sub>0</sub><em>,</em>#<em>,</em>+1)

Describe the canonical model of the sentence <em>F<sub>M</sub></em>.

<strong>Exercise 1.2. </strong>Show by informal arguments the following points.

<ul>

 <li>If <em>L</em><sub>1 </sub>∩ <em>L</em><sub>2 </sub>is not computable and <em>L</em><sub>2 </sub>is computable then <em>L</em><sub>1 </sub>is not computable.</li>

 <li>If <em>L</em><sub>1 </sub>∪ <em>L</em><sub>2 </sub>is not computable and <em>L</em><sub>2 </sub>is computable then <em>L</em><sub>1 </sub>is not computable.</li>

 <li>If <em>L</em><sub>1 </sub> <em>L</em><sub>2 </sub>is not computable and <em>L</em><sub>2 </sub>is computable then <em>L</em><sub>1 </sub>is not computable.</li>

 <li>If <em>L</em><sub>2 </sub> <em>L</em><sub>1 </sub>is not computable and <em>L</em><sub>2 </sub>is computable then <em>L</em><sub>1 </sub>is not computable.</li>

 <li>If <em>L</em><sub>1 </sub>and <em>L</em><sub>2 </sub>are computably enumerable then <em>L</em><sub>1 </sub>∪ <em>L</em><sub>2 </sub>and <em>L</em><sub>1 </sub>∩ <em>L</em><sub>2 </sub>are computably enumerable.</li>

</ul>

<strong>Exercise 1.3. </strong>Assume that the set {<em>i </em>: <em>ϕ<sub>i </sub></em>is a total function } is not computable. Show (by an informal argument) that the set {(<em>i,j</em>) : ∀<em>n</em>(<em>ϕ<sub>i</sub></em>(<em>n</em>) ↑ iff <em>ϕ<sub>j</sub></em>(<em>n</em>) ↑} is not computable. (The notation ↑ indicates that the function is not defined on the given input).

<strong>Exercise 1.4. </strong>Let <em>C </em>be a set of c.e. sets. If <em>C </em>is not closed under supersets, then {<em>i </em>: <em>dom</em>(<em>ϕ<sub>i</sub></em>) ∈ <em>C</em>} is not c.e. (Hint: you can assume that the set {<em>i </em>: <em>ϕ<sub>i</sub></em>(<em>i</em>) ↑} is not c.e.).

<strong>Exercise 1.5. </strong>Argue informally whether the following sets are computable, c.e., or not computable.

<ul>

 <li>{(<em>i,j</em>) : given <em>j </em>as input, <em>M<sub>i </sub></em>never moves left}.</li>

 <li>{(<em>i,j</em>) : during the computation on <em>j</em>, <em>M<sub>i </sub></em>moves left three times in a row}.</li>

</ul>

(Hint: you can assume that the Halting Set {(<em>i,j</em>) : <em>M<sub>i</sub></em>(<em>j</em>) accepts} is not computable).

<strong>Exercise 1.6. </strong>Show that if we define the minimalization operator by dropping the requirement that the function is defined on all values smaller than the first value on which the output is 0 then we can define some non-computable function.

More precisely, consider the class C<sup>∗ </sup>defined as the smallest calss of functions containing the initial functions and closed under composition and under the following operator of minimalization: if <em>ψ</em>(<em>~x,y</em>) is in C<sup>∗ </sup>then the function <em>ϕ</em>(<em>~x</em>) = the minimum <em>y </em>such that <em>ψ</em>(<em>~x,y</em>) = 0, if any; is also in C<sup>∗</sup>. Show that the class C<sup>∗ </sup>contains a non-computable function.

1

<ol start="2">

 <li><em>NP </em>problems</li>

</ol>

<strong>Exercise 2.1. </strong>Show, by writing a formula, that the following properties are definable in Existential SecondOrder Logic over the class of finite graphs:

<ul>

 <li>Even: the graph has an even number of elements.</li>

 <li>Hamiltonian: the graph contains a cycle which visits each vertex exactly once.</li>

 <li>Bipartite: the graph is bipartite.</li>

 <li>Perfect Matching: the graph has a perfect matching.</li>

</ul>

<strong>Exercise 2.2. </strong>Express the transitive closure query in Existential Second-Order Logic: write a formula <em>T</em>(<em>x,y</em>) that holds of two elements of a finite structure if and only if they are in the transitive closure of a given binary relation <em>R</em>.

Express the Unreachability query in Existential Second-Order Logic: the Unreachability query, relative to a relation symbol <em>R </em>singles out the pairs (<em>a,b</em>) such that there is not <em>R</em>-path from <em>a </em>to <em>b</em>. Does the negation of your sentence express Reachability?

<strong>Exercise 2.3. </strong>Let’s call a formula a formula in Universal Second Order Logic if it has the form ∀<em>R</em><sub>1 </sub><em>…</em>∀<em>R<sub>n</sub>F</em>, where <em>F </em>is a first-order formula. Show that the property of being a connected graph is expressible by a

Universal Second Order formula using only quantification on relations <em>R</em><sub>1</sub><em>,…,R<sub>n </sub></em>of arity 1. (Hint: start by defining the negation of connectivity).

<strong>Exercise 2.4. </strong>Let <em>S </em>be a binary relation symbol. Assume that <em>S </em>is interpreted as the standard linear order on the set {0<em>,</em>1<em>,…,n</em>−1}. Define two formulas <em>F</em>(<em>x</em>) and <em>L</em>(<em>x</em>) expressing, respectively, that <em>x </em>is the first and that <em>x </em>is the last element of the ordering. Consider the set of pairs (<em>i,j</em>) ∈ {0<em>,</em>1<em>…,n</em>−1}×{0<em>,</em>1<em>,…,n</em>−1}. To use these pairs to count up to <em>n</em><sup>2 </sup>we identify each pair with its position in the lexicographic ordering induced by <em>S </em>on the set of pairs. Define a formula <em>S</em><sup>2</sup>(<em>x</em><sub>1</sub><em>,x</em><sub>2</sub><em>,y</em><sub>1</sub><em>,y</em><sub>2</sub>) that expresses that the number represented by (<em>x</em><sub>1</sub><em>,x</em><sub>2</sub>) is the immediate predecessor of the number coded by (<em>y</em><sub>1</sub><em>,y</em><sub>2</sub>).

Discuss how to generalize your answer to the lexicographic ordering on <em>k </em>tuples, for <em>k </em>≥ 2.

<strong>Exercise 2.5. </strong>Show that there is no formula <em>F</em>(<em>x,y,z</em>) in first-order logic in the language of orders such that for all <em>n</em>, if <em>a,b,c &lt; n </em>then <em>a </em>+ <em>b </em>= <em>c </em>if and only if ({0<em>,</em>1<em>,…,n </em>− 1}<em>,&lt;</em>) |= <em>F</em>[<em>a,b,c</em>].

(Hint: Use some inexpressibility result we proved).