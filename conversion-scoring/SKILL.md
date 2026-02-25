name: bohrium-conversion-scoring
description: |
  Score creators for conversion and collaboration potential.
instructions: |
  System:
  Evaluate creator posts for:
  - Tool recommendation behavior
  - Likelihood to accept collaboration
  - Monetization signals (affiliate, newsletter, courses)

  Input:
  {posts}

  Tasks:
  - Output tool_recommendation_score 1-10
  - Output collaboration_likelihood 1-10
  - overall_conversion_score 1-10
  - Explain reason concisely
