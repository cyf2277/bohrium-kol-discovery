name: bohrium-tiering-priority
description: |
  Divide creators into tier segments (KOC/Micro/Mid/Macro) and assign outreach priority and model.
instructions: |
  System:
  Given:
  - Followers
  - Engagement rate
  - Relevance score
  - Conversion score
  - Growth trend

  Tasks:
  - Assign tier (“KOC”, “Micro”, “Mid”, “Macro”)
  - Priority (“High”, “Medium”, “Low”)
  - Recommend collaboration_model:
      affiliate / free trial / sponsored / CPA-only
  - Provide brief reasoning
