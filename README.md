# Achintya Mishra

Equity research candidate combining data science and finance. BTech (Computer & IoT), Manipal University Jaipur.

**Site:** [achintya1311.github.io](https://achintya1311.github.io) — all of the below, one page.

- **Valuation:** [reverse-dcf-engine](https://github.com/Achintya1311/reverse-dcf-engine) solves for the constant growth rate a share price implies, with reinvestment tied to growth through return on capital and the margin held at the base year, then tests it against history and peers. Its README says when no growth rate reproduces the price. Paired with a [three-statement model](https://github.com/Achintya1311/three-statement-model) built from primary filings.
- **Pipeline:** [STOCKSTALKER](https://github.com/Achintya1311/STOCKSTALKER) is the front door to eight linked public repos (itself plus seven research repos; the private capstone note it feeds and the separate stockstalker-lab are not counted). Six of the seven (valuation, [Monte Carlo risk](https://github.com/Achintya1311/monte-carlo-risk-lab), an [Indian factor model](https://github.com/Achintya1311/fama-french-factor-model), [options](https://github.com/Achintya1311/implied-vol-surface), [sentiment](https://github.com/Achintya1311/headline-sentiment-vs-price) and the three-statement model) are read into one tear sheet for any NSE stock (options for F&O names only; sentiment finds headlines only for the 23 companies in its hand-written lookup and reports no coverage elsewhere); the seventh, the [portfolio optimiser](https://github.com/Achintya1311/markowitz-portfolio-optimizer), sits outside it, as position sizing is left out of the tear sheet on purpose. The three-statement model's fundamentals are built by hand for one researched name (GULFOILLUB).
- **Research:** How test-set peeking inflates benchmark comparisons, using CRAFT — a machine-learning pipeline — as the system under study, run on seven datasets. Across 163 public datasets in three benchmark collections, changing the comparison model changes which method looks ahead in 31% of cases. Submitted to a conference in 2026.
- **Certifications:** NISM Series XV (Research Analyst) and NISM Series VIII (Equity Derivatives).

Each repo reports what failed as well as what worked. See the Limitations section of each README.

Educational research on historical data. Not investment advice. Not a SEBI-registered research analyst.
