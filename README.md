# $\mathcal{P}$ $\text{vs}$ $\mathcal{NP}$

Welcome to the $\mathcal{P}$ vs. $\mathcal{NP}$ project, where I delve into the world of computational complexity, focusing on the $\mathcal{P}$ vs. $\mathcal{NP}$ problem. This project aims to explore various reduction techniques to transform problems into one another, demonstrating these concepts through the OCaml functional programming language and possibly python to make it easier for others to use and read the code as well. I hope to learn as much as possible about this topic, review papers and books, and write extensive notes from my algorithm courses. Ultimately, I aim to develop a formal method for exploring reductions in programming.

# $\mathcal{P}$

TODO

Overview of the class of problems know as $\mathcal{P}$

# $\mathcal{NP}$

TODO 

Overview of the class of problems know as $\mathcal{NP}$

# $\mathcal{NP}-\text{complete}$

TODO

Overview of the class of probelms know as $\mathcal{NP}$ - $\text{complete}$

## Resources 

1. [Algorithms by Jeff Erickson](https://jeffe.cs.illinois.edu/teaching/algorithms/)
2. [Mathematics and Computation by Avi Wigderson](https://www.math.ias.edu/avi/book)
3. [P versus NP problem : Wiki](https://en.wikipedia.org/wiki/P_versus_NP_problem)


## Outline 

I have outlined the directory structure I hope to follow for now but this is not set in stone as the final design of 
the project. A possible restructre could occur sometime in the future. For now this is what I will follow.

```bash
P_vs_NP_Project/
│
├── docs/               # Documentation and notes
│   ├── papers/         # Research papers
│   ├── books/          # Books and eBooks
│   └── notes/          # Personal study notes
│
├── src/                # Source code
│   ├── common/         # Common utilities and helper functions
│   ├── p/              # Code specific to P class problems
│   ├── np/             # Code specific to NP class problems
│   └── np_complete/    # Code specific to NP-Complete problems
│
├── examples/           # Example problems and their solutions
│   ├── sat/            # SAT problem examples and reductions
│   ├── tsp/            # Travelling Salesman problem examples and reductions
│   └── other/          # Other problems
│
├── tests/              # Unit tests and testing frameworks
│   ├── p_tests/        
│   ├── np_tests/
│   └── np_complete_tests/
│
└── README.md           # Project overview and setup instructions

```

