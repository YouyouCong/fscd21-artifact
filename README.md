# A Functional Abstraction of Typed Invocation Contexts (Artifact)

This artifact includes an Agda formalization of our typed calculus of
`control`/`prompt` and CPS translation.
The code is checked using Agda version 2.6.0.1.

- `lambdaf.agda`: The λF calculus presented in Sections 3 and 5.
The function `go` serves as the proof of termination (Theorem 4).
The expression `exp4` represents the motivating example from Section 2.

- `lambdaf-red.agda`: The reduction rules of λF.
The relation `Reduce` serves as the proof of preservation (Theorem 1).

- `cps.agda`: The λC calculus and CPS translation presented in Sections 
4 and 6.
The cpse function serves as the proof of type preservation (Theorem 3).

- `lambdac-red.agda`: The reduction rules of λC.
The relation `Reduce` serves as the proof of the preservation property.
