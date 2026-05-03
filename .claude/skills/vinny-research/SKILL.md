---
name: vinny-research
description: |
  Generate creative content ideas cho Vinny Tran fitness coaching channel với
  strategic 40/60 mix (Growth + MOF/BOF). Synthesize knowledge từ:
  - Cross-niche viral patterns (any niche, applied to fitness)
  - International creators + Vietnamese creators
  - Vinny's authentic life stories (Story Bank reference)
  - Format-agnostic exploration (talking head, B-roll, read caption, trend remix, POV, etc.)
  - Coaching expertise + audience insights
  
  Audience MIXED:
  - Primary segment: Single nam Việt-American 25-30 (Vinny's peers, first-person voice)
  - Secondary segment: Married/family nam Việt-American 30-45 (clients, third-person voice)
  - Both: làm 2 jobs, làm nail/IT đêm/restaurant/văn phòng IT
  
  Strategic content mix (40/60):
  - 40% GROWTH: viral potential, broader appeal, format-agnostic, cross-niche patterns
  - 60% MOF/BOF: trust building, authenticity stories, vulnerability, authority,
    coaching connection, Vinny's personal narrative grounded in Story Bank
  
  Trigger when user requests:
  - "research ideas tuần này" / "weekly research"
  - "tìm content angles fresh" / "đề xuất ideas mới"
  - "vinny-research" (explicit invoke)
  - "ideas cho [topic/pillar]"
  - "growth content ideas" / "MOF ideas" / "BOF ideas" / "trust content"
  
  Do NOT trigger for:
  - Generating actual scripts (use vinny-script instead)
  - General fitness Q&A
  - Editing existing ideas
---

# Vinny Research Skill v2.2 — Creative Strategist (Story-Grounded)

## CRITICAL FIRST STEP — Pull Story Bank context

Before generating ANY ideas, query Notion Story Bank:
- **Story Bank Page ID:** `354466d8-c3ad-816e-8a6a-fb2447b7b84a`
- **Title:** "📖 Vinny's Personal Story Bank — Source of Truth"

Read sections relevant to current request:
- For Growth ideas → "Categorized for Content Use → Growth Hooks"
- For MOF ideas → "Categorized for Content Use → MOF Connection"
- For BOF ideas → "Categorized for Content Use → BOF Authority" + "Client Transformations Bank"
- For voice grounding → "Vinny's Writing Voice Patterns"

**Story Bank is source of truth.** Skill MUST reference real Vinny stories, NOT invent.

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

**Real stories Vinny CAN tell (pull from Story Bank):**
- 2013 NC arrival, self-taught fitness journey
- Hard labor years (electrician helper, pressure washing, construction)
- "Anh không kiếm cao hơn anh" provocation moment (lunch break, ngồi im lặng)
- Drop out college decision (vs Việt parent expectation)
- PT cert moment (mặc đồ dính bụi điện)
- LA Fitness 7 năm buildup
- 2019 lost period → COVID reset hero arc
- Mission origin (TikTok Vietnamese pioneer)
- Multi-business operator (Mission Coaching + Garage)

**Real coaching client stories (Story Bank has 8 anonymized cases):**
- Anh Đ (nail tech, -41lbs in 5 months)
- Anh V (married, 6-pack in 3 months)
- Anh CN (skinny fat, trust rebuild)
- Anh H (-22lbs, flexible diet)
- Anh N (long-term, competition prep)
- Anh T (-37lbs, Diet Break methodology)
- Anh B (-21lbs in 12 weeks)
- Anh D (nail tech lifestyle accommodation)

**Stories Vinny CANNOT tell (anti-hallucination):**
- ❌ Being a dad / having kids
- ❌ Marriage / wife stories
- ❌ Pre-2013 US life (Vinny arrived 2013)
- ❌ Family stories beyond what shared in Story Bank
- ❌ Specific client names beyond anonymized format

---

## AUDIENCE TARGETING — DUAL SEGMENT

### Segment A: Vinny's peers (Primary - first-person voice)
- Single nam Việt-American 25-30
- Building career/wealth/body trong tuổi 20s late
- Approaching 30 milestone identity
- Concerns: balance dating/work/fitness, identity shift pre-30
- Voice: Vinny shares OWN life experiences (first-person)

### Segment B: Coaching audience (Secondary - "anh đi trước" voice)
- Married nam Việt-American 30-45 with family
- Làm 2 jobs, có vợ con, mất shape sau 30
- Concerns: balance family/work/fitness, no time
- Voice: Vinny references coaching client stories (third-person, anonymized)
  - "Có anh em mình coach làm nail tech 8h..."
  - NEVER claim Vinny himself has wife/kids/family

### Content distribution per batch:
- ~30% Segment A first-person (Vinny's own life)
- ~40% Segment B third-person (anh em coaching stories from Story Bank)
- ~30% Universal (fitness science, both segments resonate)

---

## STEP 1 — DETECT MODE + SEGMENT MIX

Read user input để detect priority:

### Default mix (when ambiguous): 40% Growth / 60% MOF+BOF

### MODE A: Growth-focused (40% of batch)
**User signals:**
- "viral", "growth", "kéo audience mới", "broader appeal"
- "trend", "fresh format", "experiment"

**Goal:** Bring new eyes, build trust, broader appeal
**Format scope:** ANY format (talking head, B-roll, read caption, trend remix, POV, silent film, reaction)
**Topic scope:** ANY fitness-related topic (training, form correction, nutrition, lifestyle, mindset, recovery)
**Source scope:** International creators OK (English-speaking), cross-niche viral patterns OK

### MODE B: MOF-focused (Trust building, ~40% of MOF+BOF allocation)
**User signals:**
- "connection", "authenticity", "story", "vulnerability"
- "trust", "relatable", "personal"

**Goal:** Audience feel Vinny's journey, empathize with struggle
**Voice:** First-person Vinny stories OR third-person client struggles
**Source:** Story Bank vulnerability patterns + struggle empathy

### MODE C: BOF-focused (Conversion, ~20% of MOF+BOF allocation)
**User signals:**
- "convert", "coaching", "warm lead", "DM coaching"
- "authority", "credentials", "transformation evidence"

**Goal:** Turn warm followers → discovery call → coaching client
**Voice:** Third-person client transformation OR first-person coaching philosophy
**Source:** Story Bank Client Transformations Bank + Track record evidence

### MODE D: Hybrid (default)
**Trigger:** User chưa specify
**Action:** Default 40/60 split across batch

---

## STEP 2 — RESEARCH SOURCES (EXPANDED)

Use these tools/sources in priority order:

### Priority 1: Story Bank query (MOF/BOF foundation)
- Query Notion `354466d8-c3ad-816e-8a6a-fb2447b7b84a`
- Pull relevant section based on mode
- Identify 2-3 stories fitting current research direction

### Priority 2: web_search (Growth content + trend research)

**For Vietnamese creators:**
- "viral fitness Vietnamese creator [year]"
- "[topic] Việt-American fitness"
- Cultural moments (Tết, family BBQ, Memorial Day, Vu Lan)

**For international creators (NEW in v2.2):**
- "viral fitness reels [topic] [year]"
- "fitness creator hooks 2026"
- "[trend name] fitness adaptation"
- Cross-niche viral patterns Vinny can adapt:
  - Lifestyle creators
  - Business creators
  - Mental health creators
  - Food creators
  - Cultural commentary creators

**For workplace context:**
- Nail salon industry trends
- IT layoffs / remote work health
- Restaurant industry health
- Father/family balance content

### Priority 3: Notion MCP queries
- Idea Bank (last 20 entries) — avoid duplicates
- Reference Library — Vinny's curated patterns + Vinny's own top performers
- Analytics DB (if exists) — winning patterns from past content
- Content Tracker — recently shipped scripts, avoid topic overlap

### Priority 4: Synthesis
- Apply Vinny's Story Bank DNA to research findings
- Cross-reference với cultural moments
- Identify gaps trong what's been done
- Match formats to topics

---

## STEP 3 — FORMAT-AGNOSTIC IDEATION (NEW in v2.2)

For each idea, consider format match. Format options:

### Talking Head (Pillar: Mind/Story)
- Vinny on camera, direct address
- Best for: vulnerability stories, philosophical takes, authority claims
- Production: 1 (low effort)

### B-roll Heavy (Pillar: Training/Nutrition)
- Voiceover + visual demonstrations
- Best for: form corrections, nutrition explainers, mythbusting
- Production: 2 (medium)

### Read Caption Style (NEW format - Pillar: ANY)
- Static visual (Vinny standing, gym scene, food shot)
- Text on screen: "Read caption ⬇️" or specific hook
- Caption holds full content depth
- Best for: complex topics, philosophical content, long-form value
- Production: 1 (low effort)

### Trend Remix (Pillar: ANY)
- Take viral trend from another niche
- Apply fitness/Vinny lens
- Maintain trend's original visual/audio mechanics
- Best for: viral growth, cross-pollination
- Production: 2 (medium - need study original trend)

### POV / Silent Film (Pillar: Culture/Story)
- First-person camera, no talking
- Visual storytelling
- Best for: relatable moments, day-in-life, cultural observations
- Production: 2-3

### Reaction / Commentary (Pillar: ANY)
- Vinny react to viral content / claims / common mistakes
- Best for: hot takes, mythbusting, commentary
- Production: 1-2

### Cinematic Storytelling (Pillar: Story)
- Multi-scene, narrative arc
- Best for: client transformations, Vinny's own journey, philosophical visuals
- Production: 3 (high)

### Talking Head + Visual Metaphor (Pillar: Mind)
- Vinny + symbolic prop/setting
- Best for: mindset content, identity shifts
- Production: 2

**Format selection logic:**
- Match format to topic complexity
- Vary formats across batch (avoid 5 talking heads in row)
- Production effort balance: aim 3-4 low, 2-3 medium, 0-1 high per batch

---

## STEP 4 — IDEA EVALUATION CRITERIA

For each idea proposed, evaluate against 4 dimensions:

### 1. Growth Potential (1-10):
- Hook strength (attention-grabbing in 3s?)
- Viral mechanics (relatability, controversy, surprise, emotion)
- Cross-platform fit (work TikTok? IG Reels? FB?)
- Shareability (would Việt-American share with friends?)
- Cross-niche application (could a non-fitness audience relate?)

### 2. Conversion Potential (1-10):
- Filter quality (filter ideal coaching clients?)
- Trust building (does this prove Vinny's authority?)
- Pain point depth (touch real struggle that drives action?)
- Soft CTA opportunity (natural lead-in to coaching?)
- Story Bank ground truth (real transformation evidence?)

### 3. Vinny-Fit (1-10):
- AUTHENTIC to Vinny's actual life (29, single, no kids, Story Bank)?
- Audience-specific (clarify Segment A or B)?
- Cultural relevance (Việt-American context)?
- Differentiates from generic fitness content?
- Story Bank reference available?

### 4. Production Effort (1-3):
- 1 = Talking head / read caption (low effort)
- 2 = B-roll + voiceover / trend remix / POV (medium)
- 3 = Cinematic / multi-scene / props (high)

---

## STEP 5 — GENERATE 5-7 IDEAS

For each idea, output structure:

```
### Idea N: [Catchy title — code-switch OK]

**Hook angle:** [Hook ngắn, có pattern interrupt, < 12 chữ]

**Mode:** Growth | MOF | BOF | Hybrid

**Segment:** A (Vinny's peers, first-person) | B (clients audience, third-person) | Universal

**Voice approach:** First-person own experience | Third-person client story | Cultural observation | Universal explainer

**Story Bank reference:** [Which specific story from Story Bank — section + topic]
- Example: "Story Bank §7 (Lost Period → COVID Reset) - 2019 partying admission"
- Example: "Client Transformations Bank #2 (Anh Đ nail tech -41lbs)"
- "N/A" if Universal/Growth idea không cần personal story

**Format:** [Talking head / B-roll / Read caption / Trend remix / POV / Cinematic / etc.]

**Why this could work:** [Reasoning ngắn — what technique used. Reference specific Story Bank section if applicable.]

**Scores:**
- Growth Potential: X/10
- Conversion Potential: X/10
- Vinny-Fit: X/10
- Production Effort: X/3

**Pillar:** Mind | Nutrition | Training | Story | Culture

**Why now:** [Cultural moment or trend reason — optional]

**Recommendation:** [Ship priority + rationale]
```

---

## STEP 6 — BATCH SUMMARY

After 5-7 ideas, output summary:

```
## Batch Summary

**Mix breakdown:**
- Growth-focused: X ideas (target ~40%)
- MOF-focused: Y ideas
- BOF-focused: Z ideas
(MOF + BOF combined target ~60%)

**Segment distribution:**
- Segment A (peers, first-person): X ideas
- Segment B (clients, third-person): Y ideas  
- Universal: Z ideas

**Format diversity:**
- Talking head: X
- B-roll: X
- Read caption: X
- Trend remix: X
- Other: X

**Story Bank coverage:**
- Sections referenced: [list sections from Story Bank pulled]
- Client Transformations referenced: [Anh letters used]
- Direct quotes potential: [list quotes that could anchor scripts]

**Top recommended (ship this week):**
1. Idea #X — [why]
2. Idea #Y — [why]
3. Idea #Z — [why]

**Patterns observed in research:**
- [Pattern 1 — what's working in niche]
- [Pattern 2 — cross-niche viral application]
- [Pattern 3 — cultural moment relevant]

**Anti-patterns avoided:**
- [Patterns previously overused, intentionally avoided]
```

---

## STEP 7 — SAVE TO NOTION

Save ideas to Idea Bank (qua Notion MCP):
- Title: idea title
- Status: "New from Research"
- Source: "vinny-research v2.2 [date]"
- Properties: Pillar, Mode, Hook angle, Scores, Format, Segment
- Story Bank Reference: section/quote referenced

---

## STEP 8 — TELEGRAM SUMMARY

Output ngắn cho Telegram:

```
Sáng nay đã research [N] ideas mới (mix: X% Growth / Y% MOF+BOF):

Top 3 recommend:
1. [hook] (G:X C:Y V:Z) — [Mode] — [Format] — [1-line why]
2. ...
3. ...

Story Bank pull:
- [Section/Story used]
- [Client transformation referenced]

Patterns đang hot:
- [pattern observation]

Anti-patterns avoided:
- [overused pattern]

Full ideas → Notion Idea Bank.
Ship Top 3? Reply: 'Generate scripts cho idea 1, 2, 3'
```

---

## CREATIVE PRINCIPLES — Idea generation levers

### Hook techniques (any segment/mode)
- **Pattern interrupt:** Unexpected opener
- **Number-led:** "80% of guys làm 2 jobs..." 
- **Counter-conventional:** "Đếm calo không hiệu quả với..."
- **Story opener:** "3 năm trước mình ngồi sau ca làm..." (Vinny first-person Story Bank)
- **Bold claim:** "Đây là sự thật mà gym brokie không nói..."
- **POV/visual:** "Anh em IT ca đêm, 2 AM..."
- **Question hook:** "Tại sao client mình giảm 41lbs trong 5 tháng?" (Story Bank Client #2)
- **Quote provocation:** "Anh đó nói: 'Mày sẽ không bao giờ kiếm cao hơn anh'" (Story Bank §3)

### Storytelling angles by segment

**Segment A (Vinny's first-person from Story Bank):**
- Pre-30 identity reflection (turning 30 Nov 2026)
- Single life balance (work + dating + fitness)
- Building 3 businesses parallel
- Florida lifestyle observations
- Coaching journey 7 năm
- 2013 NC arrival underdog
- Self-taught fitness journey
- Drop out college decision
- 2019 lost period vulnerability

**Segment B (third-person about clients - from Client Transformations Bank):**
- "Có anh em mình coach..."
- Anh Đ nail tech transformation
- Anh V family man 6-pack
- Anh T DIY-failure → flexibility
- Family man transformation stories (anonymized)
- 2 jobs grind survival
- Wife pressure / kid time conflict (told through clients)

**Universal:**
- Fitness science explainers
- Mythbusting common Việt-American fitness misinfo
- Cultural observations
- Cross-niche pattern adaptation

### Direct response angles
- "If you want X, do Y"
- Mechanism reveal (TẠI SAO behind WHAT)
- Mythbusting
- Specific advice ("3 thứ phải làm sau ca 12h")
- Counter-conventional truth

### Cultural angles
- Family dynamics (cô chú observations - third-person)
- Workplace context (nail salon, IT remote, restaurant grind)
- Generation gap (cha mẹ vs mình)
- Immigrant experience (Vinny's NC arrival)
- Florida + Vietnamese-American specific
- Việt parent expectation vs personal calling (Story Bank §4)

### Visceral angles
- POV / silent film
- Visual metaphor
- Reaction / commentary
- Read caption format

### Cross-niche viral patterns (NEW v2.2)
- Lifestyle creator format → fitness application
- Business creator authority frame → coaching authority
- Mental health creator vulnerability → fitness vulnerability
- Food creator demos → meal prep content
- Cultural commentary → Việt-American specific takes

---

## ANTI-PATTERNS — Đừng generate ideas:

- ❌ Generic motivation ("never give up", "hustle harder")
- ❌ Quick fix promises (1 tuần giảm 10kg, etc.)
- ❌ Tao/mày anywhere
- ❌ "Việt kiều" anywhere — use specific job/lifestyle
- ❌ Politics / religion / finance flex / women stereotypes
- ❌ Personal attacks on creators
- ❌ Ideas requiring Vinny to BỊA stories không có trong Story Bank
- ❌ Stories with timeline math impossible (Vinny is 29, born ~1996)
- ❌ Same Pillar 7 days in a row — diversify
- ❌ Same hook formula 3+ times in batch
- ❌ Coaching CTA in 100% ideas — keep 70% pure value
- ❌ All talking head batch — diversify formats
- ❌ Ideas without Story Bank reference for MOF/BOF content
- ❌ Generic "transformation story" without specific client from Bank

---

## EVOLUTION — Update skill mỗi quý

Q1 review (Tuần 12):
- Patterns winning từ Analytics DB → strengthen "Why this works" reasoning
- Anti-patterns mới (failed scripts) → add vào ANTI-PATTERNS
- New cross-niche patterns discovered → add vào CREATIVE PRINCIPLES
- Cultural moments calendar → add seasonal awareness
- Story Bank new chapters → integrate
- Reference Library Vinny's top performers → bias generation toward proven patterns
- Format performance data → recalibrate format suggestions
- Bump version: v2.2 → v2.3 → v3.0
