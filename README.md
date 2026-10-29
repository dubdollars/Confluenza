Confluenza
A living AI/macro investment thesis, rebuilt from primary-source interviews and weighted by cross-source confluence.
Confluenza reads long-form interview and podcast transcripts (investors, operators, researchers, strategists), extracts the claims each speaker makes about AI and the macro backdrop, and keeps a scored, auditable thesis that updates every time a new batch of transcripts is added. Edition 21 covers 186 transcripts from 135 distinct voices across 61 scored themes.
Live app: https://dubdollars.github.io/Confluenza/
![Velocity Board](docs/velocity_board.png)
---
How this was built
I'm not a software developer. I designed the scoring method, wrote the rules, and directed Claude (Anthropic's model) to build the app and to process each batch of transcripts against everything read before. Every edition is a full rebuild of the single `index.html` file: I review the new themes, the conviction moves and the changelog entries, send back what I disagree with, and publish when it holds up. Twenty-one editions have shipped since July 2026.
The method is the product. The code is a plain, dependency-free web page so that every number on it can be traced to a rule and a source.
---
What it does
Velocity Board. Themes ranked by how fast conviction is moving, not by its level. The edge is noticing convergence early, so new and accelerating themes sit at the top.
Themes. Each theme carries a conviction score (0–10), the independent voices behind it, a camp (bull / bear / contested / emerging), and an append-only dated changelog so you can see how and why the score moved.
Timeline and Predictions. A catalyst roadmap plus a scorecard of specific, dated claims made by named speakers, tracked to hit or miss.
Watchlist. Tickers and instruments mapped to themes, each with an explicit risk label (core, moderate, speculative) and the contested tail that could break the thesis.
Source X-Ray. A bias check on the library itself: which incentive classes are represented (operators, allocators, sell-side, academics, journalists), which are missing, and which high-conviction themes rest on a single class.
Methodology. How scoring, velocity, confluence, chronology and bias control work, in plain language.
---
The scoring rules
Independent voices, not mentions. One person appearing three times is one voice.
Opposed incentives count double. Agreement between a bull and a bear, or between a vendor and a skeptic, is the strongest signal in the system.
Contested stays contested. Disagreement is shown as a fork, never averaged into a false middle.
Recency and specificity are weighted. Dated, falsifiable claims outrank vibes.
Bear themes are risks, not sell signals, until a named trigger fires.
Every edition is bumped against all prior editions, so the "New Since Last" view shows exactly what moved and why.
---
Technical notes
Single self-contained `index.html` (HTML, CSS and vanilla JavaScript; no build step, no dependencies, no network calls). The data layer is a JavaScript object at the top of the file; the views render from it. Hosted on GitHub Pages. Used/archived state for draft posts persists in the browser only.
---
Disclaimer
Research prototype, not investment advice. Content reflects the biased, self-interested views of the transcript speakers. Tickers are research candidates only; prices and valuations are not live. Do your own diligence.
---
© 2026 Elliott Walter. All rights reserved. Shared for review; not licensed for reuse.
