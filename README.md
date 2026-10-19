## Hi, I'm Manish

Final-year B.Tech in Chemical Engineering at **IIT Bombay** (minor in AI and Data Science, CPI 9.74/10), graduating May 2027.

I build ML systems for problems where the answer has to be **correct, not just plausible**: simulating chemical reactions, pricing derivatives and auditing quantitative research. Most of my work comes down to careful evaluation: fixed protocols, held-out sets, matched controls and honest error analysis.

### What I'm working on

- **ML-accelerated reaction-path search:** a machine-learned (MACE) Hessian preconditioner for nudged elastic band optimisation. On a pre-registered 60-system benchmark with a sealed held-out set, it converges on 33/60 systems vs 28/60 for FIRE, using a median 0.18× the force evaluations. *(research, IIT Bombay)*
- **Quant Auditor:** a small fine-tuned LLM agent (Qwen3-4B, SFT then GRPO) that audits trading backtests by running diagnostic experiments, catching look-ahead bias, missing costs and same-bar fills. *(in progress)*

### Selected projects

| Project | What it is |
|---|---|
| [**Spatiotemporal GNN for sales forecasting**](https://github.com/Manish-785/sales-demand-forecasting) | First-author paper ([arXiv:2511.19267](https://arxiv.org/abs/2511.19267)). Joint forecasting across 45 stores with a learned store graph; lowest overall error and most consistent across stores vs ARIMA, LSTM and XGBoost. |
| [**Heston pricing and SPX calibration**](https://github.com/Manish-785/IE624-Heston-Pricing-using-Monte-Carlo) | Heston Monte Carlo pricer (Euler and Andersen QE) with implied-vol inversion and a semi-analytic check, calibrated to live SPX option chains. |
| [**Option pricing and delta hedging**](https://github.com/Manish-785/option_pricing_project) | Black–Scholes, binomial and Monte Carlo pricing of 36,900+ listed options; delta-hedging back-tests. |
| **MolGenX** ([backend](https://github.com/https-kanika/MolGenX-backend), [frontend](https://github.com/adityapatil2310/MolGenX-frontend)) | Protein-conditioned molecule generator (550K+ BindingDB samples, 100% validity). 1st of 64,000+ in the Google Developer Solution Challenge. Team project. |
| [**KELP**](https://github.com/Manish-785/KELP) | Multi-agent LLM pipeline that turns company documents into anonymised, cited pitch decks. |

### Experience

- **Morgan Stanley:** Summer Associate, Asia FX Structuring (2026). Built a TARF pricing engine validated to within 1bp on 40+ benchmark trades, and an FX volatility screener.
- **iWealth:** Quant Developer (2025). Earnings-call transcription (Whisper) and filings-summary pipelines for the investment team.
- **Dreamplan:** Full Stack Developer (2024–25), wealth-advice fintech in Denmark.

### Tools

`Python` · `PyTorch` · `Hugging Face` · `QLoRA / Unsloth` · `vLLM` · `NumPy / SciPy / pandas` · `ASE` · `MACE` · `VASP` · `C++` · `SQL` · `Excel` · `Bloomberg (DLIB)`

### Contact

[Email](mailto:msn07082005@gmail.com) · [LinkedIn](https://www.linkedin.com/in/manish-singh785) · [arXiv](https://arxiv.org/abs/2511.19267)
