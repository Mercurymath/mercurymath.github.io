## Real Analysis

Brief summary: 
```
Real analysis is the branch of mathematical analysis which studies real numbers, sequences, series of real numbers and real functions. It is distinguished from complex analysis which focuses on complex numbers and their functions. This report will include properties of real-valued sequences and functions, ranging from limit, convergence and continuity to differentiability and integrability
```

### Markdown

1.Sequences and Limits

The notion of sequence is central in real analysis. Among sequences, convergent sequences are a particularly important branch. Based on convergent sequences, the notion of a convergent series will also be introduced in this chapter.

1.1 Sequences

In General, a sequence is function f:N→R, with a domain being usually taken to be natural numbers. The general term of the function is denoted as (an)=(an)n∈N=(a1,a2,a3,⋯)
  1.2 Sequences converging to a limit
A sequence tending to a limit is said to be convergent. Otherwise it is divergent. 
By definition, a sequence (an)n∈N converges to a limit a ∈ R if for all ⍷ ≥ 0, there always exists a natural number N, such that for any natural number n, if n>N, then |an - a| < ⍷. We can write this as lim(an) = a or an approaches a as n approaches positive infinity. As we can imply from this definition, the value of  an fluctuates around the limit a without deviating from a farther than ⍷. This range is thus called the ⍷-neighbourhood of the point an. Specially, sequences whose terms tend to 0 are called null sequences. In other words, (an)n∈N is a null sequence if and only if for any ⍷ > 0, all the elements of the sequence belong to the ⍷-neighbourhood of zero, apart from only finitely many.
Convergent sequences have several properties. 
•A sequence can have at most one limit. In other words, the limit of a sequence is unique
•Any convergent sequence is bounded. A sequence is said to be bounded only if there exists a real number M such that for all natural number n, |an| < M
•If the limit of a sequence is not zero, then there exists a natural number N such that for any natural number n, if n > N, then |an|>1\2 |a|             
Proof: Fix ⍷ to be 1\2 |a| > 0. Then there exists a natural number N such that for all n > N, 

                 
This implies that |an| > |a| - 1\2 |a| = 1\2 |a|. 
Proceeding from this, we can get further implications of this theorem


Consider two cases: 
Case 1: a > 0, then for n>N 
Case 2: a < 0, then for n>N

•For any two real sequences an and bn which tend to a and b respectively, if for all natural numbers n, an ≥ bn, then a ≥ b.
•The Sandwich rule: if all any natural number n, an ≤ bn ≤ cn and both an and cn tend to a, then bn also tends to a
Proof: Let ⍷ > 0. 
Then we can find two natural numbers such that 

Then choosing N to be max{N1,N2}, it’s easy to deduce that 


•For any two real sequences an and bn which tend to a and b respectively, 
A.The limit of (an + bn) tends to (a + b)

B.The limit of (an - bn) tends to (a - b)
C.The limit of (anbn) tends to ab
D.The limit of (an / bn) tends to a / b, if b ≠ 0
•Proof for A : Choosing N1 such that for all n>N1,  |an - a| < ⍷/2. Choosing N2 such that for all n>N2, |bn - b| < ⍷/2. 
   Then for all n>max{N1,N2}, 


•Proof for B: Similar to proof for A, choosing N1 such that for all n>N1,  |an - a| < ⍷/2. Choosing N2 such that for all n>N2, |bn - b| < ⍷/2. 
   Then |an - a| + |bn - b| < ⍷ and |an - a| + |bn - b| >= |(an - bn) - (a - b)|.
   Hence, |(an - bn) - (a - b)| < ⍷, for all n>max{N1,N2}
•Proof for C: Since both sequences an and bn are convergence, they are also bounded. Let K be such that for n, |an|<=K and |bn|<=K.
   Then we have,

   Choosing N1 such that for all n>N1,  K|an - a| < ⍷/2 and N2 such that for all n>N2, 
   K|bn - b| < ⍷/2. Then for all
•Proof for D: 











