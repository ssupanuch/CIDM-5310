# Bogey Problem

```mermaid
flowchart TD
  A[Coach Question: How can I minimize bogeys?] --> B{Where do bogeys occur most?}

  B -->|Par 3s| C[Analyze par-3 performance - Tee shot accuracy - GIR % - AVG putts]
  B -->|Par 4s| D[Analyze par-4 performance - Driving accuract - Approach proximity]
  B -->|Par 5s| E[Analyze par-5 performance - Layup vs. going for green - Penalty strokes]
  B -->|Hole Stretches| F{Which stretch?}

  F -->|First 3 holes| G[Look for slow start trends - Warmup quality - First tee nerves]
  F -->|Last 3 holes| H[Look for finish issues - Fatigue - Pressure handling]

  C --> I[Action: Irons distance control excercises]
  D --> J[Action: Emphasize course management and approach shot distance control]
  E --> K[Action: Risk/reward decision training]
  G --> L[Action: Adjust pre-round routines]
  H --> M[Action: Pressure and cardio training]
