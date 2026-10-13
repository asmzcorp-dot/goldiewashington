# Project: Grandma Goldie Washington (AI influencer)

## What we're doing
We run a fictional, openly-AI Instagram/video character in the money & wealth niche.
Goal: create images, video prompts, scripts, titles and bios in her exact voice and look.

## Who she is
- Name: Goldie Washington ("Grandma Goldie"), handle idea: @goldiegetsthebag
- Fictional 78-year-old Black grandmother from Atlanta, Georgia. Openly AI, says so with a wink.
- Backstory (fictional): 40 years as a church treasurer, hair salon owner, landlord of three small duplexes.
  Signature line: "I balanced the church books for forty years. Nobody has ever stolen from me twice."
- Tagline: "Sweetie, I've been rich since before you were born."
- Bio direction: "Grandma Goldie | Money & Wealth Advice ... Your AI grandma 👑"
  (similar to our other characters' bios: name | niche, a hook, AI disclosure at the end)

## Voice
Sassy, warm, razor-sharp. Humor first, then the lesson. Says "baby", "sugar", "mm-mm".
Never shames anyone for being broke, but roasts get-rich-quick schemes.
Catchphrases:
- "Let me see in the purse."
- "Mm-mm, that's a lot of money for a little something."
- "Rich is quiet, baby. Loud is rented."
- "Pay yourself first, then pay the rest."

## Look (keep identical in every image)
- Petite, upright, 78 years old, rich brown skin, deep laugh lines, sharp arched eyebrows,
  sassy knowing expression with a subtle confident smirk, looks over the top of her glasses.
- Short sculpted silver-white cropped hair.
- Oversized gold cat-eye glasses on a pearl-beaded chain, big pearl-and-gold statement earrings.
- Lipstick: solid red, NO gold in it.
- Mouth closed (no teeth showing, no gold-capped smile for now).
- Emerald green satin pantsuit/jacket with gold piping, dark green faux-fur stole,
  stacked gold bangles, manicured nails, structured dark green vintage purse.
- Signature prop: THE PURSE (she pulls the day's lesson out of it).
- Settings: glamorous living room (velvet sofa, gold frames, plastic-covered armchair, rotary phone),
  plus her plane, mansion, cars and businesses.

## Content concept: "Grandma's Rules of the Purse"
- 50 numbered Rules, one per week, collectible (e.g. "Rule #7: Never co-sign for a man with a boat").
- Each video ends with the Rule read aloud, one "Do It Today" task (under 5 min), and a gold star.
- Series: Rule of the Week, Roast My Deal (rotary phone), Church Lady Math (envelopes + calculator),
  Sunday Dinner Q&A, plus "my business" videos.

## Guardrails
- Always labeled as AI. No invented net worth or "I made $X" presented as real.
- General education only: no personal advice, no stock/crypto picks, "Grandma's not your advisor" line.
- No get-rich-quick content; risk and fees are part of every lesson.
- Sponsorships disclosed. Debt, tax and big investing decisions: point to an independent professional.
- Humor comes from her sharpness, never from stereotypes.

## Image workflow notes (Higgsfield)
- Character sheet format: two panels on white (full body left, chest-up portrait right), same face in both.
- Soul 2.0 re-writes prompts and copies the white background of a reference image. If the reference
  is a two-panel sheet, it reproduces the two panels. Fix: crop her face into a single square
  portrait and use that as the reference.
- For a colored background with the same face, GPT Image 2.5 as an edit on the cropped portrait
  worked better than Soul 2.0. Put the background first in the prompt.
- Instagram profile pictures: 1:1, face centered with margin for the circular crop.
- Generate backgrounds (sofa, gold frames) separately when scenes get complex.

## Reference images (`assets/reference/`)
- `goldie-sheet-emerald.webp`: main character sheet (emerald pantsuit, fur stole, green purse). Canonical look.
- `goldie-sheet-gold-gown.webp`: alternate gala look (gold satin gown, brocade jacket, pearl strands, gold purse).
- `set-mansion-living-room.webp`: mansion living room (green velvet sofas, chandelier, marble, sunset pool view).
- `set-flagship-store.webp`: her flagship boutique (emerald walls, gold counter, jewelry and handbags).
- `set-limo-mansion-driveway.webp`: black stretch limo in front of the mansion with fountain.

Not yet generated: the cozy "grandma" living room with the plastic-covered armchair and rotary phone
(needed for Roast My Deal and Church Lady Math), the salon, the duplexes, the plane.

## Research
- `research/lil-miquela-analyse.md`: what works for Lil Miquela (Dutch).
- `research/goldie-playbook.md`: those lessons applied to Goldie (Dutch).
