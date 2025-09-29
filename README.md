# knowledge-augmentation-project
This repository contains the notebooks and supplementary files for my seminar project on "Exploring the Transferability of ULTRA to PICKLE – Evaluation of a Graph Foundation Model on a Plant Science Knowledge Graph Corpus" as part of the seminar "Exploring Knowledge Augmentation Methods for Language Models" at Deutsches Forschungszentrum für Künstliche Intelligenz (DFKI), September 2025.

## Contents
- logfiles contains the logs for all 15 model instances trained within the scope of this project as txt files
- data_conversion.ipynb contains the code for converting the brat-formatted PICKLE [1] files to txt files with (head entity, relation, tail entity) triples (Section 4)
- experiments.ipynb contains the code for training the 15 model instances with ULTRA (Section 5)
- model_evaluation.ipynb contains the code for evaluating model performance and all figures in the project report (Section 5 & Appendix)
- transductive_datasets_relations.tsv contains the numbers of entities and relations as well as performance metrics for the datasets distributed with ULTRA, adopted from [2]


## References
[1] Serena Lotreck, Kenia Segura Abá, Melissa D Lehti-Shiu, Abigail Seeger, Brianna N I Brown, Thilanka Ranaweera, Ally Schumacher, Mohammad Ghassemi, and Shin-Han Shiu. 2023. Plant Science Knowledge Graph Corpus: a gold standard entity and relation corpus for the molecular plant sciences. in silico Plants, 6(1):diad021. _eprint: https://academic.oup.com/insilicoplants/article-pdf/6/1/diad021/55144192/diad021.pdf.
[2] Mikhail Galkin, Xinyu Yuan, Hesham Mostafa, Jian Tang, and Zhaocheng Zhu. 2024. Towards Foundation Models for Knowledge Graph Reasoning. _eprint: 2310.04562.
