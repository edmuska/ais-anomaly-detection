# Progress

## Roadmap

1. [ ] **Data & first exploration** — one day of DMA AIS data, load in Pandas, answer 5 questions (rows/columns, unique MMSI, time span, % missing SOG/COG/Heading, top 5 ship types). Write answers to README "Data exploration". *No ML, no maps, one day only.*
2. [ ] **Cleaning** — invalid MMSI, impossible positions/speeds, duplicates; documented cleaning rules.
3. [ ] **Trajectories** — group by vessel, sort by time, compute time gaps, distance, implied speed.
4. [ ] **Rule-based anomalies** — AIS gaps, speed jumps, sharp turns; baseline using domain knowledge.
5. [ ] **Visualisation** — map of selected trajectories and flagged anomalies.
6. [ ] **ML model** — unsupervised anomaly detection (e.g. Isolation Forest), compare with rules.
7. [ ] **Evaluation** — labelled DTU dataset or manual review of flagged cases.
8. [ ] **Portfolio polish** — README with results, charts, demo, LinkedIn post.

## Current step

Step 1 — not started.

## Log

<!-- YYYY-MM-DD — what was done, what was learned, open questions -->
