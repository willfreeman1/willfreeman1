### Will Freeman — Data Scientist, Austin TX

ML, LLMs, and causal inference, coming from the business side (marketing,
growth, M&A). I build end-to-end: find the problem, ship the model, build
the evidence that it's real. Currently going deeper on healthcare —
genomics, drug discovery, oncology.

**Three projects, three honest numbers:**

- **[nhtsa-complaint-llm](https://github.com/willfreeman1/nhtsa-complaint-llm)** —
  fine-tuned a 7B open model to within 0.4 points of a frontier model on a
  551-case hand-checked test set, then shipped it with monitoring, CI, and
  a retraining gate that **rejected its own retrain** when the numbers
  didn't clear the bar set in advance.
- **[causal_uplift_project](https://github.com/willfreeman1/causal_uplift_project)** —
  uplift modeling with doubly-robust off-policy evaluation on a randomized
  holdout, built to fix a circular evaluation flaw common in take-home
  versions of this problem.
- **[graph_fraud_aml](https://github.com/willfreeman1/graph_fraud_aml)** —
  graph neural networks for anti-money-laundering, scored the way a
  compliance desk actually works: dollars caught at a fixed daily review
  budget, not raw accuracy.

I write down stop-or-continue thresholds before I see results, and I've
killed projects when they didn't clear them (see CorpFam, linked from
nhtsa-complaint-llm's writeup) rather than publish a flattering number.

[LinkedIn](https://www.linkedin.com/in/willfreeman1) · willfreeman@gmail.com
