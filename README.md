# hi, i’m nhi dinh

I’m a PhD student in Math + TCS at UIC, and a UIUC Stats + CS alum (math minor).

these days i’m mostly interested in:
- mathematical foundations of representation learning + retrieval
- NLP + LLM systems
- high-dimensional probability / geometry of embeddings
- model evaluation + error analysis
- AI agents / reliability
- theoretical cs, probability, and combinatorics

I’m especially interested in questions like: when does nearest-neighbor retrieval actually work, how does it behave as dimension / corpus size / noise grow, and when do retrieval-augmented models start to fail?

I like projects where there is both a mathematical question and a systems question: can we understand why a method should work, test where it breaks, and then build something useful around it?

## what i’m working on

- **[specshield](https://github.com/nhidinh2/specshield)** — structural monitor for tool-using AI agents. it looks at typed actions, dataflow taint, and approval provenance instead of only asking another LLM whether an action looks safe.
- **representation learning + retrieval theory** — interested in the probability / geometry behind embedding spaces, nearest-neighbor retrieval, robustness to noise, and theoretical behavior of RAG systems.
- **NLP / retrieval / evals** — playing around with embeddings, retrieval pipelines, benchmark design, and error analysis for LLM systems.
- **random structures + tcs** — random hypergraphs, combinatorics, thresholds, and algorithmic questions.

## retrieval + ML systems

- **[NewsTrace](https://github.com/nhidinh2/newTrace)** — live AI / tech news tracker that groups same-event articles into evolving stories, keeps provenance + independent-source counts, and compares full vs. compressed embedding retrieval. on a 30-day corpus, 32D SVD used 92% less embedding memory with no measurable loss in retrieval quality.
- **[Vietnamese GraphRAG Q&A](https://github.com/nhidinh2/AICusotmerBot)** — GraphRAG-style QA over documents in Vietnamese: indexing, entity / relationship extraction, embeddings, local + global retrieval, source citations, and Neo4j visualization.
- **[AutoCalendarNLP](https://github.com/nhidinh2/AutoCalendarNLP)** — takes natural-language task descriptions, extracts things like date / time / people / location, and turns them into Google Calendar events through FastAPI.
- **[specshield](https://github.com/nhidinh2/specshield)** — prompt-injection / agent-safety project with multi-step taint tracking, English + Vietnamese attack scenarios, and evaluation tooling.
- **[predicting-cc](https://github.com/nhidinh2/predicting-cc)** — end-to-end ML forecasting pipeline with feature engineering, XGBoost-style models, calibration, backtesting, tests, CLI tooling, and a React dashboard.

## other things i’ve built / worked on

- **[cylindrical tiling enumeration](https://github.com/nhidinh2/countingstrips)** — compute counts, match OEIS sequences, and try to prove the patterns.
- **[merton-calibration](https://github.com/nhidinh2/merton-calibration)** — calibrate the Merton structural credit model; compare baseline vs EWMA-smoothed volatility estimates.
- **[MHI-ALGO](https://github.com/nhidinh2/MHI-ALGO)** — Metropolis-Hastings vs Gibbs, tuning + diagnostics.
- **[crypto-forecasting](https://github.com/nhidinh2/crypto-forecasting)** — Bitcoin forecasting with ARIMAX + eGARCH in R and Python.
- **[BoostStockModel](https://github.com/nhidinh2/BoostStockModel)** — IEX DEEP/TRADE data → XGBoost → C++ / Strategy Studio backtesting + analytics.

## tools

Python • SQL • C++ • C • R  
PyTorch • scikit-learn • GraphRAG • embeddings • FastAPI • Streamlit • Neo4j  
NumPy • pandas • SciPy • Git • Linux • Docker • pytest • LLM APIs

currently looking for NLP / applied AI / ML research engineering work where i can do retrieval, evals, data pipelines, and model / system experimentation.

nhidinh2@illinois.edu
