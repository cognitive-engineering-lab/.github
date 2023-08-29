# Cognitive Engineering Lab

[As defined by Don Norman][cognitive-engineering-norman], cognitive engineering is:

> neither Cognitive Psychology, nor Cognitive Science, nor Human Factors. It is a type of applied Cognitive Science, trying to apply what is known from science to the design and construction of machines.

The Cognitive Engineering Lab (CEL) is a research organization for creating human-centered software systems. Our goal is to use computers to support complex cognitive tasks: programming, technical communication, learning, and so on. We apply theories of human cognitive capabilities and limitations to understand how computers can best provide such cognitive support.

CEL is led by [Will Crichton], a postdoctoral researcher at Brown University (who's on the job market right now!). The current focus of CEL is to supersede two venerable languages whose time has long since passed: C and TeX. With regards to C, we focus on improving the usability of [Rust], a language for safe systems programming. Our Rust projects include:
* [The Rust Book Experiment]: a scientific approach to the improvement of how we teach Rust at scale. Includes:
  * [Aquascope]: a Rust compiler plugin to visualize ownership at compile-time and run-time.
  * [mdbook-quiz]: an mdBook extension to embed interactive quizzes into web-based textbooks.
  * [Quizicist]: a tool that automatically generates quiz questions from textbook content using LLMs.
* [Flowistry](https://github.com/willcrichton/flowistry): a static information flow analysis for Rust, incorporated into the IDE as a program slicer.
* The Trait Debugger: an ongoing project to make programs involving complex systems of trait constraints easier to debug.

With regards to TeX, we believe there is no clear and worthy successor language, so we are building one. Our document-related projects include:
* [Nota](https://nota-lang.org/): a document language for the 21st century.
* The Document Calculus: an ongoing project to formalize the semantics of document languages.

[cognitive-engineering-norman]: https://github.com/cognitive-engineering-lab/.github/blob/8ed2d979dd36dc573e0f253129c8faad6035fd14/cognitive-engineering.pdf
[The Rust Book Experiment]: https://rust-book.cs.brown.edu/
[Rust]: https://rust-lang.org/
[Will Crichton]: https://willcrichton.net/
[Aquascope]: https://github.com/cognitive-engineering-lab/aquascope
[mdbook-quiz]: https://github.com/cognitive-engineering-lab/mdbook-quiz
[Quizicist]: https://quizici.st/
