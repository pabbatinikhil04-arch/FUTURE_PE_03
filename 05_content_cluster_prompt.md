# prompts/05_content_cluster_prompt.md

> **Reusable Prompt: Content Cluster Strategy Generator**
> Use this prompt to automatically build a full content cluster — including the pillar topic, supporting topics, internal links, anchor text, and publishing order.

---

## What is a Content Cluster?

A content cluster is a group of related blog posts organized around one central topic. It works like this:

```
          [PILLAR BLOG]
         /      |       \
   [Blog A]  [Blog B]  [Blog C]
        \       |       /
         \      |      /
          [Blog D]  [Blog E]
```

- The **pillar blog** covers the main topic broadly and in depth
- Each **supporting blog** covers one specific sub-topic in detail
- All supporting blogs **link back to the pillar**
- The pillar **links out to each supporting blog**
- Supporting blogs **cross-link** where relevant

This architecture tells Google: *"This website is a trusted authority on this entire topic."*

---

## Prompt Template — Content Cluster Builder

```
You are an expert SEO strategist and content architect.

Build a complete content cluster strategy for the following business:

Business Name: [BUSINESS_NAME]
Location: [CITY], [STATE]
Business Type: [BUSINESS_TYPE]
Primary Topic: [PRIMARY_TOPIC]
Primary Keyword: [PRIMARY_KEYWORD]
Target Audience: [TARGET_AUDIENCE]

---

### DELIVERABLES

Generate each of the following sections completely:

---

#### 1. PILLAR BLOG DETAILS

Provide:
- Pillar blog title
- Primary keyword
- Target search intent
- Estimated word count
- URL slug
- 5 H2 headings to include in the pillar blog
- Why this topic earns topical authority

---

#### 2. SUPPORTING BLOG TOPICS (generate 5)

For each supporting blog, provide:
- Blog title
- Target keyword
- Search intent (informational / commercial / navigational)
- Estimated word count
- URL slug
- 3 H2 headings to include
- Which section of the pillar blog it should link from
- Anchor text for the internal link from the pillar

---

#### 3. INTERNAL LINKING MAP

Create a plain-text map showing:
- Which supporting blogs link back to the pillar (and with what anchor text)
- Which supporting blogs cross-link to each other (and where relevant)
- Where the pillar blog links to each supporting blog

Format as a readable list, not code.

---

#### 4. KEYWORD MAP

Create a table with columns:
| Content Piece | Target Keyword | Search Intent | Funnel Stage |

Funnel stages:
- Awareness (reader is just learning)
- Consideration (reader is comparing options)
- Decision (reader is ready to act)

---

#### 5. SEARCH INTENT TABLE

For each piece of content, describe:
- What the reader is trying to accomplish
- What answer they expect to find
- What action this content should nudge them toward

---

#### 6. PUBLISHING ORDER

Recommend the order to publish the content cluster for maximum SEO impact.
Explain why each piece is published in that sequence.

---

#### 7. MONTHLY CONTENT PLAN (3 months)

Lay out which content to publish in which week across 12 weeks.
Include a brief note on what to promote after each publish (social post, WhatsApp broadcast, local Facebook group, etc.)

---

Rules:
- All blog topics must be genuinely useful to the target audience
- Every internal link must make editorial sense — not forced
- Publishing order should reflect how Google builds topical understanding
- Do not suggest duplicate content or near-identical topics
- All keyword targets should be realistic for a local business website
```

---

## How to Use This Prompt

1. Fill in the placeholders with your client's details
2. Run in Claude (best for long structured outputs)
3. Save the full output to `outputs/07_content_cluster.md`
4. Use the publishing order to plan your editorial calendar
5. Use the internal linking map as a checklist when uploading each blog

---

## Scaling This Strategy

Once the first cluster is complete and indexed (typically 4–8 weeks), you can:

**Expand to a second cluster** on a related topic:

| Cluster 1 | Cluster 2 |
|---|---|
| Spoken English Classes | Interview Preparation |
| Pillar: Best Spoken English Classes in Chennai | Pillar: How to Prepare for a Job Interview in Chennai |
| Supports: How to improve fluency, grammar tips, etc. | Supports: Common interview questions, body language, etc. |

**Add a third cluster** for an adjacent service:

| Cluster 3 |
|---|
| Personality Development |
| Pillar: Personality Development Courses in Chennai |
| Supports: Public speaking tips, confidence building, etc. |

By month 6, you will have **3 interconnected content clusters** that collectively cover every major search query your target audience types — building genuine topical authority in Google's eyes.

---

## Why This Works (The SEO Logic)

Google does not rank individual blog posts in isolation. It evaluates **topical coverage**. A website that has one article about spoken English will lose to a website that has a pillar blog, five supporting blogs, and strong internal links — even if the individual articles are similar in quality.

Content clusters work because they:
- Show Google that your site covers a topic **completely**
- Keep readers on your site longer (reducing bounce rate)
- Build **internal PageRank** through cross-linking
- Make it easier to earn **backlinks** (one strong cluster attracts more links than scattered articles)

---

*A single content cluster, executed well, can earn more traffic in six months than years of random blog posting.*
