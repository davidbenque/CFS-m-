CFS(m): universal paradigm for computational flavor synthesis.
==============================================================

Lanza T.<sup>1</sup> and Benque D.<sup>2</sup>

<sup>1</sup> NMRC (National Mango Research Centre), London UK
<sup>2</sup> IRMA (International Ramen Manufacturers Association), Paris
FR

**Table of Contents:**   
1. [Abstract and Introduction](https://github.com/davidbenque/CFS-m-)  
2. [Materials and Methods](02-02-materials-methods/)  
&nbsp;&nbsp;&nbsp;&nbsp;a. [Experimental Design](https://github.com/davidbenque/CFS-m-/tree/master/02-materials-methods#experimental-design)  
&nbsp;&nbsp;&nbsp;&nbsp;b. [Microfuidic Lab-On-Chip Separator](https://github.com/davidbenque/CFS-m-/tree/master/02-materials-methods#microfuidic-lab-on-chip-separator)  
&nbsp;&nbsp;&nbsp;&nbsp;c. [Flavor Markup Language (FML)](https://github.com/davidbenque/CFS-m-/tree/master/02-materials-methods#flavor-markup-language-fml)  
&nbsp;&nbsp;&nbsp;&nbsp;d. [Blind Tests](https://github.com/davidbenque/CFS-m-/tree/master/02-materials-methods#blind-tests)  
3. [Results and Conclusions](03-results-conclusions/)  
4. [References](references.md)


Abstract
--------

We disclose an experimental apparatus and novel methods for ester
synthesis in artificial flavor production using off-the-shelf
ingredients. This new approach is the direct outcome of our ongoing
research in flavor mapping using mass spectrometry on convenience foods.
We detail preliminary findings and experimental design, as well as a
framework to build on these findings using two key innovations: the
Flavor Markup Language (FML) and Synchronous On-Demand Aroma (SODA)
Streaming API. On this basis we propose a new universal and distributed
paradigm for computational <sup>[1](#fn:1)</sup> flavor synthesis.

Introduction
------------

The analysis and classification of flavors along a continuous
spectrum<sup>[2](#fn:2)</sup> has long been a key challenge for both
food science and industry. Ester chain optimisation has made rapid
progress in the last decade but some hurdles remain–a coherent systems
approach still falls short of unifying niche areas such as coffee
flavor<sup>[3](#fn:3)</sup>. Consumer "clean label"<sup>[4](#fn:4)</sup>
concerns are also placing existing systems under increasing pressure.

In this setting, our initial research was concerned with flavor mapping
following a network-based approach<sup>[5](#fn:5)</sup> and focusing on
convenience foods<sup>[6](#fn:6)</sup>. A typical study would use High
Performance Liquid Chromatography (HPLC) to separate off-the-shelf
products into their constituent components. The resulting fraction pool
would then be quantified<sup>[7](#fn:7)</sup> and modelled
computationally<sup>[8](#fn:8)</sup> to generate correlation analysis
reports (fig. 2) between a pool of up to 4 products and the full flavor
spectrum (fig. 1). Such results are typically commissioned and used to
optimise production systems by 1) Reducing costs across multiple product
outputs. 2) Maximising the use of waste fractions into new outputs.

![](figures/Flavor-Spectrum.jpg) 

**Fig. 1 Flavor Spectrum**  
 Linear classification of flavors<sup>[9](#fn:9)</sup>

![](figures/Correlation-Reports/CC-880.jpg) **A**

![](figures/CC_contact-sheet.jpg) **B**

 **Fig. 2 Flavor Correlation Chart**  
 **A.** Computational model output exemplar showing Correlation
Coefficient (CC) for a given triple. **B.** Full result set  
[See full dataset](figures/Correlation-Reports)

----------

One recent study involved a top-tier market sample of 52 products on
which we were running our established series of analysis methods. The
sample pool was a median cross section of "shopping
basket"<sup>[10](#fn:10)</sup> items.

We were using a Correlation Coefficient variable between 0.0 and 1.0 as
a proxy for mapping multi-dimensional flavor space, with 1.0 as the
hypoethical perfect match with the full flavor spectrum. We routinely
witnessed correlation coefficients up to a maximum of 0.54, however a
specific sample of 3 products yielded a score of 0.95, meaning the
cumulative pool of their components almost covered the entire flavor
space.

We isolated the 3 products (Coca-Cola Company's Coca-Cola Classic™,
Fanta Orange™ and Sprite™) and were able to reproduce coefficients
between 0.94 and 0.96 in subsequent experiments. Checking the spectrum
footprint against our existing databases revealed that the missing 0.06
to 0.04 could be closed significantly with the addition of a fourth
source: Monosodium Glutamate (MSG)<sup>[11](#fn:11)</sup>. The resulting
pool (further referred to as CFS(m)) was ranked at up to 0.984
correlation coefficient by our model (fig. 3). Given the 0.15 error
margin generally accepted by the flavor industry this is equivalent to a
confident match with the full flavor spectrum.

![](figures/CC-CFS-MSG.jpg)

**Fig. 3 The CFS(m) Correlation**
 **3.a.** Initial Correlation result of the CFS sample: Coca-Cola
Company's Coca-Cola Classic™, Fanta Orange™ and Sprite™ against the
flavor spectrum **3.b.** Footprint Record for MSG. **3.c.** Combined
CFS(m) Correlation showing a coefficient of 0.992

On the basis of this exceptional match, we designed a study to test the
hypothesis chemically, the results of which are detailed here. Our aim
was primarily to test the viability of CFS(m) in reproducing a range of
flavors from our convenience foods database and, should this be
successful, to establish protocols for the systematisation of CFS(m)
synthesis for further experimentation, reproducibility and
characterization.
