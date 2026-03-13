# Sample Size Negotiator

An interactive tool that shows exactly what coverage you get at any sample size — and generates a stakeholder-ready explanation on the spot.

**[Try it live →](https://dekic648.github.io/sample-size-negotiator/)**

## What it does

UX researchers constantly face the question: *"Can't we just test with fewer people?"* This tool turns that conversation into a data-driven negotiation.

Given your study parameters, it calculates:
- **Recommended participant count** for your target coverage
- **Actual coverage %** at that sample size
- **Marginal gain** from adding one more participant
- **Coverage loss** from running with fewer participants
- **A ready-to-paste stakeholder script** explaining the trade-off

Includes a coverage curve chart showing diminishing returns visually.

## Method

- **Formative studies**: Uses the binomial probability model `P(discover) = 1 − (1 − p)^n` where p is the expected problem occurrence rate
- **Summative studies**: Uses the standard margin-of-error formula for proportions at 95% confidence

Based on Sauro, J. & Lewis, J.R. (2016). *Quantifying the User Experience* (2nd ed.). Morgan Kaufmann.

## License

MIT
