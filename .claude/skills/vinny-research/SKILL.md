---
name: vinny-research
description: |
  Generate creative content ideas cho Vinny Tran fitness coaching channel.
  Synthesize knowledge từ growth/marketing/personal brand best practices
  + Vinny's coaching expertise + audience insights để đề xuất ideas có
  potential viral cao và convert leads tốt.
  
  Audience: Nam Việt-American 25-45, US (làm nail/IT đêm/restaurant/
  văn phòng IT, thường có vợ con, làm 2 jobs).
  
  Mục tiêu mỗi idea phải address ít nhất 1 trong 2:
  1. GROWTH: bring new eyes to page, viral potential
  2. CONVERSION: turn cold lead → warm lead → coaching client
  
  Default mix: 70% growth-focused / 30% conversion-focused.
  
  Trigger when user requests:
  - "research ideas tuần này" / "weekly research"
  - "tìm content angles fresh" / "đề xuất ideas mới"
  - "vinny-research" (explicit invoke)
  - "ideas cho [topic/pillar]"
  - "growth content ideas" / "conversion ideas"
  
  Do NOT trigger for:
  - Generating actual scripts (use vinny-script instead)
  - General fitness Q&A
  - Editing existing ideas
---

# Vinny Research Skill v2 — Creative Strategist

## CONTEXT — Vinny's brand

**Audience primary:** Nam Việt-American 25-45, US (Cali/Texas/Florida prim)
- Nghề: nail tech / IT (đặc biệt ca đêm) / restaurant / văn phòng IT / skilled trades
- Family: thường có vợ con, làm 2 jobs, ngủ 5-6h
- Body state: skinny-fat, bụng bia, mất shape sau 30
- Mindset: muốn lấy lại body nhưng sợ mất cuộc sống / không có time / không tin promise quick fix

**Vinny's voice:**
- "Người anh đi trước" — đã từng skinny-fat, đã transform, giờ giúp anh em khác
- 7+ năm coaching experience (LA Fitness + private clients)
- Mình/bạn (NEVER tao/mày)
- Code-switching tiếng Anh OK khi natural cho Việt-American context
- KHÔNG dùng từ "Việt kiều" — dùng nghề/hoàn cảnh cụ thể

**3 pillars:** Mind / Nutrition / Training

**Growth Goals 2026:** 413k → 570k followers EOY (IG 47k→70k, FB 208k→300k, TikTok 158k→200k)

## STEP 1 — DEFINE GOAL FIRST

Read user input để detect priority mode:

**MODE A: Pure Growth (no CTA conversion)**
- User says: "viral", "growth", "kéo audience mới", "broader appeal"
- 70% of content should be this mode
- Goal: bring new eyes, build trust, no sales

**MODE B: Conversion-focused (DM coaching CTA OK)**
- User says: "convert leads", "coaching content", "warm lead", "DM coaching"
- 30% of content
- Goal: turn warm followers → discovery call → client

**MODE C: Hybrid (default)**
- User chưa specify
- Default: bias 70% growth / 30% conversion across batch of ideas

## STEP 2 — RESEARCH SOURCES

Use these tools/sources in priority order:

**Priority 1: web_search** (primary)
- Latest viral trends in fitness/health niche
- What Vietnamese-American creators đang làm
- Cultural moments (Tết, family BBQ, immigrant experience, etc.)
- Workplace cultural moments (nail salon, IT layoffs, restaurant industry)
- General creator economy trends

**Priority 2: Notion MCP queries**
- Idea Bank (last 20 entries) — avoid duplicates
- Reference Library (if exists) — Vinny's curated viral patterns
- Analytics DB (if exists) — winning patterns from past content

**Priority 3: Synthesis** (no tool needed)
- Apply Vinny's existing DNA + audience insights
- Cross-reference với cultural moments
- Identify gaps trong what's been done

## STEP 3 — IDEA GENERATION CRITERIA

For each idea proposed, evaluate against 4 dimensions:

**1. Growth Potential (1-10):**
- Hook strength (how attention-grabbing in 3s?)
- Viral mechanics (relatability, controversy, surprise, emotion)
- Cross-platform fit (work TikTok? IG Reels? FB?)
- Shareability (would Việt-American share with friends/spouse?)

**2. Conversion Potential (1-10):**
- Filter quality (filter ideal coaching clients?)
- Trust building (does this prove Vinny's authority?)
- Pain point depth (touch real struggle that drives action?)
- Soft CTA opportunity (natural lead-in to coaching?)

**3. Vinny-Fit (1-10):**
- Authentic to Vinny's voice/experience?
- Audience-specific (anh em làm nail, IT đêm, etc.)?
- Cultural relevance (Việt-American context)?
- Differentiates from generic fitness content?

**4. Production Effort (1-3):**
- 1 = Talking head only (low effort)
- 2 = B-roll + voiceover (medium)
- 3 = Cinematic / multi-scene / props (high)

## STEP 4 — GENERATE 5-7 IDEAS

For each idea, output structure:

```
### Idea N: [Catchy title — code-switch OK]

**Hook angle:** [Hook ngắn, có pattern interrupt, < 12 chữ]

**Why this could work:** [Reasoning ngắn — không name-drop creators. 
Mention which technique: storytelling / direct response / cultural angle / 
data reveal / vulnerability / mythbusting / etc.]

**Scores:**
- Growth Potential: X/10
- Conversion Potential: X/10
- Vinny-Fit: X/10
- Production Effort: X/3

**Mode:** Growth | Conversion | Hybrid

**Pillar:** Mind | Nutrition | Training | Story | Culture

**Suggested format:** [Talking head 30s | Cinematic 60s | POV 45s | etc.]

**Why now:** [Cultural moment or trend reason — optional]

**Recommendation:** [Vinny should ship this nếu... / consider this when...]
```

## STEP 5 — BATCH SUMMARY

After 5-7 ideas, output summary:

```
## Batch Summary

**Mix breakdown:**
- Growth-focused: X ideas
- Conversion-focused: Y ideas
- Hybrid: Z ideas

**Top recommended (ship this week):**
1. Idea #X — [why]
2. Idea #Y — [why]

**Patterns observed in research:**
- [Pattern 1 — what's working in niche]
- [Pattern 2 — cultural moment relevant]

**Next suggested research areas:**
- [Topic worth deeper dive next time]
```

## STEP 6 — SAVE TO NOTION

Save ideas to Idea Bank (qua Notion MCP):
- Title: idea title
- Status: "New from Research"
- Source: "vinny-research v2 [date]"
- Properties: Pillar, Mode, Hook angle, Scores, Format

## STEP 7 — TELEGRAM SUMMARY

Output ngắn cho Telegram:

```
Sáng nay đã research [N] ideas mới (mix: X growth / Y conversion):

Top 3 recommend:
1. [hook] (G:X C:Y V:Z) — [1-line why]
2. ...
3. ...

Patterns đang hot:
- [pattern observation]

Full ideas → Notion Idea Bank.
Ship Top 3? Reply: 'Generate scripts cho idea 1, 2, 3'
```

## CREATIVE PRINCIPLES (drawn from creator economy best practices)

When ideating, consider these creative levers:

**Hook techniques:**
- Pattern interrupt (unexpected opener)
- Number-led ("80% of guys làm 2 jobs...")
- Counter-conventional ("Đếm calo không hiệu quả với...")
- Story opener ("3 năm trước mình ngồi sau ca làm...")
- Bold claim ("Đây là sự thật mà gym brokie không nói...")
- POV/visual ("Anh em IT ca đêm, 2 AM...")

**Storytelling angles:**
- Personal vulnerability
- Customer transformation
- Cultural identity (Việt-American specific)
- Day-in-life slice
- Behind-the-scenes
- Failure-then-lesson

**Direct response angles:**
- "If you want X, do Y"
- Mechanism reveal (TẠI SAO behind WHAT)
- Mythbusting
- Specific advice ("3 thứ phải làm sau ca 12h")

**Cultural angles:**
- Family dynamics (vợ chia sẻ cho chồng — viral loop)
- Workplace context (nail salon culture, IT remote, restaurant grind)
- Generation gap (cha mẹ vs mình)
- Immigrant experience

**Visceral angles:**
- POV/silent film
- Visual metaphor
- Reaction/commentary

**Hybrid: Vinny's signature combos**
- Cultural pain + mechanism reveal + soft conversion
- Personal story + mythbusting
- Vulnerability + authority + invitation

## ANTI-PATTERNS — Đừng generate ideas:

- Generic motivation ("never give up", "hustle harder")
- Quick fix promises (1 tuần giảm 10kg, etc.)
- Tao/mày anywhere
- "Việt kiều" anywhere — use specific job/lifestyle
- Politics / religion / finance flex / women stereotypes
- Personal attacks on creators
- Bịa stories — chỉ dùng stories thật từ Vinny background
- Same Pillar 7 days in a row — diversify
- Same hook formula 3+ times in batch
- Coaching CTA in 100% ideas — keep 70% pure value

## EVOLUTION — Update skill mỗi quý

Q1 review (Tuần 12):
- Patterns winning từ Analytics DB → strengthen "Why this could work" reasoning
- Anti-patterns mới (failed scripts) → add vào ANTI-PATTERNS
- New creator techniques discovered → add vào CREATIVE PRINCIPLES
- Cultural moments calendar → add seasonal awareness
- Bump version: v2 → v3 → v4
