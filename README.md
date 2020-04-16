
# awesome-biomedical-machine-learning

收集生物、基因、医学人工智能相关资料

Collect biological, genetic, medical artificial intelligence related materials

## 目录
- [1. 生物 Biology](https://github.com/DenseAI/awesome-medical-machine-learning#1-生物-biology)
- [2. 基因 Genomics](https://github.com/DenseAI/awesome-medical-machine-learning#2-基因-genomics)
	- [2.1 基因序列分析与预测 Gene sequence analysis and prediction](https://github.com/DenseAI/awesome-medical-machine-learning#21-基因序列分析与预测-gene-sequence-analysis-and-prediction)
	- [2.2 泛癌症分析  Pan-cancer analysis](https://github.com/DenseAI/awesome-medical-machine-learning#22-泛癌症分析--pan-cancer-analysis)
	- [2.3 单细胞 Single-Cell](https://github.com/DenseAI/awesome-medical-machine-learning#23-单细胞-single-cell)
	- [2.4 表观基因组学 Epigenomes](https://github.com/DenseAI/awesome-medical-machine-learning#24-表观基因组学-epigenomes)
	- [2.5 多基因风险评分 Polygenic Risk Scores](https://github.com/DenseAI/awesome-biomedical-machine-learning#25-多基因风险评分-polygenic-risk-scores)
- [3 生物医学 Biomedical Science](https://github.com/DenseAI/awesome-biomedical-machine-learning#3-生物医学-biomedical-science)
    - [3.1 生物医学NLP BioNLP](https://github.com/DenseAI/awesome-biomedical-machine-learning#31-生物医学nlp-bionlp)
    - [3.2 Histopathology 组织病理学](https://github.com/DenseAI/awesome-biomedical-machine-learning#32-histopathology-组织病理学)
    - [3.3 临床决策辅助系统 Clinical Decision Support System](https://github.com/DenseAI/awesome-biomedical-machine-learning#33-临床决策辅助系统-clinical-decision-support-system)

## 1. 生物 Biology

## 2. 基因 Genomics

- [Helmholtz Zentrum München, German Research Center for Environmental Health, Theis lab](https://www.helmholtz-muenchen.de/icb/research/groups/theis-lab/publications/index.html)
- [Deep learning: new computational modelling techniques for genomics](https://www.nature.com/articles/s41576-019-0122-6) Eraslan, G., Avsec, Ž., Gagneur, J. et al. Nat Rev Genet 20, 389–403 (2019). https://doi.org/10.1038/s41576-019-0122-6
- [Computational Systems Biology: Deep Learning in the Life Sciences](https://mit6874.github.io/)
- [Standards and guidelines for the interpretation of sequence variants: a joint consensus recommendation of the American College of Medical Genetics and Genomics and the Association for Molecular Pathology](https://www.nature.com/articles/gim201530?ux=07df2189-4e01-4c08-8ef3-5619cff0ca61&ux2=3739b439-66b5-4bf5-921e-0916eef236a7&ux3=&uxconf=Y) Richards, S., Aziz, N., Bale, S. et al. Genet Med 17, 405–423 (2015). https://doi.org/10.1038/gim.2015.30

#### 2.1 基因序列分析与预测 Gene sequence analysis and prediction
- [Predicting effects of noncoding variants with deep learning–based sequence model](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4768299) Zhou J, Troyanskaya O G. Nature methods, 2015, 12(10): 931-934.
- [Deep learning sequence-based ab initio prediction of variant effects on expression and disease risk](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6094955/)
Zhou J, Theesfeld C L, Yao K, et al. Nature genetics, 2018, 50(8): 1171-1179.
- [DeepWAS: Multivariate genotype-phenotype associations by directly integrating regulatory information using deep learning](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007616) Arloth J, Eraslan G, Andlauer T F M, et al. PLOS Computational Biology, 2020, 16(2): e1007616.
- [Graph Neural Networks: A Review of Methods and Applications](https://arxiv.org/abs/1812.08434) Jie Zhou, Ganqu Cui, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Lifeng Wang, Changcheng Li, Maosong Sun
- [A Comprehensive Survey on Graph Neural Networks](https://arxiv.org/abs/1901.00596) Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu
- [Learning causality in genomics](https://ypark.github.io/_docs/research_genomics_web.html)
- [DANN: a deep learning approach for annotating the pathogenicity of genetic variants](https://academic.oup.com/bioinformatics/article/31/5/761/2748191) Quang D, Chen Y, Xie X. Bioinformatics, 2015, 31(5): 761-763.
- [ *** A general framework for estimating the relative pathogenicity of human genetic variants](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3992975) Kircher, M., Witten, D., Jain, P. et al. Nat Genet 46, 310–315 (2014). https://doi.org/10.1038/ng.2892
    ##### 2.1.1 Software
    - [DeepWAS: Directly integrating regulatory information into GWAS using machine learning](https://github.com/cellmapslab/DeepWAS)
    - [Graph attention networks](https://github.com/PetarV-/GAT) Veličković P, Cucurull G, Casanova A, et al. . arXiv preprint arXiv:1710.10903, 2017.
    - [BioBombe: Sequentially compressed gene expression features enhances biological signatures](https://github.com/greenelab/BioBombe)
    - [DANN](https://cbcl.ics.uci.edu/public_data/DANN/)
    
    ##### 2.1.2 Interpretation of Model Predictions
	- [A unified approach to interpreting model predictions](https://papers.nips.cc/paper/7062-a-unified-approach-to-interpreting-model-predictions) Lundberg S M, Lee S I. Advances in neural information processing systems. 2017: 4765-4774.
	- [shap: A game theoretic approach to explain the output of any machine learning model](https://github.com/slundberg/shap)
	
	##### 2.1.3 Data
	- [T2DKP Datasets](http://www.kp4cd.org/datasets/t2d) 
    
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
- [ *** A deep learning system accurately classifies primary and metastatic cancers using passenger mutation patterns](https://www.nature.com/articles/s41467-019-13825-8) Jiao, W., Atwal, G., Polak, P. et al.  Nat Commun 11, 728 (2020). https://doi.org/10.1038/s41467-019-13825-8
- [Translating cancer genomics into precision medicine with artificial intelligence: applications, challenges and future perspectives](https://link.springer.com/article/10.1007/s00439-019-01970-5) Xu J, Yang P, Xue S, et al. Human genetics, 2019, 138(2): 109-124.
- [Analysis of 100,000 human cancer genomes reveals the landscape of tumor mutational burden](https://link.springer.com/article/10.1186/s13073-017-0424-2)
Chalmers, Z.R., Connelly, C.F., Fabrizio, D. et al. Genome Med 9, 34 (2017).
- [ *** Whole-genome deep-learning analysis identifies contribution of noncoding mutations to autism risk.](https://www.nature.com/articles/s41588-019-0420-0) Zhou, J., Park, C.Y., Theesfeld, C.L. et al. Nat Genet 51, 973–980 (2019). https://doi.org/10.1038/s41588-019-0420-0
    ##### 2.2.1 癌症预测 Cancer Prognosis prediction
    - [Circulating tumor DNA 5-hydroxymethylcytosine as a novel diagnostic biomarker for esophageal cancer](https://www.nature.com/articles/s41422-018-0014-x)
    Tian, X., Sun, B., Chen, C. et al. Cell Res 28, 597–600 (2018). https://doi.org/10.1038/s41422-018-0014-x
    - [Integrating multi-omics data with deep learning for predicting cancer prognosis](https://www.biorxiv.org/content/10.1101/807214v1.full)
    Hua Chai, Xiang Zhou, Zifeng Cui, Jiahua Rao, Zheng Hu, Yutong Lu, Huiying Zhao, Yuedong Yang. bioRxiv 807214; doi: https://doi.org/10.1101/807214
    - [Cancer classification of single-cell gene expression data by neural network](https://academic.oup.com/bioinformatics/article-abstract/36/5/1360/5585747) Kim B H, Yu K, Lee P C W.  Bioinformatics, 2020, 36(5): 1360-1366.
    - [Deep learning based tumor type classification using gene expression data](https://dl.acm.org/doi/10.1145/3233547.3233588) Lyu B, Haque A. //Proceedings of the 2018 ACM international conference on bioinformatics, computational biology, and health informatics. 2018: 89-96.
    - [Sensitive and specific multi-cancer detection and localization using methylation signatures in cell-free DNA](https://www.sciencedirect.com/science/article/pii/S0923753420360580) M.C.Liu1, G.R.Oxnard, E.A.Klein, C.Swanton, M.V.Seiden, https://doi.org/10.1016/j.annonc.2020.02.011
    - [Microbiome analyses of blood and tissues suggest cancer diagnostic approach](https://www.nature.com/articles/s41586-020-2095-1) Poore, G.D., Kopylova, E., Zhu, Q. et al.  Nature 579, 567–574 (2020). https://doi.org/10.1038/s41586-020-2095-1
    - [Identification of 12 cancer types through genome deep learning](https://www.nature.com/articles/s41598-019-53989-3) Sun, Y., Zhu, S., Ma, K. et al. Sci Rep 9, 17256 (2019). https://doi.org/10.1038/s41598-019-53989-3
    - [DeepMicro: deep representation learning for disease prediction based on microbiome data](https://www.nature.com/articles/s41598-020-63159-5) Oh, M., Zhang, L. Sci Rep 10, 6026 (2020). https://doi.org/10.1038/s41598-020-63159-5
    - [Overall survival prediction of non-small cell lung cancer by integrating microarray and clinical data with deep learning](https://www.nature.com/articles/s41598-020-61588-w) Lai, Y., Chen, W., Hsu, T. et al. Sci Rep 10, 4679 (2020). https://doi.org/10.1038/s41598-020-61588-w
    - [A deep learning approach to automate refinement of somatic variant calling from cancer sequencing data](https://www.nature.com/articles/s41588-018-0257-y) Ainscough, B.J., Barnell, E.K., Ronning, P. et al. Nat Genet 50, 1735–1743 (2018). https://doi.org/10.1038/s41588-018-0257-y
    - [Classification models for Invasive Ductal Carcinoma Progression, based on gene expression data-trained supervised machine learning](https://www.nature.com/articles/s41598-020-60740-w) Roy, S., Kumar, R., Mittal, V. et al. Sci Rep 10, 4113 (2020). https://doi.org/10.1038/s41598-020-60740-w
    - [Integrating multi-platform genomic datasets for kidney renal clear cell carcinoma subtyping using stacked denoising autoencoders](https://www.nature.com/articles/s41598-019-53048-x) Gu, T., Zhao, X. Sci Rep 9, 16668 (2019). https://doi.org/10.1038/s41598-019-53048-x
    - [OncoOmics approaches to reveal essential genes in breast cancer: a panoramic view from pathogenesis to precision medicine](https://www.nature.com/articles/s41598-020-62279-2)López-Cortés, A., Paz-y-Miño, C., Guerrero, S. et al.  Sci Rep 10, 5285 (2020). https://doi.org/10.1038/s41598-020-62279-2
    - [A community effort to create standards for evaluating tumor subclonal reconstruction](https://www.nature.com/articles/s41587-019-0364-z) Salcedo, A., Tarabichi, M., Espiritu, S.M.G. et al.  Nat Biotechnol 38, 97–107 (2020). https://doi.org/10.1038/s41587-019-0364-z
    - [ *** Dissecting the single-cell transcriptome network underlying gastric premalignant lesions and early gastric cancer](https://www.sciencedirect.com/science/article/pii/S221112471930525X) Zhang P, Yang M, Zhang Y, et al.  Cell reports, 2019, 27(6): 1934-1947. e5.
    ##### 2.2.2 Software 
    - [tcga: Microbial analysis in TCGA data](https://github.com/biocore/tcga)
    - [cancer-data: TCGA data acquisition and processing for Project Cognoma](https://github.com/cognoma/cancer-data)
    - [DeepMicro: Deep representation learning for disease prediction based on microbiome data](https://github.com/minoh0201/DeepMicro)
    - [overall_survival_nsclc: bimodal DNN for NSCLC patient overall survival prediction](https://github.com/idssplab/overall_survival_nsclc) 
    - [DeepSVR](https://github.com/griffithlab/DeepSVR)
    - [cancer_subtyping](https://github.com/tjgu/cancer_subtyping)
    
    ##### 2.2.3 Data
    - [CancerSEA: a cancer single-cell state atlas](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6324047/) Yuan H, Yan M, Zhang G, et al.  Nucleic acids research, 2019, 47(D1): D900-D908.
    - [The Medical Genome Reference Bank contains whole genome and phenotype data of 2570 healthy elderly](https://www.nature.com/articles/s41467-019-14079-0) Pinese, M., Lacaze, P., Rath, E.M. et al.  Nat Commun 11, 435 (2020). https://doi.org/10.1038/s41467-019-14079-0

#### 2.3 单细胞 Single-Cell
- [ *** RNA sequencing: the teenage years](https://www.nature.com/articles/s41576-019-0150-2) Stark R, Grzelak M, Hadfield J. Nature Reviews Genetics, 2019, 20(11): 631-656. 
[PDF](https://www.uab.edu/hcgs/images/PDF_documents/RNA_sequencing-the_teenage_years_Nat_Rev_Genetics.pdf)   中文: [RNA-seq 这十年](https://cloud.tencent.com/developer/article/1483493)
- [ *** Current best practices in single‐cell RNA‐seq analysis: a tutorial](https://www.embopress.org/doi/10.15252/msb.20188746) Luecken M D, Theis F J. Molecular systems biology, 2019, 15(6). 
中文：[重磅综述：三万字长文读懂单细胞RNA测序分析的最佳实践教程 （原理、代码和评述）](https://mp.weixin.qq.com/s?__biz=MzI5MTcwNjA4NQ==&mid=2247491322&idx=1&sn=0556e7e8723cac79cc32a2b99e7cadc6&chksm=ec0ddb70db7a5266a4826aa91f26e62c9b6c3fff6711ac646ef581511eaacb2a56df2f59d092&scene=21#wechat_redirect)
- [ *** Single-cell RNA-seq denoising using a deep count autoencoder](https://www.nature.com/articles/s41467-018-07931-2) Eraslan, G., Simon, L.M., Mircea, M. et al. Nat Commun 10, 390 (2019). https://doi.org/10.1038/s41467-018-07931-2
- [ *** Construction of a human cell landscape at single-cell level](https://www.nature.com/articles/s41586-020-2157-4) Han, X., Zhou, Z., Fei, L. et al. Nature (2020). https://doi.org/10.1038/s41586-020-2157-4
- [Clustering single-cell RNA-seq data with a model-based deep learning approach](https://www.nature.com/articles/s42256-019-0037-0) Tian, T., Wan, J., Song, Q. et al. Nat Mach Intell 1, 191–198 (2019). https://doi.org/10.1038/s42256-019-0037-0
- [Imputing Single-cell RNA-seq data by combining Graph Convolution and Autoencoder Neural Networks](https://www.biorxiv.org/content/10.1101/2020.02.05.935296v1) Jiahua Rao, Xiang Zhou, Yutong Lu, Huiying Zhao, Yuedong Yang
bioRxiv 2020.02.05.935296; doi: https://doi.org/10.1101/2020.02.05.935296
- [Probabilistic cell-type assignment of single-cell RNA-seq for tumor microenvironment profiling](https://www.nature.com/articles/s41592-019-0529-1)
Zhang, A.W., O’Flanagan, C., Chavez, E.A. et al. Nat Methods 16, 1007–1015 (2019). https://doi.org/10.1038/s41592-019-0529-1
- [DeepImpute: an accurate, fast, and scalable deep neural network method to impute single-cell RNA-seq data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1837-6)
Arisdakessian, C., Poirion, O., Yunits, B. et al. Genome Biol 20, 211 (2019). https://doi.org/10.1186/s13059-019-1837-6
- [Unsupervised generative and graph representation learning for modelling cell differentiation](https://www.biorxiv.org/content/10.1101/801605v1.full) Ioana Bica, Helena Andrés-Terré, Ana Cvejic, Pietro Liò. bioRxiv 801605; doi: https://doi.org/10.1101/801605
- [A comparison of automatic cell identification methods for single-cell RNA sequencing data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1795-z) Abdelaal, T., Michielsen, L., Cats, D. et al. Genome Biol 20, 194 (2019). https://doi.org/10.1186/s13059-019-1795-z
github: [scRNAseq_Benchmark](https://github.com/tabdelaal/scRNAseq_Benchmark)
- [Scalable analysis of cell-type composition from single-cell transcriptomics using deep recurrent learning](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6774994) Deng Y, Bao F, Dai Q, et al. Nature methods, 2019, 16(4): 311-314.
- [Deep learning for inferring gene relationships from single-cell expression data](https://www.biorxiv.org/content/10.1101/365007v2.full) Yuan Y, Bar-Joseph Z.  Proceedings of the National Academy of Sciences, 2019, 116(52): 27151-27158.
- [Emerging deep learning methods for single-cell RNA-seq data analysis](https://link.springer.com/article/10.1007/s40484-019-0189-2) Zheng, J., Wang, K. Quant Biol 7, 247–254 (2019). https://doi.org/10.1007/s40484-019-0189-2
- [DeepImpute: an accurate, fast, and scalable deep neural network method to impute single-cell RNA-seq data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1837-6) Arisdakessian, C., Poirion, O., Yunits, B. et al. Genome Biol 20, 211 (2019). https://doi.org/10.1186/s13059-019-1837-6
- [Deep learning enables accurate clustering and batch effect removal in single-cell RNA-seq analysis](https://www.biorxiv.org/content/10.1101/530378v1.full) Xiangjie Li, Yafei Lyu, Jihwan Park, Jingxiao Zhang, Dwight Stambolian, Katalin Susztak, Gang Hu, Mingyao Li. bioRxiv 530378; doi: https://doi.org/10.1101/530378
- [Using neural networks for reducing the dimensions of single-cell RNA-Seq data](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5737331/)Lin C, Jain S, Kim H, et al. Nucleic acids research, 2017, 45(17): e156-e156.
- [DigitalDLSorter: Deep-Learning on scRNA-Seq to deconvolute gene expression data](https://www.frontiersin.org/articles/10.3389/fgene.2019.00978/full) Torroja C, Sanchez-Cabo F. Frontiers in genetics, 2019, 10: 978.
- [Tools for the analysis of high-dimensional single-cell RNA sequencing data. Nat Rev Nephrol (2020)](https://www.nature.com/articles/s41581-020-0262-0) Wu, Y., Zhang, K. https://doi.org/10.1038/s41581-020-0262-0
- [Using transfer learning from prior reference knowledge to improve the clustering of single-cell RNA-Seq data](https://www.nature.com/articles/s41598-019-56911-z) Mieth, B., Hockley, J.R.F., Görnitz, N. et al.  Sci Rep 9, 20353 (2019). https://doi.org/10.1038/s41598-019-56911-z
- [Realistic in silico generation and augmentation of single-cell RNA-seq data using generative adversarial networks](https://www.nature.com/articles/s41467-019-14018-z) Marouf, M., Machart, P., Bansal, V. et al. Nat Commun 11, 166 (2020). https://doi.org/10.1038/s41467-019-14018-z
- [Reconstruction of Cell-type-Specific Interactomes at Single-Cell Resolution](https://www.sciencedirect.com/science/article/pii/S2405471219303837) Mohammadi S, Davila-Velderrain J, Kellis M. Cell Systems, 2019, 9(6): 559-568. e4.
- [Probabilistic cell-type assignment of single-cell RNA-seq for tumor microenvironment profiling](https://www.nature.com/articles/s41592-019-0529-1) Zhang, A.W., O’Flanagan, C., Chavez, E.A. et al. Nat Methods 16, 1007–1015 (2019). https://doi.org/10.1038/s41592-019-0529-1
- [PAGA: graph abstraction reconciles clustering with trajectory inference through a topology preserving map of single cells](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1663-x) Wolf, F.A., Hamey, F.K., Plass, M. et al. Genome Biol 20, 59 (2019). https://doi.org/10.1186/s13059-019-1663-x
- [Realistic in silico generation and augmentation of single-cell RNA-seq data using generative adversarial networks](https://www.nature.com/articles/s41467-019-14018-z) Marouf, M., Machart, P., Bansal, V. et al.  Nat Commun 11, 166 (2020). https://doi.org/10.1038/s41467-019-14018-z
- [A reference map of the human binary protein interactome](https://www.nature.com/articles/s41586-020-2188-x) Luck, K., Kim, D., Lambourne, L. et al. Nature (2020). https://doi.org/10.1038/s41586-020-2188-x
- [ *** Single-cell RNA-seq data analysis on the receptor ACE2 expression reveals the potential risk of different human organs vulnerable to 2019-nCoV infection](http://journal.hep.com.cn/fmd/article/0000/2095-0217/26697) Zou X, Chen K, Zou J, et al.  Frontiers of medicine, 2020: 1-8.
- [Comprehensive integration of single-cell data](https://www.cell.com/cell/fulltext/S0092-8674(19)30559-8) Stuart T, Butler A, Hoffman P, et al.  Cell, 2019, 177(7): 1888-1902. e21.
	##### 2.3.1 Single-Cell Software
	- [ *** DCA: Deep count autoencoder for denoising scRNA-seq data](https://github.com/theislab/dca)
	- [scDeepCluster for Single Cell RNA-seq data](https://github.com/ttgump/scDeepCluster) 
	- [cellassign: Automated, probabilistic assignment of cell types in scRNA-seq data](https://github.com/Irrationone/cellassign)
	- [scVI: scDeep generative modeling for single-cell omics data](https://github.com/YosefLab/scVI)
	- [scVAE: Variational auto-encoders for single-cell gene expression data](https://github.com/scvae/scvae)
	- [KPNN: Knowledge-primed neural networks enable biologically interpretable deep learning on single-cell sequencing data](https://github.com/epigen/KPNN)
	- [deepimpute: An accurate and efficient deep learning method for single-cell RNA-seq data imputation](https://github.com/lanagarmire/DeepImpute)
	- [DiffVAE: Unsupervised generative and graph neural methods for modelling cell differentiation](https://github.com/ioanabica/DiffVAE)
	- [scScope](https://github.com/AltschulerWu-Lab/scScope)
	- [CNNC: covolutional neural network based coexpression analysis](https://github.com/xiaoyeye/CNNC)
	- [deepimpute: An accurate and efficient deep learning method for single-cell RNA-seq data imputation](https://github.com/lanagarmire/DeepImpute)
	- [digitalDLSorter: A pipeline to generate a Deep Nerual Network cell type deconvolution model for bulk RNASeq samples from single cell experiment data](https://github.com/cartof/digitalDLSorter)
	- [Deep learning approaches for single cell data](https://github.com/TranslationalBioinformaticsUnit/singlecelldb/wiki/Deep-learning-approaches-for-single-cell-data)
	- [awesome-single-cell](https://github.com/seandavi/awesome-single-cell)
	- [singlecelldb: Deep learning approaches for single cell data](https://github.com/TranslationalBioinformaticsUnit/singlecelldb/wiki/Deep-learning-approaches-for-single-cell-data)
	- [scHCL: A tool defines cell types in human based on single-cell digital expression](https://github.com/ggjlab/scHCL)
	- [SCINET: Single-Cell Imputation and NETwork inference](https://github.com/shmohammadi86/SCINET)
	- [paga: Mapping out the coarse-grained connectivity structures of complex manifolds.](https://github.com/theislab/paga)
	
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


#### 2.5 多基因风险评分 Polygenic Risk Scores
- [Towards clinical utility of polygenic risk scores](https://academic.oup.com/hmg/article/28/R2/R133/5540980) Samuel A Lambert, Gad Abraham, Michael Inouye, Human Molecular Genetics, Volume 28, Issue R2, 15 October 2019, Pages R133–R142, https://doi.org/10.1093/hmg/ddz187
- [A machine-learning heuristic to improve gene score prediction of polygenic traits](https://www.nature.com/articles/s41598-017-13056-1) Paré, G., Mao, S. & Deng, W.Q.  Sci Rep 7, 12665 (2017). https://doi.org/10.1038/s41598-017-13056-1
- [Polygenic risk scores outperform machine learning methods in predicting coronary artery disease status](https://onlinelibrary.wiley.com/doi/full/10.1002/gepi.22279) Gola D, Erdmann J, Müller‐Myhsok B, et al. Genetic Epidemiology, 2020.
- [Fine-mapping type 2 diabetes loci to single-variant resolution using high-density imputation and islet-specific epigenome maps](https://www.nature.com/articles/s41588-018-0241-6) Mahajan, A., Taliun, D., Thurner, M. et al.  Nat Genet 50, 1505–1513 (2018). https://doi.org/10.1038/s41588-018-0241-6
- [Machine learning SNP based prediction for precision medicine](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6445847/) Ho D S W, Schierding W, Wake M, et al. Frontiers in Genetics, 2019, 10.
- [Analysis of polygenic risk score usage and performance in diverse human populations](https://www.nature.com/articles/s41467-019-11112-0) Duncan, L., Shen, H., Gelaye, B. et al.  Nat Commun 10, 3328 (2019). https://doi.org/10.1038/s41467-019-11112-0
- [Polygenic and clinical risk scores and their impact on age at onset and prediction of cardiometabolic diseases and common cancers](https://www.nature.com/articles/s41591-020-0800-0) Mars, N., Koskela, J.T., Ripatti, P. et al.  Nat Med (2020). https://doi.org/10.1038/s41591-020-0800-0
- [The personal and clinical utility of polygenic risk scores](https://www.nature.com/articles/s41576-018-0018-x) orkamani, A., Wineinger, N.E. & Topol, E.J. Nat Rev Genet 19, 581–590 (2018). https://doi.org/10.1038/s41576-018-0018-x
- [Using the structure of genome data in the design of deep neural networks for predicting amyotrophic lateral sclerosis from genotype](https://academic.oup.com/bioinformatics/article/35/14/i538/5529261) Yin B, Balvert M, van der Spek R A A, et al. Bioinformatics, 2019, 35(14): i538-i547.
    ##### 2.5.1 Software
    - [GraBLD: an R based software package that makes polygenic traits prediction using gradient boosted and LD adjusted gene score weights](https://github.com/GMELab/GraBLD)
    - [ldpred: a Python based software package that adjusts GWAS summary statistics for the effects of linkage disequilibrium (LD)](https://github.com/bvilhjal/ldpred)
    - [AnnoPred: Genetic risk prediction integrating LD and functional annotations](https://github.com/yiminghu/AnnoPred)
    



#### 2.x 待分类
- [The accessible chromatin landscape of the human genome](https://www.nature.com/articles/nature11232) Thurman, R., Rynes, E., Humbert, R. et al. Nature 489, 75–82 (2012). https://doi.org/10.1038/nature11232


## 3 生物医学 Biomedical Science

#### 3.1 生物医学NLP BioNLP

#### 3.1.1 命名实体识别竞赛 Named Entity Recognition Competition
- [CCKS 2017 电子病历命名实体识别](https://biendata.com/competition/CCKS2017_2/)
- [CCKS 2018 面向中文电子病历的命名实体识别 ](https://biendata.com/competition/CCKS2018_1/)

#### 3.2 Histopathology 组织病理学
- [Classification and mutation prediction from non–small cell lung cancer histopathology images using deep learning](https://www.nature.com/articles/s41591-018-0177-5) Coudray N, Ocampo P S, Sakellaropoulos T, et al. Nature medicine, 2018, 24(10): 1559-1567.
    ##### 3.3.1 Software
    - [DeepPATH: The DeepPATH framework gathers the codes that have been used to study the use of a deep learning architecture (inception v3 from Google) to classify Lung cancer images.](https://github.com/ncoudray/DeepPATH) 
    
#### 3.3 临床决策辅助系统 Clinical Decision Support System
- [Development and application of a machine learning approach to assess short-term mortality risk among patients with cancer starting chemotherapy](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6324307) Elfiky A A, Pany M J, Parikh R B, et al. JAMA network open, 2018, 1(3): e180926-e180926.
