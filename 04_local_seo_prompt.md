# prompts/04_local_seo_prompt.md

> **Reusable Prompt: Local SEO Blog Adapter**
> Use this prompt to take any existing blog and adapt it for a specific city, neighborhood, or service area — without rewriting from scratch.

---

## Why Local SEO Matters

For coaching institutes, clinics, salons, and any brick-and-mortar business, **local SEO is the fastest path to real walk-in traffic**. When someone searches "spoken english classes in T. Nagar" instead of just "spoken english classes," they are ready to visit. They have already decided to act — they just need to find the right place.

Google's local algorithm rewards content that:
- Mentions the **exact location** naturally
- Targets **hyper-local keywords** (area + service)
- Includes **practical local signals** (nearby landmarks, transport routes, area context)
- Matches the **search intent** of someone physically near that location

---

## Prompt Template — Local SEO Adapter

```
You are a local SEO specialist and content writer.

I have an existing blog on the following topic. Your job is to adapt it for a specific city and service area.

---

### EXISTING BLOG DETAILS

Blog Topic: [BLOG_TOPIC]
Current Target Keyword: [CURRENT_KEYWORD]

---

### LOCAL ADAPTATION DETAILS

Business Name: [BUSINESS_NAME]
City: [CITY]
Neighborhood / Area: [NEIGHBORHOOD]
State: [STATE]
Country: [COUNTRY]

New Target Keyword: [SERVICE] in [NEIGHBORHOOD] [CITY]

Nearby Landmarks (for local context): [LANDMARK_1], [LANDMARK_2], [LANDMARK_3]

Nearby Metro / Transport: [METRO_STATION or BUS_ROUTE]

---

### YOUR TASKS

1. **Rewrite the H1** to include the new local keyword naturally.

2. **Rewrite the meta title** (under 60 characters) with [NEIGHBORHOOD] + [CITY] + [SERVICE].

3. **Rewrite the meta description** (140–155 characters) with the local keyword and a CTA.

4. **Rewrite the introduction** (100–150 words):
   - Mention [CITY] and [NEIGHBORHOOD] in the first two sentences
   - Reference why this specific area is convenient for the target audience
   - Mention at least one nearby landmark or transport point naturally

5. **Add a new H2 section** titled:
   "Why [NEIGHBORHOOD], [CITY] is a Great Place to Learn Spoken English"
   - Write 150–200 words about the area
   - Mention connectivity, working population, student density, or any local relevance
   - Do not invent facts — write in general, honest terms

6. **Rewrite the CTA** to include the area name and a local action (visit us in [NEIGHBORHOOD], call our [CITY] centre, etc.)

7. **Update the slug** to include the location:
   Format: [service-slug]-in-[neighborhood]-[city]

8. **Suggest 3 local SEO meta tags** (as HTML):
   - <title>
   - <meta name="description">
   - <meta name="keywords"> (for local signals — even though Google doesn't use this for ranking, it's useful for documentation)

---

Rules:
- Do not change the core advice or informational content of the original blog
- Only localize: headings, intro, CTA, one new section, and meta fields
- Mention the location keyword 3–5 times naturally across the full article
- Do not stuff the location into every sentence — it must read naturally
- Never invent local facts (population numbers, area statistics, etc.)
```

---

## Variable Reference Table

Use this table to quickly fill in your prompt for any city:

| Variable | Chennai Example | Mumbai Example | Hyderabad Example |
|---|---|---|---|
| `[CITY]` | Chennai | Mumbai | Hyderabad |
| `[NEIGHBORHOOD]` | T. Nagar | Andheri West | Kukatpally |
| `[STATE]` | Tamil Nadu | Maharashtra | Telangana |
| `[LANDMARK_1]` | Panagal Park | Lokhandwala Market | KPHB Colony |
| `[LANDMARK_2]` | Pondy Bazaar | Andheri Railway Station | Hitech City |
| `[METRO_STATION]` | T. Nagar Metro | Andheri Metro | Miyapur Metro |

---

## How to Use for Multiple Cities (Scale Strategy)

If you serve students across multiple areas of Chennai, you can run this prompt multiple times to create **city-area landing pages or blog variants**:

| Area | Target Keyword |
|---|---|
| T. Nagar | spoken english classes in t nagar chennai |
| Anna Nagar | spoken english classes in anna nagar chennai |
| Velachery | spoken english institute in velachery |
| Tambaram | english speaking course in tambaram |
| Adyar | spoken english coaching in adyar chennai |

Each adapted blog or landing page targets a **hyper-local search query** — dramatically increasing your chances of appearing in local Google search results.

---

## Tips for Local SEO Beyond Blogs

This prompt handles **on-page local SEO**. For full local SEO impact, also:

- Add your business to **Google Business Profile**
- Include your **NAP (Name, Address, Phone)** consistently on every page
- Get listed in **local directories** (Sulekha, Justdial, UrbanPro)
- Ask students for **Google Reviews** mentioning the area name

---

*Local SEO is where small coaching institutes beat big national platforms. A student searching "spoken english classes in T. Nagar" is not looking for a YouTube channel — they are looking for a place they can walk into tomorrow.*
