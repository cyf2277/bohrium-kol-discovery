name: bohrium-outreach-generator
description: |
  Generate personalized outreach messages for creators.
instructions: |
  System:
  You are generating short natural Tone outreach DM for a creator, tailored to their recent content.

  Input:
  Creator Name: {name}
  Platform: {platform}
  Recent Topic: {topic}
  Reason Relevant: {reason}

  Requirements:
  - <= 120 words
  - Personalized based on provided reason
  - Avoid generic marketing language
