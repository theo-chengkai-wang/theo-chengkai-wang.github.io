---
title: "Algebraic Theories and Quantum Communication"
collection: works
category: main
permalink: /works/2024-09-MSc-thesis
excerpt: 'Thesis Project for my MSc in Advanced Computer Science at Oxford supervised by Sam Staton. This thesis gives an algebraic formulation to classically controlled quantum communication. Presented at PLanQC 2025.'
date: 2024-09-10
# venue: 'Thesis'
label: "Master's Thesis, University of Oxford; PLanQC Extended Abstract"
collaborators: [{name: "Sam Staton", url: "https://www.cs.ox.ac.uk/people/samuel.staton/main.html"}]
urls: [{name: "[PDF]Thesis", url: "/files/works/2024_09_Oxford_Thesis.pdf"}, {name: "[PDF]Extended Abstract at PLanQC", url: "/files/works/2025_01_PLanQC.pdf"}, {name: "[PDF]Slides at PLanQC", url: "/files/works/2025_01_PLanQC_slides.pdf"}]
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

With the advent of quantum computing and communication comes the need for corresponding programming language primitives. In this dissertation, we study a notion of classically controlled quantum communication (sending and receiving qubits) using Staton's language of parameterised algebraic theories (PAT) ([Staton 2015](https://www.cs.ox.ac.uk/people/samuel.staton/papers/popl2015.pdf)). More specifically, we start by showing the well-formedness of the standard combinations of algebraic theories (sums and tensors) for PATs. Then, we define a PAT for quantum communication, \\(\mathsf{I/O}\otimes \mathsf{Quantum}\\), as the tensor of a standard I/O theory and Staton's complete axiomatisation for qubit quantum computing \\(\mathsf{Quantum}\\). Finally, we give two complementary models to this algebraic theory: one operational and one denotational. The first model is based on an operational semantics where the program sends and receives qubits to and from an environment modelled by a quantum stream. It concretely demonstrates the notion of quantum communication and ensures that our theory is non-degenerate (unlike the [Eckmann-Hilton](https://en.wikipedia.org/wiki/Eckmann%E2%80%93Hilton_argument) setting). The second model is based on an elegant denotational semantics, constructed as a free I/O monad on \\(\mathbf{CP}^{\infty}\\), the category of matrix algebras and CP maps completed with infinite biproducts ([Pagani, Selinger, Valiron 2013](https://arxiv.org/abs/1311.2290)). We show that these two models correspond to the same notion of communication in the sense that the denotational model is adequate and fully abstract with respect to the operational model. 
