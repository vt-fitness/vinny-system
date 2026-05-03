---
name: vinny-script
description: |
  Generate fitness video scripts cho Vinny Tran channel với multi-angle 
  creative approach. Output 2-3 angle drafts mỗi request để Vinny pick best.
  
  Skill grounded in Story Bank (Notion ID: 354466d8-c3ad-816e-8a6a-fb2447b7b84a)
  - Pull authentic Vinny stories before generating personal narrative
  - Reference 8 real client transformations (Client Transformations Bank)
  - Match Vinny's actual writing voice (extracted from 8 IG posts)
  - Anti-hallucination: NEVER bịa Vinny là dad/married/has kids
  
  Audience MIXED:
  - Primary segment: Single nam Việt-American 25-30 (Vinny's peers)
  - Secondary segment: Married/family nam Việt-American 30-45 (clients)
  
  Tone: "Người anh đi trước" - mình/bạn (NEVER tao/mày). 
  Code-switching tiếng Anh OK khi natural cho Việt-American context.
  KHÔNG dùng từ "Việt kiều" — dùng nghề/hoàn cảnh cụ thể.
  
  Default mix: 40% Growth (broad appeal, soft/no CTA) / 60% MOF+BOF 
  (trust building + coaching conversion).
  
  Trigger when user requests:
  - "viết script cho idea X" / "generate script cho [topic]"
  - "vinny-script" (explicit invoke)
  - "script multi-angle" / "3 angles cho video"
  - "convert idea X sang script"
  
  Do NOT trigger for:
  - Idea brainstorming (use vinny-research instead)
  - General fitness Q&A
  - Editing existing scripts (request iteration explicitly)
  - Long-form YouTube scripts (>3 min)
---

# Vinny Script Skill v1.2 — Multi-Angle Creative (Story-Grounded)

## CRITICAL FIRST STEP — Pull Story Bank context

**Before generating ANY script with personal/client stories, query Notion Story Bank:**
- **Story Bank Page ID:** `354466d8-c3ad-816e-8a6a-fb2447b7b84a`
- **Title:** "📖 Vinny's Personal Story Bank — Source of Truth"

Read sections relevant to current request:
- For Vinny first-person stories → Sections 1-11 (Origin → Mission Era)
- For client transformation scripts → "Client Transformations Bank" (8 cases)
- For voice grounding → "Vinny's Writing Voice Patterns"
- For hook material → "Raw Direct Quotes" + ⭐ marked moments
- For philosophy content → "Vinny's Coaching Philosophy" (5 pillars)

**Story Bank is source of truth.** Skill MUST reference real Vinny stories, NEVER invent.

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
- ❌ "Con trai mình" / "vợ mình" — Vinny KHÔNG có
- ❌ Pre-2013 US life (Vinny arrived 2013, age 13-14)
- ❌ Family stories beyond what's in Story Bank
- ❌ Specific client names beyond anonymized format ("Anh Đ", "Anh V")

---

## AUDIENCE TARGETING — DUAL SEGMENT

### Segment A: Vinny's peers (Primary - first-person voice)
- Single nam Việt-American 25-30
- Use: "Mình", "lúc mình", "tuần trước mình"
- Personal experiences từ Story Bank (Vinny's actual life)

### Segment B: Coaching audience (Secondary - "anh đi trước" voice)
- Married nam Việt-American 30-45 with family
- Use: "Có anh em mình coach...", "Một bạn client làm [nghề]..."
- Pull from Client Transformations Bank (8 anonymized cases)
- NEVER first-person family stories

### Universal:
- Fitness science, mythbusting
- Either voice OK depending on framing

---

## STEP 1 — DETECT MODE

Read user input + idea context để detect priority:

### MODE: Growth (default 40% of content)
- Pure value content, no coaching CTA
- Soft CTA: "save", "share with anh em", community building
- Goal: viral potential, broader appeal
- Format scope: ANY (talking head, B-roll, read caption, trend remix, POV, etc.)

### MODE: MOF (Trust building, ~40% of MOF+BOF allocation)
- Vulnerability stories from Story Bank
- Empathy with audience struggle
- "Mình đã từng vậy" energy
- Soft CTA: connection-building, save, community
- Goal: trust + relatability

### MODE: BOF (Conversion-focused, ~20% of MOF+BOF)
- Authority + transformation evidence
- Pull from Client Transformations Bank
- Soft DM coaching CTA OK (natural integration)
- Goal: turn warm followers → discovery call → coaching client

### MODE: Hybrid
- Default when ambiguous
- Lean 40/60 across the script body

---

## STEP 2 — DETECT SEGMENT

Read idea details để detect target segment:

### Segment A (Vinny's peers - first-person):
**Idea signals:**
- Single life, pre-30 identity, building business, dating
- Self-taught fitness journey
- Vietnamese-American immigrant experience  
- Building wealth in 20s late

**Voice approach:**
- Use: "Mình", "lúc mình", "hồi đó mình", "năm mình..."
- Personal experiences ONLY from Story Bank
- Direct first-person testimony

### Segment B (Family/coaching clients - third-person):
**Idea signals:**
- Dad life, wife pressure, kid time, family balance
- Married couple challenges
- Family-related fitness struggles

**Voice approach:**
- Use: "Có anh em mình coach...", "Một bạn client...", "Mấy anh em làm nail..."
- Pull from 8 Client Transformations Bank
- NEVER first-person family stories

### Universal:
- Fitness science, mythbusting
- Either voice OK depending on framing

---

## STEP 3 — ANALYZE THE IDEA

Before generating, evaluate:

**Hook strength:** What's the pattern interrupt? What hooks attention in 3s?

**Pillar fit:** Mind / Nutrition / Training / Story / Culture
- Mind/Story → vulnerability + narrative work well (pull Story Bank §7 lost period)
- Nutrition/Training → mechanism reveal + specific advice work
- Culture → cultural moments + family dynamics (third-person if family)
- Story → Vinny first-person Story Bank chapters

**Format fit:** What format best serves this idea?
- Story content → Talking head, Cinematic, Read caption
- Mechanism content → Talking head + B-roll
- Trend application → Trend remix
- Cultural moment → POV / Silent film, Cinematic
- Authority content → Talking head, Read caption (caption depth)

**Audience pain depth:** Surface-level vs deep struggle?
- Deep pain → BOF/conversion-friendly (pull Client Transformations Bank)
- Surface pain → Growth-friendly

**Production effort:** 1-3
- 1 = Talking head / Read caption (low effort)
- 2 = B-roll + voiceover / Trend remix / POV (medium)
- 3 = Cinematic / multi-scene / props (high)

**Authenticity check:**
- Does this idea require Vinny to bịa story he can't tell?
- If yes: REFRAME to use third-person (coaching client from Bank) or skip

---

## STEP 4 — GENERATE 2-3 ANGLES

Generate 2-3 different creative approaches for the same idea. Each angle should use a different lens/format/voice. Pick from these creative levers:

### Storytelling angles (Story Bank grounded)

**Personal vulnerability** (Vinny first-person from Story Bank)
- 2019 lost period admission (Story Bank §7)
- Self-taught NC arrival underdog (Story Bank §1)
- Drop out college risk (Story Bank §4)
- "Anh không kiếm cao hơn anh" provocation (Story Bank §3)

**Customer transformation** (third-person from Client Transformations Bank)
- Anh Đ nail tech (-41lbs, 5 months)
- Anh V family 6-pack (3 months)
- Anh T DIY-failure → Flexible Diet
- Anh B 12-week structured approach
- Anh CN trust rebuild post-bad-coach

**Day-in-life slice** (relatable moment from Story Bank)
- Vinny's training routine
- Coaching session observation
- Mission gym daily

**Behind-the-scenes** (show work)
- Mission gym setup
- Client check-in process
- Programming session

**Failure-then-lesson** (vulnerability + insight from Story Bank)
- LA Fitness 0 clients early days
- COVID gym shutdown reality check
- 2019 lost period reckoning

### Direct response angles
- **Pattern interrupt + bold claim**
- **Mechanism reveal** (TẠI SAO behind WHAT)
- **Mythbusting**
- **"If you want X, do Y"**
- **Specific advice** ("3 thứ phải làm sau ca 12h")

### Cultural angles
- **Family dynamics** — cô chú (third-person observations)
- **Workplace context** — nail salon, IT remote, restaurant grind
- **Generation gap** — Việt parent vs personal path (Story Bank §4)
- **Cultural code-switching**

### Format-specific angles (NEW v1.2)

**Read Caption Style:**
- Static visual + "Read caption ⬇️" hook
- Caption holds full content depth
- Best for: long-form value, philosophy, complex topics

**Trend Remix:**
- Apply viral trend pattern from another niche
- Maintain trend's mechanics
- Add Vinny lens

**POV / Silent Film:**
- Visual storytelling, no/minimal talking
- Best for: relatable moments, day-in-life

### Hybrid combos (Vinny's signature)
- Cultural pain + mechanism reveal + soft conversion
- Personal story (Story Bank) + mythbusting + community CTA
- Vulnerability + authority + invitation to coaching

---

**For each angle, provide:**

```
### Angle [N]: [Catchy descriptor — 3-5 chữ]

**Approach:** [Which creative lever this uses — 1 sentence]

**Voice:** First-person (Vinny own from Story Bank §X) | Third-person (Client Transformations Bank #X) | Universal

**Story Bank reference:** [Specific section/quote/client]
- Example: "Story Bank §3 - Provocation moment, lunch break electrician helper"
- Example: "Client Transformations Bank #2 - Anh Đ nail tech -41lbs in 5 months"
- "N/A" if pure educational content

**Format:** [Talking head / B-roll / Read caption / Trend remix / POV / Cinematic / Hybrid]

**Why this works for THIS idea:** [Reasoning - what about this idea makes this angle a fit]

**Authenticity check:** [Does this require Vinny to bịa? PASS/REFRAME needed]

**Hook (giây 0-3) — 3 variations:**
1. [Hook variation 1]
2. [Hook variation 2]  
3. [Hook variation 3]

**Full script (timestamped):**

[0-3s] Hook
[3-8s] Setup / Context
[8-15s] Mechanism / Twist / Reveal
[15-25s] Solution / Insight
[25-30s] Close / CTA

**Production notes:**
- Visual cues
- B-roll suggestions
- Energy/pace
- Music vibe (cinematic/upbeat/reflective)
- Format-specific notes (if read caption: text positioning; if trend remix: original trend reference)

**Length:** [30s / 45s / 60s / 90s]

**Mode:** Growth | MOF | BOF | Hybrid

**Predicted scores:**
- Growth Potential: X/10
- Conversion Potential: X/10
- Vinny-Fit: X/10 (Story Bank reference verified?)
```

---

## STEP 5 — RECOMMEND BEST ANGLE

After 2-3 angles, output:

```
## Recommendation

**Best angle for this idea:** Angle [N] — [descriptor]

**Why this beats other options:**
- [Reason 1 — specific to this idea/audience]
- [Reason 2 — Story Bank ground truth strength]
- [Reason 3 — production efficiency or platform fit]

**Production tips:**
- [Specific advice for shooting/editing]

**Posting strategy:**
- Best platform priority: TikTok / IG / FB / YouTube Shorts
- Best posting day/time: [day] [time slot]
- Caption focus: [growth-led / value-led / story-led]
```

---

## STEP 6 — GENERATE CAPTIONS (ALL 4 PLATFORMS) — VINNY VOICE GROUNDED

Pull Vinny's actual writing voice from Story Bank "Vinny's Writing Voice Patterns" section.

### Caption 7-Step Structure (Vinny's actual signature pattern):

```
1. Opening congratulation / acknowledgment
   "Hôm nay mình muốn..." / "Thêm một câu chuyện..." (BOF)
   "[Hook angle]" (Growth)

2. Before context (struggle)
   - "Đã từng tự tập nhưng không kết quả"
   - "Đã có coach trước → thất vọng"
   - "Skinny fat / béo / mất tự tin"

3. Pain point amplification
   - Công việc bận (nail / IT / restaurant)
   - Thông tin mâu thuẫn trên mạng
   - On-off cycle

4. Decision moment
   - "Anh ấy đã quyết định nghiêm túc thay đổi"
   - "Anh ấy nhắn tin cho mình..."

5. Solution applied (Vinny's expertise from Coaching Philosophy)
   - Custom plan based on lifestyle
   - Specific accommodations (nail tech schedule, dad family time)
   - Flexible diet, không cắt tinh bột

6. Result + transformation (specific numbers)
   - "[X]lbs giảm trong [Y] tháng"
   - "6-pack rõ trong [N] tuần"
   - Plus quality outcomes: tự tin, năng lượng

7. Soft CTA / Universal lesson
   - "Câu chuyện của [Name] là minh chứng rõ ràng..."
   - "Comment '🔥' nếu bạn..."
   - "Hãy nhớ rằng, một quyết định nghiêm túc có thể thay đổi tất cả"
```

### Voice Signatures (use Vinny's actual phrases):

**Pronouns (NEVER violate):**
- Self: "mình" (ALWAYS)
- Audience: "bạn"
- Clients: "anh [Letter]" or "bạn ấy"

**Vinny's actual phrases (recurring across 8 IG posts):**
- "Hành trình của [Name] không hề dễ dàng"
- "Vòng lặp on-off liên tục: tập rồi bỏ, bỏ rồi lại bắt đầu"
- "Quyết định nghiêm túc thay đổi"
- "Phù hợp với công việc của anh ấy"
- "Một thân hình săn chắc"
- "Cân bằng hoàn hảo với công việc"
- "Linh hoạt trong việc ăn uống"
- "Mất tự tin với body của bạn ấy"
- "Sự thay đổi đáng kinh ngạc"
- "Mình rất tự hào về [Name]"

**Sign-off patterns:**
- "Mình rất tự hào về [Name]"
- "Comment '🔥' nếu bạn..."
- "Hãy nhớ rằng, một quyết định nghiêm túc có thể thay đổi tất cả"

### Caption variants per platform:

```
## Caption IG (story-led, 8-10 hashtags, save+follow CTA)
[Long-form Vinny voice 5-7 paragraphs, follow 7-step structure if BOF]

## Caption FB (longer hook, 4 hashtags, comment CTA)
[Similar to IG but slightly more conversational opening]

## Caption TikTok (siêu ngắn, 5 hashtags, comment-bait)
[3-5 lines max, hook + curiosity gap + comment-bait CTA]

## Caption YouTube Shorts (description SEO, 1-2 hashtags)
[2-3 sentences, story-led + Vinny credentials, SEO keywords]
```

---

## STEP 7 — SAVE TO NOTION (IF REQUESTED)

When user asks to save:
- Update idea status: "Script Drafted" or "Scripting Approval"
- Add script to Content Tracker
- Reference original idea ID
- Save all 4 captions to respective fields
- Tag với Segment (A/B/Universal) for analytics
- Tag với Story Bank reference (section/client used)

---

## CREATIVE CONSTRAINTS — Hard rules

### Voice & tone
- ✅ Mình/bạn (always)
- ✅ "Người anh đi trước" framing
- ✅ Code-switching English OK if natural ("Flexible Diet", "DM coaching", "app guidance")
- ❌ Tao/mày (anywhere, ever)
- ❌ "Chuyên gia" / "expert" tone
- ❌ Generic "anh em ơi"

### Audience targeting
- ✅ Specific: "anh em làm nail / IT đêm / restaurant / 2 jobs / có vợ con"
- ❌ "Việt kiều" anywhere
- ❌ Vague "mọi người"

### Authority anchoring (when relevant)
- ✅ "7 năm coaching", "100+ anh em đã transform", "Master Trainer LA Fitness"
- ✅ Specific Client Transformation Bank evidence
- ✅ Story Bank ⭐ marked moments
- ❌ Vague "anh từng thấy", "có người nói"

### Stories — CRITICAL anti-hallucination
- ✅ Stories from Story Bank ONLY (verified true facts)
- ✅ Third-person about coaching clients from Client Transformations Bank
- ✅ Third-person family/cultural observations
- ❌ NEVER bịa stories về Vinny having kids/wife
- ❌ NEVER timeline math impossible (Vinny born ~1996, arrived US 2013)
- ❌ NEVER "con trai mình" / "vợ mình"
- ✅ When idea targets family audience: REFRAME to third-person client story from Bank

### Hook structure
- Hook giây 0-3 PHẢI có ≥ 3/4 components:
  1. Visual cue cụ thể
  2. Verbal hook < 12 chữ
  3. Text on screen
  4. Sound/music vibe

### CTA strategy by mode
- **Growth mode:** NO "DM coaching". Soft CTA = "save", "share with anh em", "comment 🔥"
- **MOF mode:** Connection-building CTA ("comment 1 chữ nếu thấy mình ở đây")
- **BOF mode:** Soft "DM 'COACHING'" or "link in bio" — natural, not pushy
- **Hybrid:** Default value-first, soft conversion at very end

### Coaching philosophy alignment (Story Bank §11)
Vinny's 5 pillars to reinforce in BOF/MOF content:

1. **Lifestyle-first approach** — Plan phù hợp công việc client
2. **Flexible Diet methodology** — Vẫn ăn cơm, vẫn ăn ngoài cùng gia đình
3. **Sustainable over fast** — Knowledge building để client tự sắp xếp
4. **Structured + Specific** — App coaching, lịch tập khoa học
5. **Trust earned through honesty** — Acknowledge struggles, không oversell

### Content boundaries
- ❌ Politics
- ❌ Religion
- ❌ Finance flex
- ❌ Women stereotypes / anti-rhetoric
- ❌ Health misinformation
- ❌ Personal attacks on creators
- ❌ Quick fix promises
- ❌ "Cắt tinh bột" / extreme dieting promotion (against Vinny philosophy)

---

## ANTI-PATTERNS — Đừng generate scripts:

- ❌ All 3 angles the same approach
- ❌ Rhetorical questions opener (overused)
- ❌ Generic motivation
- ❌ Round numbers not believable
- ❌ Hooks không có pattern interrupt
- ❌ Solutions không có mechanism
- ❌ CTA "DM COACHING" trong growth-mode scripts
- ❌ Scripts cụt — phải đủ structure
- ❌ **CRITICAL: Stories that require Vinny to bịa about family/kids/wife**
- ❌ **CRITICAL: Timeline impossible for 29-year-old**
- ❌ **CRITICAL: Personal stories không có trong Story Bank**
- ❌ Generic "transformation story" without specific Client Bank reference
- ❌ All talking head batch — vary formats

---

## REFRAMING GUIDE — Anti-hallucination

If idea targets family/dad audience but Vinny không có family:

**WRONG approach (bịa):**
"Con trai mình hỏi: 'Sao bụng ba mềm?'"
→ Vinny không có con. HALLUCINATION.

**RIGHT approach Option 1 — Third-person client (Client Bank):**
"Có anh em mình coach kể: con trai 6 tuổi vỗ bụng anh hỏi 'Sao bụng ba mềm?'"
→ Vinny là witness/coach, không phải protagonist. AUTHENTIC.

**RIGHT approach Option 2 — First-person observation:**
"Tuần rồi mình ngồi tâm sự với 1 client làm IT đêm. Anh kể chuyện con trai..."
→ Vinny present trong story as coach, không phải dad. AUTHENTIC.

**RIGHT approach Option 3 — Vinny's own family context (third-person):**
"Mình nhớ ba mình hồi 50 tuổi, bụng bia 30 năm..."
→ Vinny observation về ba (third-person), authentic.

---

## EXAMPLE WORKFLOW (for reference)

**User input:** "Generate scripts cho idea: Why anh em IT đêm tăng cân nhanh"

**Skill execution:**

1. **Pull Story Bank** → Find:
   - Client Bank Anh T (DIY failed → Flexible Diet) - relevant struggle
   - Client Bank Anh H (restaurant style, irregular eating) - relevant pattern
   - Story Bank §7 (2019 lost period clubbing → eating bad) - relevant authority

2. **Detect mode + segment:**
   - Mode: MOF (vulnerability/empathy) + BOF (mechanism + soft CTA)
   - Segment: B (clients) primarily, with hint of Universal (mechanism)

3. **Generate 3 angles:**
   - Angle 1: "Story-led empathy" - Open with Anh T case (Client Bank), 
     mechanism reveal (Flexible Diet), soft CTA
   - Angle 2: "Mechanism mythbust" - Universal explainer, why "skip meals 
     then big dinner" fails biologically, soft community CTA
   - Angle 3: "Read caption depth" - Visual hook ("IT đêm 2 AM ăn ramen"), 
     full caption explains mechanism + reference Anh T case

4. **Recommend Angle 1** for highest empathy + conversion potential

5. **Generate captions** following 7-step Vinny structure with signature phrases

6. **Save Notion** with Story Bank reference logged

---

## EVOLUTION — Update skill mỗi quý

Q1 review (Tuần 12):
- Patterns winning từ Analytics DB → strengthen "Why this works" reasoning
- Anti-patterns mới (failed scripts) → add vào ANTI-PATTERNS
- New creative angles discovered → add vào STEP 4 levers
- Hook variations winning → add to creative principles
- Story Bank new chapters → integrate
- Client Transformations Bank new entries → expand
- Reference Library Vinny's top performers → bias toward proven patterns
- Format performance data → recalibrate format suggestions
- Voice signature evolution → update verbatim phrases bank
- Bump version: v1.2 → v1.3 → v2.0
