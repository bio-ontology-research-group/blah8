# Unlocking the Power of Language Models for Gene Function Extraction from Literature

Authors: Senay Kafkas, Sumyyah Toonsi, Robert Hoehndorf
Affiliation: King Abdullah University of Science and Technology 
Thuwal, Saudi Arabia

Project Description:

Studying gene functions is essential as it reveals fundamental biological processes governing life. Genes contain instructions for building proteins, which are crucial for cellular functions. This understanding aids scientists in disease mechanism exploration, identifying drug targets, and developing personalized therapies. This knowledge advances medical research, and personalized medicine, and enhances human health. 

The Gene Ontology (GO) captures gene products' functions in classes and establishes a relationship between them. Annotating proteins with Gene Ontology (GO) functions by hand from biomedical literature is a laborious task that necessitates automation. Earlier approaches primarily depended on unsupervised (dictionary-based [1,2], text similarity [3]) and supervised machine learning-based [4] methods to extract gene functions from the literature.

However, none of the existing studies explored the potential of LLMs in gene function extraction from scientific articles. To unveil the potential of LLMs in gene function extraction, we will use several recent cutting-edge LLMs (e.g. GPT3.5-turbo, GPT4, Falcon180B) and design zero-shot, few-shot, and fine-tuning (weakly supervision) experiments. We will compare the performance of the LLMs against baseline/other methods (e.g. dictionary-based approach) on a benchmarking dataset.

References:
[1] Sumyyah Toonsi. Automatic Protein Function Annotation Through Text Mining”. PhD Thesis (2019).

[2] Jia-Hong Wang et al. GenCLiP 3: mining human genes’ functions and regulatory networks from PubMed based on co-occurrences and natural language processing, Bioinformatics, Vol. 36, Issue 6,  pp. 1973–1975, (2019), https://doi.org/10.1093/bioinformatics/btz807

[3] Couto FM, et. al. GOAnnotator: linking protein GO annotations to evidence text. J Biomed Discov Collab. 1:19. (2006),  doi: 10.1186/1747-5333-1-19. 

[4] Andrea Fossati et al. Towards a systematic characterization of protein complex function: a natural language processing and machine-learning framework. Pre-print: bioRxiv, (2021), doi: https://doi.org/10.1101/2021.02.24.432789
