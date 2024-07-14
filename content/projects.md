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
        **Machine Learning Research**: Recent advancements in machine learning, such as deep generative models, have proven to be powerful tools for learning data distributions and making predictions. However, these methods often fall short in essential aspects needed for scientific discovery, such as causality, interpretability, disentanglement, uncertainty quantification, and decision-making. Our research focuses on enhancing these capabilities to make machine learning methods more robust and effective in driving the discovery process.

        **Molecular Biology Research**: Our research leverages recent breakthroughs in genetic engineering and high-throughput profiling technologies, such as CRISPR and single-cell RNA sequencing, to study complex diseases and improve drug discovery. Our interdisciplinary approach integrates advanced computational methods with experimental biology, particularly focusing on the immune system, to drive impactful scientific discoveries and advancements in understanding cellular processes and disease mechanisms.
  - block: markdown
    content:
      title: ':rocket: Our Research'
      subtitle: ''
      text: |-
        <p>We strive to address these challenges in our main areas of research laid out below.</p>
            <ul>
                <li><a href="#probabilistic-inference-and-generative-models">Probabilistic Inference and Generative Models</a></li>
                <li><a href="#causal-inference-and-identifiability">Causal Structure Learning, Inference and Identifiability Theory</a></li>
                <li><a href="#machine-learning-for-single-cell-omics-data-analysis">Machine Learning for Single-Cell Omics Data Analysis</a></li>
                <li><a href="#spatial-transcriptomics-data-analysis">Spatial Transcriptomics Data Analysis</a></li>
                <li><a href="#single-cell-perturbation-data-modeling">Single-cell Perturbation Data Modeling</a></li>
            </ul>
            <h3 id="probabilistic-inference-and-generative-models">Probabilistic Inference and Generative Models</h3>
            <p>
                We develop ML methodology for making generative models more interpretable and usable for downstream tasks such as decision-making and hypothesis testing. These models are particularly useful in handling high-dimensional, noisy, and incomplete data typical in applied scientific research.
            </p>
            <ul class="key-publications">
                <li>Lopez, R., Regier, J., Jordan, M. I., & Yosef, N. "Information constraints on auto-encoding variational Bayes." <em>Advances in Neural Information Processing Systems</em>, 2018. </li>
                <li>Lopez, R., Boyeau, P., Yosef, N., Jordan, M. I., & Regier, J. "Decision-making with auto-encoding variational Bayes." <em>Advances in Neural Information Processing Systems</em>, 2020. </li>
            </ul>
            <h3 id="causal-inference-and-identifiability">Causal Structure Learning, Inference and Identifiability Theory</h3>
            <p>
                We develop causal machine learning approaches that can leverage high-dimensional data. Towards this goal, we are interested in tractable approaches to causal structure learning that have the potential to scale to tens of thousands of variables. Additionally, we are interested in causal representation learning, where interventions are conducted on latent variables of a deep generative model. 
            </p>
            <ul class="key-publications">
                <li>Lopez, R., Huetter, JC., Pritchard, J., & Regev, A. Large-scale differentiable causal discovery of factor graphs. Advances in Neural Information Processing Systems, 2022.</li>
                <li>Sethuraman, M. G., Lopez, R., Mohan, R., Fekri, F., & Hajiramezanali, E. "NODAGS-Flow: Nonlinear cyclic causal structure learning." <em>International Conference on Artificial Intelligence and Statistics</em>, 2023.</li>
                <li>Lopez, R., Huetter, JC., Hajiramezanali, E., Pritchard, J., & Regev, A. "Towards the Identifiability of Comparative Deep Generative Models." <em>Conference on Causal Learning and Reasoning</em>, 2024.</li>
            </ul>
            <h3 id="machine-learning-for-single-cell-omics-data-analysis">Machine Learning for Single-Cell Omics Data Analysis</h3>
            <p>
                Our lab develops advanced algorithms to analyze single-cell omics data, enhancing our understanding of cellular states and dynamics. We focus on improving methods for differential expression analysis, integration of multi-omics data, and robust modeling of cellular heterogeneity. These innovations are vital for deciphering the complexities of single-cell data and driving biological discoveries.
            </p>
            <ul class="key-publications">
                <li>Lopez, R., Boyeau, P., Regier, J., Gayoso, A., Jordan, M. I., & Yosef, N. "Deep generative modeling for single-cell transcriptomics." <em>Nature Methods</em>, 2018.</li>
                <li>Gayoso, A., Lopez, R., Xing, G., Boyeau, P., Wu, K., Jayasuriya, M., Regier, J., & Yosef, N. (2022). A Python library for probabilistic analysis of single-cell omics data. <em>Nature Biotechnology</em>.</li>
                <li>Boyeau, P., Regier, J., Gayoso, A., Jordan, M. I., Lopez, R.*, & Yosef, N.* (2023). An empirical Bayes method for differential expression analysis of single cells with deep generative models. <em>Proceedings of the National Academy of Sciences</em>.</li>
            </ul>
            <h3 id="spatial-transcriptomics-data-analysis">Spatial Transcriptomics Data Analysis</h3>
            <p>
                Leveraging spatial transcriptomics, we aim to map cellular organization within tissues, combining computational biology techniques with experimental data to uncover spatial patterns and interactions at the molecular level. Our research focuses on developing robust methods for analyzing spatially resolved transcriptomics data, leading to new insights into tissue architecture and cellular function.
            </p>
            <ul class="key-publications">
                <li>Lopez, R., Li, B., Keren-Shaul, H., Boyeau, P., Kedmi, M., Pilzer, D., et al. "DestVI identifies continuums of cell types in spatial transcriptomics data." <em>Nature Biotechnology</em>, 2022.</li>
                <li>Lopez, R., Nazaret, A., Langevin, M., Samaran, J., Regier, J., Jordan, M. I., & Yosef, N. (2019). A joint model of unpaired data from scRNA-seq and spatial transcriptomics for imputing missing gene expression measurements. <em>ICML Workshop in Computational Biology</em>.</li>
            </ul>
            <h3 id="single-cell-perturbation-data-modeling">Single-cell Perturbation Data Modeling</h3>
            <p>
                We explore the effects of genetic and chemical perturbations at the single-cell level, developing models that can predict cellular responses to these perturbations. This research helps in understanding the mechanisms of action for various perturbations, aiding in drug discovery and therapeutic interventions. Our models aim to be robust, interpretable, and applicable across different biological contexts.
            </p>
            <ul class="key-publications">
                <li>Lopez, R., Tagasovska, N., Ra, S., Cho, K., Pritchard, J. K., & Regev, A. "Learning causal representations of single cells via sparse mechanism shift modeling." <em>Conference on Causal Learning and Reasoning</em>, 2023.</li>
                <li>Tu, X., Huetter, J., Wang, Z. J., Kudo, T., Regev, A., & Lopez, R. "A Supervised Contrastive Framework for Learning Disentangled Representations of Cell Perturbation Data." <em>Machine Learning in Computational Biology</em>, 2023.</li>
            </ul>
---
