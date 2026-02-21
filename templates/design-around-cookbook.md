# Design-Around Cookbook
TrollProof Playbook – Infringement Shield

**Goal:** Practical, founder-level guide to tweak your product/feature so it **avoids** matching patent claims — even obvious or broad ones.
No lawyer needed for early pivots. Focus on changing **at least one essential element** of a claim.

Use this when your DIY scan flags a worrying patent.
Time: 30–90 min per potential hit.

**Core Principle (Golden Rule):**
To avoid literal infringement → omit **at least one** element from every independent claim.
To avoid Doctrine of Equivalents → make the change **substantially different** in function/way/result.

**Step-by-Step Cookbook**

1. **Identify the Threatening Claim** (5 min)
   - Copy the broadest independent claim (usually claim 1).
   - Break it into numbered elements:
     Example claim: "A method comprising: 1. receiving user input data; 2. processing with AI model; 3. generating personalized output; 4. displaying output to user."
     → Elements: [1] receive data, [2] AI process, [3] generate personalized, [4] display.

2. **Map Your Current Implementation** (5 min)
   - For each element: Does your product do **exactly** this?
     - Yes → Must change it.
     - No → Safe on that element.

3. **Quick Design-Around Options** (pick 1–2 per element)
   Choose changes that keep core value but break claim match.

   **Category A: Remove / Omit Element**
   - Drop [4] display → output via voice/audio only (TTS)
   - Skip [3] personalization → use static/default templates

   **Category B: Change How Element Works**
   - Replace [2] AI model → switch from ML to rule-based/heuristic logic
   - Change [1] receiving data → use pre-defined templates instead of user input

   **Category C: Add Extra Step / Limitation**
   - Add manual review/approval before [3] generation
   - Require multi-user input for [1] data collection

   **Category D: Switch Tech Paradigm**
   - From generative AI → curated database lookup
   - From real-time processing → offline/batch mode
   - From cloud AI → local/on-device model (different jurisdiction risks)

   **Category E: Narrow Scope / Niche Twist**
   - Limit to specific user group (e.g. only non-verbal learners)
   - Use different input type (voice vs text vs gesture)

4. **Validate the Workaround** (10 min)
   - Re-read the claim: Does your new version still hit **every** element?
     - If yes → try another change.
   - Gut-check equivalents: Is your version "substantially the same" in function/way/result?
     - Different way/function/result = stronger defense.

5. **Document the Pivot** (5 min – critical for defense)
   - Write dated note:
     - "Reviewed US Pat. 12,345,678 claim 1 on [DATE]"
     - "Changed [element X] from [old] to [new] to avoid match"
     - "New implementation: [brief description]"
   - Timestamp: Git commit, screenshot, Notion entry.

6. **Common 2025–2030+ AI/Software Design-Around Patterns**
   - Generative prompt → rule-based template filling
   - Deep learning model → symbolic AI / decision tree
   - End-to-end neural net → modular pipeline with human-in-loop
   - Cloud inference → on-device edge computing
   - Real-time adaptation → periodic batch updates
   - User-specific model → shared base model + lightweight fine-tune

7. **Red Flags to Watch For**
   - Claim uses functional language ("means for X") → harder to design around
   - Very broad/abstract claim → likely §101 Alice vulnerable (note for later)
   - Patent owned by NPE/troll → pivot faster, document heavily

**Quick Wins Table**

| Threatening Element          | Easy Design-Around Options                  | Impact on UX/Value |
|------------------------------|---------------------------------------------|---------------------|
| "AI processing"              | Rule-based logic, lookup table              | Low–Medium          |
| "Personalized generation"    | Curated templates + user overrides          | Low                 |
| "Receiving dynamic input"    | Pre-set profiles / defaults                 | Medium              |
| "Real-time output"           | Batch / offline generation                  | Medium              |
| "Displaying to user"         | Voice output, export to file                | Low                 |

**Final Checklist**
- [ ] Changed at least one element per independent claim
- [ ] Documented pivot with date + rationale
- [ ] Tested new version with users (verify value intact)
- [ ] Re-scan in 3 months (new filings happen fast)

Design-arounds are cheap insurance.
One small pivot today can save six-figure fights tomorrow.

Stay creative. Stay free.