
# Part 1 - Brainstorm: Statistics

## Distributions
## Statistical Models
## Methods for Estimation
## Methods for Hypothesis Testing

# Part 2 - Brainstorm: Technologies in Biology

## Microarray
## ...

## In-class exercise 1 (15 minutes)

### Technologies: 

```{r}
techs <- c("microarray", "rna-seq", "dna-seq", 
           "bisulphite-seq", "cytometry", "mass-spec", 
           "10x-chromium", "oxford-nanopore")

s <- sample(length(techs))
data.frame(row=s, techs)
```

### Task: 
#### produce a 2-3 point summary of "how it works"
#### links to a few (<5) good resources
#### create a markdown file for it and upload to README.me in "group assignment" repo

# Part 3 - Brainstorm: Applications in genomics 

# Part 4 - Brainstorm: Linking Technologies to Applications to Statistics

## e.g., microarray -> gene expression -> normally distributed (log intensities)

# Part 5 - Brainstorm: Methods/algorithms in genomics associated to Computer Science

# Part 6 - Pick a "technology" (from above, from [1] or otherwise) to briefly describe

## Exercise 2 (in groups of 1-3): 
### Goal: 
#### write ~2 sentences about what the method does
#### again, make the link (technology -> application -> statistics)
#### list the github usernames of everyone in your group
#### submit a pull request to brainstorm_modified.md

[1] [https://liorpachter.wordpress.com/seq/](https://liorpachter.wordpress.com/seq/)


# brainstorm-group-1_rna-seq
brainstorm-group-1_rna-seq created by GitHub Classroom

# Group Members

* Falko
* Wenfei
* Xi
* Ainesh

## RNAseq introduction
[RNAseq introduction](https://prezi.com/view/4Xsw1r6RbN8kvAiNyKqZ)

## Why do we sequence RNA? 
Since DNA sequence is identical (in theory) throughout one individual organism, what makes the various tissue/cell types is the usage of the DNA. The first step of using the DNA is transcription that generates RNA. The transcriptome conveys biological information that reflects the function of a cell/tissue. Thus, profiling RNA could help us understand how a cell/tissue work and probe the state of a cell/tissue.
## Applications
(1) Differentiation gene expression analysis
(2) Explore novel RNA expression, eg. non-coding RNA, micro RNA, piwi RNA etc.
(3) Explore the RNA post-transcription processing, eg. splicing, etc.
## Statistics
Negative binominal GLM, Cox-Reid Approximate Conditional Variance, 

#### General info
* RNA splicing patterns: How are genes actually transcribed and subsequently translated into proteins?
* Gene discovery: Presence of unique stretches of DNA might reveal previously undiscovered genes.
* Gene expression profiling: Expression levels of known genes can be inferred by looking at relative amounts of RNA expression.
* Profiling of miRNAs implicated in cancer
* Targeted cancer gene profiling

#### Links
* [Wikipedia](https://en.wikipedia.org/wiki/RNA-Seq)
* [Ebi](https://www.ebi.ac.uk/training/online/course/functional-genomics-ii-common-technologies-and-data-analysis-methods/applications-rna-seq)
* [Illumina](https://www.illumina.com/areas-of-interest/cancer/research/sequencing-methods/cancer-rna-seq.html)

## Methodology

The first step is to prepare the cDNA library. 

1. RNA isolation / extraction - This can be done using liquid nitrogen and using a mortar and pestle to break it apart. It is essential to maintain the integrity of the RNA in this step.
2. RNA selection - RNA can be kept as is, filtered, depleted or filtered for RNA that binds to specific sequences.
3. cDNA synthesis - The RNA is now reverse transcribed to cDNA i.e. creating a double stranded DNA from an RNA template




