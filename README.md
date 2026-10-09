# PandaAI Research Atlas

An interactive dashboard for the PandaAI paper on arXiv and the work around it.

Open `dashboard/pandaai-atlas.html` in a browser. It has no build step and needs no server.

## Papers covered

- **PandaAI: A Practical Agent CQ2 for Neuro-symbolic Data Analysis And Integrated Decision-Making in Quantitative Finance** (arXiv [2606.06823](https://arxiv.org/abs/2606.06823)), Yuqi Li, Siyuan Liu, Bingjun Liu, June 2026
- **Navigating the Alpha Jungle: An LLM-Powered MCTS Framework for Formulaic Factor Mining** (arXiv [2505.11122](https://arxiv.org/abs/2505.11122)). This is the search method PandaAI builds on.
- Related LLM alpha-mining papers, plus a list of unrelated "PANDA" papers that share the name

## Interactive sections

- Closed-loop architecture: select a module to see what it does
- LLM-guided MCTS: step through UCT selection and adjust exploration
- Frequent Subtree Avoidance: ban common root genes and watch formula diversity change
- IC, Rank IC, ICIR and drawdown: adjust signal, persistence, regime decay and costs on a simulated 300-stock universe

The simulations use synthetic data. They show how each mechanism works and don't reproduce the paper's results.
