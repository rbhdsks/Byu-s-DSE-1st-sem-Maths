# Real Analysis: Questions from the Uploaded Notes

[Question-solving and PYQ strategy](real_analysis_solving_strategy.md)

**Scope:** the five handwritten note PDFs in this repository, reviewed on 11 October 2026. These are notes-based practice questions, not authenticated previous-year questions. “Notes example” means an example/exercise has been restated from the notes; “Practice variant” means a new question on a concept in those notes. No exam frequency or marks are inferred.

Assume sequence indices n=1,2,... unless stated otherwise. For metric questions use the specified ambient space. Difficulty refers to a beginner's likely effort.

Try the question before opening its hint or answer check. A final answer without its required proof does not count as complete.

## Sets

### Q01 — Easy

**Notes example.** Source: [Sets, PDF p. 1](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Sets%20lec%201_261007_183939.pdf#page=1).

For A_n=[0,n], n≥1, find the union and intersection of all A_n. Justify both by membership.

<details>
<summary>Hint — open only after an attempt</summary>

Write A_1,A_2,A_3. For the union, ask whether every nonnegative real belongs to some interval.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

Union [0,∞); intersection [0,1]. Given x≥0 choose an integer n≥max(1,x); the intersection is the smallest member A_1.

</details>

### Q02 — Medium

**Notes example.** Source: [Sets, PDF p. 3](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Sets%20lec%201_261007_183939.pdf#page=3).

For A_n=[0,n/(n+1)], n=0,1,2,..., find the union and intersection. Check whether 1 belongs to the union.

<details>
<summary>Hint — open only after an attempt</summary>

A_0={0}. Every right endpoint is less than 1, but approaches 1.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

Union [0,1); intersection {0}. For 0≤x<1 choose n≥x/(1−x). No finite n includes 1.

</details>

### Q03 — Easy

**Notes example.** Source: [Sets, PDF p. 3](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Sets%20lec%201_261007_183939.pdf#page=3).

For A_n={−n,n}, n=0,1,2,..., find the union and intersection.

<details>
<summary>Hint — open only after an attempt</summary>

Compare A_0 and A_1 before considering all the sets.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

Union is the integers Z; intersection is empty because A_0∩A_1 is empty.

</details>

### Q04 — Medium

**Notes example.** Source: [Sets, PDF p. 2](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Sets%20lec%201_261007_183939.pdf#page=2).

Prove the two De Morgan laws for an indexed family of subsets of a fixed universe U.

<details>
<summary>Hint — open only after an attempt</summary>

For arbitrary x∈U, translate intersection into “for every index” and union into “there exists an index.”

</details>

<details>
<summary>Answer / proof checkpoint</summary>

x∈(∩A_i)^c iff there exists i with x∉A_i iff x∈∪A_i^c. Similarly, x∈(∪A_i)^c iff for every i, x∈A_i^c iff x∈∩A_i^c. Use equivalences or prove both inclusions.

</details>

### Q05 — Easy

**Notes example.** Source: [Sets, PDF p. 1](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Sets%20lec%201_261007_183939.pdf#page=1).

Prove that the sum of any two odd integers is even. Explain why checking 3+5 and 15+7 is insufficient.

<details>
<summary>Hint — open only after an attempt</summary>

Write arbitrary odd integers as 2k+1 and 2m+1.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

Their sum is 2(k+m+1), an even integer. Finitely many numerical examples cannot establish the universal statement.

</details>

## Bounds

### Q06 — Easy

**Practice variant.** Source: [Bounds, PDF p. 1–4](mathematical_methods/Real%20Analysis/Byu%27s-Notes/BOUND_261009_203646.pdf#page=1).

For (0,4), (0,4], [0,4], and {1,2,3,4}, find supremum, infimum, maximum and minimum when they exist.

<details>
<summary>Hint — open only after an attempt</summary>

First identify the extreme bounds; then separately test membership.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

For the first three sets, sup=4 and inf=0. For (0,4): neither max nor min; for (0,4]: max=4, no min; for [0,4]: max=4,min=0. For {1,2,3,4}: sup=max=4 and inf=min=1.

</details>

### Q07 — Medium

**Practice variant.** Source: [Bounds, PDF p. 2–3](mathematical_methods/Real%20Analysis/Byu%27s-Notes/BOUND_261009_203646.pdf#page=2).

Prove sup(0,4)=4 using the epsilon characterization.

<details>
<summary>Hint — open only after an attempt</summary>

You need both the upper-bound condition and a point strictly above 4−epsilon for every epsilon>0.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

Every x∈(0,4) is ≤4. For epsilon>0 choose x=4−min(epsilon/2,2). Then x∈(0,4) and x>4−epsilon. Hence 4 is the least upper bound.

</details>

### Q08 — Medium

**Practice variant.** Source: [Bounds, PDF p. 3–4](mathematical_methods/Real%20Analysis/Byu%27s-Notes/BOUND_261009_203646.pdf#page=3).

Prove inf(0,4]=0 using the analogous epsilon characterization.

<details>
<summary>Hint — open only after an attempt</summary>

Show 0≤x for all x in the set, then find x<epsilon.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

For epsilon>0 take x=min(epsilon/2,2). Then x∈(0,4] and x<epsilon. Together with the lower bound this proves inf=0.

</details>

### Q09 — Medium

**Notes example.** Source: [Bounds, PDF p. 1–2](mathematical_methods/Real%20Analysis/Byu%27s-Notes/BOUND_261009_203646.pdf#page=1).

Prove that the positive integers are not bounded above in R. State the property of R you use.

<details>
<summary>Hint — open only after an attempt</summary>

Negate boundedness above: for every real M, find n∈N with n>M.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

By the Archimedean property, such an n exists for every M. Merely listing 101 or one million does not prove the claim for every bound.

</details>

### Q10 — Hard

**Notes example.** Source: [Bounds, PDF p. 5–6](mathematical_methods/Real%20Analysis/Byu%27s-Notes/BOUND_261009_203646.pdf#page=5).

Let A,B be nonempty subsets of R bounded above. Define A+B={a+b:a∈A,b∈B}. Prove sup(A+B)=sup A+sup B.

<details>
<summary>Hint — open only after an attempt</summary>

Prove upper bound first. Then choose one element from each set within epsilon/2 of its supremum.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

Let alpha=sup A,beta=sup B. Every a+b≤alpha+beta. Given epsilon>0, choose a>alpha−epsilon/2 and b>beta−epsilon/2; then a+b>alpha+beta−epsilon. Therefore alpha+beta is the supremum.

</details>

## Sequences

### Q11 — Easy

**Notes example.** Source: [Sequences, PDF p. 2–3](mathematical_methods/Real%20Analysis/Byu%27s-Notes/SEQUENCE_261007_224724.pdf#page=2).

State the epsilon–N definition of a_n→L, with quantifiers in the correct order. Explain what N may depend on.

<details>
<summary>Hint — open only after an attempt</summary>

Epsilon is arbitrary; N is chosen afterwards; every sufficiently late term must work.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

For every epsilon>0 there exists N∈N such that for every n≥N, |a_n−L|<epsilon. N may depend on epsilon and the sequence, but cannot be chosen separately for each later n.

</details>

### Q12 — Medium

**Notes example.** Source: [Sequences, PDF p. 2–3](mathematical_methods/Real%20Analysis/Byu%27s-Notes/SEQUENCE_261007_224724.pdf#page=2).

Prove 1/n→0 directly from the definition, giving an explicit integer N.

<details>
<summary>Hint — open only after an attempt</summary>

Solve 1/n<epsilon backwards, then write the proof forwards.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

Choose N=floor(1/epsilon)+1. For every n≥N, n>1/epsilon, so |1/n|<epsilon.

</details>

### Q13 — Medium

**Practice variant.** Source: [Sequences, PDF p. 1–3](mathematical_methods/Real%20Analysis/Byu%27s-Notes/SEQUENCE_261007_224724.pdf#page=1).

Prove 1−1/n→1 using the epsilon–N definition.

<details>
<summary>Hint — open only after an attempt</summary>

Simplify |(1−1/n)−1| before choosing N.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

The error equals 1/n. The same N as Q12 works.

</details>

## More sequences

### Q14 — Medium

**Notes example.** Source: [More sequences, PDF p. 4](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Notes_261009_203531.pdf#page=4).

Prove (3n+1)/(2n²+n)→0 directly.

<details>
<summary>Hint — open only after an attempt</summary>

Use 1/n+1/(2n+1), or bound the whole expression by a constant times 1/n.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

The expression equals 1/n+1/(2n+1)<3/(2n). Choose N=floor(3/(2epsilon))+1, then every n≥N gives an error less than epsilon.

</details>

### Q15 — Medium

**Notes example.** Source: [More sequences, PDF p. 4–6](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Notes_261009_203531.pdf#page=4).

Prove 1/(−2)^n→0. Explain why alternating signs do not prevent convergence here.

<details>
<summary>Hint — open only after an attempt</summary>

The absolute error is 2^(−n); control its size, not its sign.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

Choose N=max(1,floor(log₂(1/epsilon))+1). Then n≥N implies 2^(−n)<epsilon. The magnitude tends to zero despite the alternating signs.

</details>

### Q16 — Medium

**Notes example.** Source: [More sequences, PDF p. 4](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Notes_261009_203531.pdf#page=4).

Show that −n² has no finite real limit.

<details>
<summary>Hint — open only after an attempt</summary>

Suppose its limit were L∈R and try epsilon=1. Make n² larger than |L|+1.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

For every N choose n≥N with n²>|L|+1. Then |−n²−L|≥n²−|L|>1, contradicting convergence to L. It tends to −∞, which is not convergence to a finite real number.

</details>

### Q17 — Medium

**Notes example.** Source: [More sequences, PDF p. 1–3](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Notes_261009_203531.pdf#page=1).

A sequence equals 1/((n−4)(n−7)) except a_4=10 and a_7=2. Prove it tends to 0. Also explain why 1/(n−4), with no value specified at n=4, is not a sequence defined on all positive integers.

<details>
<summary>Hint — open only after an attempt</summary>

Choose N beyond the exceptional indices as well as large enough for the error bound.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

For n≥14, n−4≥n/2 and n−7≥n/2, so |a_n|≤4/n². Choose N=max(14,floor(2/sqrt(epsilon))+1). The exceptional terms are before the chosen tail. The second formula has no value at index 4 until that value is supplied.

</details>

### Q18 — Hard

**Practice variant.** Source: [More sequences, PDF p. 1–3](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Notes_261009_203531.pdf#page=1).

Prove that changing finitely many terms of a convergent sequence does not change its limit.

<details>
<summary>Hint — open only after an attempt</summary>

Let K be the largest changed index; combine it with the original cutoff.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

If b_n=a_n for n>K and a_n→L, choose N=max(N_epsilon,K+1). For n≥N, |b_n−L|=|a_n−L|<epsilon.

</details>

### Q19 — Hard

**Practice variant.** Source: [More sequences, PDF p. 3](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Notes_261009_203531.pdf#page=3).

If a_n→a and b_n→b, prove a_n+b_n→a+b using epsilon/2. Why choose max(N_1,N_2), not min(N_1,N_2)?

<details>
<summary>Hint — open only after an attempt</summary>

Use the triangle inequality and make both tail estimates hold simultaneously.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

Choose cutoffs for |a_n−a|<epsilon/2 and |b_n−b|<epsilon/2, then N=max(N_1,N_2). The sum error is less than epsilon. The minimum need not lie beyond both cutoffs.

</details>

## Metrics

### Q20 — Medium

**Notes example.** Source: [Metrics, PDF p. 1](mathematical_methods/Real%20Analysis/Byu%27s-Notes/NOTES_261011_225240.pdf#page=1).

Prove d(x,y)=|x−y| is a metric on R.

<details>
<summary>Hint — open only after an attempt</summary>

Write all four axioms and prove each; cite the absolute-value triangle inequality for the last.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

Nonnegativity; |x−y|=0 iff x=y; |x−y|=|y−x|; |x−z|≤|x−y|+|y−z|.

</details>

### Q21 — Medium

**Notes example.** Source: [Metrics, PDF p. 1](mathematical_methods/Real%20Analysis/Byu%27s-Notes/NOTES_261011_225240.pdf#page=1).

Which fail to be metrics on R? (a) x−y; (b) |x²−y²|; (c) |x−2y|; (d) (x−y)². Give one decisive counterexample for each.

<details>
<summary>Hint — open only after an attempt</summary>

To disprove a metric, one failed axiom is enough. Try equal points, opposite points, or 0,1,2.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

(a) d(0,1)=−1 violates nonnegativity. (b) d(−1,1)=0 with unequal points. (c) d(1,1)=1 violates zero self-distance. (d) d(0,2)=4>1+1=d(0,1)+d(1,2) violates the triangle inequality.

</details>

### Q22 — Medium

**Notes example.** Source: [Metrics, PDF p. 2](mathematical_methods/Real%20Analysis/Byu%27s-Notes/NOTES_261011_225240.pdf#page=2).

On X={a,b,c}, let d(x,y)=0 if x=y and 1 otherwise. Prove it is a metric; compute open balls for 0<r≤1 and r>1. Are {a}, {a,b} and X open?

<details>
<summary>Hint — open only after an attempt</summary>

For the triangle inequality, when x≠z at least one of x≠y or y≠z holds.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

It is the discrete metric. B(x,r)={x} for 0<r≤1 and X for r>1. Every subset is open: at any member choose r=1/2. In particular all three named sets are open.

</details>

### Q23 — Hard

**Notes example, domain clarified.** Source: [Metrics, PDF p. 2](mathematical_methods/Real%20Analysis/Byu%27s-Notes/NOTES_261011_225240.pdf#page=2).

For x=(x_1,x_2), y=(y_1,y_2) in R², prove d(x,y)=max(|x_1−y_1|,|x_2−y_2|) is a metric.

<details>
<summary>Hint — open only after an attempt</summary>

Bound each coordinate difference by d(x,y)+d(y,z), then take the maximum.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

For i=1,2, |x_i−z_i|≤|x_i−y_i|+|y_i−z_i|≤d(x,y)+d(y,z). Hence the maximum obeys the triangle inequality. Nonnegativity, symmetry, and zero distance iff both coordinates agree establish the other axioms.

</details>

### Q24 — Medium

**Notes example / practice variant.** Source: [Metrics, PDF p. 3](mathematical_methods/Real%20Analysis/Byu%27s-Notes/NOTES_261011_225240.pdf#page=3).

With the usual metric on R: compute B(2,3) and the closed ball of radius 3; prove (−10,10) is open; prove its complement is closed.

<details>
<summary>Hint — open only after an attempt</summary>

For a ball solve |y−2|<3. For openness choose a radius smaller than the distance to either endpoint.

</details>

<details>
<summary>Answer / proof checkpoint</summary>

Open ball (−1,5), closed ball [−1,5]. For x∈(−10,10), take r=(10−|x|)/2>0; if |y−x|<r then |y|<10. The complement (−∞,−10]∪[10,∞) is closed because its complement is open.

</details>

## Corrections to keep beside the notes

- For A_n=[0,n/(n+1)], the union is **[0,1)**, not [0,1]: approaching an endpoint does not put it in any member set.
- To disprove a lower bound c, exhibit an element x of the set with x<c. Whether c belongs to the set is not the test.
- The supremum approximation is conveniently written: for every epsilon>0, some x∈S satisfies sup S−epsilon<x≤sup S.
- A sequence is a function N→R: R is the **codomain**; its actual range need not equal R. Choose the cutoff N as a positive integer.
- Read “matrix space” in the distance notes as **metric space**. Open balls use d(x,y)<r; closed balls use ≤r.
- A set is open iff its **complement is closed**. A set need not itself be either open or closed exclusively: both and neither are possible.
- The max-coordinate distance exercise is on R², not on a single real coordinate.
- Do not memorize the unclear short lemma on Metrics p.4 without the complete statement; it is not used as a theorem here.
