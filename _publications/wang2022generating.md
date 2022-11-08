---
title: "Generating directed networks with predetermined assortativity measures"
collection: publications
permalink: /publication/wang2022generating
excerpt: 'In this paper, we proposed an efficient algorithm, called DiDPR, for generating directed networks with predetermined (directed) assortativity measures. The proposed algorithm is 
capable of preserving some important network properties, such as in- and out-degree distributions. The key idea of the algorithm is to convert the generation procedure to solving a convex
optimization problem. The performance assessment of the proposed algorithm was done through extensive simulations and a Facebook wall post social network. The implementation of DiDPR is
available in R package [wdnet](https://CRAN.R-project.org/package=wdnet).'
date: 2022-10-10
venue: 'Statistics and Computing'
paperurl: 'https://doi.org/10.1007/s11222-022-10161-8'
citation: 'Wang, T., Yan, J., Yuan, Y. and Zhang, P. (2022). 
&quot;Generating directed networks with predetermined assortativity measures.&quot; 
<i>Statistics and Computing</i>, <b>91</b>(5), 91.'
---
Assortativity coefficients are important metrics to analyze both directed and undirected networks. In general, it is not guaranteed that the fitted model will always agree with the assortativity coefficients 
in the given network, and the structure of directed networks is more complicated than the undirected ones. Therefore, we provide a remedy by proposing a degree-preserving rewiring algorithm, called DiDPR, for 
generating directed networks with given directed assortativity coefficients. We construct the joint edge distribution of the target network by accounting for the four directed assortativity coefficients 
simultaneously, provided that they are attainable, and obtain the desired network by solving a convex optimization problem. Our algorithm also helps check the attainability of the given assortativity coefficients.  
We assess the performance of the proposed algorithm by simulation studies with focus on two different network models, namely Erdös–Rényi and preferential attachment random networks. We then apply the algorithm to 
a Facebook wall post network as a real data example. The codes for implementing our algorithm are publicly available in R package [wdnet](https://CRAN.R-project.org/package=wdnet).

[BibTex](https://panpanzhang99299.github.io/files/wang2022generating.bib)

[Mathematical review](https://mathscinet.ams.org/mathscinet-getitem?mr=4493723)

[Download paper here](https://doi.org/10.1007/s11222-022-10161-8)
