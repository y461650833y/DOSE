<!-- addtoany:= -->

<link rel="stylesheet" href="https://guangchuangyu.github.io/css/font-awesome.min.css">

<!-- release:=DOSE -->
<!-- devel:=DOSE -->
<!-- download:=DOSE:=total -->
<!-- download:=DOSE:=month -->

This package implements five methods proposed by _Resnik_, _Schlicker_, _Jiang_, _Lin_ and _Wang_ respectively for measuring semantic similarities among DO terms and gene products. Enrichment analyses including hypergeometric model and gene set enrichment analysis are also implemented for discovering disease associations of high-throughput biological data.


`DOSE` is released within the [Bioconductor](https://bioconductor.org/packages/DOSE) project and the source code is hosted in <a href="https://github.com/GuangchuangYu/DOSE"><i class="fa fa-github fa-lg"></i> GitHub</a>.


## <i class="fa fa-user"></i> Author

Guangchuang Yu, School of Public Health, The University of Hong Kong.

## <i class="fa fa-book"></i> Citation

Please cite the following article when using `DOSE`:

<!-- doi:=10.1093/bioinformatics/btu684 -->
<!-- citation:=Ug5p-4gJ2f0C:=16627502277303919270 -->
<!-- altmetric:=2788597 -->

__Yu G__, Wang L, Yan G and He QY<sup>*</sup>. DOSE: an R/Bioconductor package for Disease Ontology Semantic and Enrichment analysis. **Bioinformatics**, 2015, 31(4):608-609.


## <i class="fa fa-pencil"></i> Featured Articles

<img src="https://guangchuangyu.github.io/featured_img/DOSE/c5mb00663e-f1_hi-res.gif" width="500">

<i class="fa fa-hand-o-right"></i> Find out more on <i class="fa fa-pencil"></i> [Featured Articles](https://guangchuangyu.github.io/DOSE/featuredArticles/).


## <i class="fa fa-download"></i> Installation

Install `DOSE` is easy, follow the guide in the [Bioconductor page](https://bioconductor.org/packages/DOSE/):

```r
## try http:// if https:// URLs are not supported
source("https://bioconductor.org/biocLite.R")
## biocLite("BiocUpgrade") ## you may need this
biocLite("DOSE")
```

## <i class="fa fa-cogs"></i> Overview

#### <i class="fa fa-angle-double-right"></i> Semantic similarity measurement

+ DO term semantic similarity
+ Gene semantic similarity

#### <i class="fa fa-angle-double-right"></i> Enrichment Analysis

+ DO (Disease Ontology)
+ NCG (Network of Cancer Genes)
+ DisGeNet (gene-disease and SNP-disease associations)

#### <i class="fa fa-angle-double-right"></i> Visualization

+ barplot
+ cnetplot
+ dotplot
+ enrichMap
+ gseaplot
+ simplot
+ upsetplot


<i class="fa fa-hand-o-right"></i> Find out details and examples on <i class="fa fa-book"></i> [Documentation](https://guangchuangyu.github.io/DOSE/documentation/).

## <i class="fa fa-wrench"></i> Related Tools

<ul class="fa-ul">
	<li><i class="fa-li fa fa-angle-double-right"></i><a href="https://guangchuangyu.github.io/clusterProfiler">clusterProfiler</a> for Ontologies/pathways enrichment analyses</li>
	<li><i class="fa-li fa fa-angle-double-right"></i><a href="https://guangchuangyu.github.io/GOSemSim">GOSemSim</a> for GO semantic similarity measurement</li>
	<li><i class="fa-li fa fa-angle-double-right"></i><a href="https://guangchuangyu.github.io/meshes">meshes</a> for MeSH Enrichment and Semantic analysis</li>
	<li><i class="fa-li fa fa-angle-double-right"></i><a href="https://guangchuangyu.github.io/ReactomePA">ReactomePA</a> for Reactome pathway analysis</li>
</ul>

<i class="fa fa-hand-o-right"></i> Find out more on [projects](https://guangchuangyu.github.io/#projects).


## <i class="fa fa-code-fork"></i> Projects that depend on _DOSE_

<!-- package_depend:=DOSE:=CRAN -->

<!-- package_depend:=DOSE:=BioC -->


## <i class="fa fa-comment"></i> Feedback
<ul class="fa-ul">
	<li><i class="fa-li fa fa-hand-o-right"></i> Please make sure you [follow the guide](https://guangchuangyu.github.io/2016/07/how-to-bug-author/) before posting any issue/question</li>
	<li><i class="fa-li fa fa-bug"></i> For bugs or feature requests, please post to <i class="fa fa-github-alt"></i> [github issue](https://github.com/GuangchuangYu/DOSE/issues)</li>
	<li><i class="fa-li fa fa-question"></i>  For user questions, please post to [Bioconductor support site](https://support.bioconductor.org/) and [Biostars](https://www.biostars.org/). We are following every post tagged with **DOSE**</li>
	<li><i class="fa-li fa fa-commenting"></i> Join the group chat on <a href="https://twitter.com/hashtag/DOSE"><i class="fa fa-twitter fa-lg"></i></a> and <a href="http://huati.weibo.com/k/DOSE"><i class="fa fa-weibo fa-lg"></i></a></li>
</ul>
