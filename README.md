# ♟ AI Feature Validator

**Is your AI feature actually ready to build?**

Most AI features fail not because the model is bad — but because no one asked the right questions before building. This tool scores your AI feature idea across 3 layers used by senior AI product leaders, and gives you an honest read on where it stands.

---

## The 3-layer framework

**Layer 1 — Technical truth**
Can this actually be built reliably on real data? Do you have a fallback when the model fails?

**Layer 2 — Behavioral truth**
Will this change what users actually *do* on day 30? Or just impress them on day 1?

**Layer 3 — Business truth**
Does this move a metric your business actually tracks — at sustainable unit economics?

Most AI pilots fail at Layer 2. Most AI products fail at Layer 3.

---

## Try it

**Streamlit Cloud (recommended)**

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io)

1. Fork this repo
2. Go to [share.streamlit.io](https://share.streamlit.io) and connect your fork
3. Add your `ANTHROPIC_API_KEY` in the Streamlit secrets panel
4. Deploy

**Run locally**

```bash
git clone https://github.com/ibmlachezar/ai-feature-validator
cd ai-feature-validator

pip install -r requirements.txt

export ANTHROPIC_API_KEY=your_key_here
streamlit run app.py
```

---

## Who this is for

- AI startup founders evaluating feature ideas before committing engineering time
- Product managers running AI feature reviews
- Engineering leads pressure-testing assumptions before a sprint
- Anyone who has ever shipped an AI demo that nobody used

---

## What you get

- A score (0–100) for each of the 3 layers
- A plain-English verdict: **Ship it / Validate First / Redesign**
- The top risk in each layer
- 3 specific next steps you can act on this week

---

## Built by

**Lachezar Atanasov** — Head of AI Product, AI startup founder, and advisor to multiple AI companies. Previously shipped frontier GenAI products at Google scale.

→ [lachezaratanasov.com](https://lachezaratanasov.com)
→ [LinkedIn](https://www.linkedin.com/in/lachezar-atanasov198/)

---

## Contributing

Found a gap in the framework? Open an issue or submit a PR. The framework improves with real-world use.

## License

MIT — use it, fork it, adapt it for your team.


---

> Last updated: May 2025
