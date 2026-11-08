# JFLAP Automata and Formal Languages

This repository contains JFLAP exercises for automata theory and formal languages. The files cover finite automata, regular expressions and grammars, pushdown automata, parsing, Turing machines, and the pumping lemma.

## What is JFLAP?

[JFLAP](https://www.jflap.org/) is an educational software tool for creating and simulating formal-language models, including finite automata, grammars, pushdown automata, and Turing machines. Most files in this repository use JFLAP's `.jff` XML-based format.

## Setup

1. Install a Java runtime if one is not already available.
2. Download JFLAP from the https://www.jflap.org/
3. Launch JFLAP (usually by opening its `.jar` file; if needed, run `java -jar JFLAP.jar` from a terminal).
4. In JFLAP, choose **File → Open** and select a `.jff` file from this repository.
5. Use the relevant JFLAP menu to inspect or simulate the model. The exact menu depends on the exercise type.


## Files and questions

| Question no. | Question | Description |
|---:|---|---|
| 1 | DFA | JFLAP file for a deterministic finite automaton. |
| 2 | DFA | JFLAP file for a deterministic finite automaton. |
| 3 | DFA | JFLAP file for a deterministic finite automaton. |
| 4 | DFA | JFLAP file for a deterministic finite automaton. |
| 5 | DFA to NFA | JFLAP exercise involving conversion from a DFA to an NFA. |
| 6 | DFA to NFA | JFLAP exercise involving conversion from a DFA to an NFA. |
| 7 | DFA to NFA | JFLAP exercise involving conversion from a DFA to an NFA. |
| 8 | NFA | JFLAP file for a nondeterministic finite automaton. |
| 9 | NFA | JFLAP file for a nondeterministic finite automaton. |
| 10 | NFA | JFLAP file for a nondeterministic finite automaton. |
| 11 | Regular expression ending | Regular expression exercise about strings ending with the specified pattern. |
| 12 | Regular expression with exactly one `a` | Regular expression exercise requiring exactly one occurrence of `a`. |
| 13 | Regular expression to DFA — DFA | DFA-side file for a regular-expression-to-DFA exercise. |
| 14 | Regular expression to DFA — regular expression | Regular-expression-side file for a regular-expression-to-DFA exercise. |
| 15 | Regular grammar | JFLAP file containing a regular grammar. |
| 16 | Grammar to DFA — DFA | DFA-side file for a grammar-to-DFA exercise. |
| 17 | Grammar to DFA — grammar | Grammar-side file for a grammar-to-DFA exercise. |
| 18 | Mealy machine | JFLAP file for a Mealy machine. |
| 19 | Moore machine | JFLAP file for a Moore machine. |
| 20 | CFG for `aⁿbⁿ` | Context-free grammar exercise for strings with matching numbers of `a`s followed by `b`s. |
| 21 | CFG palindrome | Context-free grammar for palindrome strings. |
| 22 | CFG to CNF — CFG | Context-free grammar input for conversion to Chomsky Normal Form. |
| 23 | CFG to CNF — CNF | Chomsky Normal Form result for the conversion exercise. |
| 24 | PDA for `aⁿbⁿ` | Pushdown automaton exercise for strings with matching numbers of `a`s followed by `b`s. |
| 25 | CFG to NPDA — CFG | Context-free grammar input for conversion to a nondeterministic pushdown automaton. |
| 26 | CFG to NPDA — NPDA | Nondeterministic pushdown automaton result for the conversion exercise. |
| 27 | NPDA to CFG — CFG | Context-free grammar result for an NPDA-to-CFG exercise. |
| 28 | NPDA to CFG — NPDA | Nondeterministic pushdown automaton input for conversion to a CFG. |
| 29 | LL parsing | JFLAP file for an LL parsing exercise. |
| 30 | CYK parsing | JFLAP grammar file for a CYK parsing exercise. |
| 31 | One-tape Turing machine | JFLAP file for a single-tape Turing machine. |
| 32 | Multi-tape Turing machine | JFLAP file for a multi-tape Turing machine. |
| 33 | Turing-machine building blocks | JFLAP file demonstrating Turing-machine building blocks. |
| 34 | Simple L-system | JFLAP file for a simple L-system. |
| 35 | Regular pumping lemma | The `.txt` file explains why `{0ⁿ1ⁿ \| n ≥ 0}` is not regular using the pumping lemma. The `.jff` file contains a CFG for that language; it is a grammar example, not an interactive pumping-lemma proof. |

## Notes for using this repository

- Open `.jff` files in JFLAP rather than editing them as ordinary text; they store the model and its structure.
- The Q35 `.jff` file is a context-free grammar for `{0ⁿ1ⁿ | n ≥ 0}`; it represents the language, not the interactive pumping-lemma proof. Keep the `.txt` file for the proof and JFLAP instructions.


## References

- [JFLAP — official website and downloads](https://www.jflap.org/)
- [JFLAP documentation](https://www.jflap.org/tutorial/)

## Contributors

- **Bhagyashri Joshi** — D12B, 23
