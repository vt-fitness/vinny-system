---
name: vinny-research
description: |
  Generate creative content ideas cho Vinny Tran fitness coaching channel với
  strategic 40/60 mix (Growth + MOF/BOF). Skill operates INDEPENDENTLY using
  multiple sources, không 100% dependent on Reference Library.
  
  PRIMARY GENERATION SOURCES (always available):
  - Skill creative principles (hook techniques, format patterns)
  - Story Bank (Vinny authenticity, ID: 354466d8-c3ad-816e-8a6a-fb2447b7b84a)
  - Web search (cross-niche viral patterns, international creators)
  - Notion Idea Bank history (avoid recent duplicates)
  
  OPTIONAL SUPPLEMENT (Reference Library):
  - Anti-duplication safeguard
  - Pattern inspiration when entries exist
  - Skill works fine if Reference Library empty
  
  Audience MIXED:
  - Primary segment: Single nam Việt-American 25-30 (Vinny's peers)
  - Secondary segment: Married/family nam Việt-American 30-45 (clients)
  - Both: làm 2 jobs, làm nail/IT đêm/restaurant/văn phòng IT
  
  Strategic content mix (40/60):
  - 40% GROWTH: viral potential, broader appeal, format-agnostic, cross-niche
  - 60% MOF/BOF: trust, authenticity, vulnerability, authority, coaching connection
  
  Trigger when user requests:
  - "research ideas tuần này" / "weekly research"
  - "tìm content angles fresh" / "đề xuất ideas mới"
  - "vinny-research" (explicit invoke)
  - "ideas cho [topic/pillar]"
  - "growth content ideas" / "MOF ideas" / "BOF ideas"
---

# Vinny Research Skill v2.3 — Creative Strategist (Independent + Anti-Duplication)

## ARCHITECTURE PRINCIPLE (NEW v2.3)

**Skill is CREATIVELY INDEPENDENT.** Reference Library is supplementary, not required.

```
PRIMARY SOURCES (always used):
  ├── Skill creative principles
  ├── Story Bank (Vinny authenticity)
  ├── Web search (trends, international creators)
  └── Idea Bank history (recent batch)

OPTIONAL SUPPLEMENT:
  └── Reference Library (anti-duplication check + pattern inspiration)
       ├── If empty → skip check, no penalty
       ├── If duplicate found → flag for user choice
       └── If pattern relevant → optional inspire variation
```

→ **Skill generates quality ideas regardless of Reference Library state.**

---

## STEP 0 — STORY BANK CONTEXT (REQUIRED)

Before generating ANY ideas, query Notion Story Bank:
- **Story Bank Page ID:** `354466d8-c3ad-816e-8a6a-fb2447b7b84a`
- **Title:** "📖 Vinny's Personal Story Bank — Source of Truth"

Read sections relevant to current request:
- For Growth ideas → "Categorized for Content Use → Growth Hooks"
- For MOF ideas → "Categorized for Content Use → MOF Connection"
- For BOF ideas → "Categorized for Content Use → BOF Authority" + "Client Transformations Bank"
- For voice grounding → "Vinny's Writing Voice Patterns"

**Story Bank is REQUIRED.** Skill MUST reference real Vinny stories.

---

## VINNY'S ACTUAL BACKGROUND (CORE FACTS - NEVER VIOLATE)

**Personal:**
- Age: 29 (turning 30 in November 2026)
- Marital status: SINGLE
- Children: NONE
- Location: Pompano Beach, Florida
- Came to US: 2013, age 13-14 (NC first, FL since ~2015)
- Building 3 businesses: Mission Coaching, Mission Garage (2024), content creation

**Coaching credentials:**
- 7+ years experience (LA Fitness → private → online)
- Reached Master Trainer at LA Fitness
- Helped 100+ Vietnamese-American men transform
- Specializes: anh em làm 2 jobs (nail/IT đêm/restaurant)

**Stories Vinny CANNOT tell:**
- ❌ Being a dad / having kids
- ❌ Marriage / wife stories
- ❌ Pre-2013 US life (Vinny arrived 2013)
- ❌ Family stories beyond Story Bank
- ❌ Specific client names beyond anonymized format

---

## AUDIENCE TARGETING — DUAL SEGMENT

### Segment A: Vinny's peers (Primary - first-person voice)
- Single nam Việt-American 25-30
- Voice: "Mình", "lúc mình", "tuần trước mình"
- Personal experiences from Story Bank

### Segment B: Coaching audience (Secondary - "anh đi trước" voice)
- Married nam Việt-American 30-45 with family
- Voice: "Có anh em mình coach...", "Một bạn client..."
- Pull from Client Transformations Bank
- NEVER first-person family stories

### Universal:
- Fitness science, mythbusting
- Either voice OK depending on framing

### Distribution per batch:
- ~30% Segment A first-person
- ~40% Segment B third-person
- ~30% Universal

---

## STEP 1 — DETECT MODE + SEGMENT MIX

### Default mix: 40% Growth / 60% MOF+BOF

### MODE A: Growth-focused (40%)
**Signals:** "viral", "growth", "kéo audience mới", "trend", "fresh format"
**Goal:** Bring new eyes, build trust
**Format scope:** ANY (talking head, B-roll, read caption, trend remix, POV, silent)
**Topic scope:** ANY fitness-related (training, form, nutrition, lifestyle, mindset)
**Source scope:** International creators OK, cross-niche viral patterns OK

### MODE B: MOF-focused (~40% of MOF+BOF)
**Signals:** "connection", "authenticity", "story", "vulnerability"
**Goal:** Trust + relatability
**Voice:** First-person Vinny stories OR third-person client struggles

### MODE C: BOF-focused (~20% of MOF+BOF)
**Signals:** "convert", "coaching", "warm lead", "DM coaching"
**Goal:** Warm followers → coaching client
**Voice:** Third-person client transformation OR first-person coaching philosophy

### MODE D: Hybrid (default)
Default 40/60 split across batch

---

## STEP 2 — PRIMARY SOURCE GENERATION (CORE WORKFLOW)

Generate ideas using primary sources. This is the PRIMARY pathway, không depend on Reference Library.

### 2A. Web Search Research

**For Vietnamese creators:**
- "viral fitness Vietnamese creator [year]"
- "[topic] Việt-American fitness"
- Cultural moments (Tết, family BBQ, Memorial Day, Vu Lan)

**For international creators (KEY v2.3):**
- "viral fitness reels [topic] [year]"
- "fitness creator hooks [year]"
- "[trend name] fitness adaptation"
- Cross-niche viral patterns

**For workplace context:**
- Nail salon industry trends
- IT layoffs / remote work health
- Father/family balance content

### 2B. Story Bank Mining

Pull stories matching mode + segment:
- Growth → ⭐ marked moments (high viral potential)
- MOF → Vulnerability sections (lost period, struggles)
- BOF → Client Transformations Bank + authority moments

### 2C. Idea Bank Recent Check

Query Notion Idea Bank last 20-30 entries to:
- Avoid topic duplication within recent batches
- Identify untouched patterns/pillars
- Maintain content diversity

### 2D. Synthesize Generation

Apply Vinny's DNA + research findings to generate 5-7 ideas.

---

## STEP 3 — REFERENCE LIBRARY CHECK (OPTIONAL, NEW v2.3)

**This step is OPTIONAL. Skip gracefully if Reference Library empty.**

### 3A. Query Reference Library

Query Notion for Reference Library entries:
- Match generated ideas vs existing entries
- Match criteria:
  * Pillar overlap (e.g. both Mind/Story)
  * Audience segment match (A vs B)
  * Hook structure similarity
  * Topic theme overlap

### 3B. Score similarity

For each generated idea, score similarity vs Reference Library entries (0-100%):

```
0-39%: Unique → no flag, proceed normally
40-69%: Near-duplicate → soft flag, suggest variation as option
70-100%: Duplicate → hard flag, present user choice
```

### 3C. User Choice Flow (when duplicate detected)

When idea scores ≥70% similarity vs Reference Library entry:

**Output flag in batch summary:**

```
⚠️ DUPLICATE DETECTED on Idea #N

Generated: "[Idea title]"
Similar to: "[Reference Library entry title]"
Match score: X%
Match reasons: [pillar/segment/hook/topic overlap]

Vinny chọn:
A. Skip this idea → mình generate alternative idea
B. Variation angle → mình generate different angle on same topic
C. Proceed anyway → keep as-is

Reply with letter A/B/C để mình proceed.
```

### 3D. If Reference Library empty

```
ℹ️ Reference Library empty / no relevant entries
Anti-duplication check: SKIPPED
Proceeding with primary generation only.
```

→ No quality penalty. Skill output identical to non-Reference flow.

---

## STEP 4 — IDEA EVALUATION CRITERIA

For each idea, evaluate 4 dimensions:

### 1. Growth Potential (1-10):
- Hook strength
- Viral mechanics
- Cross-platform fit
- Shareability
- Cross-niche application

### 2. Conversion Potential (1-10):
- Filter quality
- Trust building
- Pain point depth
- Soft CTA opportunity
- Story Bank ground truth

### 3. Vinny-Fit (1-10):
- AUTHENTIC to Vinny's actual life (Story Bank verified)?
- Audience-specific?
- Cultural relevance?
- Differentiates from generic?

### 4. Production Effort (1-3):
- 1 = Talking head / read caption
- 2 = B-roll + voiceover / trend remix / POV
- 3 = Cinematic / multi-scene

---

## STEP 5 — GENERATE 5-7 IDEAS

For each idea, output structure:

```
### Idea N: [Catchy title]

**Hook angle:** [Hook ngắn, < 12 chữ]

**Mode:** Growth | MOF | BOF | Hybrid

**Segment:** A (peers, first-person) | B (clients, third-person) | Universal

**Voice approach:** First-person Vinny | Third-person client | Cultural observation | Universal explainer

**Story Bank reference:** [Specific section/quote/client]
- Example: "Story Bank §7 (Lost Period → COVID Reset)"
- Example: "Client Transformations Bank #2 (Anh Đ nail tech -41lbs)"
- "N/A" if Universal/educational

**Format:** [Talking head / B-roll / Read caption / Trend remix / POV / Cinematic]

**Reference Library status:**
- ✅ Unique (no duplicate detected)
- ⚠️ Near-duplicate ([Reference Library entry], X% match) — variation suggested
- 🚫 Duplicate ([Reference Library entry], X% match) — user choice required
- ℹ️ Library empty (check skipped)

**Why this could work:** [Reasoning - cite Story Bank if applicable]

**Scores:**
- Growth Potential: X/10
- Conversion Potential: X/10
- Vinny-Fit: X/10
- Production Effort: X/3

**Pillar:** Mind | Nutrition | Training | Story | Culture

**Why now:** [Cultural moment / trend reason]

**Recommendation:** [Ship priority + rationale]
```

---

## STEP 6 — BATCH SUMMARY

```
## Batch Summary

**Mix breakdown:**
- Growth-focused: X ideas (target ~40%)
- MOF-focused: Y ideas
- BOF-focused: Z ideas

**Segment distribution:**
- Segment A (peers): X
- Segment B (clients): Y
- Universal: Z

**Format diversity:**
- Talking head: X
- B-roll: X
- Read caption: X
- Trend remix: X
- Other: X

**Story Bank coverage:**
- Sections referenced: [list]
- Client Transformations referenced: [Anh letters]
- Direct quotes potential: [list]

**Reference Library status:**
- ✅ Unique ideas: X
- ⚠️ Near-duplicates flagged: Y
- 🚫 Duplicates requiring user choice: Z
- ℹ️ Library empty: [yes/no]

**🚫 USER CHOICE REQUIRED:**
[List ideas requiring Vinny decision A/B/C]

**Top recommended (assuming Vinny resolves duplicates):**
1. Idea #X — [why]
2. Idea #Y — [why]
3. Idea #Z — [why]

**Patterns observed in research:**
- [Pattern 1]
- [Pattern 2]

**Anti-patterns avoided:**
- [Patterns previously overused]
```

---

## STEP 7 — HANDLE USER CHOICE RESPONSE

If user replies với A/B/C cho duplicate idea:

### Choice A: Skip
```
Skip Idea #N "[title]" → Generate alternative idea
- Alternative direction: [different pillar/angle/segment]
- New idea generated: "[New idea title]"
- Updated batch reflects swap
```

### Choice B: Variation angle
```
Generate variation on same topic with different angle:
- Original duplicate: "[Reference X angle]"
- New variation: "[Different approach to same topic]"
- Format/segment shift to differentiate
```

### Choice C: Proceed anyway
```
Keep idea as-is despite duplicate flag
- Note in Idea Bank: "Intentional duplicate per Vinny choice"
- Variation might emerge in script generation (vinny-script v1.3 step)
```

---

## STEP 8 — SAVE TO NOTION IDEA BANK

After user resolves duplicates (or no duplicates), save final ideas:

- Database: Idea Bank (`34d466d8-c3ad-8001-bafb-000b62f811ba`)
- Title, Status, Source, Pillar, Mode, Hook angle, Scores, Format, Segment
- Story Bank Reference field
- Reference Library Status field (Unique/Variation/Skipped/Empty)

---

## STEP 9 — TELEGRAM SUMMARY

```
Sáng nay đã research [N] ideas mới (mix: X% Growth / Y% MOF+BOF):

Top 3 recommend:
1. [hook] (G:X C:Y V:Z) — [Mode] — [Format] — [1-line why]
2. ...
3. ...

Story Bank pull:
- [Section/Story used]
- [Client transformation referenced]

Reference Library check:
- Unique: X ideas
- Duplicates flagged: Y (require Vinny choice)
- Library empty: [yes/no]

Patterns đang hot:
- [pattern]

Full ideas → Notion Idea Bank.
[If duplicates flagged] Resolve duplicates first: Reply A/B/C cho Idea #N
[If no duplicates] Ship Top 3? Reply: 'Generate scripts cho idea 1, 2, 3'
```

---

## CREATIVE PRINCIPLES — Idea generation levers

### Hook techniques
- **Pattern interrupt:** Unexpected opener
- **Number-led:** "80% of guys làm 2 jobs..."
- **Counter-conventional:** "Đếm calo không hiệu quả..."
- **Story opener:** "3 năm trước mình..." (Story Bank)
- **Bold claim:** "Đây là sự thật mà gym brokie không nói..."
- **POV/visual:** "Anh em IT ca đêm, 2 AM..."
- **Question hook:** "Tại sao client mình giảm 41lbs trong 5 tháng?" (Client Bank)
- **Quote provocation:** "Anh đó nói: 'Mày sẽ không bao giờ kiếm cao hơn anh'" (Story Bank §3)

### Storytelling angles by segment

**Segment A (Vinny's first-person from Story Bank):**
- Pre-30 identity reflection
- Single life balance
- Building 3 businesses
- 2013 NC arrival underdog
- Self-taught fitness journey
- Drop out college
- 2019 lost period

**Segment B (third-person clients - Client Transformations Bank):**
- Anh Đ nail tech transformation
- Anh V family man 6-pack
- Anh T DIY-failure → flexibility
- Family man stories anonymized

**Universal:**
- Fitness science explainers
- Mythbusting
- Cross-niche pattern adaptation

### Direct response angles
- "If you want X, do Y"
- Mechanism reveal
- Mythbusting
- Specific advice
- Counter-conventional truth

### Cultural angles
- Family dynamics (third-person)
- Workplace context (nail/IT/restaurant)
- Generation gap
- Immigrant experience
- Florida + Việt-American specific

### Visceral angles
- POV / silent film
- Visual metaphor
- Reaction / commentary
- Read caption format

### Cross-niche viral patterns (KEY v2.3)
- Lifestyle creator → fitness application
- Business creator → coaching authority
- Mental health → fitness vulnerability
- Food creator → meal prep
- Cultural commentary → Việt-American takes

---

## ANTI-PATTERNS

- ❌ Generic motivation
- ❌ Quick fix promises
- ❌ Tao/mày
- ❌ "Việt kiều"
- ❌ Politics / religion / finance flex / women stereotypes
- ❌ Personal attacks on creators
- ❌ Ideas requiring Vinny BỊA stories không có trong Story Bank
- ❌ Stories with timeline impossible (Vinny born ~1996)
- ❌ Same Pillar 7 days in row
- ❌ Same hook formula 3+ times in batch
- ❌ Coaching CTA in 100% ideas
- ❌ All talking head batch
- ❌ Ideas without Story Bank reference for MOF/BOF
- ❌ **NEW v2.3: Auto-skip duplicates without user choice**
- ❌ **NEW v2.3: 100% dependency on Reference Library**

---

## EVOLUTION — Update mỗi quý

Q1 review (Tuần 12):
- Patterns winning từ Analytics → strengthen reasoning
- Anti-patterns mới → add
- Cross-niche patterns discovered → add
- Cultural moments calendar → add seasonal awareness
- Story Bank new chapters → integrate
- Reference Library winning patterns → bias generation
- Format performance data → recalibrate
- User choice resolution patterns → optimize duplicate handling
- Bump version: v2.3 → v2.4 → v3.0
