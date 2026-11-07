# Prompt Logic

## Prompt framework: RTCFT + Rules
| Part | Meaning |
|---|---|
| Role | Who the AI should act as |
| Task | What to produce |
| Context | Business, product, audience, platform |
| Format | Exact structure of the output |
| Tone | Voice of the ad |
| Rules | What to avoid |

## Prompt 1: Hooks
```
Role: You are a UGC ad copywriter for local businesses in India.
Task: Write 6 scroll-stopping hooks for the same product.
Context: Business: Sweet Crumbs Home Bakery, Salem. Products: custom birthday cakes, cupcake boxes, eggless options. Audience: young adults and families who order cakes for birthdays.
Format: One line per hook, under 15 words, each using a different angle (problem, curiosity, POV, question, budget, tip).
Tone: Real customer talking to a friend. Casual, not salesy.
Rules: No fake reviews, no invented discounts, no "best in Salem".
```

## Prompt 2: Full scripts
```
Role: You are a UGC ad scriptwriter.
Task: Write 3 short-form ad scripts (about 30 seconds each) using the hooks above.
Context: Same business and audience.
Format: Problem -> Solution -> CTA. For each script give: Hook (0-3s), Problem (3-10s), Solution (10-22s), CTA (22-30s), and on-screen text.
Tone: Authentic, spoken, simple English.
Rules: Sound like a real customer, not a company. No unverifiable claims.
```

## Prompt 3: Platform adaptation
```
Task: Adapt Script A for Instagram Reels, Facebook and YouTube Shorts.
Format: For each platform give length, style, caption and CTA.
Rules: Instagram = short and trendy, Facebook = slightly longer and family-friendly, YouTube Shorts = searchable title and a clear first line.
```

## Prompt 4: Captions and CTAs
```
Task: Write 3 captions with a clear CTA for the bakery ads.
Format: 2 to 3 short lines + CTA line + 3 hashtags.
Tone: Warm and friendly.
```

## Refinement prompts used
- "Make hook 1 shorter and more curious."
- "Rewrite the CTA to be clearer: one action only."
- "Make the script sound more like a real customer, less like an advertisement."

## Why this structure works
- **Many hooks first** gives choice, so the strongest opening is picked.
- **Problem, Solution, CTA** keeps the story clear in 30 seconds.
- **Rules line** stops fake claims.
- **Platform prompt** keeps the same idea but changes length and style.

## Refinements applied to the first output
| Refinement | Result |
|---|---|
| "Make hook 1 shorter and more curious." | Hook 1 became "Birthday in two days. No cake. Now what?" |
| "Rewrite the CTA to be clearer: one action only." | Every CTA now asks for one action (DM, message, ask, save). |
| "Make the script sound more like a real customer, less like an advertisement." | Scripts use spoken lines like "Okay, I totally forgot." |

## Review notes
- Removed an unfinished placeholder in Script B and added a creator note instead, so only a real customer's honest opinion is added.
- Added timings to all three scripts.
