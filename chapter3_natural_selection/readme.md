# Chapter 3: Natural Selection

### 3.1: The Fundamental Model
Natural selection is one of the most powerful forces in evolution. The **fundamental model** of natural selection focuses on how differential survival and reproduction of individuals based on their traits affect allele frequencies over time. The core idea is that individuals with advantageous traits (and thus alleles) are more likely to survive and reproduce, increasing the frequency of those alleles in the population.

### 3.2: Relative Fitness
**Fitness** refers to the reproductive success of an individual or genotype compared to others in the population. The key metric in selection is **relative fitness**, which normalizes the fitness values so that the highest fitness is set to 1. For example, if the relative fitness of genotype \( A \) is \( w_A \), and that of genotype \( B \) is \( w_B \), the relative fitness values can be used to predict changes in allele frequencies. The change in allele frequency due to selection is proportional to the difference in fitness:

$$
\Delta p = p(1 - p)(w_A - w_B)
$$

Where:
- \( \Delta p \) is the change in allele frequency,
- \( p \) is the allele frequency,
- \( w_A \) and \( w_B \) are the relative fitness of genotypes \( A \) and \( B \).

### 3.3: Three Kinds of Selection
There are three main types of selection that act on populations:

1. **Directional Selection**: Favors one extreme phenotype, causing the allele frequency to shift in one direction.
2. **Stabilizing Selection**: Favors the average phenotype, reducing variation.
3. **Disruptive Selection**: Favors both extreme phenotypes, increasing variation.

These types of selection shape the genetic diversity and mean phenotype of the population over time.

### 3.4: Mutation-Selection Balance
In the **mutation-selection balance**, deleterious mutations are continuously introduced into the population through mutation, while natural selection acts to remove these harmful alleles. The equilibrium frequency of a deleterious allele is given by:

$$
q = \sqrt{\frac{u}{s}}
$$

Where:
- \( q \) is the frequency of the deleterious allele,
- \( u \) is the mutation rate,
- \( s \) is the selection coefficient (the strength of selection against the deleterious allele).

### 3.5: The Heterozygous Effects of Alleles
This section deals with how alleles that are harmful in the homozygous state can sometimes be maintained in the population due to heterozygote advantage (also known as **overdominance**). For example, in the case of sickle-cell anemia, individuals heterozygous for the sickle-cell allele have a fitness advantage in malaria-endemic regions. The equilibrium frequency of such an allele is given by:

$$
q = \frac{s_1}{s_1 + s_2}
$$

Where:
- \( s_1 \) and \( s_2 \) are the selection coefficients for the two alleles.

### 3.6: Changing Environments
Environmental changes can lead to **adaptive evolution**, where traits that are advantageous in one environment become disadvantageous in another. As environments change, the selection pressures on the population also change, leading to shifts in allele frequencies and sometimes rapid evolutionary change.

### 3.7: Selection and Drift
In small populations, **genetic drift** can overpower selection, causing allele frequencies to fluctuate randomly. This can lead to the fixation of alleles that are not necessarily the most fit. The balance between selection and drift is determined by the **effective population size** \( N_e \) and the selection coefficient \( s \). When \( N_e s \gg 1 \), selection dominates; when \( N_e s \ll 1 \), drift dominates.

### 3.8: Derivation of the Fixation Probability
The **fixation probability** of a new mutation in a population depends on the interplay between genetic drift and selection. For a neutral mutation (no selection), the probability that the mutation will become fixed is:

$$
P_{\text{fix}} = \frac{1}{2N}
$$

Where \( N \) is the population size. For a beneficial mutation with selection coefficient \( s \), the fixation probability is approximately:

$$
P_{\text{fix}} \approx \frac{2s}{1 - e^{-2Ns}}
$$

This shows that the strength of selection and the size of the population are both crucial in determining whether a beneficial mutation will become fixed.
