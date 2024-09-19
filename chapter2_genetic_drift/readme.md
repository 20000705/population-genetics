# Genetic Drift: Example Problems and Solutions

## 2.1 The Basic Model of Genetic Drift
In a population of size \( N \), genetic drift is the random fluctuation of allele frequencies due to random sampling. The probability that two alleles drawn from a population are identical by descent is called **homozygosity** (\( G \)), while the probability that two alleles are different by state is called **heterozygosity** (\( H \)).

At equilibrium, the probability that two alleles are identical by descent is:

$$
G = \frac{1}{1 + 4Nu}
$$

Where:
- \( N \) = Population size
- \( u \) = Mutation rate per generation.

## 2.2 Rate of Decay of Heterozygosity
The decay of heterozygosity over time can be described using the following equation:

$$
H_{t+1} = H_t \left( 1 - \frac{1}{2N} \right)
$$

Where \( H_t \) is the heterozygosity at generation \( t \).

### Problem 2.3: Average Time to Homozygosity
The average time for a population to become homozygous is approximately two generations. The formula can be written as:

$$
\mathbb{E}(T_c) = 4N \left( 1 + \frac{1}{2} + \frac{1}{3} \right)
$$

## 2.4 Mutation and Drift
Mutation introduces variation into the population at a rate \( 2Nu \), while genetic drift eliminates variation at a rate \( 1/(2N) \). At equilibrium, the balance between mutation and drift is expressed by:

$$
G = \frac{1}{1 + 4Nu}
$$

Where \( G \) is the probability of homozygosity.

## 2.5 Effective Population Size
The **effective population size** \( N_e \) is defined as the size of an idealized population that loses heterozygosity at the same rate as the actual population. If the population size fluctuates, the effective population size can be calculated as the harmonic mean:

$$
N_e = \left( \frac{1}{t} \sum_{i=1}^t \frac{1}{N_i} \right)^{-1}
$$

Where \( N_i \) is the population size at generation \( i \).

## 2.6 The Coalescent
The coalescent process traces the genealogy of alleles back to their most recent common ancestor. The expected coalescence time for a sample of size \( n \) is given by:

$$
\mathbb{E}(T_n) = \frac{4N}{n(n-1)}
$$

The total coalescent time for \( n \) alleles is:

$$
T_c = \sum_{i=2}^{n} i T_i = 4N \sum_{i=2}^{n} \frac{1}{i(i-1)}
$$

## Problem 2.12: Estimating \( \theta \)
For a neutral mutation rate \( u \), the expected number of segregating sites \( S_n \) is related to \( \theta = 4Nu \) by the equation:

$$
\mathbb{E}(S_n) = \theta \sum_{i=2}^{n} \frac{1}{i-1}
$$

An estimator for \( \theta \) is:

$$
\hat{\theta} = \frac{S_n}{\sum_{i=2}^{n} \frac{1}{i-1}}
$$
