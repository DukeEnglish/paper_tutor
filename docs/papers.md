# cs.CL 

| Item |Content|
| --- |---|
|idx| 1 |
|title| Cross-lingual neural fuzzy matching for exploiting target-language monolingual corpora in computer-aided translation |
|authors| Miquel Esplà-GomisVíctor M. Sánchez-CartagenaJuan Antonio Pérez-OrtizFelipe Sánchez-Martínez
|links| http://dx.doi.org/10.18653/v1/2022.emnlp-main.511 |
|updated| 2024-01-16 14:00:28 UTC |
|summary| Computer-aided translation CAT tools based on translation memories MTplay a prominent role in the translation workflow of professional translators.However the reduced availability of in-domain TMs as compared to in-domainmonolingual corpora limits its adoption for a number of translation tasks. Inthis paper we introduce a novel neural approach aimed at overcoming thislimitation by exploiting not only TMs but also in-domain target-language TLmonolingual corpora and still enabling a similar functionality to that offeredby conventional TM-based CAT tools. Our approach relies on cross-lingualsentence embeddings to retrieve translation proposals from TL monolingualcorpora and on a neural model to estimate their post-editing effort. The paperpresents an automatic evaluation of these techniques on four language pairsthat shows that our approach can successfully exploit monolingual texts in aTM-based CAT environment increasing the amount of useful translationproposals and that our neural model for estimating the post-editing effortenables the combination of translation proposals obtained from monolingualcorpora and from TMs in the usual way. A human evaluation performed on a singlelanguage pair confirms the results of the automatic evaluation and seems toindicate that the translation proposals retrieved with our approach are moreuseful than what the automatic evaluation shows. |


| Item |Content|
| --- |---|
|idx| 2 |
|title| Morphology and Syntax of the Tamil Language |
|authors| Kengatharaiyer Sarveswaran
|links| http://arxiv.org/abs/2401.08367v1 |
|updated| 2024-01-16 13:52:25 UTC |
|summary| This paper provides an overview of the morphology and syntax of the Tamillanguage focusing on its contemporary usage. The paper also highlights thecomplexity and richness of Tamil in terms of its morphological and syntacticfeatures which will be useful for linguists analysing the language andconducting comparative studies. In addition the paper will be useful for thosedeveloping computational resources for the Tamil language. It is proven as arule-based morphological analyser cum generator and a computational grammar forTamil have already been developed based on this paper. To enhance accessibilityfor a broader audience the analysis is conducted without relying on anyspecific grammatical formalism. |


| Item |Content|
| --- |---|
|idx| 3 |
|title| Hallucination Detection and Hallucination Mitigation: An Investigation |
|authors| Junliang LuoTianyu LiDi WuMichael JenkinSteve LiuGregory Dudek
|links| http://arxiv.org/abs/2401.08358v1 |
|updated| 2024-01-16 13:36:07 UTC |
|summary| Large language models LLMs including ChatGPT Bard and Llama haveachieved remarkable successes over the last two years in a range of differentapplications. In spite of these successes there exist concerns that limit thewide application of LLMs. A key problem is the problem of hallucination.Hallucination refers to the fact that in addition to correct responses LLMscan also generate seemingly correct but factually incorrect responses. Thisreport aims to present a comprehensive review of the current literature on bothhallucination detection and hallucination mitigation. We hope that this reportcan serve as a good reference for both engineers and researchers who areinterested in LLMs and applying them to real world tasks. |


| Item |Content|
| --- |---|
|idx| 4 |
|title| Salute the Classic: Revisiting Challenges of Machine Translation in the Age of Large Language Models |
|authors| Jianhui PangFanghua YeLongyue WangDian YuDerek F. WongShuming ShiZhaopeng Tu
|links| http://arxiv.org/abs/2401.08350v2 |
|updated| 2024-01-17 06:47:29 UTC |
|summary| The evolution of Neural Machine Translation NMT has been significantlyinfluenced by six core challenges Koehn and Knowles 2017 which have actedas benchmarks for progress in this field. This study revisits these challengesoffering insights into their ongoing relevance in the context of advanced LargeLanguage Models LLMs: domain mismatch amount of parallel data rare wordprediction translation of long sentences attention model as word alignmentand sub-optimal beam search. Our empirical findings indicate that LLMseffectively lessen the reliance on parallel data for major languages in thepretraining phase. Additionally the LLM-based translation system significantlyenhances the translation of long sentences that contain approximately 80 wordsand shows the capability to translate documents of up to 512 words. Howeverdespite these significant improvements the challenges of domain mismatch andprediction of rare words persist. While the challenges of word alignment andbeam search specifically associated with NMT may not apply to LLMs weidentify three new challenges for LLMs in translation tasks: inferenceefficiency translation of low-resource languages in the pretraining phase andhuman-aligned evaluation. The datasets and models are released athttps://github.com/pangjh3/LLM4MT. |


| Item |Content|
| --- |---|
|idx| 5 |
|title| RoTBench: A Multi-Level Benchmark for Evaluating the Robustness of Large Language Models in Tool Learning |
|authors| Junjie YeYilong WuSongyang GaoSixian LiGuanyu LiXiaoran FanQi ZhangTao GuiXuanjing Huang
|links| http://arxiv.org/abs/2401.08326v1 |
|updated| 2024-01-16 12:45:15 UTC |
|summary| Tool learning has generated widespread interest as a vital means ofinteraction between Large Language Models LLMs and the physical world.Current research predominantly emphasizes LLMs capacity to utilize tools inwell-structured environments while overlooking their stability when confrontedwith the inevitable noise of the real world. To bridge this gap we introduceRoTBench a multi-level benchmark for evaluating the robustness of LLMs in toollearning. Specifically we establish five external environments each featuringvarying levels of noise i.e. Clean Slight Medium Heavy and Unionproviding an in-depth analysis of the models resilience across three criticalphases: tool selection parameter identification and content filling.Experiments involving six widely-used models underscore the urgent necessityfor enhancing the robustness of LLMs in tool learning. For instance theperformance of GPT-4 even drops significantly from 80.00 to 58.10 when there isno substantial change in manual accuracy. More surprisingly the noisecorrection capability inherent in the GPT family paradoxically impedes itsadaptability in the face of mild noise. In light of these findings we proposeRoTTuning a strategy that enriches the diversity of training environments tobolster the robustness of LLMs in tool learning. The code and data areavailable at https://github.com/Junjie-Ye/RoTBench. |


# cs.AI 

| Item |Content|
| --- |---|
|idx| 1 |
|title| KADEL: Knowledge-Aware Denoising Learning for Commit Message Generation |
|authors| Wei TaoYucheng ZhouYanlin WangHongyu ZhangHaofen WangWenqiang Zhang
|links| http://arxiv.org/abs/2401.08376v1 |
|updated| 2024-01-16 14:07:48 UTC |
|summary| Commit messages are natural language descriptions of code changes which areimportant for software evolution such as code understanding and maintenance.However previous methods are trained on the entire dataset without consideringthe fact that a portion of commit messages adhere to good practice i.e.good-practice commits while the rest do not. On the basis of our empiricalstudy we discover that training on good-practice commits significantlycontributes to the commit message generation. Motivated by this finding wepropose a novel knowledge-aware denoising learning method called KADEL.Considering that good-practice commits constitute only a small proportion ofthe dataset we align the remaining training samples with these good-practicecommits. To achieve this we propose a model that learns the commit knowledgeby training on good-practice commits. This knowledge model enablessupplementing more information for training samples that do not conform to goodpractice. However since the supplementary information may contain noise orprediction errors we propose a dynamic denoising training method. This methodcomposes a distribution-aware confidence function and a dynamic distributionlist which enhances the effectiveness of the training process. Experimentalresults on the whole MCMD dataset demonstrate that our method overall achievesstate-of-the-art performance compared with previous methods. Our source codeand data are available at https://github.com/DeepSoftwareAnalytics/KADEL |


| Item |Content|
| --- |---|
|idx| 2 |
|title| Hallucination Detection and Hallucination Mitigation: An Investigation |
|authors| Junliang LuoTianyu LiDi WuMichael JenkinSteve LiuGregory Dudek
|links| http://arxiv.org/abs/2401.08358v1 |
|updated| 2024-01-16 13:36:07 UTC |
|summary| Large language models LLMs including ChatGPT Bard and Llama haveachieved remarkable successes over the last two years in a range of differentapplications. In spite of these successes there exist concerns that limit thewide application of LLMs. A key problem is the problem of hallucination.Hallucination refers to the fact that in addition to correct responses LLMscan also generate seemingly correct but factually incorrect responses. Thisreport aims to present a comprehensive review of the current literature on bothhallucination detection and hallucination mitigation. We hope that this reportcan serve as a good reference for both engineers and researchers who areinterested in LLMs and applying them to real world tasks. |


| Item |Content|
| --- |---|
|idx| 3 |
|title| Boosting Gradient Ascent for Continuous DR-submodular Maximization |
|authors| Qixin ZhangZongqi WanZengde DengZaiyi ChenXiaoming SunJialin ZhangYu Yang
|links| http://arxiv.org/abs/2401.08330v1 |
|updated| 2024-01-16 12:49:10 UTC |
|summary| Projected Gradient Ascent PGA is the most commonly used optimization schemein machine learning and operations research areas. Nevertheless numerousstudies and examples have shown that the PGA methods may fail to achieve thetight approximation ratio for continuous DR-submodular maximization problems.To address this challenge we present a boosting technique in this paper whichcan efficiently improve the approximation guarantee of the standard PGA toemphoptimal with only small modifications on the objective function. Thefundamental idea of our boosting technique is to exploit non-oblivious searchto derive a novel auxiliary function F whose stationary points are excellentapproximations to the global maximum of the original DR-submodular objectivef. Specifically when f is monotone and gamma-weakly DR-submodular wepropose an auxiliary function F whose stationary points can provide a better1-e-gamma-approximation than thegamma2/1gamma2-approximation guaranteed by the stationary points off itself. Similarly for the non-monotone case we devise another auxiliaryfunction F whose stationary points can achieve an optimalfrac1-min_boldsymbolxinmathcalCboldsymbolx_infty4-approximationguarantee where mathcalC is a convex constraint set. In contrast thestationary points of the original non-monotone DR-submodular function can bearbitrarily badcitepchen2023continuous. Furthermore we demonstrate thescalability of our boosting technique on four problems. In all of these fourproblems our resulting variants of boosting PGA algorithm beat the previousstandard PGA in several aspects such as approximation ratio and efficiency.Finally we corroborate our theoretical findings with numerical experimentswhich demonstrate the effectiveness of our boosting PGA methods. |


| Item |Content|
| --- |---|
|idx| 4 |
|title| RoTBench: A Multi-Level Benchmark for Evaluating the Robustness of Large Language Models in Tool Learning |
|authors| Junjie YeYilong WuSongyang GaoSixian LiGuanyu LiXiaoran FanQi ZhangTao GuiXuanjing Huang
|links| http://arxiv.org/abs/2401.08326v1 |
|updated| 2024-01-16 12:45:15 UTC |
|summary| Tool learning has generated widespread interest as a vital means ofinteraction between Large Language Models LLMs and the physical world.Current research predominantly emphasizes LLMs capacity to utilize tools inwell-structured environments while overlooking their stability when confrontedwith the inevitable noise of the real world. To bridge this gap we introduceRoTBench a multi-level benchmark for evaluating the robustness of LLMs in toollearning. Specifically we establish five external environments each featuringvarying levels of noise i.e. Clean Slight Medium Heavy and Unionproviding an in-depth analysis of the models resilience across three criticalphases: tool selection parameter identification and content filling.Experiments involving six widely-used models underscore the urgent necessityfor enhancing the robustness of LLMs in tool learning. For instance theperformance of GPT-4 even drops significantly from 80.00 to 58.10 when there isno substantial change in manual accuracy. More surprisingly the noisecorrection capability inherent in the GPT family paradoxically impedes itsadaptability in the face of mild noise. In light of these findings we proposeRoTTuning a strategy that enriches the diversity of training environments tobolster the robustness of LLMs in tool learning. The code and data areavailable at https://github.com/Junjie-Ye/RoTBench. |


| Item |Content|
| --- |---|
|idx| 5 |
|title| Large Language Models are Null-Shot Learners |
|authors| Pittawat TaveekitworachaiFebri AbdullahRuck Thawonmas
|links| http://arxiv.org/abs/2401.08273v1 |
|updated| 2024-01-16 10:53:11 UTC |
|summary| This paper presents null-shot prompting. Null-shot prompting exploitshallucination in large language models LLMs by instructing LLMs to utilizeinformation from the Examples section that never exists within the providedcontext to perform a task. While reducing hallucination is crucial andnon-negligible for daily and critical uses of LLMs we propose that in thecurrent landscape in which these LLMs still hallucinate it is possible infact to exploit hallucination to increase performance in performing taskscompared to standard zero-shot prompting. Experiments with six LLMs showimprovements in performance across the majority of eight datasets includingreading comprehension arithmetic reasoning and closed-book questionanswering. The observed inconsistency in increased relative performance acrossLLMs also potentially indicates a different degree of inherent hallucination ineach model. These differences show that it is possible to utilize null-shotprompting as a way to detect degrees of hallucination in LLMs using existingbenchmarking datasets. We also perform ablation studies includingexperimenting with a modified version of null-shot prompting that incorporatesideas from zero-shot chain-of-thought prompting which shows different trendsof results. |


# cs.LG 

| Item |Content|
| --- |---|
|idx| 1 |
|title| Robotic Imitation of Human Actions |
|authors| Josua SpisakMatthias KerzelStefan Wermter
|links| http://arxiv.org/abs/2401.08381v1 |
|updated| 2024-01-16 14:11:54 UTC |
|summary| Imitation can allow us to quickly gain an understanding of a new task.Through a demonstration we can gain direct knowledge about which actions needto be performed and which goals they have. In this paper we introduce a newapproach to imitation learning that tackles the challenges of a robot imitatinga human such as the change in perspective and body schema. Our approach canuse a single human demonstration to abstract information about the demonstratedtask and use that information to generalise and replicate it. We facilitatethis ability by a new integration of two state-of-the-art methods: a diffusionaction segmentation model to abstract temporal information from thedemonstration and an open vocabulary object detector for spatial information.Furthermore we refine the abstracted information and use symbolic reasoning tocreate an action plan utilising inverse kinematics to allow the robot toimitate the demonstrated action. |


| Item |Content|
| --- |---|
|idx| 2 |
|title| Sparse PCA with False Discovery Rate Controlled Variable Selection |
|authors| Jasin MachkourArnaud BreloyMichael MumaDaniel P. PalomarFrédéric Pascal
|links| http://arxiv.org/abs/2401.08375v1 |
|updated| 2024-01-16 14:07:36 UTC |
|summary| Sparse principal component analysis PCA aims at mapping large dimensionaldata to a linear subspace of lower dimension. By imposing loading vectors to besparse it performs the double duty of dimension reduction and variableselection. Sparse PCA algorithms are usually expressed as a trade-off betweenexplained variance and sparsity of the loading vectors i.e. number ofselected variables. As a high explained variance is not necessarily synonymouswith relevant information these methods are prone to select irrelevantvariables. To overcome this issue we propose an alternative formulation ofsparse PCA driven by the false discovery rate FDR. We then leverage theTerminating-Random Experiments T-Rex selector to automatically determine anFDR-controlled support of the loading vectors. A major advantage of theresulting T-Rex PCA is that no sparsity parameter tuning is required. Numericalexperiments and a stock market data example demonstrate a significantperformance improvement. |


| Item |Content|
| --- |---|
|idx| 3 |
|title| Weighted Spectral Filters for Kernel Interpolation on Spheres: Estimates of Prediction Accuracy for Noisy Data |
|authors| Xiaotong LiuJinxin WangDi WangShao-Bo Lin
|links| http://arxiv.org/abs/2401.08364v1 |
|updated| 2024-01-16 13:46:10 UTC |
|summary| Spherical radial-basis-based kernel interpolation abounds in image sciencesincluding geophysical image reconstruction climate trends description andimage rendering due to its excellent spatial localization property and perfectapproximation performance. However in dealing with noisy data kernelinterpolation frequently behaves not so well due to the large condition numberof the kernel matrix and instability of the interpolation process. In thispaper we introduce a weighted spectral filter approach to reduce the conditionnumber of the kernel matrix and then stabilize kernel interpolation. The mainbuilding blocks of the proposed method are the well developed sphericalpositive quadrature rules and high-pass spectral filters. Using a recentlydeveloped integral operator approach for spherical data analysis wetheoretically demonstrate that the proposed weighted spectral filter approachsucceeds in breaking through the bottleneck of kernel interpolation especiallyin fitting noisy data. We provide optimal approximation rates of the new methodto show that our approach does not compromise the predicting accuracy.Furthermore we conduct both toy simulations and two real-world dataexperiments with synthetically added noise in geophysical image reconstructionand climate image processing to verify our theoretical assertions and show thefeasibility of the weighted spectral filter approach. |


| Item |Content|
| --- |---|
|idx| 4 |
|title| Personalized Federated Learning of Probabilistic Models: A PAC-Bayesian Approach |
|authors| Mahrokh Ghoddousi BoroujeniAndreas KrauseGiancarlo Ferrari Trecate
|links| http://arxiv.org/abs/2401.08351v1 |
|updated| 2024-01-16 13:30:37 UTC |
|summary| Federated learning aims to infer a shared model from private anddecentralized data stored locally by multiple clients. Personalized federatedlearning PFL goes one step further by adapting the global model to eachclient enhancing the models fit for different clients. A significant level ofpersonalization is required for highly heterogeneous clients but can bechallenging to achieve especially when they have small datasets. To addressthis problem we propose a PFL algorithm named PAC-PFL for learningprobabilistic models within a PAC-Bayesian framework that utilizes differentialprivacy to handle data-dependent priors. Our algorithm collaboratively learns ashared hyper-posterior and regards each clients posterior inference as thepersonalization step. By establishing and minimizing a generalization bound onthe average true risk of clients PAC-PFL effectively combats over-fitting.PACPFL achieves accurate and well-calibrated predictions supported byexperiments on a dataset of photovoltaic panel power generation FEMNISTdataset Caldas et al. 2019 and Dirichlet-partitioned EMNIST dataset Cohenet al. 2017. |


| Item |Content|
| --- |---|
|idx| 5 |
|title| We don't need no labels: Estimating post-deployment model performance under covariate shift without ground truth |
|authors| Jakub BiałekWojtek KuberskiNikolaos Perrakis
|links| http://arxiv.org/abs/2401.08348v1 |
|updated| 2024-01-16 13:29:30 UTC |
|summary| The performance of machine learning models often degrades after deploymentdue to data distribution shifts. In many use cases it is impossible tocalculate the post-deployment performance because labels are unavailable orsignificantly delayed. Proxy methods for evaluating model performancestability like drift detection techniques do not properly quantify datadistribution shift impact. As a solution we propose a robust and accurateperformance estimation method for evaluating ML classification models onunlabeled data that accurately quantifies the impact of covariate shift onmodel performance. We call it multi-calibrated confidence-based performanceestimation M-CBPE. It is model and data-type agnostic and works for anyperformance metric. It does not require access to the monitored model - it usesthe model predictions and probability estimates. M-CBPE does not need userinput on the nature of the covariate shift as it fully learns from the data. Weevaluate it with over 600 dataset-model pairs from US census data and compareit with multiple benchmarks using several evaluation metrics. Results show thatM-CBPE is the best method to estimate the performance of classification modelsin any evaluation context. |


# cs.CV 

| Item |Content|
| --- |---|
|idx| 1 |
|title| SAMF: Small-Area-Aware Multi-focus Image Fusion for Object Detection |
|authors| Xilai LiXiaosong LiHaishu TanJinyang Li
|links| http://arxiv.org/abs/2401.08357v1 |
|updated| 2024-01-16 13:35:28 UTC |
|summary| Existing multi-focus image fusion MFIF methods often fail to preserve theuncertain transition region and detect small focus areas within large defocusedregions accurately. To address this issue this study proposes a newsmall-area-aware MFIF algorithm for enhancing object detection capability.First we enhance the pixel attributes within the small focus and boundaryregions which are subsequently combined with visual saliency detection toobtain the pre-fusion results used to discriminate the distribution of focusedpixels. To accurately ensure pixel focus we consider the source image as acombination of focused defocused and uncertain regions and propose athree-region segmentation strategy. Finally we design an effective pixelselection rule to generate segmentation decision maps and obtain the finalfusion results. Experiments demonstrated that the proposed method canaccurately detect small and smooth focus areas while improving object detectionperformance outperforming existing methods in both subjective and objectiveevaluations. The source code is available at https://github.com/ixilai/SAMF. |


| Item |Content|
| --- |---|
|idx| 2 |
|title| Multi-view Distillation based on Multi-modal Fusion for Few-shot Action Recognition(CLIP-$\mathrm{M^2}$DF) |
|authors| Fei GuoYiKang WangHan QiWenPing JinLi Zhu
|links| http://arxiv.org/abs/2401.08345v1 |
|updated| 2024-01-16 13:23:51 UTC |
|summary| In recent years few-shot action recognition has attracted increasingattention. It generally adopts the paradigm of meta-learning. In this fieldovercoming the overlapping distribution of classes and outliers is still achallenging problem based on limited samples. We believe the combination ofMulti-modal and Multi-view can improve this issue depending on informationcomplementarity. Therefore we propose a method of Multi-view Distillationbased on Multi-modal Fusion. Firstly a Probability Prompt Selector for thequery is constructed to generate probability prompt embedding based on thecomparison score between the prompt embeddings of the support and the visualembedding of the query. Secondly we establish a Multi-view. In each view wefuse the prompt embedding as consistent information with visual and the globalor local temporal context to overcome the overlapping distribution of classesand outliers. Thirdly we perform the distance fusion for the Multi-view andthe mutual distillation of matching ability from one to another enabling themodel to be more robust to the distribution bias. Our code is available at theURL: urlhttps://github.com/cofly2014/MDMF. |


| Item |Content|
| --- |---|
|idx| 3 |
|title| Generative Denoise Distillation: Simple Stochastic Noises Induce Efficient Knowledge Transfer for Dense Prediction |
|authors| Zhaoge LiuXiaohao XuYunkang CaoWeiming Shen
|links| http://arxiv.org/abs/2401.08332v2 |
|updated| 2024-01-17 07:18:11 UTC |
|summary| Knowledge distillation is the process of transferring knowledge from a morepowerful large model teacher to a simpler counterpart student. Numerouscurrent approaches involve the student imitating the knowledge of the teacherdirectly. However redundancy still exists in the learned representationsthrough these prevalent methods which tend to learn each spatial locationsfeatures indiscriminately. To derive a more compact representation conceptfeature from the teacher inspired by human cognition we suggest aninnovative method termed Generative Denoise Distillation GDD wherestochastic noises are added to the concept feature of the student to embed theminto the generated instance feature from a shallow network. Then the generatedinstance feature is aligned with the knowledge of the instance from theteacher. We extensively experiment with object detection instancesegmentation and semantic segmentation to demonstrate the versatility andeffectiveness of our method. Notably GDD achieves new state-of-the-artperformance in the tasks mentioned above. We have achieved substantialimprovements in semantic segmentation by enhancing PspNet and DeepLabV3 bothof which are based on ResNet-18 resulting in mIoU scores of 74.67 and 77.69respectively surpassing their previous scores of 69.85 and 73.20 on theCityscapes dataset of 20 categories. The source code is available athttps://github.com/ZhgLiu/GDD. |


| Item |Content|
| --- |---|
|idx| 4 |
|title| Un-Mixing Test-Time Normalization Statistics: Combatting Label Temporal Correlation |
|authors| Devavrat TomarGuillaume VrayJean-Philippe ThiranBehzad Bozorgtabar
|links| http://arxiv.org/abs/2401.08328v1 |
|updated| 2024-01-16 12:48:52 UTC |
|summary| In an era where test-time adaptation methods increasingly rely on the nuancedmanipulation of batch normalization BN parameters one critical assumptionoften goes overlooked: that of independently and identically distributedi.i.d. test batches with respect to unknown labels. This assumptionculminates in biased estimates of BN statistics and jeopardizes systemstability under non-i.i.d. conditions. This paper pioneers a departure from thei.i.d. paradigm by introducing a groundbreaking strategy termed Un-MixingTest-Time Normalization Statistics UnMix-TNS. UnMix-TNS re-calibrates theinstance-wise statistics used to normalize each instance in a batch by mixingit with multiple unmixed statistics components thus inherently simulating thei.i.d. environment. The key lies in our innovative online unmixing procedurewhich persistently refines these statistics components by drawing upon theclosest instances from an incoming test batch. Remarkably generic in itsdesign UnMix-TNS seamlessly integrates with an array of state-of-the-arttest-time adaptation methods and pre-trained architectures equipped with BNlayers. Empirical evaluations corroborate the robustness of UnMix-TNS undervaried scenarios ranging from single to continual and mixed domain shifts.UnMix-TNS stands out when handling test data streams with temporal correlationincluding those with corrupted real-world non-i.i.d. streams sustaining itsefficacy even with minimal batch sizes and individual samples. Our results seta new standard for test-time adaptation demonstrating significant improvementsin both stability and performance across multiple benchmarks. |


| Item |Content|
| --- |---|
|idx| 5 |
|title| The Faiss library |
|authors| Matthijs DouzeAlexandr GuzhvaChengqi DengJeff JohnsonGergely SzilvasyPierre-Emmanuel MazaréMaria LomeliLucas HosseiniHervé Jégou
|links| http://arxiv.org/abs/2401.08281v1 |
|updated| 2024-01-16 11:12:36 UTC |
|summary| Vector databases manage large collections of embedding vectors. As AIapplications are growing rapidly so are the number of embeddings that need tobe stored and indexed. The Faiss library is dedicated to vector similaritysearch a core functionality of vector databases. Faiss is a toolkit ofindexing methods and related primitives used to search cluster compress andtransform vectors. This paper first describes the tradeoff space of vectorsearch then the design principles of Faiss in terms of structure approach tooptimization and interfacing. We benchmark key features of the library anddiscuss a few selected applications to highlight its broad applicability. |


# stat.ML 

| Item |Content|
| --- |---|
|idx| 1 |
|title| Sparse PCA with False Discovery Rate Controlled Variable Selection |
|authors| Jasin MachkourArnaud BreloyMichael MumaDaniel P. PalomarFrédéric Pascal
|links| http://arxiv.org/abs/2401.08375v1 |
|updated| 2024-01-16 14:07:36 UTC |
|summary| Sparse principal component analysis PCA aims at mapping large dimensionaldata to a linear subspace of lower dimension. By imposing loading vectors to besparse it performs the double duty of dimension reduction and variableselection. Sparse PCA algorithms are usually expressed as a trade-off betweenexplained variance and sparsity of the loading vectors i.e. number ofselected variables. As a high explained variance is not necessarily synonymouswith relevant information these methods are prone to select irrelevantvariables. To overcome this issue we propose an alternative formulation ofsparse PCA driven by the false discovery rate FDR. We then leverage theTerminating-Random Experiments T-Rex selector to automatically determine anFDR-controlled support of the loading vectors. A major advantage of theresulting T-Rex PCA is that no sparsity parameter tuning is required. Numericalexperiments and a stock market data example demonstrate a significantperformance improvement. |


| Item |Content|
| --- |---|
|idx| 2 |
|title| Causal Machine Learning for Moderation Effects |
|authors| Nora BearthMichael Lechner
|links| http://arxiv.org/abs/2401.08290v1 |
|updated| 2024-01-16 11:34:59 UTC |
|summary| It is valuable for any decision maker to know the impact of decisionstreatments on average and for subgroups. The causal machine learningliterature has recently provided tools for estimating group average treatmenteffects GATE to understand treatment heterogeneity better. This paperaddresses the challenge of interpreting such differences in treatment effectsbetween groups while accounting for variations in other covariates. We proposea new parameter the balanced group average treatment effect BGATE whichmeasures a GATE with a specific distribution of a priori-determined covariates.By taking the difference of two BGATEs we can analyse heterogeneity moremeaningfully than by comparing two GATEs. The estimation strategy for thisparameter is based on double/debiased machine learning for discrete treatmentsin an unconfoundedness setting and the estimator is shown to besqrtN-consistent and asymptotically normal under standard conditions.Adding additional identifying assumptions allows specific balanced differencesin treatment effects between groups to be interpreted causally leading to thecausal balanced group average treatment effect. We explore the finite sampleproperties in a small-scale simulation study and demonstrate the usefulness ofthese parameters in an empirical example. |


| Item |Content|
| --- |---|
|idx| 3 |
|title| Statistical Test for Attention Map in Vision Transformer |
|authors| Tomohiro ShiraishiDaiki MiwaTeruyuki KatsuokaVo Nguyen Le DuyKoichi TajiIchiro Takeuchi
|links| http://arxiv.org/abs/2401.08169v1 |
|updated| 2024-01-16 07:18:47 UTC |
|summary| The Vision Transformer ViT demonstrates exceptional performance in variouscomputer vision tasks. Attention is crucial for ViT to capture complexwide-ranging relationships among image patches allowing the model to weigh theimportance of image patches and aiding our understanding of the decision-makingprocess. However when utilizing the attention of ViT as evidence inhigh-stakes decision-making tasks such as medical diagnostics a challengearises due to the potential of attention mechanisms erroneously focusing onirrelevant regions. In this study we propose a statistical test for ViTsattentions enabling us to use the attentions as reliable quantitative evidenceindicators for ViTs decision-making with a rigorously controlled error rate.Using the framework called selective inference we quantify the statisticalsignificance of attentions in the form of p-values which enables thetheoretically grounded quantification of the false positive detectionprobability of attentions. We demonstrate the validity and the effectiveness ofthe proposed method through numerical experiments and applications to brainimage diagnoses. |


| Item |Content|
| --- |---|
|idx| 4 |
|title| Fundamental limits of community detection from multi-view data: multi-layer, dynamic and partially labeled block models |
|authors| Xiaodong YangBuyu LinSubhabrata Sen
|links| http://arxiv.org/abs/2401.08167v1 |
|updated| 2024-01-16 07:13:32 UTC |
|summary| Multi-view data arises frequently in modern network analysis e.g. relationsof multiple types among individuals in social network analysis longitudinalmeasurements of interactions among observational units annotated networks withnoisy partial labeling of vertices etc. We study community detection in thesedisparate settings via a unified theoretical framework and investigate thefundamental thresholds for community recovery. We characterize the mutualinformation between the data and the latent parameters provided the degreesare sufficiently large. Based on this general result i we derive a sharpthreshold for community detection in an inhomogeneous multilayer block modelcitepchen2022global ii characterize a sharp threshold for weak recoveryin a dynamic stochastic block model citepmatias2017statistical and iiiidentify the limiting mutual information in an unbalanced partially labeledblock model. Our first two results are derived modulo coordinate-wise convexityassumptions on specific functions -- we provide extensive numerical evidencefor their correctness. Finally we introduce iterative algorithms based onApproximate Message Passing for community detection in these problems. |


| Item |Content|
| --- |---|
|idx| 5 |
|title| Differentially Private Sliced Inverse Regression: Minimax Optimality and Algorithm |
|authors| Xintao XiaLinjun ZhangZhanrui Cai
|links| http://arxiv.org/abs/2401.08150v1 |
|updated| 2024-01-16 06:47:43 UTC |
|summary| Privacy preservation has become a critical concern in high-dimensional dataanalysis due to the growing prevalence of data-driven applications. Proposed byLi 1991 sliced inverse regression has emerged as a widely utilizedstatistical technique for reducing covariate dimensionality while maintainingsufficient statistical information. In this paper we propose optimallydifferentially private algorithms specifically designed to address privacyconcerns in the context of sufficient dimension reduction. We proceed toestablish lower bounds for differentially private sliced inverse regression inboth the low and high-dimensional settings. Moreover we develop differentiallyprivate algorithms that achieve the minimax lower bounds up to logarithmicfactors. Through a combination of simulations and real data analysis weillustrate the efficacy of these differentially private algorithms insafeguarding privacy while preserving vital information within the reduceddimension space. As a natural extension we can readily offer analogous lowerand upper bounds for differentially private sparse principal componentanalysis a topic that may also be of potential interest to the statistical andmachine learning community. |


# cs.HC 

| Item |Content|
| --- |---|
|idx| 1 |
|title| Understanding User Experience in Large Language Model Interactions |
|authors| Jiayin WangWeizhi MaPeijie SunMin ZhangJian-Yun Nie
|links| http://arxiv.org/abs/2401.08329v1 |
|updated| 2024-01-16 12:49:00 UTC |
|summary| In the rapidly evolving landscape of large language models LLMs mostresearch has primarily viewed them as independent individuals focusing onassessing their capabilities through standardized benchmarks and enhancingtheir general intelligence. This perspective however tends to overlook thevital role of LLMs as user-centric services in human-AI collaboration. This gapin research becomes increasingly critical as LLMs become more integrated intopeoples everyday and professional interactions. This study addresses theimportant need to understand user satisfaction with LLMs by exploring four keyaspects: comprehending user intents scrutinizing user experiences addressingmajor user concerns about current LLM services and charting future researchpaths to bolster human-AI collaborations. Our study develops a taxonomy of 7user intents in LLM interactions grounded in analysis of real-world userinteraction logs and human verification. Subsequently we conduct a user surveyto gauge their satisfaction with LLM services encompassing usage frequencyexperiences across intents and predominant concerns. This survey compiling411 anonymous responses uncovers 11 first-hand insights into the current stateof user engagement with LLMs. Based on this empirical analysis we pinpoint 6future research directions prioritizing the user perspective in LLMdevelopments. This user-centered approach is essential for crafting LLMs thatare not just technologically advanced but also resonate with the intricaterealities of human interactions and real-world applications. |


| Item |Content|
| --- |---|
|idx| 2 |
|title| Adapt/Exchange decisions or generic choices: Does framing influence how people integrate qualitatively different risks? |
|authors| Romy MüllerAlexander Blunk
|links| http://arxiv.org/abs/2401.08241v1 |
|updated| 2024-01-16 09:53:39 UTC |
|summary| In complex systems decision makers often have to consider qualitativelydifferent risks when choosing between options. Do their strategies ofintegrating these risks depend on the framing of problem contents In thepresent study participants were either instructed that they were choosingbetween two ways of solving a complex problem or between two generic options.The former was framed as a modular plant scenario that required choices betweenmodifying parameter settings in a current module Adapt and replacing themodule by another one Exchange. The risk was higher for Adapt to harm theproduct and for Exchange to harm the plant. These risks were presented asprobabilities and participants were either told that the consequences of bothrisks were equally severe content-same group or that harming the plant wasmuch worse content-different group. A third group made decisions based on thesame probabilities but received a generic task framing no-content group. Weexpected framing to affect risk integration leading the content-same group tomake different choices than the no-content group. Contrary to this hypothesisthese two groups were strikingly similar in their decision outcomes andstrategies but clearly differed from the content-different group. Thesefindings question whether ecological validity can be enhanced merely by framinga task in terms of real-world problem contents. |


| Item |Content|
| --- |---|
|idx| 3 |
|title| EEG-based Cognitive Load Estimation of Acoustic Parameters for Data Sonification |
|authors| Gulshan SharmaSurbhi MadanManeesh BilalpurAbhinav DhallRamanathan Subramanian
|links| http://arxiv.org/abs/2401.08164v1 |
|updated| 2024-01-16 07:11:14 UTC |
|summary| Sonification is a data visualization technique which expresses dataattributes via psychoacoustic parameters which are non-speech audio signalsused to convey information. This paper investigates the binary estimation ofcognitive load induced by psychoacoustic parameters conveying the focus levelof an astronomical image via Electroencephalogram EEG embeddings. Employingmachine learning and deep learning methodologies we demonstrate that EEGsignals are reliable for a binary estimation of cognitive load b isolatingeasy vs difficult visual-to-auditory perceptual mappings and c capturingperceptual similarities among psychoacoustic parameters. Our key findingsreveal that 1 EEG embeddings can reliably measure cognitive load achieving apeak F1-score of 0.98 2 Extreme focus levels are easier to detect viaauditory mappings than intermediate ones and 3 psychoacoustic parametersinducing comparable cognitive load levels tend to generate similar EEGencodings. |


| Item |Content|
| --- |---|
|idx| 4 |
|title| 'One Style Does Not Regulate All': Moderation Practices in Public and Private WhatsApp Groups |
|authors| Farhana ShahidDhruv AgarwalAditya Vashistha
|links| http://arxiv.org/abs/2401.08091v1 |
|updated| 2024-01-16 03:32:15 UTC |
|summary| WhatsApp is the largest social media platform in the Global South and is avirulent force in global misinformation and political propaganda. Due toend-to-end encryption WhatsApp can barely review any content and this oftenpushes the responsibility of moderation towards group admins. Yet little isknown about how WhatsApp group admins manage their groups what factors andvalues influence moderation decisions and what challenges they face inmoderating their groups. To fill this gap we interviewed admins of 32 diversegroups and reviewed content from 30 public groups in India and Bangladesh. Weobserved notable differences in the formation members behavior andmoderation of public versus private groups as well as in how WhatsApp adminsoperate compared to those on other platforms. We used Baumrinds typology ofparenting styles as a lens to explore moderation practices in WhatsApp groupsand identified four moderation styles based on how responsive and controllingthe admins were and discuss design recommendations to help them better manageproblematic content in WhatsApp groups. |


| Item |Content|
| --- |---|
|idx| 5 |
|title| TrajVis: a visual clinical decision support system to translate artificial intelligence trajectory models in the precision management of chronic kidney disease |
|authors| Zuotian LiXiang LiuZiyang TangPengyue ZhangNanxin JinMichael EadonQianqian SongYingjie ChenJing Su
|links| http://arxiv.org/abs/2401.08067v1 |
|updated| 2024-01-16 02:51:42 UTC |
|summary| Objective: Our objective is to develop and validate TrajVis an interactivetool that assists clinicians in using artificial intelligence AI models toleverage patients longitudinal electronic medical records EMR forpersonalized precision management of chronic disease progression. Methods: Wefirst perform requirement analysis with clinicians and data scientists todetermine the visual analytics tasks of the TrajVis system as well as itsdesign and functionalities. A graph AI model for chronic kidney disease CKDtrajectory inference named DEPOT is used for system development anddemonstration. TrajVis is implemented as a full-stack web application withsynthetic EMR data derived from the Atrium Health Wake Forest BaptistTranslational Data Warehouse and the Indiana Network for Patient Care researchdatabase. A case study with a nephrologist and a user experience survey ofclinicians and data scientists are conducted to evaluate the TrajVis system.Results: The TrajVis clinical information system is composed of four panels:the Patient View for demographic and clinical information the Trajectory Viewto visualize the DEPOT-derived CKD trajectories in latent space the ClinicalIndicator View to elucidate longitudinal patterns of clinical features andinterpret DEPOT predictions and the Analysis View to demonstrate personal CKDprogression trajectories. System evaluations suggest that TrajVis supportsclinicians in summarizing clinical data identifying individualized riskpredictors and visualizing patient disease progression trajectoriesovercoming the barriers of AI implementation in healthcare. Conclusion: TrajVisbridges the gap between the fast-growing AI/ML modeling and the clinical use ofsuch models for personalized and precision management of chronic diseases. |


# cs.MA 

| Item |Content|
| --- |---|
|idx| 1 |
|title| A Day-to-Day Dynamical Approach to the Most Likely User Equilibrium Problem |
|authors| Jiayang LiQianni WangLiyang FengJun XieYu Marco Nie
|links| http://arxiv.org/abs/2401.08013v1 |
|updated| 2024-01-15 23:43:41 UTC |
|summary| The lack of a unique user equilibrium UE route flow in traffic assignmenthas posed a significant challenge to many transportation applications. Themaximum-entropy principle which advocates for the consistent selection of themost likely solution as a representative is often used to address thechallenge. Built on a recently proposed day-to-day DTD discrete-timedynamical model called cumulative logit CULO this study provides a newbehavioral underpinning for the maximum-entropy UE MEUE route flow. It hasbeen proven that CULO can reach a UE state without presuming travelers areperfectly rational. Here we further establish that CULO always converges tothe MEUE route flow if i travelers have zero prior information about routesand thus are forced to give all routes an equal choice probability or ii alltravelers gather information from the same source such that the so-calledgeneral proportionality condition is satisfied. Thus CULO may be used as apractical solution algorithm for the MEUE problem. To put this idea intopractice we propose to eliminate the route enumeration requirement of theoriginal CULO model through an iterative route discovery scheme. We alsoexamine the discrete-time versions of four popular continuous-time dynamicalmodels and compare them to CULO. The analysis shows that the replicator dynamicis the only one that has the potential to reach the MEUE solution with someregularity. The analytical results are confirmed through numerical experiments. |


| Item |Content|
| --- |---|
|idx| 2 |
|title| Emergency Localization for Mobile Ground Users: An Adaptive UAV Trajectory Planning Method |
|authors| Zhihao ZhuJiafan HeLuyang HouLianming XuWendi ZhuLi Wang
|links| http://arxiv.org/abs/2401.07256v1 |
|updated| 2024-01-14 11:20:20 UTC |
|summary| In emergency search and rescue scenarios the quick location of trappedpeople is essential. However disasters can render the Global PositioningSystem GPS unusable. Unmanned aerial vehicles UAVs with localizationdevices can serve as mobile anchors due to their agility and high line-of-sightLoS probability. Nonetheless the number of available UAVs during the initialstages of disaster relief is limited and innovative methods are needed toquickly plan UAV trajectories to locate non-uniformly distributed dynamictargets while ensuring localization accuracy. To address this challenge wedesign a single UAV localization method without hovering use the maximumlikelihood estimation MLE method to estimate the location of mobile users anddefine the upper bound of the localization error by considering usersmovement.Combining this localization method and localization error-index weutilize the enhanced particle swarm optimization EPSO algorithm and edgeaccess strategy to develop a low complexity localization-oriented adaptivetrajectory planning algorithm. Simulation results demonstrate that our methodoutperforms other baseline algorithms enabling faster localization withoutcompromising localization accuracy. |


| Item |Content|
| --- |---|
|idx| 3 |
|title| Trust from Ethical Point of View: Exploring Dynamics Through Multiagent-Driven Cognitive Modeling |
|authors| Abbas Tariverdi
|links| http://arxiv.org/abs/2401.07255v1 |
|updated| 2024-01-14 11:19:18 UTC |
|summary| The paper begins by exploring the rationality of ethical trust as afoundational concept. This involves distinguishing between trust andtrustworthiness and delving into scenarios where trust is both rational andmoral. It lays the groundwork for understanding the complexities of trustdynamics in decision-making scenarios. Following this theoretical groundworkwe introduce an agent-based simulation framework that investigates thesedynamics of ethical trust specifically in the context of a disaster responsescenario. These agents utilizing emotional models like Plutchiks Wheel ofEmotions and memory learning mechanisms are tasked with allocating limitedresources in disaster-affected areas. The model which embodies the principlesdiscussed in the first section integrates cognitive load management Big Fivepersonality traits and structured interactions within networked orhierarchical settings. It also includes feedback loops and simulates externalevents to evaluate their impact on the formation and evolution of trust amongagents. Through our simulations we demonstrate the intricate interplay ofcognitive emotional and social factors in ethical decision-making. Theseinsights shed light on the behaviors and resilience of trust networks in crisissituations emphasizing the role of rational and moral considerations in thedevelopment of trust among autonomous agents. This study contributes to thefield by offering an understanding of trust dynamics in socio-technical systemsand by providing a robust adaptable framework capable of addressing ethicaldilemmas in disaster response and beyond. The implementation of the algorithmspresented in this paper is available at this GitHub repository:urlhttps://github.com/abbas-tari/ethical-trust-cognitive-modeling. |


| Item |Content|
| --- |---|
|idx| 4 |
|title| A Dynamic Agent Based Model of the Real Economy with Monopolistic Competition, Perfect Product Differentiation, Heterogeneous Agents, Increasing Returns to Scale and Trade in Disequilibrium |
|authors| Subhamon SupanthaNaresh Kumar Sharma
|links| http://arxiv.org/abs/2401.07070v1 |
|updated| 2024-01-13 13:10:20 UTC |
|summary| We have used agent-based modeling as our numerical method to artificiallysimulate a dynamic real economy where agents are rational maximizers of anobjective function of Cobb-Douglas type. The economy is characterised byheterogeneous agents acting out of local or imperfect informationmonopolistic competition perfect product differentiation allowance forincreasing returns to scale technology and trade in disequilibrium. Analgorithm for economic activity in each period is devised and a general purposeopen source agent-based model is developed which allows for counterfactualinquiries testing out treatments analysing causality of various economicprocesses outcomes and studying emergent properties. 10000 simulations with10 firms and 80 consumers are run with varying parameters and the results showthat from only a few initial conditions the economy reaches equilibrium whilein most of the other cases it remains in perpetual disequilibrium. It alsoshows that from a few initial conditions the economy reaches a disaster whereall the consumer wealth falls to zero or only a single producer remains.Furthermore from some initial conditions an ideal economy with high wagerate high consumer utility and no unemployment is also reached. It was alsoobserved that starting from an equal endowment of wealth in consumers and inproducers inequality emerged in the economy. In majority of the cases most ofthe firms6-7 shut down because they were not profitable enough and only a fewfirms remained. Our results highlight that all these varying outcomes arepossible for a decentralized market economy with rational optimizing agents. |


| Item |Content|
| --- |---|
|idx| 5 |
|title| Aquarium: A Comprehensive Framework for Exploring Predator-Prey Dynamics through Multi-Agent Reinforcement Learning Algorithms |
|authors| Michael KölleYannick ErpeldingFabian RitzThomy PhanSteffen IlliumClaudia Linnhoff-Popien
|links| http://arxiv.org/abs/2401.07056v1 |
|updated| 2024-01-13 12:09:49 UTC |
|summary| Recent advances in Multi-Agent Reinforcement Learning have prompted themodeling of intricate interactions between agents in simulated environments. Inparticular the predator-prey dynamics have captured substantial interest andvarious simulations been tailored to unique requirements. To prevent furthertime-intensive developments we introduce Aquarium a comprehensive Multi-AgentReinforcement Learning environment for predator-prey interaction enabling thestudy of emergent behavior. Aquarium is open source and offers a seamlessintegration of the PettingZoo framework allowing a quick start with provenalgorithm implementations. It features physics-based agent movement on atwo-dimensional edge-wrapping plane. The agent-environment interactionobservations actions rewards and the environment settings agent speedprey reproduction predator starvation and others are fully customizable.Besides a resource-efficient visualization Aquarium supports to record videofiles providing a visual comprehension of agent behavior. To demonstrate theenvironments capabilities we conduct preliminary studies which use PPO totrain multiple prey agents to evade a predator. In accordance to theliterature we find Individual Learning to result in worse performance thanParameter Sharing which significantly improves coordination andsample-efficiency. |

