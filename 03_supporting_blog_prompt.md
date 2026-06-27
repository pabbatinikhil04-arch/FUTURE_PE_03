# prompts/03_supporting_blog_prompt.md

> **Reusable Prompt: Supporting Blog Generator (Content Cluster)**
> Use this prompt to generate 900–1200 word supporting blogs that surround your pillar article and build topical depth.

---

## What is a Supporting Blog?

Supporting blogs are smaller, focused articles that:

- Target **secondary keywords** that the pillar blog cannot cover in depth
- Answer **specific questions** your audience is searching for
- Link back to the **pillar blog** (and to each other where relevant)
- Help Google understand your site covers a topic **completely**

A well-structured content cluster signals topical authority — which is one of the strongest ranking factors in modern SEO.

---

## Prompt Template — Supporting Blog

```
You are a professional SEO content writer.

Write a complete, SEO-optimized supporting blog article for the following:

Business Name: [BUSINESS_NAME]
Location: [CITY], [STATE]
Business Type: [BUSINESS_TYPE]
Target Audience: [TARGET_AUDIENCE]

Blog Topic: [BLOG_TOPIC]
Target Keyword: [TARGET_KEYWORD]
Pillar Blog Title: [PILLAR_BLOG_TITLE]
Pillar Blog URL Slug: [PILLAR_SLUG]

---

### REQUIREMENTS

**Length:** 900–1200 words

**Tone:** Helpful, conversational, and honest. No sales pressure. Write like a knowledgeable friend giving real advice.

**Structure — generate in this exact order:**

---

**SEO TITLE**
Under 60 characters. Include [TARGET_KEYWORD].

**META DESCRIPTION**
140–155 characters. Include [TARGET_KEYWORD] and a CTA.

**SLUG**
URL-friendly slug for this specific blog post.

---

**H1**
Clear, keyword-rich heading that reflects the reader's actual question or goal.

---

**Introduction (100–150 words)**
- Open with an empathetic observation about the reader's situation
- State the specific problem or goal this blog addresses
- Tell the reader what they will get from this article

---

**[H2 SECTION 1] — Core concept or problem statement**
(150–200 words — provide real, helpful information)

---

**[H2 SECTION 2] — Practical steps, tips, or explanation**
(200–250 words — use numbered steps or short paragraphs, not heavy bullets)

---

**[H2 SECTION 3] — Deeper insight, common mistakes, or real-world example**
(150–200 words)

---

**[H2 SECTION 4] — Actionable advice to move forward**
(100–150 words)

---

**FAQs (3 questions)**
Write 3 questions a reader at this stage of their journey would ask.
For each, write a 2–3 sentence answer.

---

**Conclusion (80–100 words)**
Summarize the key takeaway. Encourage the reader to act.

---

**CTA**
Friendly, clear call to action. Mention a free demo class, a consultation call, or a visit to the institute. Keep it conversational.

---

**Internal Links (formatted as markdown links)**
- Link back to the pillar blog: anchor text + [[PILLAR_SLUG]]
- Suggest 2 other supporting blog topics to link to (you can use placeholder slugs)

---

Rules:
- Use [TARGET_KEYWORD] naturally 4–6 times
- No invented statistics, rankings, or testimonials
- Every section must flow into the next
- Write for the reader, not for the algorithm
```

---

## How to Use This Prompt

### Step 1: Run once per supporting blog topic

For the Vivekananda Spoken English Academy content cluster, run this prompt **four times** with these inputs:

| Blog # | Blog Topic | Target Keyword |
|---|---|---|
| Blog 1 | How to Improve Spoken English Confidence | how to improve spoken english |
| Blog 2 | Best Spoken English Course for Job Seekers | spoken english for job seekers |
| Blog 3 | Interview English Tips for Freshers | spoken english for interviews |
| Blog 4 | Why Personality Development Matters for Career Growth | personality development classes chennai |

### Step 2: Save each output

- Blog 1 → `outputs/03_blog_how_to_improve_spoken_english.md`
- Blog 2 → `outputs/04_blog_best_spoken_english_course.md`
- Blog 3 → `outputs/05_blog_interview_english_tips.md`
- Blog 4 → `outputs/06_blog_personality_development.md`

### Step 3: Add internal links manually

Once all four blogs are written, go back and add cross-links between them using the anchor texts suggested in each article's internal links section.

---

## Customization

- To write for a **different city**, change `[CITY]` and add: "Mention the location naturally 2–3 times in the article."
- To **increase depth**, add: "Include one real-world scenario or example that illustrates the main point."
- To **optimize for featured snippets**, add: "For the FAQ section, format answers in 40–60 words each so they are eligible for Google's featured snippet."

---

*The supporting blog is where most of your keyword wins will come from. Write each one as if it is the only article a new reader will ever see from this business.*
