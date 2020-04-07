
# awesome-medical-machine-learning

收集生物、基因、医学人工智能相关资料
## 目录
- [1. 生物 Biology](https://github.com/DenseAI/awesome-medical-machine-learning#1-生物-biology)
- [2. 基因 Genomics](https://github.com/DenseAI/awesome-medical-machine-learning#2-基因-genomics)
	- [2.1 基因序列分析与预测 Gene sequence analysis and prediction](https://github.com/DenseAI/awesome-medical-machine-learning#21-基因序列分析与预测-gene-sequence-analysis-and-prediction)
	- [2.2 泛癌症分析  Pan-cancer analysis](https://github.com/DenseAI/awesome-medical-machine-learning#22-泛癌症分析--pan-cancer-analysis)
	- [2.3 单细胞 Single-Cell](https://github.com/DenseAI/awesome-medical-machine-learning#23-单细胞-single-cell)
	- [2.4 表观基因组学 Epigenomes](https://github.com/DenseAI/awesome-medical-machine-learning#24-表观基因组学-epigenomes)
	
- [3 医学 Medicine](https://github.com/DenseAI/awesome-medical-machine-learning#3-医学-medicine)

## 1. 生物 Biology

## 2. 基因 Genomics

- [Helmholtz Zentrum München, German Research Center for Environmental Health, Theis lab](https://www.helmholtz-muenchen.de/icb/research/groups/theis-lab/publications/index.html)
- [Deep learning: new computational modelling techniques for genomics](https://www.nature.com/articles/s41576-019-0122-6) Eraslan, G., Avsec, Ž., Gagneur, J. et al. Nat Rev Genet 20, 389–403 (2019). https://doi.org/10.1038/s41576-019-0122-6
- [Computational Systems Biology: Deep Learning in the Life Sciences](https://mit6874.github.io/)
#### 2.1 基因序列分析与预测 Gene sequence analysis and prediction
- [Predicting effects of noncoding variants with deep learning–based sequence model](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4768299) Zhou J, Troyanskaya O G. Nature methods, 2015, 12(10): 931-934.
- [Deep learning sequence-based ab initio prediction of variant effects on expression and disease risk](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6094955/)
Zhou J, Theesfeld C L, Yao K, et al. Nature genetics, 2018, 50(8): 1171-1179.
- [DeepWAS: Multivariate genotype-phenotype associations by directly integrating regulatory information using deep learning](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007616) Arloth J, Eraslan G, Andlauer T F M, et al. PLOS Computational Biology, 2020, 16(2): e1007616.
- [Graph Neural Networks: A Review of Methods and Applications](https://arxiv.org/abs/1812.08434) Jie Zhou, Ganqu Cui, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Lifeng Wang, Changcheng Li, Maosong Sun
- [A Comprehensive Survey on Graph Neural Networks](https://arxiv.org/abs/1901.00596) Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu
    ##### 2.1.1 Software
    - [DeepWAS: Directly integrating regulatory information into GWAS using machine learning](https://github.com/cellmapslab/DeepWAS)
    - [Graph attention networks](https://github.com/PetarV-/GAT) Veličković P, Cucurull G, Casanova A, et al. . arXiv preprint arXiv:1710.10903, 2017.
    - [BioBombe: Sequentially compressed gene expression features enhances biological signatures](https://github.com/greenelab/BioBombe)
    
    ##### 2.1.2 Interpretation of Model Predictions
	- [A unified approach to interpreting model predictions](https://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions) Lundberg S M, Lee S I. Advances in neural information processing systems. 2017: 4765-4774.
	- [shap: A game theoretic approach to explain the output of any machine learning model](https://github.com/slundberg/shap)
    
#### 2.2 泛癌症分析  Pan-cancer analysis
- [Pan-cancer analysis of whole genomes](https://www.nature.com/articles/s41586-020-1969-6) 
Campbell, P.J., Getz, G., Korbel, J.O. et al. Nature 578, 82–93 (2020). https://doi.org/10.1038/s41586-020-1969-6
- [The repertoire of mutational signatures in human cancer](https://www.nature.com/articles/s41586-020-1943-3)Alexandrov L B, Kim J, Haradhvala N J, et al.  Nature, 2020, 578(7793): 94-101.
- [The evolutionary history of 2,658 cancers](https://www.nature.com/articles/s41586-019-1907-7) Gerstung M, Jolly C, Leshchiner I, et al.  Nature, 2020, 578(7793): 122-128.
- [Patterns of somatic structural variation in human cancer genomes](https://www.nature.com/articles/s41586-019-1913-9) Li, Y., Roberts, N.D., Wala, J.A. et al. Nature 578, 112–121 (2020). https://doi.org/10.1038/s41586-019-1913-9
- [Genomic basis for RNA alterations in cancer](https://www.nature.com/articles/s41586-020-1970-0)Calabrese, C., Davidson, N.R., Demircioğlu, D. et al. Nature 578, 129–136 (2020). https://doi.org/10.1038/s41586-020-1970-0
- [Analyses of non-coding somatic drivers in 2,658 cancer whole genomes](https://www.nature.com/articles/s41586-020-1965-x) Rheinbay, E., Nielsen, M.M., Abascal, F. et al. Nature 578, 102–111 (2020). https://doi.org/10.1038/s41586-020-1965-x
- [Comprehensive molecular characterization of mitochondrial genomes in human cancers](https://www.nature.com/articles/s41588-019-0557-x) Yuan, Y., Ju, Y.S., Kim, Y. et al. Nat Genet 52, 342–352 (2020). https://doi.org/10.1038/s41588-019-0557-x
- [Disruption of chromatin folding domains by somatic genomic rearrangements in human cancer](https://www.nature.com/articles/s41588-019-0564-y)Akdemir, K.C., Le, V.T., Chandran, S. et al.  Nat Genet 52, 294–305 (2020). https://doi.org/10.1038/s41588-019-0564-y
- [A deep learning system accurately classifies primary and metastatic cancers using passenger mutation patterns](https://www.nature.com/articles/s41467-019-13825-8) Jiao, W., Atwal, G., Polak, P. et al.  Nat Commun 11, 728 (2020). https://doi.org/10.1038/s41467-019-13825-8
- [Translating cancer genomics into precision medicine with artificial intelligence: applications, challenges and future perspectives](https://link.springer.com/article/10.1007/s00439-019-01970-5) Xu J, Yang P, Xue S, et al. Human genetics, 2019, 138(2): 109-124.
- [Analysis of 100,000 human cancer genomes reveals the landscape of tumor mutational burden](https://link.springer.com/article/10.1186/s13073-017-0424-2)
Chalmers, Z.R., Connelly, C.F., Fabrizio, D. et al. Genome Med 9, 34 (2017).
- [Whole-genome deep-learning analysis identifies contribution of noncoding mutations to autism risk.](https://www.nature.com/articles/s41588-019-0420-0) Zhou, J., Park, C.Y., Theesfeld, C.L. et al. Nat Genet 51, 973–980 (2019). https://doi.org/10.1038/s41588-019-0420-0
    ##### 2.2.1 癌症预测 Cancer Prognosis prediction
    - [Circulating tumor DNA 5-hydroxymethylcytosine as a novel diagnostic biomarker for esophageal cancer](https://www.nature.com/articles/s41422-018-0014-x)
    Tian, X., Sun, B., Chen, C. et al. Cell Res 28, 597–600 (2018). https://doi.org/10.1038/s41422-018-0014-x
    - [Integrating multi-omics data with deep learning for predicting cancer prognosis](https://www.biorxiv.org/content/10.1101/807214v1.full)
    Hua Chai, Xiang Zhou, Zifeng Cui, Jiahua Rao, Zheng Hu, Yutong Lu, Huiying Zhao, Yuedong Yang. bioRxiv 807214; doi: https://doi.org/10.1101/807214
    - [Cancer classification of single-cell gene expression data by neural network](https://academic.oup.com/bioinformatics/article-abstract/36/5/1360/5585747) Kim B H, Yu K, Lee P C W.  Bioinformatics, 2020, 36(5): 1360-1366.
    - [Deep learning based tumor type classification using gene expression data](https://dl.acm.org/doi/10.1145/3233547.3233588) Lyu B, Haque A. //Proceedings of the 2018 ACM international conference on bioinformatics, computational biology, and health informatics. 2018: 89-96.
    - [Sensitive and specific multi-cancer detection and localization using methylation signatures in cell-free DNA](https://www.sciencedirect.com/science/article/pii/S0923753420360580) M.C.Liu1, G.R.Oxnard, E.A.Klein, C.Swanton, M.V.Seiden, https://doi.org/10.1016/j.annonc.2020.02.011

#### 2.3 单细胞 Single-Cell
- [RNA sequencing: the teenage years](https://www.nature.com/articles/s41576-019-0150-2) Stark R, Grzelak M, Hadfield J. Nature Reviews Genetics, 2019, 20(11): 631-656. 
[PDF](https://www.uab.edu/hcgs/images/PDF_documents/RNA_sequencing-the_teenage_years_Nat_Rev_Genetics.pdf)   中文: [RNA-seq 这十年](https://cloud.tencent.com/developer/article/1483493)
- [Current best practices in single‐cell RNA‐seq analysis: a tutorial](https://www.embopress.org/doi/10.15252/msb.20188746) Luecken M D, Theis F J. Molecular systems biology, 2019, 15(6). 
中文：[重磅综述：三万字长文读懂单细胞RNA测序分析的最佳实践教程 （原理、代码和评述）](https://mp.weixin.qq.com/s?__biz=MzI5MTcwNjA4NQ==&mid=2247491322&idx=1&sn=0556e7e8723cac79cc32a2b99e7cadc6&chksm=ec0ddb70db7a5266a4826aa91f26e62c9b6c3fff6711ac646ef581511eaacb2a56df2f59d092&scene=21#wechat_redirect)
- [Clustering single-cell RNA-seq data with a model-based deep learning approach](https://www.nature.com/articles/s42256-019-0037-0) Tian, T., Wan, J., Song, Q. et al. Nat Mach Intell 1, 191–198 (2019). https://doi.org/10.1038/s42256-019-0037-0
- [Imputing Single-cell RNA-seq data by combining Graph Convolution and Autoencoder Neural Networks](https://www.biorxiv.org/content/10.1101/2020.02.05.935296v1) Jiahua Rao, Xiang Zhou, Yutong Lu, Huiying Zhao, Yuedong Yang
bioRxiv 2020.02.05.935296; doi: https://doi.org/10.1101/2020.02.05.935296
- [Probabilistic cell-type assignment of single-cell RNA-seq for tumor microenvironment profiling](https://www.nature.com/articles/s41592-019-0529-1)
Zhang, A.W., O’Flanagan, C., Chavez, E.A. et al. Nat Methods 16, 1007–1015 (2019). https://doi.org/10.1038/s41592-019-0529-1
- [DeepImpute: an accurate, fast, and scalable deep neural network method to impute single-cell RNA-seq data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1837-6)
Arisdakessian, C., Poirion, O., Yunits, B. et al. Genome Biol 20, 211 (2019). https://doi.org/10.1186/s13059-019-1837-6
- [Clustering single-cell RNA-seq data with a model-based deep learning approach](https://www.nature.com/articles/s42256-019-0037-0) Tian, T., Wan, J., Song, Q. et al. Nat Mach Intell 1, 191–198 (2019). https://doi.org/10.1038/s42256-019-0037-0
- [Unsupervised generative and graph representation learning for modelling cell differentiation](https://www.biorxiv.org/content/10.1101/801605v1.full) Ioana Bica, Helena Andrés-Terré, Ana Cvejic, Pietro Liò. bioRxiv 801605; doi: https://doi.org/10.1101/801605
- [A comparison of automatic cell identification methods for single-cell RNA sequencing data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1795-z) Abdelaal, T., Michielsen, L., Cats, D. et al. Genome Biol 20, 194 (2019). https://doi.org/10.1186/s13059-019-1795-z
github: [scRNAseq_Benchmark](https://github.com/tabdelaal/scRNAseq_Benchmark)
- [Scalable analysis of cell-type composition from single-cell transcriptomics using deep recurrent learning](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6774994) Deng Y, Bao F, Dai Q, et al. Nature methods, 2019, 16(4): 311-314.
- [Deep learning for inferring gene relationships from single-cell expression data](https://www.biorxiv.org/content/10.1101/365007v2.full) Yuan Y, Bar-Joseph Z.  Proceedings of the National Academy of Sciences, 2019, 116(52): 27151-27158.
- [Emerging deep learning methods for single-cell RNA-seq data analysis](https://link.springer.com/article/10.1007/s40484-019-0189-2) Zheng, J., Wang, K. Quant Biol 7, 247–254 (2019). https://doi.org/10.1007/s40484-019-0189-2
- [DeepImpute: an accurate, fast, and scalable deep neural network method to impute single-cell RNA-seq data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1837-6) Arisdakessian, C., Poirion, O., Yunits, B. et al. Genome Biol 20, 211 (2019). https://doi.org/10.1186/s13059-019-1837-6
- [Deep learning enables accurate clustering and batch effect removal in single-cell RNA-seq analysis](https://www.biorxiv.org/content/10.1101/530378v1.full) Xiangjie Li, Yafei Lyu, Jihwan Park, Jingxiao Zhang, Dwight Stambolian, Katalin Susztak, Gang Hu, Mingyao Li. bioRxiv 530378; doi: https://doi.org/10.1101/530378
- [Using neural networks for reducing the dimensions of single-cell RNA-Seq data](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5737331/)Lin C, Jain S, Kim H, et al. Nucleic acids research, 2017, 45(17): e156-e156.
- [Single-cell RNA-seq denoising using a deep count autoencoder](https://www.nature.com/articles/s41467-018-07931-2) Eraslan, G., Simon, L.M., Mircea, M. et al. Nat Commun 10, 390 (2019). https://doi.org/10.1038/s41467-018-07931-2
- [DigitalDLSorter: Deep-Learning on scRNA-Seq to deconvolute gene expression data](https://www.frontiersin.org/articles/10.3389/fgene.2019.00978/full) Torroja C, Sanchez-Cabo F. Frontiers in genetics, 2019, 10: 978.

	##### 2.3.1 Single-Cell Software
	- [scVI: scDeep generative modeling for single-cell omics data](https://github.com/YosefLab/scVI)
	- [cellassign: Automated, probabilistic assignment of cell types in scRNA-seq data](https://github.com/Irrationone/cellassign)
	- [scVAE: Variational auto-encoders for single-cell gene expression data](https://github.com/scvae/scvae)
	- [KPNN: Knowledge-primed neural networks enable biologically interpretable deep learning on single-cell sequencing data](https://github.com/epigen/KPNN)
	- [deepimpute: An accurate and efficient deep learning method for single-cell RNA-seq data imputation](https://github.com/lanagarmire/DeepImpute)
	- [scDeepCluster for Single Cell RNA-seq data](https://github.com/ttgump/scDeepCluster) 
	- [DiffVAE: Unsupervised generative and graph neural methods for modelling cell differentiation](https://github.com/ioanabica/DiffVAE)
	- [Deep learning approaches for single cell data](https://github.com/TranslationalBioinformaticsUnit/singlecelldb/wiki/Deep-learning-approaches-for-single-cell-data)
	- [awesome-single-cell](https://github.com/seandavi/awesome-single-cell)
	- [scScope](https://github.com/AltschulerWu-Lab/scScope)
	- [CNNC: covolutional neural network based coexpression analysis](https://github.com/xiaoyeye/CNNC)
	- [deepimpute: An accurate and efficient deep learning method for single-cell RNA-seq data imputation](https://github.com/lanagarmire/DeepImpute)
	- [DCA: Deep count autoencoder for denoising scRNA-seq data](https://github.com/theislab/dca)
	- [singlecelldb: Deep learning approaches for single cell data](https://github.com/TranslationalBioinformaticsUnit/singlecelldb/wiki/Deep-learning-approaches-for-single-cell-data)
	- [digitalDLSorter: A pipeline to generate a Deep Nerual Network cell type deconvolution model for bulk RNASeq samples from single cell experiment data](https://github.com/cartof/digitalDLSorter)
	
	##### 2.3.2 Single-Cell DataSet
	- [CellMarker: a manually curated resource of cell markers in human and mouse](http://biocc.hrbmu.edu.cn/CellMarker/index.jsp)
	- [HuRI: The Human Reference Protein Interactome Mapping Project](http://www.interactome-atlas.org/)
	
	

#### 2.4 表观基因组学 Epigenomes
- [Integrative analysis of 111 reference human epigenomes](https://www.nature.com/articles/nature14248) 
Kundaje, A., Meuleman, W., Ernst, J. et al. Nature 518, 317–330 (2015).
- [An integrated encyclopedia of DNA elements in the human genome](https://www.nature.com/articles/nature11247) 
Dunham, I., Kundaje, A., Aldred, S. et al. Nature 489, 57–74 (2012).
- [Integrative analysis of 10,000 epigenomic maps across 800 samples for regulatory genomics and disease dissection](https://www.biorxiv.org/content/10.1101/810291v2.full)
Carles B. Adsera, Yongjin P. Park, Wouter Meuleman, Manolis Kellis. bioRxiv 810291; doi: https://doi.org/10.1101/810291

#### 2.5 待分类
- [The accessible chromatin landscape of the human genome](https://www.nature.com/articles/nature11232) Thurman, R., Rynes, E., Humbert, R. et al. Nature 489, 75–82 (2012). https://doi.org/10.1038/nature11232

## 3 医学 Medicine

#### 3.1 命名实体识别 Named entity recognition
#### 3.1.1 命名实体识别竞赛 Named Entity Recognition Competition
- [CCKS 2017 电子病历命名实体识别](https://biendata.com/competition/CCKS2017_2/)
- [CCKS 2018 面向中文电子病历的命名实体识别 ](https://biendata.com/competition/CCKS2018_1/)


