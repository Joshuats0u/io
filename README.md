# PandaAI Research Atlas

An interactive dashboard for Panda AI's research papers on arXiv (Li Yuqi / 李昱琦 et al.) and the work around them.

Download `dashboard/pandaai-atlas-standalone.html` and open it in any browser. It works offline with no server. (`pandaai-atlas.html` is the source published as the Claude artifact.)

## Papers covered

Panda AI team:

- **CQ2: PandaAI: A Practical Agent CQ2 for Neuro-symbolic Data Analysis And Integrated Decision-Making in Quantitative Finance** (arXiv [2606.06823](https://arxiv.org/abs/2606.06823)), Yuqi Li, Siyuan Liu, Bingjun Liu, June 2026
- **Agora: AI Trading's Alpha Singularity: Emergent Market Reasoning through Agent-to-Agent Self-Evolution** (arXiv [2606.29194](https://arxiv.org/abs/2606.29194)), Yuqi Li, Siyuan Liu, Bingjun Liu, June 2026
- **AlphaSchema: Exploring the Space of Trading Semantics for LLM-Based Alpha Mining** (arXiv [2607.26642](https://arxiv.org/abs/2607.26642)), Jingyang Yi, Jian Yang, Yifei Jin, Yuqi Li, Jian Li, July 2026

Earlier work by Li Yuqi (not on arXiv; from a TQX research slide):

- Research on high-frequency financial transaction behavior recognition and prediction method integrating machine learning (2026, EI Compendex indexed)
- Fusion of multifactor modeling and supervised learning algorithms in quantitative finance: a comparative analysis of predictive and explanatory power (2024, Applied Mathematics and Nonlinear Sciences 9(1), DOI 10.2478/amns-2024-1237)
- The impact of systemic financial risks on the Shanghai Composite Index: evidence from an ARIMA model (2023, Proc. 2nd ICFTBA 56:1055, DOI 10.54254/2754-1169/56/20231055)

Background:

- **Navigating the Alpha Jungle: An LLM-Powered MCTS Framework for Formulaic Factor Mining** (arXiv [2505.11122](https://arxiv.org/abs/2505.11122)). This is the search method PandaAI builds on.
- Related LLM alpha-mining papers, plus a list of unrelated "PANDA" papers that share the name

## Interactive sections

- Closed-loop architecture: select a module to see what it does
- LLM-guided MCTS: step through UCT selection and adjust exploration
- Frequent Subtree Avoidance: ban common root genes and watch formula diversity change
- IC, Rank IC, ICIR and drawdown: adjust signal, persistence, regime decay and costs on a simulated 300-stock universe
- Agora: step through the five agent roles and compare a fixed scorer with a co-evolving one in a toy model
- AlphaSchema: build a five-field schema plan and run a surrogate-guided search against random search

The simulations use synthetic data. They show how each mechanism works and don't reproduce the paper's results.
