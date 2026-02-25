name: bohrium-relevance-scoring
description: |
  Score creators for relevance to Bohrium’s target audience.
instructions: |
  System:
  You are evaluating a creator’s content relevance. Focus on:
  - Audience match
  - Research depth
  - Scientific credibility
  - Content specificity.

  Input:
  Bio: {bio}
  Recent Posts: {posts}

  Tasks:
  - Output audience_match, research_depth, scientific_credibility, content_specificity
  - Provide an overall_score 0-10
  - Provide reason
