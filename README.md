# Notes on Erdős Problem #451

This repository contains my note:

📄 [Full note PDF](Notes_on_Erdos_Problem_451_Density_and_Heuristics.pdf)

---

## Problem

Erdős Problem #451 asks to estimate the minimal integer \(n_k > 2k\) such that
\[
\prod_{1 \le i \le k} (n_k - i)
\]
has no prime factor in the interval \((k,2k)\).

---

## Main results

- Introduce the density
  \[
  D_k = \prod_{\substack{k < p < 2k \\ p \ \text{prime}}}\left(1 - \frac{k}{p}\right),
  \]
  which measures the proportion of admissible integers \(n\).
- Proved:
  \[
  \log\frac{1}{D_k} = (\log 4 + o(1))\frac{k}{\log k}.
  \]
- Conjecture (heuristic + numerical evidence):
  \[
  \log n_k \asymp \frac{k}{\log k}.
  \]

---


## References

- H. Iwaniec and E. Kowalski, *Analytic Number Theory*.
- H. L. Montgomery and R. C. Vaughan, *Multiplicative Number Theory I. Classical Theory*.

---

Author: **Quanyu Tang**, Xi’an Jiaotong University

