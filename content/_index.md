This course is an introduction to *interactive theorem proving* using the proof assistant [Lean](https://lean-lang.org/). Interactive theorem proving can be used to formalize mathematics and to verify the correctness of programs. We will discuss both aspects in this course.

Formalizing mathematics in Lean involves stating and proving mathematical results, with Lean checking the correctness of the proofs as well as assisting in completion of the proofs. This not only guarantees the correctness of the results but also facilitates large-scale collaboration and the use of computer algebra systems, as trust is much less of an issue than in pen-and-paper mathematics. Formalizing a results also forces one to be precise about definitions and assumptions, which can lead to a deeper understanding of the mathematics.

Lean can also be viewed as a programming language. From this viwepoint it is pleasant and fast -- indeed fast enough that Lean is mostly written in Lean. It has a type system that is rich enough to formalize all of mathematics, allowing functions to be defined in such a way that the compiler can check that they are correct by construction. This is a powerful tool for writing correct programs, and for verifying that they are correct. Indeed, this course can also be viewed as an introduction to functional programming in Lean.

While this course will not involve AI/ML directly, in many ways Interactive Theorem Proving perfectly complements Deep Learning, in particular Generative AI. Generative AI is powerful but unreliable, so combining with Interactive Theorem Proving allows checking the results of Generative AI. Indeed many systems, such as AlphaProof, combine Deep Learning and Interactive Theorem Proving.

##### Prerequisites

The only prerequisites for this course are:

* Knowing what a mathematical proof is. For instance, having taken UM 101 or any course in the mathematics department.
* Knowing very basic programming in some programming language: `if` statements, `for` loops, and functions.

In particular, no knowledge of Lean of formal logic is required.