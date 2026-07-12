A Statistical Analysis of Randomness in Prime Gap Sequences

This repository contains the dataset, code, and documentation for the paper investigating the statistical signatures of randomness within normalized prime gaps.

📝 Abstract
[cite_start]Prime numbers form a deterministic sequence, yet the gaps between consecutive primes fluctuate irregularly[cite: 8]. [cite_start]This study evaluates whether normalized prime gaps exhibit statistical signatures of randomness by analyzing primes up to 500,000 generated using the Sieve of Eratosthenes[cite: 9]. [cite_start]Gaps were normalized by logarithmic growth and compared against exponential random gaps and pseudorandom gaps from a linear congruential generator[cite: 10]. [cite_start]The tests revealed that while prime gaps show near-zero autocorrelation, they deviate significantly in distribution and entropy from both comparison models, retaining a detectable deterministic structure[cite: 11, 12].

📂 Repository Structure
`Prime_Gap_Randomness.pdf` - The full research text.
[cite_start]`src/` - Python scripts containing the Sieve of Eratosthenes implementation and statistical tests (Chi-Square, KS test, Autocorrelation, Shannon Entropy)[cite: 9, 20, 34].
`plots/` - Generated plots including the Gap Distribution Comparison and the CDF of Normalized Gaps.

Methodology & Core Findings
Sieve of Eratosthenes: Used to isolate primes up to 500,000[cite: 9].
Normalization: Gaps were computed via $g_{n}=p_{n+1}-p_{n}$ and scaled against the Prime Number Theorem prediction $\frac{g_{n}}{log(p_{n})}$[cite: 34, 35, 36].
Result: Prime gaps demonstrate a unique blend of random-like and deterministic behavior; their near-zero autocorrelation mimics independence, but lower entropy and high KS statistics showcase a distinct internal structure[cite: 97, 99, 100, 101].

Author & Citation
[cite_start]**Author:** Aryan Jain (Interlake High School, Bellevue, WA) [cite: 4, 5]
[cite_start]**Mentorship:** Special thanks to Professor Neal Koblitz for project guidance[cite: 119].
