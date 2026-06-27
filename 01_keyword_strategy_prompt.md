# prompts/01_keyword_strategy_prompt.md

> **Reusable Prompt: SEO Keyword Strategy Generator**
> Use this prompt in ChatGPT, Claude, or Gemini to generate a complete keyword strategy for any business.

---

## Prompt Template

```
You are an expert SEO strategist with 10+ years of experience in local SEO and content marketing.

I need a complete keyword strategy for the following business:

Business Name: [BUSINESS_NAME]
Business Type: [BUSINESS_TYPE]
Location: [CITY], [STATE], [COUNTRY]
Primary Service: [PRIMARY_SERVICE]

Your task is to generate:

---

### 1. PRIMARY KEYWORD
- The single most important keyword this business should rank for
- Must include the city and service
- Format: lowercase, search-friendly

---

### 2. SECONDARY KEYWORDS (10–15 keywords)
For each keyword, provide:
- The keyword phrase
- Monthly search volume estimate (low / medium / high)
- Keyword difficulty estimate (easy / medium / hard)
- Search intent (informational / commercial / navigational / transactional)
- Best content type to target it (blog / landing page / FAQ)

---

### 3. PEOPLE ALSO ASK (PAA) IDEAS
Generate 8–10 questions real users type on Google related to this business.
Format as a numbered list.

---

### 4. META TITLE IDEAS (5 options)
For the homepage and the pillar blog.
Each meta title must:
- Be under 60 characters
- Include the primary keyword naturally
- Include a differentiator (e.g., "since 2010", "affordable", "certified")

---

### 5. META DESCRIPTION IDEAS (3 options)
For the pillar blog page.
Each meta description must:
- Be 140–155 characters
- Include the primary keyword
- Include a clear call to action

---

### 6. INTERNAL LINKING SUGGESTIONS
List 5 internal page links that a website in this niche should have, and what anchor text to use to link between them.

---

### 7. BLOG CALENDAR (3-month plan)
Suggest one blog topic per week for 12 weeks.
Organize by month.
Each topic should target a different secondary keyword.

---

Rules:
- Write everything in plain English
- Do not use keyword stuffing
- Focus on helpful, search-intent-matched content
- All suggestions must be realistic for a local [BUSINESS_TYPE] website
```

---

## How to Use This Prompt

1. Copy the prompt above
2. Replace all `[PLACEHOLDER]` values with your client's information:
   - `[BUSINESS_NAME]` → e.g., Vivekananda Spoken English Academy
   - `[BUSINESS_TYPE]` → e.g., Spoken English Institute
   - `[CITY]` → e.g., Chennai
   - `[STATE]` → e.g., Tamil Nadu
   - `[COUNTRY]` → e.g., India
   - `[PRIMARY_SERVICE]` → e.g., Spoken English coaching and personality development
3. Paste into Claude, ChatGPT, or Gemini
4. Save the output in `outputs/01_keyword_strategy.md`

---

## Example Input (Pre-filled)

```
Business Name: Vivekananda Spoken English Academy
Business Type: Spoken English & Personality Development Institute
Location: T. Nagar, Chennai, Tamil Nadu, India
Primary Service: Spoken English coaching, interview preparation, personality development
```

---

## Tips for Better Results

- Run this prompt first before any blog prompts — the keyword output feeds everything else
- Use the PAA questions to build FAQ sections in every blog
- Use the blog calendar to plan your publishing schedule before writing content
- If results feel generic, add: "The audience includes [TARGET_AUDIENCE]" to the prompt

---

*This is a reusable prompt. You can adapt it for any business type, location, or industry.*
