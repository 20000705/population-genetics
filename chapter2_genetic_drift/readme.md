# Summary of Genetic Drift and Related Concepts

## 2.1: Genetic Drift in a Small Population
Genetic drift causes random changes in allele frequencies, especially in small populations. It reduces heterozygosity over time as some alleles randomly become fixed while others are lost. In smaller populations, the effects of genetic drift are stronger because chance events have a bigger impact on the population’s genetic structure. Heterozygosity, the measure of genetic variation, decays at a rate proportional to 
$$
\frac{1}{2N}
$$
where \( N \) is the population size. The smaller the population, the quicker the decline in heterozygosity.

## 2.2: Mutation and Drift
Mutation introduces new alleles into the population, while drift removes them. This interaction between drift and mutation determines the overall level of genetic variation. At equilibrium, genetic drift removes variation at the same rate that mutations introduce it, maintaining a balance. The probability that two alleles are identical by state at equilibrium is given by:

$$
\hat{G} = \frac{1}{1 + 4Nu}
$$

Here, \( 4Nu \) reflects the balance between mutation and drift, where \( N \) is the population size and \( u \) is the mutation rate. In larger populations or populations with higher mutation rates, more genetic variation is maintained.

## 2.3: Rate of Substitution
In neutral theory, the rate at which mutations become fixed in a population (the substitution rate, \( k \)) equals the mutation rate, \( u \). Although genetic drift can cause allele frequencies to fluctuate, the substitution rate remains:
$$
k = u
$$
because the number of new mutations entering the population each generation is balanced by the proportion of those mutations that get fixed. This result implies that the rate of evolution is independent of population size when considering neutral mutations.

## 2.4: The Neutral Theory
The neutral theory of molecular evolution claims that most genetic changes at the molecular level are caused by genetic drift rather than natural selection. According to the theory, most mutations are neutral and do not affect an organism’s fitness. This theory explains the constancy of molecular evolution, as the rate of substitution is determined by the mutation rate rather than selection pressures.

The concept of a molecular clock emerges from this theory: genetic changes accumulate at a constant rate over time, allowing biologists to estimate divergence times between species. One key aspect of the neutral theory is that the rate of substitution for neutral mutations is constant and equal to the mutation rate \( u \), leading to the equation:
$$
k = u
$$

## 2.5: Effective Population Size
In real populations, sizes often fluctuate, and individuals may not contribute equally to the next generation’s gene pool. To account for this, population geneticists use the concept of effective population size \( N_e \), which represents the size of an idealized population that experiences the same rate of genetic drift as the real population. Factors like population bottlenecks, unequal numbers of breeding males and females, or fluctuations in population size reduce the effective population size relative to the actual population size. The effective size of a population with fluctuating size over generations is given by the harmonic mean of the population sizes over time:

$$
N_e \approx \left( \frac{1}{t} \sum_{i=1}^{t} \frac{1}{N_i} \right)^{-1}
$$

This formula highlights that the effective population size is most influenced by periods of small population sizes (bottlenecks).

## 2.6: The Coalescent
The coalescent process is a model that traces the genealogical relationships of alleles in a population back to their common ancestor. In a coalescent framework, the focus is on how lineages merge (or coalesce) as one moves backward in time. The rate at which coalescent events occur depends on the population size \( N \). In small populations, alleles coalesce more quickly because there are fewer individuals, while in large populations, the time to coalescence is longer.

The time until coalescence for a sample of alleles can be calculated, and it provides insight into the amount of genetic diversity and the impact of genetic drift. For example, the expected total time to coalescence for a sample of \( n \) alleles is:

$$
E(T_c) = 4N \sum_{i=2}^{n} \frac{1}{i(i-1)}
$$

The coalescent process is useful for making inferences about genetic diversity, mutation rates, and the evolutionary history of populations.
