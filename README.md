# CFS(m): Proposal for a universal and distributed paradigm for computational flavor synthesis.

Lanza T. [^1] and Benque D. [^2]

## Abstract
We disclose an experimental apparatus and novel methods for ester synthesis in artificial flavour production using off-the-shelf ingredients. This new approach is the direct if serendipitous outcome of our ongoing research in flavor mapping using mass-spectrometry on convenience foods. We detail preliminary findings and experimental design, as well as a framework to build on these findings using two key components: the Flavor Markup Language (FML) and Synthetic On-Demand Aroma (SODA) Streaming API. On this basis we propose a new universal and distributed paradigm for computational[^8] flavour synthesis.

## Introduction
The analysis and classification of flavors along a continuous spectrum[^4] has long been a key challenge for both food science and industry. Ester chain optimisation has made rapid progress in the last decade but some hurdles remain–a coherent systems approach still falls short of unifying niche areas such as coffee flavour[^6]. Consumer "clean label"[^5] concerns are placing existing systems under increasing pressure.

In this setting, our initial research was concerned with flavor mapping following a network-based approach[^7] and focusing on convenience foods[^9]. A typical study would use High Performance Liquid Chromatography (HPLC) to separate off-the-shelf products  into their constituent components. The resulting fraction pool would then be quantified[^10] and modelled computationally[^11] to generate correlation analysis reports (fig. 2) between a pool of up to 4 products and the full flavour spectrum (fig. 1). Such results are used to optimise production systems by 1) Reducing costs across multiple product outputs. 2) Maximising the use of waste fractions into new outputs. 

<img src="figures/Flavor-Spectrum.jpg" alt="Drawing" style="float:left; width: 400px;"/>

**Fig. 1 Flavor Spectrum**  
taken from XXXXXXX

<div style="clear:both"></div>

<img src="figures/Correlation-Reports/CC-880.pdf" style="float:left; width: 400px;"/>

**Fig. 2 Flavor Correlation Chart**  
Computational model output showing Correlation Coefficient (CC) for a given triple. [See full dataset](http://)

<div style="clear:both"></div>

One recent study involved a top-tier market sample of 52 products on which we were running our established series of analysis methods. The sample pool was a median cross section of "shopping basket"[^12] items, so nothing prepared us for the remarkable results that our models delivered. Whereas we routinely witnessed correlation coefficients up to a maximum of 0.54, a specific sample of 3 products yielded a score of 0.95, meaning the pool of their components almost covered the entire flavour spectrum. We isolated the 3 products (Coca-Cola Company's Coca-Cola Classic™, Fanta Orange™ and Sprite™) and were able to reproduce coefficients between 0.94 and 0.96 in subsequent experiments. Checking the spectrum footprint against our existing databases revealed that the missing 0.06 to 0.04 could be closed significantly with the addition of a fourth source: Monosodium Glutamate (MSG)[^13]. The resulting pool (further referred to as CFS(m)) was ranked at up to 0.984 correlation coefficient by our model (fig. 3). Given the 0.15 error margin generally accepted by the flavour industry this is equivalent to a confident match with the full flavour spectrum.


<img src="figures/CFS-CA-98.9.png" alt="Drawing" style="float:left; width: 400px;"/>

**Fig. 2 Flavor Correlation Chat**  
[Click for full size](#)  
Graph showing the best possible correlation outcome between products #12 and #03 and #28.

<div style="clear:both"></div>

Having found this exceptional and unexpected match and proven it computationally. We designed an initial wet-lab study to test the hypothesis chemically, the results of which are detailed here. Our aim was primarily to test the viability of CFS(m) in reproducing a range of flavors from our convenience foods database and, should this be successful, to establish protocols for the systematisation of CFS(m) synthesis for further experimentation, reproducibility and characterization. 


## Materials and Methods


>> Image of lab on chip circuit

Fischer–Speier esterification



## Results

>> Table of results per ester



## Conclusions
CFS(m) Could be extended to all flavors

>> Modular systems CMYK, RGB 

question "clean Label" aspirations. make them more realistic



[^1]: Lanza Affiliation
[^2]: Benque Affiliation 
[^4]: MATTHEWS, J. S., SUGISAWA, H. and MAC GREGOR, D. R. (1962), The Flavor Spectrum of Apple-Wine Volatiles. *Journal of Food Science*, 27: 355–362.
[^5]: Zink, D. L. (1997). The impact of consumer demands and trends on food processing. *Emerging Infectious Diseases*, 3(4), 467.
[^6]:Shibamoto, T. (1991). An overview of coffee aroma and flavor chemistry. In *Quatorzieme colloque scientifique international sur le cafe*, San Francisco, 14-19 juillet 1991. (pp. 107-116).
[^7]: Ahn, Y. Y., Ahnert, S. E., Bagrow, J. P., & Barabási, A. L. (2011). Flavor network and the principles of food pairing. *Scientific reports*, 1.
[^8]: Network analysis and data mining in food science: the emergence of computational gastronomy DOI 10.1186/2044-7248-2-4
[^9]: Verlegh, P. W., & Candel, M. J. (1999). The consumption of convenience foods: reference groups and eating situations. *Food Quality and Preference*, 10(6), 457-464.
[^10]: Caballero-Ortega, H., Pereda-Miranda, R., & Abdullaev, F. I. (2007). HPLC quantification of major active components from 11 different saffron (Crocus sativus L.) sources. *Food Chemistry*, 100(3), 1126-1131.
[^11]: Bhat, N. V., Minderman Jr, P. A., McAvoy, T., & Wang, N. S. (1990). Modeling chemical process systems via neural computation. *Control Systems Magazine*, IEEE, 10(3), 24-30.
[^12]: Manchanda, P., Ansari, A., & Gupta, S. (1999). The “shopping basket”: A model for multicategory purchase incidence decisions. *Marketing Science*, 18(2), 95-114.
[^13]: [http://pubchem.ncbi.nlm.nih.gov/compound/23672308](http://pubchem.ncbi.nlm.nih.gov/compound/23672308)