# Priority and Difficulty

[Roadmap](README.md) · [Complete topic checklist](topics.md)

These are **suggested learning-difficulty labels for a beginner**, not lecturer-assigned marks, exam probabilities or an assessment of the learner. Follow the dependency order in the roadmap. Easy units establish notation; medium units build calculation skills; hard units require several concepts or proofs together. A chapter can contain all three levels.

## Priority order

| Pass | Focus | Completion target |
|---|---|---|
| 1 — Foundations first | Core preliminaries; vector spaces, span, bases; row reduction; rank and kernel | Explain definitions and solve small examples independently. |
| 2 — Build applications | Linear maps and coordinates; inner products; projections; Gram-Schmidt; least squares | Show each calculation and state the assumptions behind formulas. |
| 3 — Connect the final block | L5 spectral theory, quadratic forms, congruence and definiteness | Diagonalize a small symmetric form and classify it correctly. |
| 4 — Proof consolidation | Revisit every Proof unit and the derivations behind Core units | Reproduce the argument without copying and explain each assumption. |

Do short proof attempts while studying each block; pass 4 is consolidation, not the first time to see proofs. Orientation units need a brief understanding pass. The Wirtinger route is listed because it appears in L4; understand the direct optimal-scalar proof first and confirm with the lecturer whether both derivations are expected.

## Easy

Start here: notation, recognition and short computations. Revisit these if later work feels confusing.

| ID | Topic / task | Slides | Role |
|---|---|---|---|
| P01 | Linear algebra: vector spaces, linear mappings, lines, planes and applications | [L1 6](mathematical_methods/Sir-slides/002_LS-1_LA_prelim_-_intro%20%282%29_260831_161922.pdf#page=6) | Orientation |
| P02 | Linear versus affine functions; linear equations; nonlinear examples | [L1 7-9](mathematical_methods/Sir-slides/002_LS-1_LA_prelim_-_intro%20%282%29_260831_161922.pdf#page=7) | Core |
| P04 | Vectors, matrices and tensors: introductory illustration | [L1 12](mathematical_methods/Sir-slides/002_LS-1_LA_prelim_-_intro%20%282%29_260831_161922.pdf#page=12) | Orientation |
| P05 | Simultaneous equations; domain, codomain, matrix-vector notation and columns | [L1 13-14](mathematical_methods/Sir-slides/002_LS-1_LA_prelim_-_intro%20%282%29_260831_161922.pdf#page=13) | Core |
| P07 | Two- and three-variable linear systems; row/line/plane picture; column/vector picture; linear combinations | [L1 16-21](mathematical_methods/Sir-slides/002_LS-1_LA_prelim_-_intro%20%282%29_260831_161922.pdf#page=16) | Core |
| P09 | Statements/propositions and truth values; logical connectives | [L2 2](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=2) | Core |
| P10 | Negation, conjunction, inclusive disjunction, implication and biconditional; truth tables; consistency | [L2 3-7](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=3) | Core |
| P16 | Binary operations/composition; closure; algebraic structures | [L2 17-18](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=17) | Core |
| P17 | Associative, commutative and distributive laws; identity elements | [L2 19](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=19) | Core |
| I01 | Complex arithmetic, modulus, conjugation and conjugate transpose | [L4 2-3](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=2) | Core |
| I03 | Euclidean norm and orthogonality | [L4 7](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=7) | Core |
| S01 | Eigenvalue and nonzero eigenvector definitions; scalar multiples and linear combinations; eigenspaces including zero | [L5 2](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=2) | Core |
| S02 | Geometric meaning of Av=lambda v; identity and rotation-axis examples; spectrum notation | [L5 3](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=3) | Core |

## Medium

Practise actively: checking definitions, choosing a method and carrying out several steps.

| ID | Topic / task | Slides | Role |
|---|---|---|---|
| P03 | Taylor expansion and local linear approximation; multivariate linear/quadratic approximation | [L1 10-11](mathematical_methods/Sir-slides/002_LS-1_LA_prelim_-_intro%20%282%29_260831_161922.pdf#page=10) | Orientation |
| P06 | Contour surfaces and existence of solutions to simultaneous equations | [L1 15](mathematical_methods/Sir-slides/002_LS-1_LA_prelim_-_intro%20%282%29_260831_161922.pdf#page=15) | Core |
| P08 | Economics motivation: first-order conditions, general/Nash equilibrium, fixed points, zeros, continuity, intermediate value theorem and Gauss-Jacobi mention | [L1 22](mathematical_methods/Sir-slides/002_LS-1_LA_prelim_-_intro%20%282%29_260831_161922.pdf#page=22) | Orientation |
| P11 | Necessary and sufficient conditions; if, only if, and if and only if | [L2 8-9,30](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=8) | Core |
| P12 | Premise and conclusion; direct proof; contrapositive proof; equivalence of an implication and its contrapositive | [L2 10-12](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=10) | Core |
| P13 | Converse, counterexamples and biconditional examples | [L2 13,28-29](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=13) | Core |
| P14 | Tautology, tautological implication, tautological equivalence and logical inference | [L2 14-15](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=14) | Core |
| P15 | Universal and existential quantifiers; negation and order of quantifiers | [L2 16](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=16) | Core |
| P18 | Groups, inverses and Abelian groups; examples and non-examples | [L2 20](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=20) | Core |
| P19 | Rings and fields; multiplicative inverses; examples over integers, rationals and reals | [L2 21-22](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=21) | Core |
| P20 | Vector spaces over a field; vector addition and scalar multiplication; real, complex and continuous-function examples | [L2 23-24](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=23) | Core |
| P21 | Logic exercises: compound truth tables, exclusive OR and symbolic statements | [L2 25](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=25) | Practice |
| P22 | Algebraic-structure exercises: group checks and justification | [L2 26](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=26) | Practice |
| P23 | Vector-space and field exercises: checking axioms and counterexamples | [L2 27](mathematical_methods/Sir-slides/002_LS-2_LA_prelim_-_Logic_Group_theory%20%281%29_260831_161938.pdf#page=27) | Practice |
| F01 | Vector-space definition, axioms, scalars and examples | [L3 2-4](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=2) | Core |
| F02 | Linear combinations; linear dependence and independence; geometric and algebraic tests | [L3 5-6](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=5) | Core |
| F03 | Span, generators and spanning sets | [L3 7](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=7) | Core |
| F04 | Subspaces, closure tests, zero vector and geometric examples | [L3 8-9](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=8) | Core |
| F05 | Bases, standard bases and dimension; properties of dependent/independent sets | [L3 10-11](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=10) | Core |
| F08 | Linear transformations: definition, linearity checks and rotations | [L3 17-18](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=17) | Core |
| F09 | Range/image/column space; span of columns; rank | [L3 19-21](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=19) | Core |
| F10 | Null space/kernel, nullity and homogeneous solutions | [L3 22-23](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=22) | Core |
| F12 | Systems Ax=b; consistency via column space; homogeneous/nonhomogeneous equations | [L3 27](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=27) | Core |
| F13 | General solution as particular solution plus null space; translated subspace | [L3 28-29](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=28) | Core |
| F15 | Injective and surjective mappings and their interpretation | [L3 33](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=33) | Core |
| F17 | Equivalent systems under invertible left multiplication; elementary matrices and row operations | [L3 36-37](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=36) | Core |
| F18 | Augmented matrix; row reduction; pivots; echelon/RREF; free and dependent variables | [L3 38](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=38) | Core |
| F19 | Unique- and multiple-solution worked examples; parametrization and a null-space basis | [L3 39-41](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=39) | Practice |
| F22 | Composition of linear transformations and matrix multiplication | [L3 46](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=46) | Core |
| I02 | Real/complex inner products; linearity, conjugate symmetry, positivity and notation conventions | [L4 4-6,8](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=4) | Core |
| I08 | Orthogonality to a subspace; testing against a spanning set/basis | [L4 18](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=18) | Core |
| I09 | Orthogonal sets and their independence; orthogonal/orthonormal bases and coordinate coefficients | [L4 19-20](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=19) | Core |
| I10 | Orthogonal projection: definition, geometry, existence/uniqueness and projection onto a line | [L4 21-22](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=21) | Core |
| I11 | Projection onto a multi-vector span; projection matrix and numerical examples | [L4 23-24](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=23) | Core |
| I15 | Annihilator/residual-maker matrix M=I-P; fitted values and residuals | [L4 29](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=29) | Core |
| I16 | Gram-Schmidt orthogonalization and numerical example; normalization | [L4 31-32](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=31) | Core |
| I17 | Least-squares objective and regression interpretation; projection geometry | [L4 33-35](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=33) | Core |
| Q01 | Bilinear forms and their matrix representation | [L6 2](mathematical_methods/Sir-slides/002_LS-6_Quadratic_Forms_260927_161009.pdf#page=2) | Core |
| Q02 | Quadratic forms, diagonal restriction of a bilinear form, cross terms and symmetric representation | [L6 3](mathematical_methods/Sir-slides/002_LS-6_Quadratic_Forms_260927_161009.pdf#page=3) | Core |
| Q07 | Positive/negative definite, positive/negative semidefinite and indefinite forms and matrices | [L6 9](mathematical_methods/Sir-slides/002_LS-6_Quadratic_Forms_260927_161009.pdf#page=9) | Core |
| Q08 | Leading principal minors and the positive-definiteness test; determinant computations as needed | [L6 10](mathematical_methods/Sir-slides/002_LS-6_Quadratic_Forms_260927_161009.pdf#page=10) | Core |
| Q09 | Eigenvalue sign criteria for definiteness and semidefiniteness | [L6 10](mathematical_methods/Sir-slides/002_LS-6_Quadratic_Forms_260927_161009.pdf#page=10) | Core |
| Q10 | Classification examples, completing squares and graphs of diagonalized quadratic forms | [L6 11-13](mathematical_methods/Sir-slides/002_LS-6_Quadratic_Forms_260927_161009.pdf#page=11) | Practice |
| S03 | Eigenspace as kernel of A-lambda I; rank/nullity and singularity; characteristic polynomial and equation | [L5 4](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=4) | Core |
| S04 | Repeated and complex roots; conjugate pairs for real matrices; characteristic coefficients as elementary symmetric sums of eigenvalues | [L5 5](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=5) | Core |
| S05 | Two-by-two characteristic equation and root formula; trace as eigenvalue sum and determinant as product | [L5 6](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=6) | Core |
| S06 | Distinct real eigenvalues: solving for eigenvectors and eigenspaces | [L5 7](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=7) | Practice |
| S07 | Complex eigenvalues and conjugate eigenvectors of a real matrix; checking complex orthogonality | [L5 8](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=8) | Practice |
| S11 | Orthonormal eigenbasis for a real symmetric matrix; normalization, sign choices and worked example | [L5 13-15](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=13) | Core |
| S12 | Repeated eigenvalues; eigenspace basis by row reduction; free variables and geometric multiplicity | [L5 16-17](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=16) | Practice |
| S15 | Diagonalization as a change to an eigenvector basis; coordinate-wise stretching | [L5 21](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=21) | Core |
| S16 | Spectral applications mentioned: differential equations, econometric specification tests, quadratic forms and frequency-domain time series | [L5 21](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=21) | Orientation |
| S18 | Worked verification of S-transpose A S=D and S-inverse=S-transpose for an orthonormal eigenvector matrix | [L5 23](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=23) | Practice |

## Hard

Reserve extra time: abstract coordinates, connected arguments, theorem assumptions and proofs. These remain part of the plan.

| ID | Topic / task | Slides | Role |
|---|---|---|---|
| F06 | Unique representation in a basis: theorem and proof | [L3 12](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=12) | Proof |
| F07 | Equality of basis sizes; maximal independent/minimal spanning sets; Steinitz exchange idea and dimension proof | [L3 13-16](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=13) | Proof |
| F11 | Rank-nullity theorem, examples and proof | [L3 24-26](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=24) | Proof |
| F14 | Existence and uniqueness by rank: square, underdetermined and overdetermined systems | [L3 30-32](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=30) | Core |
| F16 | Linear implicit function theorem: statement, parameter choices and proof as presented | [L3 34-35](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=34) | Proof |
| F20 | Matrix representation in standard and arbitrary bases; coordinate vectors | [L3 42-44](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=42) | Core |
| F21 | Change-of-basis matrix, coordinate conversion and inverse conversion | [L3 45,47](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=45) | Core |
| F23 | Similarity of matrices and change of basis for an operator | [L3 48](mathematical_methods/Sir-slides/002_LS-3_LA_Foundation%20%282%29_260831_171354.pdf#page=48) | Core |
| I04 | Inner-product identities: conjugate linearity, nondegeneracy and equality tests for vectors/operators | [L4 9](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=9) | Proof |
| I05 | Cauchy-Schwarz inequality and proof: real minimization and complex optimal scalar | [L4 10-13,15](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=10) | Proof |
| I06 | Wirtinger-derivative route in the complex Cauchy-Schwarz proof | [L4 14](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=14) | Alternate proof |
| I07 | Triangle inequality and proof; norm axioms; symmetry of orthogonality | [L4 16-17](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=16) | Proof |
| I12 | Projection-matrix symmetry/self-adjointness, idempotence and singularity conditions | [L4 25](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=25) | Proof |
| I13 | Projection with an orthogonal basis; outer-product formula; linearity of projection | [L4 26-27](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=26) | Core |
| I14 | Orthogonal complement; double complement; unique orthogonal decomposition and direct sum | [L4 28,30](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=28) | Core |
| I18 | Normal equations; least-squares estimator and projection matrix under full column rank | [L4 36-37](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=36) | Core |
| I19 | Invertibility of X*X iff X has full column rank: proof | [L4 38](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=38) | Proof |
| I20 | Adjoint identity and uniqueness of the adjoint | [L4 39](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=39) | Proof |
| I21 | Fundamental subspaces: range/null-space orthogonal-complement identities for A and A* | [L4 40-42](mathematical_methods/Sir-slides/002_LS-4_Inner_product_spaces_260917_183627.pdf#page=40) | Proof |
| Q03 | Nonsingular change of variables; congruence B=S*AS; discriminant and transformation modulus | [L6 4](mathematical_methods/Sir-slides/002_LS-6_Quadratic_Forms_260927_161009.pdf#page=4) | Core |
| Q04 | Eigenvalues, orthonormal eigenvectors and orthogonal matrices used to diagonalize a symmetric quadratic form | [L6 5](mathematical_methods/Sir-slides/002_LS-6_Quadratic_Forms_260927_161009.pdf#page=5) | Core |
| Q05 | Orthogonal diagonalization examples, principal coordinates and an ellipse level set | [L6 6-7](mathematical_methods/Sir-slides/002_LS-6_Quadratic_Forms_260927_161009.pdf#page=6) | Practice |
| Q06 | Range of a quadratic form and invariance under nonsingular change of variables | [L6 8](mathematical_methods/Sir-slides/002_LS-6_Quadratic_Forms_260927_161009.pdf#page=8) | Proof |
| S08 | Similarity and identical spectra; transformation of eigenvectors under a basis change | [L5 9](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=9) | Proof |
| S09 | Real symmetric matrices have real eigenvalues: theorem and proof | [L5 10-11](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=10) | Proof |
| S10 | Orthogonality of eigenvectors for distinct eigenvalues of a real symmetric matrix: proof | [L5 12](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=12) | Proof |
| S13 | Diagonalization from n independent eigenvectors; constructing S and D; proof using AS=SD | [L5 18](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=18) | Proof |
| S14 | Distinct eigenvalues imply independent eigenvectors: induction proof and sufficient condition for diagonalization | [L5 19-20](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=19) | Proof |
| S17 | Orthogonal diagonalization of symmetric matrices; orthogonal coordinate changes and stretches; X*X and Hessian examples | [L5 22](mathematical_methods/Sir-slides/002_LS-5_Spectral_theory_260914_234611.pdf#page=22) | Core |

## What not to infer from these labels

- An easy definition may be essential to a hard proof; do not skip it.
- A numerical example may be medium even when proving its general formula is hard.
- No topic is declared “high marks” or “unlikely in the exam”: past papers and exam guidance were not provided.
- Spectral Theory now follows the uploaded L5 slides. Study it before Q04–Q05 and Q09; do not add book-only spectral topics.
- Do not expand into whole book chapters beyond the slide-matched topics. See the roadmap's parked-material table.

## Ready-to-revise checklist

- [ ] Distinguish necessary/sufficient conditions and negate quantified statements.
- [ ] Test a subspace, find a basis and compute rank/nullity.
- [ ] Solve Ax=b and describe the entire solution set.
- [ ] Change coordinates and represent a linear transformation in a chosen basis.
- [ ] Compute real/complex inner products and prove the basic inequalities.
- [ ] Perform projection and Gram-Schmidt; explain the orthogonal residual.
- [ ] Derive least squares and explain the full-column-rank assumption.
- [ ] Prove the range/kernel orthogonal-complement identities.
- [ ] Find eigenvalues/eigenspaces, handle repeated roots, and explain the diagonalizability condition.
- [ ] Prove the symmetric-matrix spectral results and the independence theorem for distinct eigenvalues.
- [ ] Diagonalize and classify quadratic forms; distinguish similarity from congruence.
- [ ] Review the slide wording cautions before memorizing theorem statements.
