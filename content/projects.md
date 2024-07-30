---
title: 'Research'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '2rem'

# Page sections
sections:
  - block: markdown
    content:
      title: ':crystal_ball: Our Mission'
      subtitle: ''
      text: |-
        **Advancing Machine Learning Research for Biological Sciences**: We develop next-generation machine learning tools tailored for biological research. Our focus is on improving causality, interpretability, disentanglement, uncertainty quantification, and decision-making in machine learning models to enhance their robustness and scientific utility.

        **Designing Innovative Computational Tools for Molecular Biology Research**: We leverage cutting-edge genetic engineering and high-throughput profiling technologies, such as CRISPR and single-cell RNA sequencing, to study complex diseases and drive drug discovery. By integrating computational methods with experimental biology, particularly in immunology, we aim to make significant advances in understanding cellular processes and disease mechanisms.
  - block: markdown
    content:
      title: ':rocket: Our Research'
      subtitle: ''
      text: |-
        <p>We strive to address these challenges in our main areas of research laid out below.</p>
            <ul>
                <li><a href="#probabilistic-inference-and-generative-models">Probabilistic Inference and Generative Models</a></li>
                <li><a href="#causal-inference-and-identifiability">Causal Structure Learning, Causal Inference and Identifiability Theory</a></li>
                <li><a href="#machine-learning-for-single-cell-omics-data-analysis">Machine Learning for Single-Cell Omics Data Analysis</a></li>
                <li><a href="#spatial-transcriptomics-data-analysis">Spatial Transcriptomics Data Analysis</a></li>
                <li><a href="#single-cell-perturbation-data-modeling">Single-cell Perturbation Data Modeling</a></li>
            </ul>
            <h3 id="probabilistic-inference-and-generative-models">Probabilistic Inference and Generative Models</h3>
            <p>
                We develop ML methodology for making generative models more interpretable and usable for downstream tasks such as decision-making and hypothesis testing. These models are particularly useful in handling high-dimensional, noisy, and incomplete data typical in applied scientific research.
            </p>
            <ul class="key-publications">
                <li>Lopez, R., Regier, J., Jordan, M. I., & Yosef, N. (2018). "<strong style="color: #57068c;">Information constraints on auto-encoding variational Bayes</strong>" <em>Advances in Neural Information Processing Systems</em> </li>
                <li>Lopez, R., Boyeau, P., Yosef, N., Jordan, M. I., & Regier, J. (2020). "<strong style="color: #57068c;">Decision-making with auto-encoding variational Bayes.</strong>" <em>Advances in Neural Information Processing Systems</em> </li>
            </ul>
            <h3 id="causal-inference-and-identifiability">Causal Structure Learning, Causal Inference and Identifiability Theory</h3>
            <p>
                We develop causal machine learning approaches that can leverage high-dimensional data. Towards this goal, we are interested in tractable approaches to causal structure learning that have the potential to scale to tens of thousands of variables. Additionally, we are interested in causal representation learning, where interventions are conducted on latent variables of a deep generative model. 
            </p>
            <ul class="key-publications">
                <li>Lopez, R., Huetter, JC., Pritchard, J., & Regev, A. (2022). "<strong style="color: #57068c;">Large-scale differentiable causal discovery of factor graphs.</strong>" Advances in Neural Information Processing Systems.</li>
                <li>Sethuraman, M. G., Lopez, R., Mohan, R., Fekri, F., & Hajiramezanali, E. (2023). "<strong style="color: #57068c;">NODAGS-Flow: Nonlinear cyclic causal structure learning.</strong>" <em>International Conference on Artificial Intelligence and Statistics</em>.</li>
                <li>Lopez, R., Huetter, JC., Hajiramezanali, E., Pritchard, J., & Regev, A. (2024). "<strong style="color: #57068c;">Towards the Identifiability of Comparative Deep Generative Models.</strong>" <em>Conference on Causal Learning and Reasoning</em>.</li>
            </ul>
            <h3 id="machine-learning-for-single-cell-omics-data-analysis">Machine Learning for Single-Cell Omics Data Analysis</h3>
            <p>
                Our lab develops advanced algorithms to analyze single-cell omics data, enhancing our understanding of cellular states and dynamics. We focus on improving methods for differential expression analysis, integration of multi-omics data, and robust modeling of cellular heterogeneity. These innovations are vital for deciphering the complexities of single-cell data and driving biological discoveries.
            </p>
            <ul class="key-publications">
                <li>Lopez, R., Boyeau, P., Regier, J., Gayoso, A., Jordan, M. I., & Yosef, N. (2018). "<strong style="color: #57068c;">Deep generative modeling for single-cell transcriptomics.</strong>" <em>Nature Methods</em>.</li>
                <li>Gayoso*, A., Lopez*, R., Xing*, G., Boyeau, P., Wu, K., Jayasuriya, M., Regier, J., & Yosef, N. (2022). "<strong style="color: #57068c;">A Python library for probabilistic analysis of single-cell omics data.</strong>" <em>Nature Biotechnology</em>.</li>
                <li>Boyeau, P., Regier, J., Gayoso, A., Jordan, M. I., Lopez*, R., & Yosef*, N. (2023). "<strong style="color: #57068c;">An empirical Bayes method for differential expression analysis of single cells with deep generative models.</strong>" <em>Proceedings of the National Academy of Sciences</em>.</li>
            </ul>
            <h3 id="spatial-transcriptomics-data-analysis">Spatial Transcriptomics Data Analysis</h3>
            <p>
                Leveraging spatial transcriptomics, we aim to map cellular organization within tissues, combining computational biology techniques with experimental data to uncover spatial patterns and interactions at the molecular level. Our research focuses on developing robust methods for analyzing spatially resolved transcriptomics data, leading to new insights into tissue architecture and cellular function.
            </p>
            <ul class="key-publications">
                <li>Lopez*, R., Nazaret*, A., Langevin*, M., Samaran*, J., Regier*, J., Jordan, M. I., & Yosef, N. (2019). "<strong style="color: #57068c;">A joint model of unpaired data from scRNA-seq and spatial transcriptomics for imputing missing gene expression measurements.</strong>" <em>ICML Workshop in Computational Biology</em>.</li>
                <li>Lopez*, R., Li*, B., Keren-Shaul*, H., Boyeau, P., Kedmi, M., Pilzer, D., et al. (2022). "<strong style="color: #57068c;">DestVI identifies continuums of cell types in spatial transcriptomics data.</strong>" <em>Nature Biotechnology</em>.</li>
            </ul>
            <h3 id="single-cell-perturbation-data-modeling">Single-cell Perturbation Data Modeling</h3>
            <p>
                We explore the effects of genetic and chemical perturbations at the single-cell level, developing models that can predict cellular responses to these perturbations. This research helps in understanding the mechanisms of action for various perturbations, aiding in drug discovery and therapeutic interventions. Our models aim to be robust, interpretable, and applicable across different biological contexts.
            </p>
            <ul class="key-publications">
                <li>Lopez*, R., Tagasovska*, N., Ra, S., Cho, K., Pritchard, J. K., & Regev, A. (2023). "<strong style="color: #57068c;">Learning causal representations of single cells via sparse mechanism shift modeling.</strong>" <em>Conference on Causal Learning and Reasoning</em>.</li>
                <li>Tu, X., Huetter, J., Wang, Z. J., Kudo, T., Regev, A., & Lopez, R. (2023). "<strong style="color: #57068c;">A Supervised Contrastive Framework for Learning Disentangled Representations of Cell Perturbation Data.</strong>" <em>Machine Learning in Computational Biology</em>.</li>
            </ul>
---
