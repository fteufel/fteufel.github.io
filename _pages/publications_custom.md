---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find a full list of my publications on <a href="https://scholar.google.com/citations?hl=en&user=pO3M3xYAAAAJ">my Google Scholar profile</a>.

<small>\* = equal contribution.</small>

{% include base_path %}

# Representation learning on DNA


<img src="https://fteufel.github.io/images/publications/bend_dna_cut.png" style="float:right;width:400px;">
[**BEND: Benchmarking DNA Language Models on biologically meaningful tasks**](https://arxiv.org/abs/2311.12570)  
<small><b>ICLR, 2024</b></small>  
<small>Frederikke Isa Marin*, <u>Felix Teufel*</u>, Marc Horlacher, Dennis Madsen, Dennis Pultz, Ole Winther, Wouter Boomsma</small>  
We introduce BEND, a collection of prediction tasks for evaluating the performance of DNA LM representations over a range of length scales.  
[Code on Github](https://github.com/frederikkemarin/BEND)  
[Data](https://sid.erda.dk/cgi-sid/ls.py?share_id=aNQa0Oz2lY)  
[Blog post](https://portal.valencelabs.com/blogs/post/benchmarking-dna-language-models-with-bend-jUET5WOJxb5xW6I)  


# Protein sorting and location prediction

<img src="https://fteufel.github.io/images/publications/secretogen.png" style="float:right;width:400px;">
[**SecretoGen: towards prediction of signal peptides for efficient protein secretion**](https://openreview.net/forum?id=vXXEfmYsvS)  
<small><b>GenBio Workshop at NeurIPS, 2023</b></small>  
<small> <u>Felix Teufel</u>, Carsten Stahlhut, Jan Refsgaard, Henrik Nielsen, Ole Winther, Dennis Madsen</small>  
SecretoGen is a generative transformer that designs host- and protein-optimized signal peptides. We show that it can be used for ranking signal peptide sequences that have good secretion performance.  
[Code on Github](https://github.com/fteufel/SecretoGen)

<img src="https://fteufel.github.io/images/publications/signalp6.png" style="float:right;width:400px;">
**[SignalP 6.0 predicts all five types of signal peptides using protein language models](https://www.nature.com/articles/s41587-021-01156-3)**  
<small><b>Nature Biotechnology, 2022</b></small>  
<small><u>Felix Teufel</u>, Jose Juan Almagro Armenteros, Alexander Rosenberg Johansen,  Magnús Halldór Gíslason, Silas Irby Pihl, Konstantinos D. Tsirigos, Ole Winther, Søren Brunak, Gunnar von Heijne and Henrik Nielsen</small>  
We used protein language models to build SignalP 6.0, the first signal peptide predictor capable of predicting all known types of signal peptides in protein sequences.  
[Available online at DTU Health Tech](https://services.healthtech.dtu.dk/service.php?SignalP-6.0)  
[Code on Github](https://github.com/fteufel/signalp-6.0)  
[Blog post](https://communities.springernature.com/posts/signalp-6-0-predicts-all-five-types-of-signal-peptides-using-protein-language-models)  


<img src="https://fteufel.github.io/images/publications/graphpart.jpeg" style="float:right;width:400px;">
[**GraphPart: homology partitioning for biological sequence analysis**](https://academic.oup.com/nargab/article/5/4/lqad088/7318077)   
<small><b>NAR Genomics and Bioinformatics, 2023</b></small>    
<small> <u>Felix Teufel</u>, Magnús Halldór Gíslason, José Juan Almagro Armenteros, Alexander Rosenberg Johansen, Ole Winther, Henrik Nielsen</small>  
We introduce GraphPart, an algorithm for homology partitioning of biological sequence datasets for machine learning.  
[Code on Github](https://github.com/graph-part/graph-part)  
[Python package](https://pypi.org/project/graph-part/)

<img src="https://fteufel.github.io/images/publications/deeploc21.png" style="float:right;width:400px;">
[**DeepLoc 2.1: multi-label membrane protein type prediction using protein language models**](https://academic.oup.com/nar/advance-article/doi/10.1093/nar/gkae237/7642068)   
<small><b>Nucleic Acids Research, 2024</b></small>    
<small> Marius Thrane Ødum, <u>Felix Teufel</u>, Vineet Thumuluri, José Juan Almagro Armenteros, Alexander Rosenberg Johansen, Ole Winther, Henrik Nielsen</small>  
DeepLoc 2.1 predicts protein subcellular locations and membrane protein types in eukaryotes.  
[Available online at DTU Health Tech](https://services.healthtech.dtu.dk/services/DeepLoc-2.1/)  

# Bayesian optimization

<img src="https://fteufel.github.io/images/publications/beebo.png" style="float:right;width:300px;">
[**Batched Energy-Entropy acquisition for Bayesian Optimization**](https://github.com/novonordisk-research/BEE-BO/blob/main/manuscript.pdf)
<small><b>ML4LMS Workshop @ ICML, 2024</b></small>    
<small> <u>Felix Teufel</u>, Carstel Stahlhut, Jesper Ferkinghoff-Borg</small>  
A statistical physics inspired acquisition function for Bayesian optimization with Gaussian processes that natively scales to batch acquisition mode.  
[Code on Github](https://github.com/novonordisk-research/BEE-BO)  
[Python package](https://pypi.org/project/beebo/)  

# Bioactive peptide discovery

<img src="https://fteufel.github.io/images/publications/deeppeptide.png" style="float:right;width:300px;">
[**DeepPeptide predicts cleaved peptides in proteins using conditional random fields**](https://doi.org/10.1093/bioinformatics/btad616)  
<small><b>Bioinformatics, 2023</b></small>  
<small><u>Felix Teufel</u>, Jan C. Refsgaard, Christian T. Madsen, Carsten Stahlhut, Mads Grønborg, Ole Winther, Dennis Madsen</small>  
Predicting native cleaved peptide products directly from precursor protein sequences, without requiring experimental peptide data.  
[Available online at University of Copenhagen Biolib](https://biolib.com/KU/DeepPeptide/)  
[Code on Github](https://github.com/fteufel/deeppeptide/)

<img src="https://fteufel.github.io/images/publications/deorph.jpg" style="float:right;width:400px;">
[**Deorphanizing Peptides using Structure Prediction**](https://pubs.acs.org/doi/full/10.1021/acs.jcim.3c00378)  
<small><b>Journal of Chemical Information and Modeling, 2023</b> and <b>MLSB Workshop at NeurIPS, 2022</b></small>  
<small><u>Felix Teufel</u>, Jan C. Refsgaard, Marina A. Kasimova, Kristine Deibler, Christian T. Madsen, Carsten Stahlhut, Mads Grønborg, Ole Winther, Dennis Madsen</small>     
We combined AlphaFold-Multimer with DeepTMHMM as a peptide receptor deorphanization method.  
[Code on Github](https://github.com/fteufel/alphafold-peptide-receptors)

<img src="https://fteufel.github.io/images/publications/ppv.png" style="float:right;width:400px;">
[**Combining mass spectrometry and machine learning to discover bioactive peptides**](https://www.nature.com/articles/s41467-022-34031-z)  
<small><b>Nature Communications, 2022</b></small>  
<small>Christian T. Madsen, Jan C. Refsgaard, <u>Felix Teufel</u>, Sonny K. Kjærulff, Zhe Wang, Guangjun Meng, Carsten Jessen, Petteri Heljo, Qunfeng Jiang, Xin Zhao, Bo Wu, Xueping Zhou, Yang Tang, Jacob F. Jeppesen, Christian D. Kelstrup, Stephen T. Buckley, Søren Tullin, Jan Nygaard-Jensen, Xiaoli Chen, Fang Zhang, Jesper V. Olsen, Dan Han, Mads Grønborg & Ulrik de Lichtenberg</small>  
Discovering bioactive peptides in large-scale peptidomics data from their mass spectrometry signal.  
[Code on Github](https://github.com/jancr/ppv) 


