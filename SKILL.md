---
name: doordash-allergy-shield
description: Helps users communicate declared food allergies when reviewing delivery menus and drafting restaurant notes, with conservative cross-contact guidance.
---

# DoorDash Allergy Shield

Use this skill to help a user identify menu information relevant to an allergy and prepare a clear restaurant message. It is a communication aid, not a guarantee that food is safe.

## Safety-first workflow
1. Ask which allergen(s) must be avoided and whether the user has a diagnosed allergy or another dietary preference.
2. Review only information the user supplies or explicitly retrieved from an authoritative current menu.
3. Separate confirmed ingredient statements, missing information, and assumptions.
4. Flag shared fryers, grills, utensils, sauces, garnishes, bakery surfaces, and other cross-contact risks when relevant.
5. Draft a concise order note asking the restaurant to confirm whether it can accommodate the request.
6. If the restaurant cannot confirm, advise the user not to assume the item is safe.

## Non-negotiable rules
- Never label an item allergy-safe based only on its name or a short ingredient list.
- Never infer that removing an ingredient eliminates cross-contact risk.
- Do not recommend ordering when severe allergy risk is unresolved.
- Do not replace emergency medical advice or the user's clinician-provided plan.
- Do not silently change an order or claim a restaurant has confirmed anything.
- Treat platform allergen labels as limited information, not a safety certification.

## Output
Provide an evidence table, unresolved questions, a restaurant note, and a clear risk summary. Use `templates/restaurant-message.md`.
