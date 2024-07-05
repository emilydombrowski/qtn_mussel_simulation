# qtn_mussel_simulation: Using a quantitative trait nucleotide simulation to assess the impact of migration and thermal selection on local adaptation in a mussel hybrid zone
A repository to hold scripts used for modelling shifts in mussel populations due to temperature and migration using a QTN model. Developed by Emily Dombrowski
2024/07/05. 

Scripts modified from Matz et al. (2020; https://github.com/z0on/CoralTriangle_SLiM_model/tree/master) and Xuerub et al. (2021; https://github.com/QuentinRougemont/marine_IBM_paper/tree/main).

## Abstract
Marine environments are undergoing changes in temperature, and novel introductions of invasive species are changing the genetic makeup of native species. Invasive species may occupy the range of a native species of the same genus, leading to a hybrid zone that is established through admixture between the invasive and native species. A hybrid zone exists along the southeastern coast of Australia consisting of invasive mussels from the Mediterranean Sea, _Mytilus galloprovincialis_, and native mussels, _Mytilus planulatus_. Populations with higher proportions of _M. galloprovincialis_ genomic elements establish in regions with higher temperatures. This study proposes to use a combination of evolutionary simulations and larval selection experiments to answer the questions: “How do migration, admixture, and thermal tolerance selection impact local adaptation?” and “How will future climatic scenarios influence survival of hybrid mussel populations?” I hypothesize that high levels of migration and increased thermal performance reduce the ability of populations to locally adapt, as an influx of generalized traits restrict specialization to an environmental optimum and extreme phenotypes that result from hybridization proliferate in forecasted hotter climate scenarios. To test this hypothesis, I will initiate a non-Wright-Fisher simulation in the evolutionary simulation software SLiM (Selection on Linked Mutations). A quantitative trait nucleotide model will simulate stochastic mutation accumulation that confers beneficial phenotypes. Selection will occur based on simulated plasticity and thermal performance curves with environmental parameters provided by the Intergovernmental Panel on Climate Change (IPCC) forecasted climate scenarios. Subsequently, I will conduct temperature based larval selection experiments to associate differential mussel survival with genome composition across life stages. Results from varying larval survival will be factored into the simulation to provide higher confidence, experimentally informed predictions. Using a combined approach, this study proposes a framework to measure and simulate temperature’s role in shaping phenotypes in a hybrid zone.

## Folders
* data
* scripts
* results

## References 
Haller, B. C., & Messer, P. W. (2023). SLiM 4: Multispecies Eco-Evolutionary Modeling. The American Naturalist, 201(5), E127–E139.
Matz, M. V., Treml, E. A., & Haller, B. C. (2020). Estimating the potential for coral adaptation to global warming across the Indo‐West Pacific. Global Change Biology, 26(6), 3473–3481.
Norberg, J. (2004). Biodiversity and ecosystem functioning: A complex adaptive systems approach. Limnology and Oceanography, 49(4part2), 1269–1277.
Xuereb, A., Rougemont, Q., Tiffin, P., Xue, H., & Phifer-Rixey, M. (2021). Individual-based eco-evolutionary models for understanding adaptation in changing seas. Proceedings. Biological Sciences, 288(1962), 20212006.
