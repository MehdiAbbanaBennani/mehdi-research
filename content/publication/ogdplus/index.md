---
title: "Generalisation Guarantees for Continual Learning with Orthogonal Gradient Descent"
date: 2020-01-01
publishDate: 2020-07-10
authors: ["Mehdi Abbana Bennani", "Masashi Sugiyama"]
publication_types: ["1"]
abstract: "In continual learning settings, deep neural networks are prone to catastrophic forgetting. Orthogonal Gradient Descent (Farajtabar et al., 2019) achieves state-of-the-art results in practice for continual learning, although no theoretical guarantees have been proven yet. We derive the first generalisation guarantees for the algorithm OGD for continual learning, for overparameterized neural networks. We find that OGD is only provably robust to catastrophic forgetting across a single task. We propose OGD+, prove that it is robust to catastrophic forgetting across an arbitrary number of tasks, and that it verifies tighter generalisation bounds. The experiments show that OGD+ outperforms OGD on settings with long range memory dependencies, even though the models are not overparameterized. Also, we derive a closed form expression of the learned models through tasks, as a recursive kernel regression relation, which captures the transferability of knowledge through tasks. Finally, we quantify theoretically the impact of task ordering on the generalisation error, which highlights the importance of the curriculum for lifelong learning."
url_pdf : "https://arxiv.org/pdf/2006.11942.pdf"
url_code : "https://github.com/MehdiAbbanaBennani/continual-learning-ogdplus"
url_video : "https://www.youtube.com/watch?v=_P1OXpjDf6Y&t=93s"
featured: true
publication: "*ICML 4th Lifelong Learning Workshop*"
---

