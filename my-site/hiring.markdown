I recently joined IMDEA and looking for talented Ph.D. students and interns
to work with. 


Projects 
---------

My current open projects focus on how to 
establish [Liquid Haskell](https://ucsd-progsys.github.io/liquidhaskell-blog/) 
as a practical and useful theorem prover. 
Ideas I would like to explore include:

- **Integration with Compiler & Compiler Optimizations:**
The major goal of verification is to prove that your code satisfies 
certain correctness properties. 
But, once you correctness properties are proved, the compiler could use them 
to optimize the running times. 
For example properties like associativity, 
map fusion, and class laws could, and should, be used
for provably correct compiler optimizations. 
The goal of this project is how the Haskell compiler 
can automatically take full advantage of
Liquid Haskell generated proofs. 

- **Error Reporting:** 
Error messages are terrible! 
This is the case in most systems that include type inference, see `ghc`, 
and Liquid Haskell is not an exception. 
[Recently](https://nikivazou.github.io/static/oopsla18main-p124-p.pdf), the idea of using gradual types for error explanation was explored. 
The goal of this project is to further explore the interaction between 
gradual types and error reporting, or use further concepts, such as testing
to aid error explanation.

- **Interactive Proving Environment:**
For theorem proving to be usable, proof generation should be interactively directed by the prover. 
Towards this goal, this project aims to investigate how existing
techniques such as tactics and interactive environments from interactive theorem provers like Coq
and Isabelle/HOL can be adapted to aid proof generation in Liquid Haskell. At the same time,
proof generation can be aided by Haskell’s code generation infrastructures such as the automatic
code derivation mechanisms.


My passion is functional programing and practical program
verification, so I am happy to discuss new research ideas in any of these directions. 




Requirements
------------

If you want to apply for a Ph.D. position 
you are required to an undergraduate degree in Computer Science or a closely related area and have strong interest in functional programming.


About IMDEA: 
------------------

The [IMDEA Software Institute](https://software.imdea.org/index.html) is [ranked](http://csrankings.org/#/index?plan&europe) among the best european institutes in the areas of 
Programming Languages and Computer Security.
Located in the [Montegancedo Science and Technology Park](https://software.imdea.org/contact_and_directions/building.html) 
it perfectly combines 
the sunny and vibrant city of Madrid with 
cutting edge research and competitive salaries. 


How to apply?
-------------
To apply send me an email at niki.vazou@imdea.org 
with your CV and submit an online application at IMDEA's 
[open positions](http://software.imdea.org/open_positions.html).



