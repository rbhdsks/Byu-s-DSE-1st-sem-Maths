# Real Analysis: Question-Solving and PYQ Strategy

[24 notes-based questions, hints and answer checks](real_analysis_questions.md)

## What this plan is based on

The uploaded notes cover indexed sets and De Morgan laws; bounds, supremum and infimum; sequences and epsilon–N proofs; metric axioms, balls and open/closed sets. The aim is to practise **turning a definition into the first line of a solution**, especially when a question feels unfamiliar.

**No actual PYQ paper is present among these files.** The process below is a PYQ-solving strategy, not an analysis of previous exam trends. The accompanying questions are not claimed to be PYQs. A year-wise selection requires the actual papers, their course/exam identity and any exam instructions.

## 1. The first three minutes when you feel blank

Write these four lines before looking at a solution:

1. **Given:** What set, sequence, function, metric or assumptions are supplied?
2. **Target:** What exactly must I compute, prove or disprove?
3. **Definition:** Translate the target into its mathematical definition.
4. **First move:** Choose an arbitrary element, simplify an error, check a metric axiom, or look for a counterexample.

You do not need the whole proof in your head before writing the first line. If the definition is missing, revisit just that definition and retry. If the definition is known but the next move is missing, use one hint rather than reading the full answer.

## 2. Match the question to a proof pattern

| Question cue | First line / move | What finishes the answer | Practice |
|---|---|---|---|
| Union or intersection of indexed sets | Write the first three members, then take arbitrary x | Prove membership/nonmembership; check endpoints and index starting value | Q01–Q03 |
| Prove a set identity | Let x be arbitrary in the common universe | Translate membership through iff statements, or prove both inclusions | Q04 |
| Universal statement | Represent arbitrary objects algebraically | A general argument, not a list of numerical checks | Q05 |
| Find supremum / infimum | Guess a candidate; write the bound inequality | Show it is a bound AND no tighter bound works; epsilon witness is useful | Q06–Q10 |
| Prove a_n→L | Let epsilon>0; simplify abs(a_n−L) on scratch paper | Choose integer N(epsilon); verify the inequality for every n≥N | Q11–Q15 |
| Show no finite limit | Suppose a candidate L exists, or negate convergence | Give a fixed error tolerance with arbitrarily late violations | Q16 |
| Finite changes or multiple cutoffs | Write down all indices beyond which conditions hold | Use their maximum; the tail must satisfy every required condition | Q17–Q19 |
| Is this a metric? | List nonnegativity, identity, symmetry, triangle inequality | Prove all axioms if yes; one explicit failure if no | Q20–Q23 |
| Find an open ball | Write {y:d(x,y)<r} | Solve the inequality and check equality at boundary radii | Q22,Q24 |
| Show A is open | Let x∈A; seek r(x)>0 | Prove every y with d(x,y)<r lies in A | Q24 |
| Show A is closed | Consider X minus A | Prove the complement open in the stated ambient space | Q24 |

The absolute-error expression in the convergence row is `abs(a_n−L)`; calculate it before choosing N.

## 3. A complete model of the thought process

**Task:** prove (3n+1)/(2n²+n)→0 (More sequences, p.4).

**Scratch work, backwards:** the target is an error less than epsilon. Split the expression:

(3n+1)/(2n²+n) = 1/n + 1/(2n+1) < 3/(2n).

It is enough to make 3/(2n)<epsilon, or n>3/(2epsilon).

**Final proof, forwards:** let epsilon>0. Choose the integer N=floor(3/(2epsilon))+1. For every n≥N, the error is less than 3/(2n)<epsilon. Therefore the sequence converges to zero.

**Transfer question:** now try (4n+1)/(3n²+n)→0 without copying the proof. This is an original practice variant, not a PYQ. For n≥1, the error is at most 5/(3n); choosing N>5/(3epsilon) works.

The transferable skill is finding a simple upper bound on the error. Memorizing the particular numerator does not help with the next question.

## 4. Hints and retry rules

Use these as adjustable practice timings, not exam rules:

- Easy question: attempt about 5–8 minutes.
- Medium: about 10–15 minutes.
- Hard proof: about 15–20 minutes, including a written plan.

If stuck, identify the exact blockage: definition, algebra, witness/counterexample, theorem choice, or proof writing. Open only the hint. Try again for five minutes. If needed, inspect the proof checkpoint, close it, and reproduce the reasoning on a blank page. Retry the same question the next day and a changed version a few days later.

Record **independent / one hint / solution seen**, not just “done.” Being able to follow a solution is different from being able to start it unaided.

## 5. Five starter sessions

Each session is a suggested **75 minutes**, adjustable to her timetable. The order follows the available notes, not an assumed exam date.

| Session | Topic | Questions | End-of-session goal |
|---|---|---|---|
| 1 | Indexed sets and proof language | Q01–Q05 | Explain union/existence versus intersection/for all; check the missing endpoint in Q02 |
| 2 | Bounds and extremal values | Q06–Q10 | Write both halves of a supremum proof; attempt the epsilon/2 argument |
| 3 | Direct convergence proofs | Q11–Q16 | Produce an explicit N and verify all later indices; distinguish finite convergence from −∞ |
| 4 | Tails and metric tests | Q17–Q21 | Combine cutoffs with max; give precise counterexamples |
| 5 | Discrete/max metrics and open sets | Q22–Q24, then retry two earlier errors | Choose a radius or metric counterexample without seeing a solution |

Within each session: **10 min** closed-book definitions, **30 min** two or three focused attempts, **15 min** checking, **15 min** rewriting one proof independently, **5 min** error log. The listed questions form a session pool; unfinished hard questions carry forward. Do not rush every listed problem merely to finish in 75 minutes.

After these sessions, mix topics rather than always announcing the chapter. Recognizing the required proof method is part of the practice.

## 6. How to use actual PYQs once available

### Pass A — Map the paper before solving

For each question record the year, question number, exact marks if shown, topic, command verb and matching notes page. Mark questions outside these notes as **coverage gap**, not as something she should already know.

| Year / paper | Question | Marks as printed | Topic and note page | First move | Attempt status | Error / retry date |
|---|---|---|---|---|---|---|
| Fill from actual paper | — | — | — | — | Unattempted | — |

Do not invent years, question numbers, marks or “frequently asked” labels. Keep the original wording, hypotheses and index conventions visible.

### Pass B — Untimed, by question type

Start with an in-scope question whose definition you can state. Try the four-line start. Group related questions initially: supremum proofs together, convergence proofs together, metric counterexamples together. Write full solutions; the aim is to build a method library.

### Pass C — Mixed questions, limited time

Select a small mix across the covered topics. Hide chapter labels. Practise deciding whether the task needs a definition, a witness, an inequality or a counterexample. Start with familiar patterns and add one unfamiliar-looking variant.

### Pass D — Full-paper conditions

Use the actual paper's duration, marks and choice rules. A practical initial allocation is:

**time for a question ≈ usable writing time × its marks / total marks attempted.**

Reserve a modest review buffer, then adjust after a practice paper. If stuck beyond the planned time, write a valid definition or useful partial step, mark the question, and return after attempting other questions. Partial-credit decisions depend on the examiner; do not assume a guaranteed score.

### Pass E — Analyse and reattempt

Classify each error as **concept / method selection / algebra / quantifier or endpoint / incomplete proof / time**. Write one sentence explaining the correction. Retry from a blank page rather than rereading the answer. Keep unseen in-scope questions for a later timed attempt if enough papers are available.

## 7. What to check before calling a proof finished

- Did I use every needed hypothesis and state the ambient space?
- Did I prove a universal claim for arbitrary inputs, not only examples?
- For a supremum, did I establish both the bound and leastness?
- For convergence, did I choose an integer N and verify every n≥N?
- For an open set, is my radius positive and does the whole ball fit?
- For a counterexample, did I name the precise statement/axiom that fails?
- Did I accidentally include an endpoint that is only approached?

## Source notes

- [Sets, PDF p. 1](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Sets%20lec%201_261007_183939.pdf#page=1)
- [Bounds, PDF p. 1](mathematical_methods/Real%20Analysis/Byu%27s-Notes/BOUND_261009_203646.pdf#page=1)
- [Sequences, PDF p. 1](mathematical_methods/Real%20Analysis/Byu%27s-Notes/SEQUENCE_261007_224724.pdf#page=1)
- [More sequences, PDF p. 1](mathematical_methods/Real%20Analysis/Byu%27s-Notes/Notes_261009_203531.pdf#page=1)
- [Metrics, PDF p. 1](mathematical_methods/Real%20Analysis/Byu%27s-Notes/NOTES_261011_225240.pdf#page=1)

Before using the notes as an answer key, read the corrections at the end of the question file. No additional continuity, compactness, differentiation or integration chapters have been added to this starter plan.
