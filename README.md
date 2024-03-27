| Year | Model                                                 | Title                                                        | Paper Link                                                   | Code                                                         | BLEU 1 | BLEU 2 | BLEU 3 | BLEU 4 | ROUGE | METEOR | CIDEr | LLM   | with impression | Comment                                 |
| ---- | ----------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------ | ------ | ------ | ------ | ----- | ------ | ----- | ----- | --------------- | --------------------------------------- |
| 2020 | R2Gen                                                 | Generating Radiology Reports via Memory-driven Transformer   | [https://arxiv.org/abs/2010.16056](https://arxiv.org/abs/2010.16056) | [https://github.com/zhjohnchan/R2Gen](https://github.com/zhjohnchan/R2Gen) | 0.353  | 0.218  | 0.145  | 0.103  | 0.277 | 0.142  |       | FALSE | FALSE           |                                         |
| 2020 | ASKG                                                  | Auxiliary Signal-Guided Knowledge Encoder-Decoder for Medical Report Generation | [https://arxiv.org/abs/2006.03744](https://arxiv.org/abs/2006.03744) | [https://github.com/mlii0117/COV-CTR](https://github.com/mlii0117/COV-CTR) | \-     |        |        |        |       |        |       | FALSE | FALSE           | different dataset                       |
| 2021 | R2GenCMN                                              | Cross-modal Memory Networks for Radiology Report Generation  | [https://aclanthology.org/2021.acl-long.459.pdf](https://aclanthology.org/2021.acl-long.459.pdf) | [https://github.com/zhjohnchan/R2GenCMN](https://github.com/zhjohnchan/R2GenCMN) | 0.353  | 0.218  | 0.148  | 0.106  | 0.278 | 0.142  |       | FALSE | FALSE           |                                         |
| 2021 | PPKED                                                 | Exploring and Distilling Posterior and Prior Knowledge for Radiology Report Generation | [https://arxiv.org/abs/2106.06963](https://arxiv.org/abs/2106.06963) |                                                              | 0.36   | 0.224  | 0.149  | 0.106  | 0.284 | 0.149  |       | FALSE | FALSE           | no mimic                                |
| 2021 | AlignTransformer                                      | AlignTransformer: Hierarchical Alignment of Visual Regions and Disease Tags for Medical Report Generation | [https://link.springer.com/chapter/10.1007/978-3-030-87199-4_7](https://link.springer.com/chapter/10.1007/978-3-030-87199-4_7) |                                                              | 0.378  | 0.235  | 0.156  | 0.112  | 0.283 | 0.158  |       | FALSE | FALSE           | no mimic                                |
| 2021 | Self-boosting                                         | A Self-boosting Framework for Automated Radiographic Report Generation | [https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_A_Self-Boosting_Framework_for_Automated_Radiographic_Report_Generation_CVPR_2021_paper.pdf](https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_A_Self-Boosting_Framework_for_Automated_Radiographic_Report_Generation_CVPR_2021_paper.pdf) |                                                              | \-     |        |        |        |       |        |       | FALSE | FALSE           | no mimic                                |
| 2021 | Knowledge Matters                                     | Knowledge Matters: Radiology Report Generation with General and Specific Knowledge | [https://arxiv.org/abs/2112.15009](https://arxiv.org/abs/2112.15009) | [https://github.com/LX-doctorAI1/GSKET](https://github.com/LX-doctorAI1/GSKET) | 0.363  | 0.228  | 0.156  | 0.115  | 0.284 |        | 0.203 | FALSE | FALSE           |                                         |
| 2021 | CA                                                    | Contrastive Attention for Automatic Chest X-ray Report Generation | [https://arxiv.org/pdf/2106.06965.pdf](https://arxiv.org/pdf/2106.06965.pdf) |                                                              | 0.35   | 0.219  | 0.152  | 0.109  | 0.283 | 0.151  |       | FALSE | FALSE           |                                         |
| 2021 | WCL                                                   | Weakly Supervised Contrastive Learning for Chest X-Ray Report Generation | [https://arxiv.org/abs/2109.12242](https://arxiv.org/abs/2109.12242) | [https://github.com/zzxslp/WCL](https://github.com/zzxslp/WCL) | 0.373  |        |        | 0.107  | 0.274 | 0.144  |       | FALSE | FALSE           |                                         |
| 2021 | CMCL                                                  | Competence-based Multimodal Curriculum Learning for Medical Report Generation | [https://arxiv.org/abs/2206.14579](https://arxiv.org/abs/2206.14579) |                                                              | 0.344  | 0.217  | 0.14   | 0.097  | 0.281 | 0.133  |       | FALSE | FALSE           |                                         |
| 2021 | RATCHET                                               | RATCHET: Medical Transformer for Chest X-ray Diagnosis and Reporting | [https://arxiv.org/abs/2107.02104](https://arxiv.org/abs/2107.02104) | [https://github.com/farrell236/RATCHET](https://github.com/farrell236/RATCHET) | 0.232  |        |        |        | 0.24  |        | 0.493 | FALSE | FALSE           |                                         |
| 2021 | -                                                     | Variational Topic Inference for Chest X-Ray Report Generation | [https://arxiv.org/pdf/2107.07314.pdf](https://arxiv.org/pdf/2107.07314.pdf) | [https://github.com/ivonajdenkoska/variational-xray-report-gen](https://github.com/ivonajdenkoska/variational-xray-report-gen) | 0.418  | 0.293  | 0.152  | 0.109  | 0.302 | 0.177  |       | FALSE | FALSE           |                                         |
| 2021 | -                                                     | Improving Factual Completeness and Consistency of Image-to-Text Radiology Report Generation | [https://arxiv.org/pdf/2010.10042.pdf](https://arxiv.org/pdf/2010.10042.pdf) |                                                              | \-     |        |        |        |       |        |       | FALSE | FALSE           | with new optimisation method            |
| 2022 | MSAT                                                  | A Medical Semantic-Assisted Transformer for Radiographic Report Generation | [https://arxiv.org/abs/2208.10358](https://arxiv.org/abs/2208.10358) | [https://github.com/wang-zhanyu/MSAT](https://github.com/wang-zhanyu/MSAT) | 0.373  | 0.235  | 0.162  | 0.12   | 0.282 | 0.143  | 0.299 | FALSE | FALSE           |                                         |
| 2022 | XProNet                                               | Cross-modal Prototype Driven Network for Radiology Report Generation | [https://arxiv.org/abs/2207.04818](https://arxiv.org/abs/2207.04818) | [https://github.com/markin-wang/xpronet?tab=readme-ov-file](https://github.com/markin-wang/xpronet?tab=readme-ov-file) | 0.344  | 0.215  | 0.146  | 0.105  | 0.279 | 0.238  |       | FALSE | FALSE           | Very high IU-xray score, prototype      |
| 2022 | CAMANet                                               | CAMANet: Class Activation Map Guided Attention Network for Radiology Report Generation | [https://arxiv.org/pdf/2211.01412.pdf](https://arxiv.org/pdf/2211.01412.pdf) | [https://github.com/Markin-Wang/CAMANet](https://github.com/Markin-Wang/CAMANet) | 0.374  | 0.23   | 0.155  | 0.112  | 0.279 | 0.145  | 0.161 | FALSE | FALSE           | Very high IU-xray score                 |
| 2022 | Purely on Transformer                                 | Automated Radiographic Report Generation Purely on Transformer: A Multicriteria Supervised Approach | [https://ieeexplore.ieee.org/document/9768661?denied=](https://ieeexplore.ieee.org/document/9768661?denied=) |                                                              | 0.351  | 0.223  | 0.157  | 0.118  | 0.287 |        | 0.281 | FALSE | FALSE           |                                         |
| 2022 | Reinforced Cross-modal Alignment                      | Reinforced Cross-modal Alignment for Radiology Report Generation | [https://aclanthology.org/2022.findings-acl.38.pdf](https://aclanthology.org/2022.findings-acl.38.pdf) |                                                              | 0.381  | 0.232  | 0.155  | 0.109  | 0.287 | 0.151  |       | FALSE | FALSE           |                                         |
| 2022 | M2KT                                                  | Radiology Report Generation with a Learned Knowledge Base and Multi-modal Alignment | [https://arxiv.org/abs/2112.15011](https://arxiv.org/abs/2112.15011) | [https://github.com/LX-doctorAI1/M2KT](https://github.com/LX-doctorAI1/M2KT) | 0.386  | 0.237  | 0.157  | 0.111  | 0.274 |        | 0.111 | FALSE | FALSE           |                                         |
| 2022 | TranSQ                                                | TranSQ: Transformer-Based Semantic Query for Medical Report Generation | [https://link.springer.com/chapter/10.1007/978-3-031-16452-1_58](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_58) | [https://github.com/zjukongming/TranSQ](https://github.com/zjukongming/TranSQ) | 0.423  | 0.261  | 0.171  | 0.116  | 0.286 | 0.168  |       | FALSE | FALSE           | image size 384                          |
| 2022 | self-guided                                           | A Self-guided Framework for Radiology Report Generation      | [https://link.springer.com/chapter/10.1007/978-3-031-16452-1_56](https://link.springer.com/chapter/10.1007/978-3-031-16452-1_56) | [https://github.com/LijunRio/A-Self-Guided-Framework](https://github.com/LijunRio/A-Self-Guided-Framework) | \-     |        |        |        |       |        |       | FALSE | FALSE           | just iu xray                            |
| 2022 | RepsNet                                               | RepsNet: Combining Vision with Language for Automated Medical Reports | [https://link.springer.com/chapter/10.1007/978-3-031-16443-9_68](https://link.springer.com/chapter/10.1007/978-3-031-16443-9_68) |                                                              | \-     |        |        |        |       |        |       | FALSE | FALSE           | with vqa and just iu xray               |
| 2022 | -                                                     | Improving the Factual Correctness of Radiology Report Generation with Semantic Rewards | [https://aclanthology.org/2022.findings-emnlp.319.pdf](https://aclanthology.org/2022.findings-emnlp.319.pdf) | [https://github.com/jbdel/vilmedic?tab=readme-ov-file](https://github.com/jbdel/vilmedic?tab=readme-ov-file) | \-     |        |        | 0.116  | 0.259 |        |       | FALSE | FALSE           | RadGraph reward                         |
| 2022 | Factual Accuracy is not Enough                        | Factual Accuracy is not Enough: Planning Consistent Description Order for Radiology Report Generation | [https://aclanthology.org/2022.emnlp-main.480.pdf](https://aclanthology.org/2022.emnlp-main.480.pdf) |                                                              | \-     |        |        | 0.168  | 0.122 |        |       | FALSE | FALSE           | one diff dataset                        |
| 2022 | -                                                     | Cross-Modal Causal Intervention for Medical Report Generation | [https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9879084](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9879084) |                                                              | \-     |        |        |        |       |        |       | FALSE | FALSE           | eye dataset                             |
| 2022 | HReMRG                                                | Hybrid Reinforced Medical Report Generation with M-Linear Attention and Repetition Penalty | [https://arxiv.org/pdf/2210.13729.pdf](https://arxiv.org/pdf/2210.13729.pdf) |                                                              | 0.481  | 0.343  | 0.256  | 0.192  | 0.38  | 0.207  | 0.372 | FALSE | FALSE           |                                         |
| 2022 | -                                                     | Multimodal Generation of Radiology Reports using Knowledge-Grounded Extraction of Entities and Relations | [https://aclanthology.org/2022.aacl-main.47.pdf](https://aclanthology.org/2022.aacl-main.47.pdf) |                                                              | 0.363  | 0.245  | 0.178  | 0.136  | 0.313 | 0.161  |       | FALSE | FALSE           |                                         |
| 2023 | -                                                     | A Systematic Review of Deep Learning-based Research on Radiology Report Generation | [https://arxiv.org/pdf/2311.14199.pdf](https://arxiv.org/pdf/2311.14199.pdf) |                                                              | \-     |        |        |        |       |        |       | FALSE | FALSE           | Survey                                  |
| 2023 | ORGAN                                                 | ORGAN: Observation-Guided Radiology Report Generation via Tree Reasoning | [https://arxiv.org/abs/2306.06466](https://arxiv.org/abs/2306.06466) | [https://github.com/wjhou/ORGan](https://github.com/wjhou/ORGan) | 0.407  | 0.256  | 0.172  | 0.123  | 0.293 | 0.162  |       | FALSE | FALSE           |                                         |
| 2023 | METransformer                                         | METransformer: Radiology Report Generation by Transformer with Multiple Learnable Expert Tokens | [https://arxiv.org/abs/2304.02211](https://arxiv.org/abs/2304.02211) |                                                              | 0.386  | 0.25   | 0.169  | 0.124  | 0.291 | 0.152  | 0.362 | FALSE | TRUE            |                                         |
| 2023 | KiUT                                                  | KiUT: Knowledge-injected U-Transformer for Radiology Report Generation | [https://arxiv.org/abs/2306.11345](https://arxiv.org/abs/2306.11345) |                                                              | 0.393  | 0.243  | 0.159  | 0.113  | 0.285 | 0.152  |       | FALSE | FALSE           |                                         |
| 2023 | R2GenGPT                                              | R2GenGPT: Radiology Report Generation with Frozen LLMs       | [https://arxiv.org/abs/2309.09812](https://arxiv.org/abs/2309.09812) | [https://github.com/wang-zhanyu/R2GenGPT](https://github.com/wang-zhanyu/R2GenGPT) | 0.411  | 0.267  | 0.186  | 0.134  | 0.297 | 0.16   | 0.269 | TRUE  | TRUE            |                                         |
| 2023 | RECAP                                                 | RECAP: Towards Precise Radiology Report Generation via Dynamic Disease Progression Reasoning | [https://arxiv.org/abs/2310.13864](https://arxiv.org/abs/2310.13864) | [https://github.com/wjhou/Recap](https://github.com/wjhou/Recap) | 0.429  | 0.267  | 0.177  | 0.125  | 0.288 | 0.168  |       | FALSE | FALSE           |                                         |
| 2023 | DCL                                                   | Dynamic Graph Enhanced Contrastive Learning for Chest X-ray Report Generation | [https://arxiv.org/pdf/2303.10323.pdf](https://arxiv.org/pdf/2303.10323.pdf) | [https://github.com/mlii0117/DCL](https://github.com/mlii0117/DCL) | \-     |        |        | 0.109  | 0.284 | 0.15   | 0.281 | FALSE | FALSE           |                                         |
| 2023 | PhenotypeCLIP                                         | PhenotypeCLIP: Phenotype-based Contrastive Learning for Medical Imaging Report Generation | [https://aclanthology.org/2023.emnlp-main.989.pdf](https://aclanthology.org/2023.emnlp-main.989.pdf) |                                                              | \-     |        |        | 0.119  | 0.286 | 0.158  | 0.259 | FALSE | FALSE           |                                         |
| 2023 | LLM-CXR                                               | LLM-CXR: Instruction-Finetuned LLM for CXR Image Understanding and Generation | [https://arxiv.org/abs/2305.11490](https://arxiv.org/abs/2305.11490) | [https://github.com/hyn2028/llm-cxr](https://github.com/hyn2028/llm-cxr) | \-     |        |        |        |       |        |       | TRUE  | FALSE           |                                         |
| 2023 | MAIRA-1                                               | MAIRA-1: A specialised large multimodal model for radiology report generation | [https://arxiv.org/abs/2311.13668](https://arxiv.org/abs/2311.13668) |                                                              |        |        |        |        |       |        |       | TRUE  | FALSE           |                                         |
| 2023 | MedXChat                                              | MedXChat: Bridging CXR Modalities with a Unified Multimodal Large Model | [https://arxiv.org/abs/2312.02233](https://arxiv.org/abs/2312.02233) |                                                              |        |        |        |        |       |        |       | FALSE | FALSE           |                                         |
| 2023 | Pragmatic Radiology Report Generation                 | Pragmatic Radiology Report Generation                        | [https://arxiv.org/pdf/2311.17154.pdf](https://arxiv.org/pdf/2311.17154.pdf) |                                                              | \-     |        |        |        |       |        |       | TRUE  | FALSE           | differnet eval way                      |
| 2023 | RadLLM                                                | RadLLM: A Comprehensive Healthcare Benchmark of Large Language Models for Radiology | [https://arxiv.org/pdf/2307.13693.pdf](https://arxiv.org/pdf/2307.13693.pdf) |                                                              | \-     |        |        |        |       |        |       | TRUE  | FALSE           | A benchmark                             |
| 2023 | RaDialog                                              | RaDialog: A Large Vision-Language Model for Radiology Report Generation and Conversational Assistance | [https://arxiv.org/pdf/2311.18681.pdf](https://arxiv.org/pdf/2311.18681.pdf) | [https://github.com/ChantalMP/RaDialog](https://github.com/ChantalMP/RaDialog) | 0.346  |        |        | 0.095  | 0.271 | 0.14   |       | TRUE  | FALSE           | with chat                               |
| 2023 | Towards Generalist Biomedical AI                      | Towards Generalist Biomedical AI                             | [https://arxiv.org/pdf/2307.14334.pdf](https://arxiv.org/pdf/2307.14334.pdf) | [https://github.com/kyegomez/Med-PaLM](https://github.com/kyegomez/Med-PaLM) | 0.323  |        |        | 0.115  | 0.275 |        | 0.262 | TRUE  | FALSE           |                                         |
| 2023 | RadFM                                                 | Towards Generalist Foundation Model for Radiology by Leveraging Web-scale 2D&3D Medical Data | [https://arxiv.org/pdf/2308.02463.pdf](https://arxiv.org/pdf/2308.02463.pdf) | [https://github.com/chaoyi-wu/RadFM?tab=readme-ov-file](https://github.com/chaoyi-wu/RadFM?tab=readme-ov-file) | \-     |        |        |        |       |        |       | TRUE  | FALSE           |                                         |
| 2023 | VLCI                                                  | Cross-Modal Causal Intervention for Medical Report Generation | [https://arxiv.org/pdf/2303.09117.pdf](https://arxiv.org/pdf/2303.09117.pdf) | [https://github.com/WissingChen/VLCI](https://github.com/WissingChen/VLCI) | 0.4    | 0.245  | 0.165  | 0.119  | 0.28  | 0.15   | 0.19  | FALSE | FALSE           |                                         |
| 2023 | -                                                     | Medical Report Generation based on Segment-Enhanced Contrastive Representation Learning | [https://arxiv.org/pdf/2312.15869.pdf](https://arxiv.org/pdf/2312.15869.pdf) |                                                              |        |        |        |        |       |        |       | FALSE | FALSE           | segment-enhanced                        |
| 2023 | -                                                     | Radiology Report Generation Using Transformers Conditioned with Non-imaging Data | [https://arxiv.org/pdf/2311.11097.pdf](https://arxiv.org/pdf/2311.11097.pdf) |                                                              | 0.333  | 0.21   | 0.142  | 0.088  |       |        |       | FALSE | FALSE           | Non-imaging data                        |
| 2023 | Replace and Report                                    | Replace and Report: NLP Assisted Radiology Report Generation | [https://aclanthology.org/2023.findings-acl.683.pdf](https://aclanthology.org/2023.findings-acl.683.pdf) |                                                              | 0.833  | 0.807  | 0.794  | 0.785  | 0.833 | 0.861  | 0.861 | FALSE | FALSE           | structured report                       |
| 2023 | CvT2DistilGPT2                                        | Improving Chest X-Ray Report Generation by Leveraging Warm Starting | [https://arxiv.org/pdf/2201.09405.pdf](https://arxiv.org/pdf/2201.09405.pdf) | [https://github.com/aehrc/cvt2distilgpt2](https://github.com/aehrc/cvt2distilgpt2) | 0.393  | 0.248  | 0.171  | 0.127  | 0.286 | 0.155  | 0.389 | FALSE | FALSE           | different image size                    |
| 2023 | RGRG                                                  | Interactive and Explainable Region-guided Radiology Report Generation | [https://openaccess.thecvf.com/content/CVPR2023/papers/Tanida_Interactive_and_Explainable_Region-Guided_Radiology_Report_Generation_CVPR_2023_paper.pdf](https://openaccess.thecvf.com/content/CVPR2023/papers/Tanida_Interactive_and_Explainable_Region-Guided_Radiology_Report_Generation_CVPR_2023_paper.pdf) | [https://github.com/ttanida/rgrg](https://github.com/ttanida/rgrg) | 0.373  | 0.249  | 0.175  | 0.126  | 0.264 | 0.168  | 0.495 | FALSE | FALSE           | w/ object detection and image size: 512 |
| 2023 | KGVL-BART                                             | KGVL-BART: Knowledge Graph Augmented Visual Language BART for Radiology Report Generation | [https://aclanthology.org/2023.eacl-main.246.pdf](https://aclanthology.org/2023.eacl-main.246.pdf) | [https://github.com/yeliu918/KG-BART](https://github.com/yeliu918/KG-BART) | \-     |        |        |        |       |        |       | FALSE | FALSE           | different dataset, w/ KG                |
| 2023 | Style-Aware                                           | Style-Aware Radiology Report Generation with RadGraph and Few-Shot Prompting | [https://arxiv.org/pdf/2310.17811v2.pdf](https://arxiv.org/pdf/2310.17811v2.pdf) |                                                              | \-     |        |        |        |       |        |       | TRUE  | FALSE           |                                         |
| 2023 | MVCO-DOT                                              | MVCO-DOT: MULTI-VIEW CONTRASTIVE DOMAIN TRANSFER NETWORK FOR MEDICAL REPORT GENERATION | [https://arxiv.org/pdf/2304.07465.pdf](https://arxiv.org/pdf/2304.07465.pdf) |                                                              | \-     |        |        |        |       |        |       | FALSE | FALSE           | Multi view                              |
| 2023 | Unify, Align and Refine                               | Unify, Align and Refine: Multi-Level Semantic Alignment for Radiology Report Generation | [https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Unify_Align_and_Refine_Multi-Level_Semantic_Alignment_for_Radiology_Report_ICCV_2023_paper.pdf](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Unify_Align_and_Refine_Multi-Level_Semantic_Alignment_for_Radiology_Report_ICCV_2023_paper.pdf) |                                                              | 0.363  | 0.229  | 0.158  | 0.107  | 0.289 | 0.157  | 0.246 | FALSE | FALSE           | image size: 128                         |
| 2023 | -                                                     | Self Adaptive Global-Local Feature Enhancement for Radiology Report Generation | [https://arxiv.org/pdf/2211.11380.pdf](https://arxiv.org/pdf/2211.11380.pdf) |                                                              | 0.363  | 0.235  | 0.164  | 0.118  | 0.301 | 0.136  |       | FALSE | FALSE           |                                         |
| 2023 | -                                                     | Attributed Abnormality Graph Embedding for Clinically Accurate X-Ray Report Generation | [https://ieeexplore.ieee.org/document/10045710](https://ieeexplore.ieee.org/document/10045710) |                                                              | \-     |        |        |        |       |        |       | FALSE | FALSE           |                                         |
| 2023 | SGT++                                                 | SGT++: Improved Scene Graph-guided Transformer for Surgical Report Generation | [https://ieeexplore.ieee.org/document/10330637](https://ieeexplore.ieee.org/document/10330637) |                                                              | \-     |        |        |        |       |        |       | FALSE | FALSE           | different dataset                       |
| 2023 | From Observation to Concept                           | From Observation to Concept: A Flexible Multi-view Paradigm for Medical Report Generation | [https://ieeexplore.ieee.org/document/10356722](https://ieeexplore.ieee.org/document/10356722) |                                                              | 0.391  | 0.249  | 0.172  | 0.125  | 0.304 | 0.16   |       | FALSE | FALSE           |                                         |
| 2023 | -                                                     | Joint Embedding of Deep Visual and Semantic Features for Medical Image Report Generation | [https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9606584](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9606584) |                                                              | 0.362  | 0.251  | 0.188  | 0.143  | 0.326 |        | 0.273 | FALSE | FALSE           |                                         |
| 2023 | -                                                     | Semi-Supervised Medical Report Generation via Graph-Guided Hybrid Feature Consistency | [https://ieeexplore.ieee.org/document/10119200](https://ieeexplore.ieee.org/document/10119200) |                                                              | 0.362  | 0.229  | 0.157  | 0.113  | 0.284 | 0.153  |       | FALSE | FALSE           | semi-supervised                         |
| 2024 | Complex Organ Mask Guided Radiology Report Generation | Complex Organ Mask Guided Radiology Report Generation        | [https://arxiv.org/pdf/2311.02329.pdf](https://arxiv.org/pdf/2311.02329.pdf) | [https://github.com/GaryGuTC/COMG_model](https://github.com/GaryGuTC/COMG_model) | 0.346  | 0.216  | 0.145  | 0.104  | 0.279 | 0.137  |       | FALSE | FALSE           |                                         |
| 2024 | ICON                                                  | ICON: Improving Inter-Report Consistency of Radiology Report Generation via Lesion-aware Mix-up Augmentation | [https://arxiv.org/pdf/2402.12844.pdf](https://arxiv.org/pdf/2402.12844.pdf) | [https://github.com/wjhou/ICon](https://github.com/wjhou/ICon) | 0.429  | 0.266  | 0.178  | 0.126  | 0.287 | 0.17   |       | FALSE | FALSE           |                                         |