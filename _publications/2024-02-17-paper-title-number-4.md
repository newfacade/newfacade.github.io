---
title: "Leetcodedataset: A temporal dataset for robust evaluation and efficient training of code llms"
collection: publications
category: conferences
permalink: /publication/2025-leetcodedataset
# excerpt: 'This paper is about fixing template issue #693.'
# date: 2024-02-17
# venue: 'GitHub Journal of Bugs'
paperurl: 'https://arxiv.org/pdf/2504.14655'
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

We introduce LeetCodeDataset, a high-quality benchmark for evaluating and training code-generation models, addressing two key challenges in LLM research: the lack of reasoning-focused coding benchmarks and self-contained training testbeds. By curating LeetCode Python problems with rich metadata, broad coverage, 100+ test cases per problem, and temporal splits (pre/post July 2024), our dataset enables contamination-free evaluation and efficient supervised fine-tuning (SFT). Experiments show reasoning models significantly outperform non-reasoning counterparts, while SFT with only 2.6K model-generated solutions achieves performance comparable to 110K-sample counterparts. The dataset and evaluation framework are available on Hugging Face and Github.
