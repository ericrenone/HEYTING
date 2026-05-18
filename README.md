# HEYTING

**Three Texts of Brouwer, 1927 and 1952: The Intuitionistic Continuum, the Dialogue with Formalism, and the Two Acts — What Constructive Mathematics Actually Requires, and What That Standard Asks of Any Framework**

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone

---

> "Historical background, principles and methods of intuitionism." — L. E. J. Brouwer, *South African Journal of Science* **49**, 139–146 (1952)

> Arend Heyting, Brouwer's student, formalized intuitionistic logic in 1930 and edited the *Collected Works*. The document is named for him because he is the figure who made Brouwer's philosophy precise enough to be used — and the standard below is, in the end, Heyting's standard.

---

## Why This Document

This is an expository document. It does not propose a framework, announce a theorem, or claim a discovery. It reads three specific texts of L. E. J. Brouwer — the 1927 paper on the domains of definition of functions, the 1927 note on intuitionistic reflections on formalism, and the 1952 retrospective on the principles of intuitionism — and explains what they say, accurately, in the order that makes the thread between them visible.

The reason to do this carefully is that intuitionism is the part of mathematics most concerned with a single question: **when has a mathematical claim actually been earned?** Brouwer's answer is exact and demanding, and it is the answer Heyting later made formal. The final section of this document turns that standard around to face the kind of work this corpus produces — not as decoration, and not by claiming any framework "is" intuitionism, but because a standard for when a claim is earned is exactly the thing a body of speculative documents most needs pointed at it. The three texts come first, on their own terms. The reflection comes last, and is marked as reflection.

---

## Part I · 1927: "On the Domains of Definition of Functions"

### I.1 The Setting

By 1927 Brouwer had been developing intuitionistic mathematics for two decades, and this paper is where its treatment of the continuum — the real line — reaches its decisive technical form. The classical continuum is a completed set of points, each real number a finished object, the whole line given all at once. Brouwer rejected this. A completed infinite totality is not something the mathematician constructs; it is something the mathematician postulates, and intuitionism does not postulate. The paper builds the continuum a different way.

### I.2 Choice Sequences

The construction rests on the **choice sequence**: an infinite sequence whose terms are produced one at a time by successive free choices, and which is *never completed*. A choice sequence is not a finished object with all its values fixed in advance. It is an object always in growth — at any moment only a finite initial segment exists, and the future terms are genuinely not yet determined.

This is the radical move, and it is worth stating plainly because it is the source of everything that follows. A real number, intuitionistically, can be given by such a sequence — a sequence of nested intervals, say, each chosen to lie inside the last, converging but never arriving. The real number is the ongoing process, not a point waiting at the end of it. The continuum is then not a set of completed points; it is the *medium* of such unfinished sequences, and it has, in Brouwer's word, a viscosity — its points cannot be cleanly separated from one another the way classical points can, because the points themselves are processes still underway.

### I.3 The Continuity Theorem

From this Brouwer drew a conclusion that sounds, to a classically trained ear, simply false: **every function defined on the whole continuum — every total real function on the unit interval — is continuous.** Classically there are discontinuous functions everywhere; the step function that is 0 below a point and 1 above it is the first example anyone meets. Brouwer's theorem says that intuitionistically there are none.

The reason is not a different theorem about the same objects; it is that the objects are different. A function, intuitionistically, must take a real number as input — and a real number is a choice sequence, of which only a finite initial segment is ever available. If the function is to deliver an output, it must do so on the basis of finite information about the input, because finite information is all there ever is. A function whose value at a point depended on the *completed* infinite sequence would be asking for something that does not exist. So the value must be determined by some finite initial segment — and a function determined by finite initial segments cannot make the sudden jump that a discontinuity requires. The step function is not a counterexample; it is not an intuitionistic function at all, because to evaluate it at the jump you would need to know the input exactly, which means completing an uncompletable sequence.

The continuity theorem, sometimes called the negative continuity theorem in this 1927 form, is therefore not a surprising fact about familiar functions. It is the direct consequence of taking seriously that the input to a function is an object given only through its finite approximations. The technical machinery the paper develops to make this rigorous — the analysis of how a function reads initial segments, what later became the *bar theorem* and the *fan theorem* — is the apparatus of modern constructive analysis, and it all flows from the single insistence that infinite objects are accessed only through finite windows.

---

## Part II · 1927: "Intuitionistic Reflections on Formalism"

### II.1 The Dialogue Brouwer Proposed

The second 1927 text is short — a few pages — and it is the most diplomatic Brouwer ever was toward his opponents. The opposition was Hilbert's formalism: the program of treating mathematics as the manipulation of symbols according to formal rules, with consistency, rather than constructive meaning, as the standard of legitimacy. Brouwer and Hilbert were by this point genuine adversaries. But in this note Brouwer set the polemic aside and listed four specific points on which, he said, intuitionism and formalism might actually enter into a dialogue — four places where the two programs could be compared on the same ground.

### II.2 The Law of the Excluded Middle

Three of those four points concerned the **law of the excluded middle** — the principle that for any proposition P, the statement "P or not-P" is true. Classically this is unquestionable. Intuitionistically it is not, and the reason is the heart of intuitionism.

To an intuitionist, "P or not-P" is a claim that one *has* either a proof of P or a proof of its negation. For a decidable question — is this specific number prime — that is fine: a procedure exists, run it, one of the two outcomes is constructed. But for a general proposition about infinitely many objects, there may be no procedure and no proof in either direction. Consider a property of natural numbers not known to hold always and not known to fail: "either every number has the property, or some number lacks it" asserts a disjunction neither side of which has been established. Classically the disjunction is true regardless, because one side must be the case in a reality independent of us. Intuitionistically the disjunction has not been *earned* — to assert it is to claim a construction one does not possess.

Brouwer's point in the 1927 note is sharp and was, for its moment, conciliatory in form: he was not declaring the formalist simply wrong, he was identifying excluded middle as the precise location where the two programs diverge, and inviting it to be examined there. The divergence is not a matter of taste. It is the difference between mathematics as the description of a pre-existing realm of facts — where every proposition already has a truth value waiting to be found — and mathematics as human construction — where a proposition has a status only once a construction has conferred one. Excluded middle is valid in the first picture and not in the second. Everything else follows from which picture one holds.

---

## Part III · 1952: "Historical Background, Principles, and Methods of Intuitionism"

### III.1 The Retrospective

The 1952 paper, written near the end of Brouwer's career, is the clearest single statement of the whole program. It is retrospective and synthetic, and it organizes intuitionism around **two acts** — two foundational moves of the mathematical mind from which, Brouwer claims, the entire subject is built.

### III.2 The First Act

The **first act of intuitionism** separates mathematics from language and logic entirely, and locates its origin in a single source: the mind's perception of the *move of time* — the falling-apart of a moment of life into two distinct things, one giving way to the next. From this bare intuition of two-ness, repeated, comes the sequence of natural numbers, and with it all of finite, discrete mathematics. The first act is constructive in the strictest sense and asks for nothing beyond the basic intuition. On its basis, Brouwer notes, ordinary discrete mathematics can be rebuilt — in slightly modified form — without trouble, because for natural numbers equality is decidable and the troublesome disjunctions are, there, genuinely earned.

But the first act alone has a cost, and Brouwer states it without flinching: with excluded middle rejected and the classical completed continuum gone, one might fear that intuitionistic mathematics must be, in his words, poor and anaemic — that analysis, the mathematics of the continuum, would have no home. The first act gives the natural numbers and stops.

### III.3 The Second Act

The **second act** is what rescues analysis, and it is the admission of exactly the object Part I described. The second act permits the mathematician to form infinite sequences whose terms are chosen freely — choice sequences — and also to form new mathematical entities by stipulating properties that earlier-constructed objects may or may not have. The choice sequence is the engine. It is what allows the continuum to be constructed *as a medium of unfinished processes* rather than postulated as a completed set, and so it is the second act that gives intuitionism its continuum and, with it, analysis.

The continuum so constructed is not the classical one with some parts removed. It is a differently built object, with properties the classical line does not have — the continuity theorem of Part I is one of them — and lacking properties the classical line is assumed to have, such as being decomposable into two disjoint nonempty pieces. Brouwer's 1952 framing makes the architecture explicit: two acts, the first giving the discrete, the second giving the continuous, and the whole of intuitionistic mathematics generated from those two and nothing else.

### III.4 The Thread Through the Three Texts

The three texts now read as one argument. The 1927 continuity paper builds the continuum from choice sequences and derives the theorem that all functions are continuous. The 1927 formalism note identifies excluded middle as the exact point of divergence from the classical picture — the principle that the constructive standard cannot accept. The 1952 retrospective names the two acts and shows that the choice sequence of the first paper *is* the content of the second act, and that the rejection of excluded middle in the second paper *is* the restriction imposed by the first. The technical paper, the polemical note, and the late synthesis are three views of a single position: **mathematics is construction, an existence claim requires an exhibited construction, and a continuum honest to that requirement is a medium of unfinished sequences rather than a set of completed points.**

---

## Part IV · The Constructive Standard, and What It Asks

This part is reflection, and is marked as such. It claims no identity between intuitionism and any framework. It does one thing: it takes the standard these three texts establish and asks what that standard, applied honestly, requires of speculative work.

### IV.1 The Standard, Stated

Brouwer's three texts converge on a criterion that Heyting later made formal in the proof interpretation of the logical connectives: **a mathematical claim is earned only when a construction for it has been exhibited.** To assert that an object exists is to produce it, or to produce a procedure that produces it. To assert "P or Q" is to have settled which. To assert "P implies Q" is to hold an actual method converting any construction of P into one of Q. An assertion backed by no construction is not a weaker result; under this standard it is not a result at all.

The standard is demanding, and that is its purpose. It is precisely a filter against claims that *sound* established but are not — against the disjunction nobody has settled, the existence nobody has witnessed, the implication nobody can carry out.

### IV.2 What It Asks of a Framework

A body of work that names mathematical objects and asserts relationships among them can be held to this standard, and the question it poses is simple: for each asserted relationship, where is the construction?

When a document states that one structure *is* another — that a renormalization-group flow *is* a particular equation, that a class of physical anomalies *is* a single estimable parameter, that a fundamental domain *is* a partition — the constructive standard asks for the exhibited map. Not a resemblance, not a suggestive parallel: a construction, in the precise sense, that takes any instance of the one and produces the corresponding instance of the other, and back. If that construction exists and is shown, the identity is earned. If it does not, the word "is" is doing work no construction supports — and by Brouwer's standard the claim has the status the unproved disjunction has, which is none.

This is the honest use of these three texts. They do not supply a framework. They supply a criterion, and the criterion is usable. Applied to any document, including the speculative documents this corpus contains, it sorts the claims into two piles: those for which a construction can be exhibited — a computation run, a theorem proved, a map written down and checked — and those for which only the word "is" is present. The first pile is earned. The second is not yet anything. Brouwer would not soften that, and the value of reading him is that he does not let it be softened.

### IV.3 The Closing Point

Intuitionism is sometimes described as a restriction — a mathematics that gives things up, that forbids excluded middle and loses the completed continuum. The 1952 paper shows that this is the wrong reading. The second act *builds* a continuum; intuitionism is generative, not merely prohibitive. But what it generates, it generates under a discipline: nothing is asserted that has not been constructed. The discipline is not the price of the mathematics. The discipline is what makes the mathematics trustworthy.

That is the whole of what these three texts offer a reader working on speculative frameworks: not a new structure to identify with col(F) and ker(F), but a question to ask of every line — *has this been constructed, or only asserted?* — and the resolve, which Brouwer had and which is the hardest part, to keep only the lines that pass.

---

## References

Brouwer, L. E. J. "Über Definitionsbereiche von Funktionen" ["On the Domains of Definition of Functions"]. *Mathematische Annalen* **97**, 60–75 (1927). English translation in van Heijenoort, *From Frege to Gödel* (1967).

Brouwer, L. E. J. "Intuitionistische Betrachtungen über den Formalismus" ["Intuitionistic Reflections on Formalism"] (1927). English translation in Mancosu, *From Brouwer to Hilbert* (1998), and in van Heijenoort (1967), 490–492.

Brouwer, L. E. J. "Historical Background, Principles and Methods of Intuitionism." *South African Journal of Science* **49**, 139–146 (1952).

Brouwer, L. E. J. *Collected Works, Volume I: Philosophy and Foundations of Mathematics.* A. Heyting (ed.). North-Holland, Amsterdam, 1975.

Brouwer, L. E. J. *Collected Works, Volume II: Geometry, Analysis, Topology and Mechanics.* H. Freudenthal (ed.). North-Holland, Amsterdam, 1976.

Brouwer, L. E. J. *Brouwer's Cambridge Lectures on Intuitionism.* D. van Dalen (ed.). Cambridge University Press, 1981.

Heyting, A. "Die formalen Regeln der intuitionistischen Logik" (1930). On the formalization of intuitionistic logic.

Heyting, A. *Intuitionism: An Introduction.* North-Holland, Amsterdam, 1956.

van Stigt, W. P. *Brouwer's Intuitionism.* North-Holland, Amsterdam, 1990.

van Atten, M. *On Brouwer.* Wadsworth, 2004.

Troelstra, A. S., van Dalen, D. *Constructivism in Mathematics: An Introduction.* North-Holland, Amsterdam, 1988.

Stanford Encyclopedia of Philosophy, "Intuitionism in the Philosophy of Mathematics" and "The Development of Intuitionistic Logic."

---

ERI Labs · Eric Ren · Jersey City, New Jersey · github.com/ericrenone · May 2026

Three texts, one standard: mathematics is construction, and an existence claim requires an exhibited construction. The continuum is built from unfinished sequences; the excluded middle is the point where the constructive picture parts from the classical one; the two acts generate the whole. The standard is usable now — of every asserted identity it asks where the construction is, and keeps only the lines that answer.
