# Swish, reimagined: teardown → PRD → working prototype

**Live prototype:** https://aasthaghub.github.io/swish-concept/
**PRD:** https://aasthaghub.github.io/swish-concept/prd.html
**Teardown (PDF):** [teardown.pdf](teardown.pdf)

> Independent concept by Aastha Gulati, Oct 2026. Not an official Swish product and not affiliated with Swish.
> Dishes, prices and macros in the prototype are illustrative. Review quotes come from public Play Store 1-star reviews.
> No internal Swish data was used.

## Why
I'm the user Swish is built for: Bengaluru, corporate job, protein-conscious, orders most lunches and many late nights.
So I used the app like one and wrote down every place I slowed down or gave up. Then I built what I'd change.

## What I found
- **Discovery:** "Protein Rich" sat in row 2, position 4, behind a side-scroll, on a tile that blended into its background. Macros only appeared after opening each dish.
- **Trust and recovery:** a 3-month pull of 1-star Play Store reviews showed 6 repeating bugs: silent cancels after up to an hour, payment taken but no food or refund, "Delivered" when nothing came, promised freebies missing, near-absent support (3 of 6 reviews), and "View dish details" missing in half the categories.
- **Context:** the home didn't know who was opening it or when. During Navratri, a highlighted dinner row showed non-veg dishes.

## What the prototype shows
Toggle **Before (today) / After (my fixes)**, time of day, persona (eats clean / 11 PM pizza person), new vs returning user, and festival mode.

| Area | Changes |
|---|---|
| Recovery and trust | 5-minute late-order decision (wait, swap kitchen, instant refund) · auto-refund in 30 s on failed payment · OTP delivery + map-pin check before dispatch · freebies as real SKUs with 2× credit if missing · support hub with instant fixes and a 2-minute WhatsApp SLA |
| Discovery | Protein Picks pinned at lunch and dinner · high-contrast protein tile · macros on every dish card · "View dish details" everywhere |
| Context | Meal Clock (home changes by time slot and persona) · Navratri mode (Strict vrat / Veg / + Non-veg) · mood pills · trending within 1 km · budget zone from order history |
| Speed | "Order again" at the very top · 1-tap order with saved pin + UPI · Top 3 and "Pick for me" for new users |
| Visual | One green family + one warm accent · slim promo strip instead of a giant banner · Menu button that stops covering content |

## PRD
Five workstreams (Recovery & trust, Protein discovery, Personalisation & context, Speed of ordering, Visual system), an experiment plan with one primary metric and one guardrail per test, a 12-week roadmap, risks with mitigations, and open questions for the team. Baselines are left blank on purpose, because I don't have Swish's internal data.

Built with Claude as a coding partner.
