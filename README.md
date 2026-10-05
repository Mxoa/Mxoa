### Hi, I am Marceau

MSc student in Machine Learning at Télécom Paris and KTH Royal Institute of Technology (double degree).

Currently a research intern at Karolinska Institutet (master thesis, until February 2027): deep learning for deformable registration of 2D-DIGE protein gel images, replacing semi-manual landmark-based alignment.

Looking for an ML/research engineer internship starting March 2027, to complement the research side with a product and engineering perspective. Open to NLP, computer vision, time series and RL, generalist by preference.

Reach me on [LinkedIn](https://www.linkedin.com/in/marceaum)

---

### Featured projects

**[Information Retrieval Benchmark Framework](https://github.com/Mxoa/Information-Retrieval-Benchmark-Framework)**
Modular benchmark of sparse (BM25, TF-IDF), dense (E5), hybrid and reranking retrieval (RRF, cross-encoder) on NFCorpus. nDCG@10 goes from 0.212 (BM25) to 0.319 (E5) and 0.395 with reranking, at a 17x throughput cost. A complementarity analysis (Jaccard, top-k overlap, diversity) explains when fusion actually helps.

**[Date-Time Parser](https://github.com/Mxoa/Transformer-based-Date-Normalization)**
Free-form English date/time expressions normalized to `YYYY-MM-DD, HH:MM`. A custom 1.4M-parameter encoder-classifier reaches 94.9% exact match against 88.2% for a fine-tuned T5-small (60M), while being 43x smaller and never producing an invalid output. Includes a synthetic data generator (~400k examples) and a Gradio demo.

**[Contrastive Music Representation Learning](https://github.com/Mxoa/Music-Embeddings-with-Contrastive-Learning)**
Self-supervised audio embeddings on raw music segments, following SimCLR/CLMR (CNN encoder, NT-Xent loss). Segments from the same track cluster together without any label: 53% k-NN genre accuracy on GTZAN against 10% for chance.

**[SinGAN Alternative Losses](https://github.com/Mxoa/SinGAN-Loss-Experiments)**
Can simpler or non-adversarial losses replace the WGAN-GP objective in SinGAN? Patch transport (Hungarian algorithm) and SIFID losses compared quantitatively and qualitatively against the official implementation.

---

### Other projects

- **[Autonomous agents in Unity](https://github.com/Mxoa/MAS-Reports)**: KTH multi-agent systems competitions (A*, Hierarchical Cooperative A*, particle filters, Velocity Obstacles, Stanley controller). Ranked 4th of 20 and 5th of 21 teams.
- **[Water Network Optimization (C++)](https://github.com/Mxoa/Water-Network-Optimization)**: graph-based modeling and flow optimization (Ford-Fulkerson, Dijkstra, Prim) for municipal water networks.
- **[DQN Lunar Lander (Gym)](https://github.com/Mxoa/RL-Lab-2)**: deep Q-learning on the classic control environment.

---

### Stack

Python, PyTorch, PyTorch Lightning, scikit-learn, Hugging Face Transformers, C++, C#, Git, Linux
