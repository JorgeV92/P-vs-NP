What am I trying to answer? Suppose you give me an algorithm to solve a specific problem along with a proposed solution. I can then confirm whether the algorithm and the solution are indeed correct. To define this in a formal setting, consider a \emph{decision problem}--a computational problem that, for a given input string $w$ over an \emph{alphabet} (typically denoted as $\Sigma$), determines a \emph{yes} or \emph{no} answer.

If there exists an algorithm that produces the correct response for any string $w$ (with $|w| = n$ representing the length of the string) using no more than $nc^k$ operations (where $k$ and $c$ are constants independent of $w$), then the problem is considered solvable in \emph{polynomial time}. Accordingly, algorithms that solve these problems fall into the $\mathcal{P}$-class.

The class $\mathcal{P}$ comprises all languages that can be decided by a deterministic Turing machine operating within polynomial time, formally expreseed as:

$$
    \mathcal{P} := \{L : L = L(M) \text{ for some deterministic polynomial-time Turing machine M}\}
$$

where, 

$$
    L(M) = \{w \in \Sigma^\star : M \text{ accepts } w \}
$$
