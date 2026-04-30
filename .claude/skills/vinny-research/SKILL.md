---
name: vinny-research
description: |
  Auto-research viral content trong niche fitness nam Việt kiều 25-45
  (US-based, làm nail/IT đêm/restaurant/văn phòng).
  
  Use web_search to scan public content + analyze patterns + generate
  fresh ideas align với Vinny Tran's DNA framework.
  
  Trigger when user requests:
  - "research trending fitness content" / "research viết script tuần này"
  - "tìm viral patterns" / "đề xuất ideas dựa trên trends"
  - "vinny-research" (explicit invoke)
  - "weekly research" / "sáng thứ 2 ideas"
  
  Do NOT trigger for:
  - General fitness advice questions
  - Editing existing scripts
  - Brand new business research (này là fitness specifically)
---

# Vinny Research Skill v1

## CONTEXT — Vinny's brand

- Audience: Nam Việt kiều 25-45, US (Cali/Texas/Florida prim)
- Tône: "Người anh đi trước" — mình/bạn (NEVER tao/mày)
- 3 pillars: Mind / Nutrition / Training
- Goal 2026: 413k → 570k followers EOY

## STEP 1 — Define search scope

Search 3 niches parallel using web_search tool:

NICHE 1 — Vietnamese fitness creators
- Query: "viral fitness coach Vietnamese TikTok 2026"
- Query: "Việt kiều fitness Instagram trending"
- Look for: Vinny audience adjacent creators

NICHE 2 — Male fitness 30+ global
- Query: "viral fitness 30s 40s male reels [current month]"
- Query: "male fitness creator anti-perfection mindset viral"
- Look for: hook patterns, mechanism reveals

NICHE 3 — Hook masters general
- Query: "viral hook formula content creator [current month]"
- Query: "top performing video hooks short form 2026"
- Look for: structural patterns, opener techniques

## STEP 2 — Pattern recognition criteria

For each search result/video found, extract:
- Hook angle (first 3 seconds)
- Pillar match (Mind / Nutrition / Training)
- Mechanism reveal? (Y/N — explain WHY behind WHAT)
- Audience-specific? (Y/N — mention specific job/lifestyle)
- Authority anchor? (Y/N — "X years experience" claim)
- Anti-pattern flag (generic motivation, fake urgency)

## STEP 3 — Cross-reference with Notion

Query 2 Notion databases via MCP:

a) Idea Bank (last 20 entries):
- Get titles, hook angles
- Avoid suggesting duplicates or similar angles

b) Reference Library (if exists):
- Get patterns Vinny captured manually
- Bias toward patterns Vinny tagged "high vinny-fit"

## STEP 4 — Generate 5-10 fresh ideas

For each idea, structure as JSON:
- hook: Vietnamese, mình/bạn tone
- pillar: Mind | Nutrition | Training
- day_type: Day 1 Honesty | Day 4a Fitness Viral | Day 4b TOF | etc.
- why_now: Context trending
- reference_pattern: URL hoặc creator inspired by
- vinny_fit_score: 1-10
- rationale: Tại sao fit Vinny audience specifically
- experiment_flag: 60_proven | 40_experiment

Mix ratio: 60% proven (DNA framework match) + 40% experiment (new angles)

## STEP 5 — Save to Notion Idea Bank

For each idea generated:
- Create page in Idea Bank
- Status: "New from Research"
- Source: "Web Research [date]"
- Properties: Pillar, Day Type, Hook Angle, Why Now

## STEP 6 — Telegram summary

After saving, output Telegram-style message:

"Sáng thứ 2 — đã research [N] ideas mới:
1. [hook ngắn] (Pillar, Day Type, fit X/10)
2. ...

Patterns đang hot tuần này:
- [Pattern 1 observation]
- [Pattern 2 observation]

Click 'Generate Script' button trong Notion Idea Bank để ship."

## ANTI-PATTERNS — Đừng generate ideas:

- Generic motivation ("never give up", "hustle harder")
- Trends không fit fitness (dating tips, finance tips)
- Hooks với rhetorical questions ("Bạn có biết...?")
- Numbers tròn không believable ("1000 người như tôi")
- Không có mechanism — chỉ có tip
- Đặt Vinny vào role guru/expert (Vinny là "anh đi trước")

## EVOLUTION — Update skill mỗi quý

Mỗi 3 tháng, Vinny review:
- Patterns winning từ Analytics DB → add vào STEP 2
- Anti-patterns mới (failed scripts) → add vào ANTI-PATTERNS
- New niches discover → add vào STEP 1 search scope
- Bump version: v1 → v2 → v3
