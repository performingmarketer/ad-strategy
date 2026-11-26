# Ad Strategy

**AI-Powered Meta Ads Creative Strategist** — a reusable, business-specific Meta Ads creative strategy skill for Claude-compatible skill systems and SKILL.md-based agent environments, plus standalone ChatGPT Custom GPT instructions.

## Package contents

This is **Ad Strategy v1.2**, with 55 example business categories across 10 sectors, a Malayalam/English Hook Formulas library, a Budget-Tier Creative Testing guide, and Post-Click WhatsApp follow-up workflows. Industry suggestions are creative-planning starting points, not Meta targeting taxonomies or guarantees.

- `SKILL.md` — primary skill instructions and discovery workflow
- `references/business-category-library.md` — **55 industry-specific business categories** across 10 sectors, with buyer motivations, creative proof, conversion funnels, and compliance notes
- `references/creative-angle-library.md` — distinct creative concepts, Malayalam/English hook formulas, and business examples
- `references/measurement-and-testing.md` — KPIs, formulas, budget-tier testing guide, and diagnostic guidance
- `references/meta-policy-and-accuracy.md` — truthfulness and policy checklist
- `references/output-templates.md` — Full, Quick, Single Asset, and Review formats (including WhatsApp first-response scripts)
- `examples/education-institute.md` — sample institute strategy
- `chatgpt-custom-gpt-instructions.txt` — paste-ready ChatGPT GPT instructions
- `README.md` — this guide

## Claude use

Where Claude supports custom Skills, upload this ZIP archive using its Skills interface. If your Claude interface does not support uploading Skills, place `SKILL.md` (and the `references` folder) in your project context or paste the standalone instructions as project instructions. Exact controls vary by product and plan.

## ChatGPT use

Use `chatgpt-custom-gpt-instructions.txt` in the Instructions field of a Custom GPT, if that feature is available to you. Upload the files inside `references/` and `examples/` as GPT Knowledge. Alternatively, paste those instructions into a regular chat. In an environment that supports SKILL.md-based agent skills, use the skill folder directly.

## Starter prompts

- “Ad Strategy: Start for my business.”
- “Create a full Meta Ads creative strategy for my education institute in Kerala.”
- “Quick Strategy for a local boutique: WhatsApp enquiries, ₹500/day, Malayalam.”
- “Review these three ad creatives and identify what to test next.”
- “Make only a 60-second Malayalam reel from the strongest problem-based angle.”

## Expected interaction

1. The skill asks for essential business details not already supplied and selects the closest business category (or creates a custom one).
2. It analyzes customer motivations, proof, objections, and conversion goal.
3. It generates meaningfully different creative concepts, scripts/copy, visual directions, and WhatsApp follow-ups.
4. It recommends a budget-fit test and measures qualified business outcomes.

The skill does **not** connect to Meta Ads Manager, publish campaigns, pull account performance, or generate actual videos/images by itself. Those actions require separate integrations/tools.

## Attribution and independence

Developed for **Performing Marketer**. This is an independent educational marketing-planning resource and is not an official product of, endorsed by, or affiliated with Meta, Facebook, Instagram, OpenAI, or Anthropic. Creative outputs require human review, current advertising-policy checks, and verification of business claims before publication.

## Licensing

This project is open source under the [MIT License](LICENSE). Copyright (c) 2026 Performing Marketer. You may use, modify, and redistribute the skill under the terms of that license. The MIT License does not grant rights to use the Performing Marketer name or logos as trademarks, or any third-party materials not owned by the project.
