<div align="center">

# Jing Li

### Quantitative Researcher

Systematic Alpha · Relative Value · Research Engineering

I build applied quantitative research systems that move from hypothesis
discovery to portfolio evidence, with causal timing, realistic frictions,
exposure controls, return attribution, and auditable evaluation.

My work spans machine-scale alpha discovery, systematic equity research, and
digital-asset relative value.

[LinkedIn](https://www.linkedin.com/in/jing-li-b80205294) · [Email](mailto:jingli8881@outlook.com)

Open to quantitative research opportunities.

</div>

---

## Selected research

<table>
<tr>
<td width="100%" valign="top">

### LLM-Driven Alpha Discovery

A quantitative R&D system that scales hypothesis exploration without allowing
generative output to validate itself. The LLM expands and formalizes the search
space; deterministic code governs chronological testing, portfolio
construction, transaction costs, liquidity, capacity, and evidence release.

**Evidence:** deployed on a 257-instrument exchange-traded universe, one
retained factor produced 13.83% net CAGR, 1.55 Sharpe, and −4.25% maximum
drawdown in walk-forward out-of-sample evaluation at 5 bp one-way cost. It
remained profitable at 10 bp and became uneconomic at 20 bp, making
implementation quality an explicit boundary of the result.

[View research system →](https://github.com/Jing-Lavinia/llm-alpha-discovery)

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">

### Systematic Equity Alpha

An end-to-end U.S. large-cap absolute-return system that separates a
market-neutral Alpha Core from a separately governed Directional Risk Overlay,
with purged walk-forward modelling, next-open execution, portfolio constraints,
and sleeve-level attribution.

**Evidence:** the development specification produced 23.49% CAGR and 1.24
Sharpe after 5 bp one-way costs. A 76-session holdout returned +7.71%, while
attribution showed that the directional overlay—not the Alpha Core—drove the
gain, defining the next research question rather than overstating stock-selection
alpha.

[View case study →](https://github.com/Jing-Lavinia/systematic-equity-alpha)

</td>
<td width="50%" valign="top">

### Crypto Relative Value

A point-in-time perpetual-futures system combining sparse mean reversion and
cross-sectional funding carry inside a shared risk, execution, and accounting
engine, with contract-lifecycle controls and exact P&L reconciliation.

**Evidence:** development performance reached 22.08% CAGR and 1.62 Sharpe at
7 bp plus historical realized funding. The locked six-month terminal evaluation
returned +4.12%, driven by funding carry; it did not independently validate the
inactive mean-reversion sleeve.

[View case study →](https://github.com/Jing-Lavinia/crypto-relative-value-research)

</td>
</tr>
</table>

## Research approach

- **Scale discovery, not discretion:** broaden the hypothesis space while
  keeping acceptance rules empirical and deterministic.
- **Treat implementation as research:** timing, exposure, turnover, financing,
  liquidity, and capacity are designed with the signal rather than added later.
- **Attribute before claiming alpha:** separate portfolio return sources and
  state what each evidence window does—and does not—validate.
- **Preserve adverse evidence:** weak components, failed stress cases, and
  unresolved questions remain visible because they improve the next decision.

## Additional trading research

- **IMC Prosperity 4 — Solo Trading Research:** five algorithmic and five manual
  challenges completed independently; ranked #1,036 of 18,803 teams globally
  and #17 in China. The case study covers rapid valuation, options path risk,
  decision attribution, and a failed release that motivated a formal gate.
  [View case study →](https://github.com/Jing-Lavinia/imc-prosperity-4-research)

## Publications and earlier research

- **Carbon Risk and Return Prediction** — corresponding author; graph-structured
  information and Multi-CNN return prediction.
  [DOI](https://doi.org/10.3389/fenvs.2022.1035809)
- **Gaussian Control with Hierarchical Semantic Graphs in 3D Human Recovery
  (HUGS)** — coauthor; no module-level or quantitative personal-contribution
  claim is made here. [arXiv](https://arxiv.org/abs/2405.12477)
- Financial prediction, structured representations, sequence models, and
  biomedical generation are summarized with explicit provenance and
  contribution boundaries.
  [Research foundations →](https://github.com/Jing-Lavinia/research-foundations)

## Public disclosure

These repositories are public evidence layers rather than complete strategy
releases. They expose enough system design, aggregate evidence, failure
analysis, and implementation detail for serious review while keeping reusable
research IP, exact signals, and empirical trading paths private.

All trading results are simulated research evidence, not live performance,
investment advice, or a guarantee of future returns.
