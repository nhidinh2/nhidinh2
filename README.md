<div align="center">

# hi, i’m nhi dinh

**math + theoretical cs · machine learning · nlp / retrieval**

PhD student @ UIC · UIUC Statistics + CS alum (math minor)

I like problems where there is both a mathematical question and a systems question: understand why a method should work, measure where it breaks, and build something useful around it.

[about](#about) · [selected work](#selected-work) · [research](#research) · [background](#background) · [contact](#contact)

</div>

---

## about

I’m a PhD student at UIC working around probability, combinatorics, theoretical CS, and machine learning. I’m especially interested in the mathematical foundations of **representation learning + retrieval**, high-dimensional probability / geometry, **LLM evaluation + reliability**, and algorithms on random or discrete structures.

Recently I’ve been building retrieval and evaluation systems and thinking about how theoretical questions about embeddings, compression, robustness, and algorithmic structure show up in real systems.

## selected work

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/nhidinh2/newTrace">NewsTrace</a></h3>
<p>Real-time AI / tech story tracker with provenance-aware retrieval, source deduplication, clustering, and compressed embeddings.</p>
<p>On a 30-day live corpus, a 32D SVD index used <b>92% less embedding memory</b> with no measurable loss in retrieval quality.</p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/nhidinh2/specshield">SpecShield</a></h3>
<p>Structural trusted monitor for tool-using AI agents.</p>
<p>Authorizes actions from typed fields, dataflow taint, and approval provenance rather than relying only on another LLM to judge whether an action looks safe.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/nhidinh2/countingstrips">Cylindrical tiling enumeration</a></h3>
<p>Computational + combinatorial work on counting border-strip decompositions on cylinders: generate data, identify patterns, connect them to known sequences, and work toward proofs.</p>
</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/nhidinh2/AICusotmerBot">Vietnamese GraphRAG Q&A</a></h3>
<p>GraphRAG-style QA over Vietnamese documents using entity / relationship extraction, embeddings, local + global retrieval, citations, and Neo4j visualization.</p>
</td>
</tr>
</table>

<p align="right"><a href="https://github.com/nhidinh2?tab=repositories">more projects →</a></p>

## research

### Algorithmic Phase Transition for Large Independent Sets in Dense Hypergraphs
**APPROX/RANDOM 2026** · with Abhishek Dhawan, Eren C. Kızıldağ, Neeladri Maitra, and Bayram A. Şahin  
[paper](https://doi.org/10.4230/LIPIcs.APPROX/RANDOM.2026.68) · [arXiv](https://arxiv.org/abs/2605.05618)

We study large independent sets in dense random hypergraphs, including online algorithms, sharp algorithmic barriers, and balanced independent sets in multipartite models.

### Choosability of Multipartite Hypergraphs
with Peter Bradshaw, Abhishek Dhawan, Shlok Mulye, and Rohan Rathi  
[arXiv](https://arxiv.org/abs/2512.21222)

Work on list coloring / choosability in multipartite uniform hypergraphs and efficient randomized coloring algorithms.

## questions i keep coming back to

- what geometric or probabilistic structure in an embedding space actually makes retrieval work?
- how far can representations be compressed before useful information disappears?
- how should we evaluate LLM systems when one aggregate metric hides the interesting failure modes?
- when do simple algorithms succeed on random structures, and where do genuine computational barriers appear?

## background

**University of Illinois Chicago** — PhD student, mathematics + theoretical CS  
**University of Illinois Urbana-Champaign** — B.S. Statistics + Computer Science, math minor

## tools i use

**Languages:** Python, SQL, C++, C, R  
**ML / data:** PyTorch, scikit-learn, NumPy, pandas, SciPy, sentence-transformers, embeddings  
**Systems:** FastAPI, Streamlit, Neo4j, Git, Linux, Docker, pytest, LLM APIs

## contact

I’m interested in research and engineering problems around retrieval, representation learning, NLP / LLM systems, evaluation, reliable agents, and mathematically grounded ML.

**email:** nhidinh2@illinois.edu
