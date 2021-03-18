---
title: "rs1815739 and what does it have to do with athletic performace?"
author: "Inga Patarcic"
date: '2021-03-15'
published: yes
---

 
In this post, I will briefly introduce:

1. genetic background of athletic performance

2. rs1815739

  
<br />

# IDEA 

Athletic performance as a phenotype occurs in multiple genetic tests: for example, it was present in the initial versions of 23andMe reports (>10 years ago, Roth et al. 2008) and I recently stumble upon it in the Genomapp (https://genomapp.com/en/)
This test was based on the single SNP: rs1815739 and that made me wonder...
This association was published cca. 14 years ago and is it still valid?
<br />
Are there new associations with athletic performance reported or not?
<br />
Do people only c/p each others tests without actually investigating the scientific information behind it?


# Sci literature check
Step 1: Googling rs1815739.
<br />
Step 2:  Identiying literature:

<br />
a) https://www.snpedia.com/index.php/Rs1815739
"This SNP, in the ACTN3 gene, encodes a premature stop codon in a muscle protein called alpha-actinin-3. The polymorphism alters position 577 of the alpha-actinin-3 protein. In publications the (C;C) genotype is often called RR, whereas the (T;T) genotype is often called XX."

b) https://selfdecode.com/snp/rs1815739/
no critical overview of reports

c) https://www.geneticlifehacks.com/actn3-your-muscle-type-gene/
Seriouslly, I need a web-site to comment on this.

d) https://www.wired.com/2008/10/the-gene-for-jamaican-sprinting-success-no-not-really/
good job!

e) Association of the ACTN3 R577X (rs1815739) polymorphism with elite power sports: A meta-analysis
Need to go to individual publications and see how did they select cases and controls.

# LIMITATIONS OF CONDUCTED STUDIES
1. Selection of cases and controls:
"Black and White elite-level bodybuilders and strength athletes in comparison to the general population." -> "The results indicate that the ACTN3 R577X nonsense allele (X) is under-represented in elite strength athletes, consistent with previous reports indicating that alpha-actinin-3 deficiency appears to impair muscle performance." NOTE: Replication failure: Rankinen et al. 2016
3.

# CITIZEN SCIENCE GENOME ANALYSIS


# MY CONTRIBUTION - myDNA R package

Two years ago, I purchased myHeritage DTC test. Since, I received only my ancestry estimations, I decide to read my own genome as bioinformatician by training. I decided to write reproducible R code and create myDNA package. This package enables you to import your genotypes in R, overlap them with GWAS Catalog and identify risk alleles. It also contains small tests that can directly identify SNPs that are associated with oligogenic traits such as lactose intolerance.


Meanwhile, I 
wrote an [myDNA R package](https://github.com/IngaPa/myDNAS), 
developed [minimal myDNA shinyApp](https://github.com/IngaPa/myDNA_shinyApp),
started myDNA blog. 
was a project leader at S3++ and educated high-school students genetics, genomics and programming: Analyze myDNA, Internet meets the Human Genome. Analysis of genomes of ancient people reported
presented at MDC PhD retreat
Presented at Berlin’s Science Week: Soapbox 2009

# FUTURE
TBA

# LITERATURE
1. Roth SM, Walsh S, Liu D, Metter EJ, Ferrucci L, Hurley BF. The ACTN3 R577X nonsense allele is under-represented in elite-level strength athletes. Eur J Hum Genet. 2008 Mar;16(3):391-4. doi: 10.1038/sj.ejhg.5201964. Epub 2007 Nov 28. PMID: 18043716; PMCID: PMC2668151.
2. Rankinen T, Fuku N, Wolfarth B, Wang G, Sarzynski MA, Alexeev DG, Ahmetov II, Boulay MR, Cieszczyk P, Eynon N, Filipenko ML, Garton FC, Generozov EV, Govorun VM, Houweling PJ, Kawahara T, Kostryukova ES, Kulemin NA, Larin AK, Maciejewska-Karłowska A, Miyachi M, Muniesa CA, Murakami H, Ospanova EA, Padmanabhan S, Pavlenko AV, Pyankova ON, Santiago C, Sawczuk M, Scott RA, Uyba VV, Yvert T, Perusse L, Ghosh S, Rauramaa R, North KN, Lucia A, Pitsiladis Y, Bouchard C. No Evidence of a Common DNA Variant Profile Specific to World Class Endurance Athletes. PLoS One. 2016 Jan 29;11(1):e0147330. doi: 10.1371/journal.pone.0147330. PMID: 26824906; PMCID: PMC4732768.
3. https://www.wired.com/2008/10/the-gene-for-jamaican-sprinting-success-no-not-really/
4. Tharabenjasin, Phuntila, Noel Pabalan, and Hamdi Jarjanazi. "Association of the ACTN3 R577X (rs1815739) polymorphism with elite power sports: A meta-analysis." PloS one 14.5 (2019): e0217390.
