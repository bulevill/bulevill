## Hi, I'm Ulises Villarreal

Ten years turning ambiguous business questions into systems that answer them repeatedly: pricing and forecasting in commodity fuels, then marketing and product analytics in consumer credit, covering experimentation, compliance, and the executive measurement infrastructure underneath. Increasingly built with agentic AI rather than by hand.

Alpha Engine is the same instinct off the clock — an options research platform with a real-chain backtester and a live execution engine. Four strategies tested, none funded, and I'd rather say that than show you a curve.

Dopplerganger estimates where an audio recording was made by matching aircraft Doppler curves against ADS-B flight data and terrain. It locates 19 of 24 realistic simulations built from real flight tracks.

Currently looking for **data science / ML and quantitative research** roles.

---

### Selected work

**[Alpha Engine](https://github.com/bulevill/alpha-engine)** — options research platform
· *Python, pandas, NumPy, SciPy, IBKR, FastAPI*
An end-to-end system for testing options strategies: signal research, a backtester priced off
real historical OPRA chains, and a risk-managed live execution engine. I've tested four
strategies against it; two came back negative or null and are retired, and two are still
standing — one gated on drawdown, one on an execution spread I can't currently reach. Neither
has cleared the risk bar I set in advance, so nothing is funded yet and the work continues on
those two constraints. Along the way an independent review found a one-day look-ahead in the
entry signal that had been inflating every headline number, which I fixed and then retired the
affected results rather than restating them.
→ [Full case study](https://github.com/bulevill/portfolio/blob/main/case-studies/alpha-engine.md)

**[Dopplerganger](https://github.com/bulevill/dopplerganger)** — acoustic geolocation from aircraft Doppler curves
· *Python, NumPy, SciPy, DuckDB, geospatial*
Estimates where an audio recording was made by matching small-aircraft Doppler curves against US
ADS-B flight data and terrain. Locates 19 of 24 realistic renders built from real flight tracks; the
detector scores 22/31 on held-out real flyover recordings (previous version 5/31).
→ [Full case study](https://github.com/bulevill/portfolio/blob/main/case-studies/dopplerganger.md)

<!--
Add 2–3 more here as you bring them. Same shape:
  **[Name](link)** — one-line description · *stack*
  Two or three sentences: what it does, and the outcome (including if the outcome was negative).
  → [Full case study](...)
Keep this list to your best 3–4. Drop the weakest when you add a stronger one.
-->

---

### More

📁 **[Portfolio](https://github.com/bulevill/portfolio)** — longer write-ups: the
reasoning, the results, and what went wrong
<!-- 📄 Résumé · 💼 LinkedIn · ✉️ Email — add if you want them public -->

---

<sub>Working on: exit-timing research for a dip-buying strategy, and a short-volatility
earnings signal that's real but currently gated on execution costs.</sub>
