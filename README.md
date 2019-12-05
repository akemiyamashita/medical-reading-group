![](mila-medical-logo-small.png)

# Mila Medical Reading Group

A group to discuss methods related to genomics, imaging, or clinical data. Enumerating all successful and impactful applications of ML/DL in medicine.

Organizer: [Joseph Paul Cohen](https://josephpcohen.com)

Join the mailing list here: https://groups.google.com/forum/#!forum/mila-medical

| Date | Speaker | Title | Reference |
|---|--|--|----|
| ... | | | |
1/13/2019 | Hasib Zunair | <details><summary>Tuberculosis severity estimation from volumetric CT scans using uniformizing techniques and 3D Convolutional Net </summary><p> Mycobacterium  tuberculosis is  a  bacteria  that  causes  tuberculosis infection (TB), which is the second most common fatal infectious
disease after HIV. In this work, we propose a unified approach, where the model can be easily deployed in developing regions not only to aid radiologists in
diagnosis but also provide diagnosis in areas were medical practitioners and diagnosis equipment are  scarce.  The  contribution  of  this work is  twofold:
introduce a 3D Convolutional Network;  introduce  and  employ various preprocessing techniques to retain maximum information while
decreasing computation cost to improve the model performance without using clinically relevant metadata. Quantitative experiments show significant improvement over our previous work which is evaluated on the Image-CLEF Tuberculosis Severity Assessment 2019. Our proposed work achieves an AUC of 73% and a binary classification accuracy of 67.5% which is an overall improvement by a margin of 12% in AUC and 6% in classification accuracy. </p></details> | [paper](https://www.researchgate.net/publication/334680379_Estimating_Severity_from_CT_Scans_of_Tuberculosis_Patients_using_3D_Convolutional_Nets_and_Slice_Selection) |
1/6/2019 | | | |
| 12/30/2019 | | Cancelled | |
| 12/23/2019 | | Cancelled | |
| 12/16/2019 | | | |
| 12/9/2019 | | Cancelled for NeurIPS | |
| 12/2/2019 | | | |
| 11/25/2019 | | | |
| 11/18/2019 | - | Cancelled for [AI for Health](https://www.meetup.com/AIForHealth/events/266542207) | |
| 11/11/2019 | Zongwei Zhou | Models Genesis: Generic Autodidactic Models for 3D Medical Image Analysis | [Paper](https://arxiv.org/abs/1908.06912) [GitHub](https://github.com/MrGiovanni/ModelsGenesis) [Slides](slides/ModelsGenesis.pdf) |
| 11/4/2019 | - | Cancelled| |
| 10/28/2019 | - | Cancelled | |
| 10/21/2019 | Smita Krishnaswamy |Deep learning and graph signal processing yield insight into cellular state spaces under complex experimental conditions | [Slides](https://www.dropbox.com/s/spf800u712prx21/MILA_talk.pptx?dl=0) |
| 10/14/2019 | - | Cancelled for Thanksgiving Day (Canada) | |
| 10/7/2019 | | | |
| 9/30/2019 | Paul Bertin| <details><summary>Disentangled Representations of Cellular Identity</summary><p>We introduce a disentangled representation for cellular identity that constructs a latent cellular state from a linear combination of condition specific basis vectors that are then decoded into gene ex- pression levels. The basis vectors are learned with a deep autoencoder model from single-cell RNA-seq data. Linear arithmetic in the disentangled representation successfully predicts nonlinear gene expression inter- actions between biological pathways in unobserved treatment conditions. We are able to recover the mean gene expression profiles of unobserved conditions with an average Pearson r = 0.73, which outperforms two linear baselines, one with an average r = 0.43 and another with an aver- age r = 0.19. Disentangled representations hold the promise to provide new explanatory power for the interaction of biological pathways and the prediction of effects of unobserved conditions for applications such as combinatorial therapy and cellular reprogramming. Our work is motivated by recent advances in deep generative models that have enabled synthesis of images and natural language with desired properties from interpolation in a latent representation of the data.</p></details> | [Paper](http://sci-hub.tw/https://link.springer.com/chapter/10.1007/978-3-030-17083-7_16) |
| 9/23/2019 | - | Cancelled for ICLR Submission Deadline | |
| 9/16/2019 | - | [AI for Health Meetup at UdeM](https://www.meetup.com/AIForHealth/events/264345677/)| |
| 9/9/2019 |Fabian Theis | <details><summary>Modeling differentiation and stimulation response in single-cell genomics</summary><p>Accurately modeling single cell state changes e.g. during differentiation or in response to perturbations is a central goal of computational biology. Single-cell technologies now give us easy and large-scale access to state observations on the transcriptomic and more recently also epigenomic level. In particular they allow resolving potential heterogeneities due to asynchronicity of differentiating or responding cells, and profiles across multiple conditions such as time points and replicates are being generated. <br>In this talk I will quickly review how to estimate lineage formation using graph abstraction as extension of pseudotemporal ordering, and how to take additional information such as RNA velocity into account. I then ask how to generalize predictions to phenomena absent from training data i.e. out-of-sample. For this, I will present scGen, a model combining variational autoencoders and latent space vector arithmetics for high-dimensional single-cell gene expression data. In benchmarks across a broad range of examples, we show that scGen accurately models dose and infection response of cells across cell types, studies and species. In particular, we demonstrate that scGen learns cell type and species specific response implying that it captures features that distinguish responding from non-responding genes and cells. </p></details> | [Paper](https://www.nature.com/articles/s41592-019-0494-8)|
| 9/2/2019 | - | Cancelled for Labor Day (US) | |
| 8/26/2019 | - | Cancelled | |
| 8/19/2019 | Joseph Paul Cohen | <details><summary>Chester: A Web Delivered Locally Computed Chest X-Ray Disease Prediction System</summary><p>Deep learning has shown promise to augment radiologists and improve the standard of care globally. Two main issues that complicate deploying these systems are patient privacy and scaling to the global population. To deploy a system at scale with minimal computational cost while preserving privacy we present a web delivered (but locally run) system for diagnosing chest X-Rays. Code is delivered via a URL to a web browser (including cell phones) but the patient data remains on the users machine and all processing occurs locally. The system is designed to be used as a reference where a user can process an image to confirm or aid in their diagnosis. The system contains three main components: out-of-distribution detection, disease prediction, and prediction explanation. The system open source and freely available here: https://mlmed.org/tools/xray</p></details> | [Paper](https://arxiv.org/abs/1901.11210)<br>[Slides](https://docs.google.com/presentation/d/14Gh_cDl6ACwpzDz4wFbmv83h65kxEiM0azCiXlqDaGw/edit) |
| 8/12/2019 | Becks Simpson | <details><summary>CARE: Class Attention to Regions of Lesion for Classification on Imbalanced Data</summary><p>To date, it is still an open and challenging problem for intelligent diagnosis systems to effectively learn from imbalanced data, especially with large samples of common diseases and much smaller samples of rare ones. Inspired by the process of human learning, this paper proposes a novel and effective way to embed attention into the machine learning process, particularly for learning characteristics of rare diseases. This approach does not change architectures of the original CNN classifiers and therefore can directly plug and play for any existing CNN architecture. Comprehensive experiments on a skin lesion dataset and a pneumonia chest X-ray dataset showed that paying attention to lesion regions of rare diseases during learning not only improved the classification performance on rare diseases, but also on the mean class accuracy.</p></details> |  [Paper](http://proceedings.mlr.press/v102/zhuang19a.html) |
| 8/5/2019 | Martin Weiss | <details><summary>Genome-wide identification of directed gene networks using large-scale population genomics data</summary><p>Identification of causal drivers behind regulatory gene networks is crucial in understanding gene function. Here, we develop a method for the large-scale inference of gene–gene interactions in observational population genomics data that are both directed (using local genetic instruments as causal anchors, akin to Mendelian Randomization) and specific (by controlling for linkage disequilibrium and pleiotropy). Analysis of genotype and whole-blood RNA-sequencing data from 3072 individuals identified 49 genes as drivers of downstream transcriptional changes (Wald P < 7 × 10−10), among which transcription factors were overrepresented (Fisher’s P = 3.3 × 10−7). Our analysis suggests new gene functions and targets, including for SENP7 (zinc-finger genes involved in retroviral repression) and BCL2A1 (target genes possibly involved in auditory dysfunction). Our work highlights the utility of population genomics data in deriving directed gene expression networks. A resource of trans-effects for all 6600 genes with a genetic instrument can be explored individually using a web-based browser.</p></details> | [Paper](https://www.nature.com/articles/s41467-018-05452-6)|
| 7/29/2019 | Mohammad Hashir | Clinical prediction on the MIMIC-III dataset: lessons learned from predicting mortality using vitals and notes (Part I) | [Slides](slides/20190729_clinicalprediction.pdf)|
| 7/22/2019 | Assya Trofimov| <details><summary>DeepKinZero: Zero-Shot Learning for Predicting Kinase-Phosphosite Associations Involving Understudied Kinases</summary><p>Protein phosphorylation is a key regulator of protein function in signal transduction pathways. Kinases are the enzymes that catalyze the phosphorylation of other proteins in a target specific manner. The dysregulation of phosphorylation is associated with many diseases including cancer. Although the advances in phosphoproteomics enable the identification of phosphosites at the proteome level, most of the phosphoproteome is still in the dark: more than 95% of the reported human phosphosites have no known kinases. Determining which kinase is responsible for phosphorylating a site remains an experimental challenge. Existing computational methods require several examples of known targets of a kinase to make accurate kinase specific predictions, yet for a large body of kinases, only a few or no target sites are reported. We present DeepKinZero, the first zero-shot learning approach to predict the kinase acting on a phosphosite for kinases with no known phosphosite information. DeepKinZero transfers knowledge from kinases with many known target phosphosites to those kinases with no known sites through a zero-shot learning model. The kinase specific positional amino acid preferences are learned using a bidirectional recurrent neural network. We show that DeepKinZero achieves significant improvement in accuracy for kinases with no known phosphosites in comparison to the baseline model and other methods available. By expanding our knowledge on understudied kinases, DeepKinZero can help to chart the phosphoproteome atlas.</p></details> | [Paper](https://www.biorxiv.org/content/10.1101/670638v2)|
| 7/15/2019 | Sreya Francis | <details><summary> Estimating Causal Effects from High-Dimensional Observational Data in Healthcare</summary><p> Everyone wants to make better decisions. The impact of a decision on an outcome of interest is called a causal effect, and is traditionally estimated by performing randomized experiments. However, large data sources such as electronic medical records present opportunities to study causal effects of interventions that are difficult to evaluate through experiments. One example is the management of septic patients in the ICU. This typically involves performing several interventions in sequence, the choice of one depending on the outcome of others. Successfully evaluating the effect of these choices depends on strong assumptions, such as having adjusted for all confounding variables. While many argue that having high-dimensional data increases the likelihood of this assumption being true, it also introduces new challenges: the more variables we use for estimating effects, the less likely that patients who received different treatments are similar in all of them. In this talk, we will discuss causal effect estimation and treatment group overlap. We will also discuss the potential outcomes framework, classical methods for estimating causal effects, as well as new ones, tailored for working with large datasets.</p></details> | [Paper](https://arxiv.org/abs/1606.03976) [Slides](slides/SreyaFrancis-CausalEffectEstimationInHealthcare.pdf) |
| 7/8/2019 | - | Cancelled for [MIDL](http://2019.midl.io/) | |
| 7/1/2019 | - | Cancelled for Canada| |
| 6/24/2019 | - | Cancelled for Quebec| |
| 6/17/2019 | - | Cancelled for CVPR | |
| 6/10/2019 | - | Cancelled for [ICML](https://icml.cc/) | |
| 6/3/2019 | Li Yao | <details><summary>Challenges in Machine Learning with Radiology</summary><p>This talk investigates three challenges in ML and radiology. Firstly, ML models trained on specialized medical data generalize poorly out-of-domain. In our recent MIDL paper (https://arxiv.org/abs/1904.01638), we empirically demonstrated the feasible of building a strong baseline for assessing such ability of neural nets. Secondly, automatic labelling with NLP from medical records only provides noisy ground truth. Our recent work (https://arxiv.org/abs/1905.02283 and https://arxiv.org/abs/1810.00967) highlights such a challenge and provides some preliminary results. Thirdly, classical non-ML models handle longitudinal data inefficiently. Some ML based recipes are presented to alleviate the computational issues (work in progress).</p></details> | |
| 5/27/2019 | Eugene Vorontsov | <details><summary>Boosting segmentation with weak supervision from image-to-image translation</summary><p>In many cases, especially with medical images, it is prohibitively challenging to produce a sufficiently large training sample of pixel-level annotations to train deep neural networks for semantic image segmentation. On the other hand, some information is often known about the contents of images. We leverage information on whether an image presents the segmentation target or whether it is absent from the image to improve segmentation performance by augmenting the amount of data usable for model training. Specifically, we propose a semi-supervised framework that employs image-to-image translation between weak labels (e.g., presence vs. absence of cancer), in addition to fully supervised segmentation on some examples. We conjecture that this translation objective is well aligned with the segmentation objective as both require the same disentangling of image variations. Building on prior image-to-image translation work, we re-use the encoder and decoders for translating in either direction between two domains, employing a strategy of selectively decoding domain-specific variations. For presence vs. absence domains, the encoder produces variations that are common to both and those unique to the presence domain. Furthermore, we successfully re-use one of the decoders used in translation for segmentation. We validate the proposed method on synthetic tasks of varying difficulty as well as on the real task of brain tumor segmentation in magnetic resonance images, where we show significant improvements over standard semi-supervised training with autoencoding.</p></details> | [Paper](https://arxiv.org/abs/1904.01636) <br> [Slides](slides/Boosting%20segmentation%20with%20weak%20supervision%20from%20image-to-image%20translation.pdf) |
| 5/21/2019 (Tuesday) | Paul Bertin &<br>Mohammad Hashir | <details><summary>Analysis of Gene Interaction Graphs for Biasing Machine Learning Models</summary><p>Gene interaction graphs aim to capture various relationships between genes and can be used to create more biologically-intuitive models for machine learning. There are many such graphs available which can differ in the number of genes and edges covered. In this work, we attempt to evaluate the biases provided by those graphs through utilizing them for 'Single Gene Inference' (SGI) which serves as, what we believe is, a proxy for more relevant prediction tasks. The SGI task assesses how well a gene's neighbors in a particular graph can 'explain' the gene itself in comparison to the baseline of using all the genes in the dataset. We evaluate seven major gene interaction graphs created by different research groups on two distinct datasets, TCGA and GTEx. We find that some graphs perform on par with the unbiased baseline for most genes with a significantly smaller feature set.</p></details> | [Paper](https://arxiv.org/abs/1905.02295) |
| 5/13/2019 | - | Cancelled for [McGill BBMESS](https://bbmess.wixsite.com/bbmess/symposium2019) | |
| 5/6/2019 | - | Cancelled for ICLR | |
| 4/29/2019 | Julien Cohen-Adad &<br>Mathieu Lavallée-Adam | [AI for Health at Mila!](https://www.meetup.com/AIForHealth/events/260733571/) | |
| 4/23/2019<br>Tuesday! | Georgy Derevyanko | <details><summary>Protein-protein docking using learned three-dimensional representations </summary><p>Abstract: Proteins are the cogs of cellular machinery. Understanding how these molecules interact and predicting structures of their complexes is unavoidable step we need to pass to understand emergence of the phenotype of an organism from its genotype. Rigid-body docking approaches the problem by assuming two proteins rigid and sampling rotations and translations of the ligand with respect to the receptor. The key idea, that allows the sampling to be performed in a reasonable timeframe is representation of the interaction energy between the two proteins as correlations of 3d protein representations. However, these representations themselves are either pretrained or handcrafted. In this work we present an algorithm that allows learning protein representations for docking in the end-to-end fashion.</p></details> | |
| 4/15/2019 |Phil Novosad |Self-ensembling for domain adaptation: application to neuroanatomical segmentation in MRI | |
| 4/8/2019 | Maxime Thibault | <details><summary>Prediction of the next medication order to assist prescription verification by pharmacists in a health care center</summary><p> In North American hospitals, pharmacists review all medication orders to ensure adequate medication use. As pharmacists move to a practice model involving direct patient care, the activity of drug order verification could benefit from a certain degree of automation to free up resources to perform clinical tasks. Potential applications of machine learning include detecting atypical orders and focusing pharmacist attention on unusual patterns instead of verifying every single order. We prototyped a machine learning model to predict the next prescribed drug during hospitalization, and we compared model predictions with pharmacist ratings on a sample of orders. This presentation will discuss health system pharmacy and the data it generates, the clinical problem we faced, how we developed a model that shows potential at helping pharmacists detect atypical orders, and how the predictions of this model correlate with pharmacist ratings.</p></details>| [Slides](slides/20190408_MILA_slides.pdf) [Repo](https://github.com/grouchysmurf/medorder_prediction) |
| 4/4/2019<br>Thursday! | Joseph Paul Cohen | <details><summary>Deep Learning Tools for Medicine: Perspectives for Impact</summary><p> Machine learning research has had and will continue to have impact in healthcare and medicine. This talk will discuss a few directions which can potentially have a transformative impact. Including clinical decision support, biased feature construction/representations, and unsupervised representation learning. With each area I will consider a pragmatic approach for any method gaining adoption. The intricacies of each potential use case and the climate of adoption all need to be considered in order to maximize impact.</p></details>| |
| 4/1/2019 | Becks Simpson | [Model Agnostic Saliency for Weakly Supervised Lesion Detection from Breast DCE-MRI](https://arxiv.org/abs/1807.07784) <br> [3D Context Enhanced Region-based Convolutional Neural Network for End-to-End Lesion Detection](https://arxiv.org/abs/1806.09648) | |
| 3/25/2019 | Cancelled | | |
| 3/18/2019 | Frederic Leblond |  <details><summary>Towards a Multimodal Spectroscopy Imaging Plateform for Intraoperative Tissue Characterization</summary><p>Abstract: We are developing multimodal intraoperative imaging tools based on an imaging platform combining Raman, fluorescence and diffuse reflectance (multi-spectral and SFDI) with the objective of gathering large spectral datasets across organ sites/pathologies and patients for the development of classification models using machine learning techniques. The combinaison of Raman, fluorescence and diffuse reflectance spectroscopic images offers the potential to provide a breadth of molecular features that can be employed for surface as well as for depth-resolved tissue characterisation. Using a versatile wide-field spectroscopic imaging plateform, databases of tissue-specific spectroscopic information can be acquired for future artificial intelligence applications. Here we will present recent results relating with the development of each imaging modality as well as progress towards the development of the multimodal imaging plateform and the wide-field intraoperative imaging probes to be used for data gathering in the scope of clinical studies. </p></details> | |
| 3/11/2019 | Thomas Rademaker |  <details><summary>Attack and defence in cellular decision-making: lessons from machine learning</summary><p>Abstract: Machine learning algorithms are sensitive to meaningless (or "adversarial") perturbations. This is reminiscent of cellular decision-making where ligands (called "antagonists") prevent correct signalling, like in early immune recognition. We draw a formal analogy between neural networks used in machine learning and models of cellular decision-making (adaptive proofreading). We apply attacks from machine learning to simple decision-making models, and show explicitly the correspondence to antagonism by weakly bound ligands. Such antagonism is absent in more nonlinear models, which inspired us to implement a biomimetic defence in neural networks filtering out adversarial perturbations. We then apply a gradient-descent approach from machine learning to different cellular decision-making models, and we reveal the existence of two regimes characterized by the presence or absence of a critical point. The critical point causes the strongest antagonists to lie close to the threshold. This is validated in the loss landscapes of robust neural networks and cellular decision-making models, and observed experimentally for immune cells. For both regimes, we explain how associated defence mechanisms shape the geometry of the loss landscape, and why different adversarial attacks are effective in different regimes. Our work connects evolved cellular decision-making to machine learning, and motivates the design of a general theory of adversarial perturbations, both for in vivo and in silico systems.</p></details> | [Paper](https://arxiv.org/abs/1807.04270) |
| 3/4/2019 |Geneviève Boucher |  <details><summary>DeepSynergy: predicting anti-cancer drug synergy with Deep Learning</summary><p>Abstract: In this paper, the authors applied a deep learning approach for predicting the synergy of drug combinations. DeepSynergy uses compound information as well as genomic information as inputs to a regression task in order to find specific drug combinations that have maximal efficacy in specific genomic context, in their case in given cancer cell lines.</p></details>  | [Paper](https://academic.oup.com/bioinformatics/article/34/9/1538/4747884) |
| 2/25/2019 | - | Cancelled for [AI for Health Event at UdeM](https://www.meetup.com/AIForHealth/events/259166623/) |  |
| 2/18/2019 | Camille Rochefort-Boulanger |  <details><summary>Comprehensive functional genomic resource and integrative model for the human brain</summary><p>Abstract: In this study, they build a gene regulatory network (GRN) for the brain, linking transcription factors, enhancers, and target genes from merging of the QTLs, generalized element-activity correlations, and Hi-C data. They integrate this GRN to a deep Boltzmann machine, by manually adding links between the visible nodes of the network given the relations from the GRN, to perform disease prediction for psychiatric disorders.</p></details> | [Paper](http://science.sciencemag.org/content/362/6420/eaat8464) |
| 2/11/2019 | Louis Collins | MRI basics: short presentation, questions + answers |  |
| 2/4/2019 | Baptiste Goujaud | Use of the adversarial training in medical imaging across examples |  |
| 1/28/2019 | Alex Zabbal | DL applications for Neuroscience |  |
| 1/21/2019 | Mandana Samiei | Training Medical Image Analysis Systems like Radiologists | [Paper](https://arxiv.org/abs/1805.10884) |
| 1/14/2019 | Martin Weiss and Paul Bertin | Gene Graph Convolutions |  |
| 12/12/2018 | Mohammed AlQuraishi | End-to-End Differentiable Learning of Protein Structure | [Paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3239970) |
| 11/28/2018 | Georgy Derevyanko | Predicting protein complexes: classical approaches and deep learning |  |
| 11/14/2018 | Julien Cohen | Connecting MRI physics and A.I. to advance neuroimaging | [Slides](slides/20181114_MILA_seminar.pdf) [gSlides](https://docs.google.com/presentation/d/1IN0lLS8lV_vSEwwyI6Vrb43HCc6ahtjY9wof_-vB0x4/edit) |
| 11/7/2018 | Georgy Derevyanko | Learning Protein Structure with a Differentiable Simulator |  |
| 10/31/2018 | Suzanne Tamang | Clinical tools: A survey of Suzanne Tamang's work |  |
| 10/24/2018 | Martin Weiss | A Survey of Mobile Computing for the Visually Impaired | [Paper](https://arxiv.org/abs/1811.10120) |
| 10/17/2018 | Paul Bertin | Uncertainty measures for Multiple Sclerosis Lesion Segmentation | [Paper](https://arxiv.org/abs/1808.01200) |
| 10/10/2018 | Abdou Mousas | Genome-wide polygenic scores for common diseases identify individuals with risk equivalent to monogenic mutations|  |
| 10/3/2018 | Vincent Frappier | Lessons from Natural Language Inference in the Clinical Domain | [Slides](slides/MILA_Medical_NLP_EHR.pdf) |
| 9/12/2018 | Assya Trofimov | dna2vec: Consistent vector representations of variable-length k-mers | [Paper](https://arxiv.org/abs/1701.06279)  |
| 9/5/2018 | Lucie Blais | Medication adherence as a predictor of morbidity and mortality in patients with chronic respiratory diseases |  |
| 8/22/2018 | Francis Dutil | DeepSEA Predicting effects of noncoding variants with deep learning–based sequence model |  |
| 8/8/2018 | Vincent Frappier | Recomendation of ICD codes literature review |  |
| 8/1/2018 | Martin Weiss | Syntax-Directed Variational Autoencoder for Structured Data | [gSlides](https://docs.google.com/presentation/d/1acNguM5q2Y0clg74dxFpnP3HMT9HhD6ayzhOnmbLmv4/edit) [Video](https://www.youtube.com/watch?v=6HqIk-PxpCo) |
| 6/27/2018 | Martin Weiss | Recurrent Neural Networks for Multivariate Time Series with Missing Values |  |
| 6/20/2018 | Vincent Frappier | Exploring sequence binding space using coevolution and structural tertiary motifs |  |
| 6/13/2018 | Joseph Paul Cohen | A survey of clinical data successes using machine learning | [Slides](https://docs.google.com/presentation/d/1hmJKGmreVzfGCjtcgy3aAFpuZHRNymN4vCBGpvfL0S0/edit) |
| 5/30/2018 | Georgy Derevyanko | Prediction of toxicity from chemical composition of a drug |  |
| 5/16/2018 | Georgy Derevyanko | End2end differentiable protein structure learning |  |
| 4/25/2018 | Everyone | Project updates |  |
| 4/18/2018 | Everyone | Project updates |  |
| 4/11/2018 | Georgy Derevyanko | Inverse Statistical Physics of Protein Sequences:  A Key Issues Review |  |
| 4/4/2018 | Joseph Cohen | Generative adversarial networks uncover epidermal regulators and predict single cell perturbations | [Slides](https://docs.google.com/presentation/d/1rS6kPXosNbSOWOiI2C8E18KWo20XEPubx6_VURYCco0/edit) |
| 3/28/2018 | Everyone | Slide Karaoke |  |
| 3/21/2018 | Martin Weiss | Network-based machine learning and graph theory algorithms for precision oncology |  |
| 3/14/2018 | Everyone | Project updates |  |
| 3/7/2018 | Francis Dutil | So you are presenting Convolutional Networks on Graphs for Learning Molecular Fingerprints | [Paper](https://arxiv.org/abs/1509.09292) |
| 2/28/2018 | Christopher Beckham | Automatic Chemical Design Using a Data-Driven Continuous Representation of Molecules |  |
| 2/21/2018 | Christopher Beckham & Geneviève Boucher | The cornucopia of meaningful leads: Applying deep adversarial autoencoders for new molecule development in oncology [Paper](http://www.oncotarget.com/index.php?journal=oncotarget&page=article&op=view&path%5B0%5D=14073&path%5B1%5D=44886) & Near-optimal probabilistic RNA-seq quantification [Paper](https://www.nature.com/articles/nbt.3519) |  |
| 2/14/2018 | Everyone | Project updates |  |
