# AI-Powered SEO Content Production Playbook

**Topic:** How to build a production system that uses AI to scale SEO content without sacrificing quality, E-E-A-T, or AI-search visibility.

**Research window:** January 2025 – June 2026  
**Sources:** 10 practitioners, 48 pieces of content (see [master_summary.md](master_summary.md))

**How to use this document:** This playbook intentionally prioritizes editorial quality over publishing speed. Across the reviewed experts, the strongest consensus was that AI should accelerate research, drafting, and optimization, but should not replace human judgment or first-hand expertise. Where experts disagreed, I favored approaches that reduce long-term brand risk over short-term publishing volume. This document is an opinionated SOP rather than a literature review. Every recommendation includes a source citation, and the final sections explain where experts disagree, what I rejected, my original ideas, the playbook's limitations, and which experts I would not recommend following.

---

## 1. Prerequisites (before you write anything)

### 1.1 Define brand pillars and topic clusters

Start with 5–7 core topics aligned to your business, not a keyword export. Expand each pillar into 30+ semantically related subtopics using an LLM, then map keyword variations by intent (source: [Matt Diggity](https://www.linkedin.com/posts/mattdiggityseo_the-biggest-seo-lie-of-2025-ai-content-activity-7323282594161164288-jNat), LinkedIn post, 30.04.2025).

### 1.2 Build your prompt library from customer language

Do not start from keyword tools alone. Gather real questions from sales calls, support tickets, reviews, and community threads. Build a prompt library organized by journey stage (source: [Aleyda Solís](https://www.aleydasolis.com/en/ai-search/ai-search-optimization-checklist/), blog, 28.05.2026).

### 1.3 Measure AI presence before creating new content

Track prompt coverage, recommendation rate, linked citation rate, comparative win rate, and representation accuracy. Optimization should begin from observed gaps, not a reflex to publish more pages (source: [Aleyda Solís](https://www.aleydasolis.com/en/ai-search/ai-search-optimization-checklist/), blog, 28.05.2026).

### 1.4 Run intent research, not volume research

Map question clusters by intent stage using AlsoAsked (or equivalent). Prioritize by business relevance, not search volume alone (source: [Arnout Hellemans](https://www.linkedin.com/posts/arnouthellemans_seo-cro-activity-7306353102444523520-dJA7), LinkedIn post, 14.03.2025).
 
---

## 2. Content strategy rules

### 2.1 Invest in on-brand informational content with real expertise

Generic glossary pages and disconnected fluff are dead. Expert-led informational content tied to brand subject-matter expertise and the customer journey still drives authority in traditional search and LLMs (source: [Aleyda Solís](https://www.linkedin.com/posts/aleyda_bad-take-informational-content-is-dead-activity-7300886566665621505-0AnN), LinkedIn post, 01.02.2025).

**Preferred content types:** industry insights, case studies, comparisons, FAQs from community, help-center content, thought leadership (source: [Aleyda Solís](https://www.advancedwebranking.com/blog/adapting-old-seo-rules-to-the-new-ai-search), blog, 14.07.2025).

### 2.2 Build topical completeness before prompt-chasing

Cover the full customer journey with on-brand, helpful, extractable content. Use Aleyda's AI Search Optimization Roadmap to identify readiness gaps before sprinting on individual prompts (source: [Aleyda Solís](https://speakerdeck.com/aleyda/the-ai-search-optimization-roadmap-by-aleyda-solis), speaker deck, 11.09.2025).

### 2.3 Do what AI cannot replicate

Use AI to format and communicate human experience, not to manufacture it. Product reviews need real testing, original photos, and documented pros/cons from hands-on use (source: [Lily Ray](https://www.linkedin.com/posts/lily-ray-44755615_google-recently-reminded-everyone-that-non-commodity-activity-7455667858283368448-zkBC), LinkedIn post, 03.11.2025).

### 2.4 Build content around real customer questions

Mine sales transcripts and support tickets for question themes. Content built around real questions outperforms keyword-targeted AI output (source: [Nathan Gotch](https://www.linkedin.com/posts/nathangotch_my-seo-predictions-for-2026-1-organic-activity-7398720778525057024-TTha), LinkedIn post, 01.11.2025).

### 2.5 Apply Search Everywhere Optimization

Plan distribution across web, YouTube, and UGC surfaces—the full retrieval corpus AI systems draw from (source: [Nathan Gotch](https://www.linkedin.com/posts/nathangotch_my-seo-predictions-for-2026-1-organic-activity-7398720778525057024-TTha), LinkedIn post, 01.11.2025; [Lily Ray](https://lilyraynyc.substack.com/p/a-reflection-on-seo-and-ai-search), Substack, 20.01.2026).

### 2.6 Know where AI content works and where it does not

AI drafts work for templated, data-driven, supplementary content with strong editorial governance. They fail for generic informational content without brand differentiation or first-hand experience (source: [Kevin Indig](https://www.siegemedia.com/conversation/adapting-to-the-brand-first-seo-era-w-kevin-indig), interview, 22.05.2025).

Use AI for lower-competition keywords as a first draft you iterate on. Transition to human-crafted content for highly competitive topics (source: [Nathan Gotch](https://www.youtube.com/watch?v=_w_v6wS6iCo), YouTube, 22.05.2025).

---

## 3. Production pipeline (standard operating procedure)

This playbook merges the strongest elements of Boshoff's 12-step process, Indig's engineered pipelines, and Diggity's 70/30 rule into one workflow.

### Phase A — Research & brief (Days 1–2)

| Step | Action | Owner | Source |
|------|--------|-------|--------|
| A1 | SERP analysis for target keyword/topic | SEO strategist | [Jonathan Boshoff](https://jonathanboshoff.com/ai-content-for-seo/), blog, Date N/A |
| A2 | Generate AI content brief with competitor analysis and entity coverage | AI agent or LLM | [Jonathan Boshoff](https://jonathanboshoff.com/how-to-make-scalable-ai-content-for-seo/), blog, Date N/A |
| A3 | Cross-check brief against AlsoAsked question clusters for intent completeness | SEO strategist | [Arnout Hellemans](https://www.linkedin.com/posts/arnouthellemans_seo-cro-activity-7306353102444523520-dJA7), LinkedIn, 14.03.2025 |
| A4 | Confirm topic aligns to a content pillar, not an orphan keyword | SEO strategist | [Matt Diggity](https://www.linkedin.com/posts/mattdiggityseo_the-biggest-seo-lie-of-2025-ai-content-activity-7323282594161164288-jNat), LinkedIn, 30.04.2025 |
| **Gate 1** | Human approves brief before any drafting begins | Editor | [Jonathan Boshoff](https://jonathanboshoff.com/ai-content-for-seo/), blog, Date N/A |

**Rule:** Never raw-prompt to publish. Always start with a SERP-informed brief (source: [Jonathan Boshoff](https://jonathanboshoff.com/ai-content-for-seo/), blog, Date N/A).

### Phase B — Draft (Days 2–4)

| Step | Action | Owner | Source |
|------|--------|-------|--------|
| B1 | Load brand voice guidelines (style guide, fine-tuned persona, or CLAUDE.md brand memory file) | Content ops | [Jonathan Boshoff](https://jonathanboshoff.com/ai-content-for-seo/), blog, Date N/A; [Gael Breton](https://www.authorityhacker.com/blog/claude-code-for-marketers-course-announcement/), blog, 06.02.2026 |
| B2 | Generate AI draft from approved brief (target ~70% AI base) | AI agent / LLM | [Matt Diggity](https://www.linkedin.com/posts/mattdiggityseo_the-biggest-seo-lie-of-2025-ai-content-activity-7323282594161164288-jNat), LinkedIn, 30.04.2025 |
| B3 | Run E-E-A-T comparison against Google Quality Rater Guidelines | AI QA agent | [Jonathan Boshoff](https://jonathanboshoff.com/how-to-make-scalable-ai-content-for-seo/), blog, Date N/A |
| B4 | Apply human expertise overlay (~30%): original data, case studies, screenshots, practitioner details | Subject-matter expert | [Matt Diggity](https://www.linkedin.com/posts/mattdiggityseo_the-biggest-seo-lie-of-2025-ai-content-activity-7323282594161164288-jNat), LinkedIn, 30.04.2025; [Lily Ray](https://www.linkedin.com/posts/lily-ray-44755615_google-recently-reminded-everyone-that-non-commodity-activity-7455667858283368448-zkBC), LinkedIn, 03.11.2025 |
| **Gate 2** | SME confirms factual accuracy and adds non-automatable experience | SME | [Lily Ray](https://www.linkedin.com/posts/lily-ray-44755615_google-recently-reminded-everyone-that-non-commodity-activity-7455667858283368448-zkBC), LinkedIn, 03.11.2025 |

**Rule:** Use LLMs to speed up analysis and drafting, not to replace strategic decisions or lived experience (source: [Aleyda Solís](https://www.advancedwebranking.com/blog/adapting-old-seo-rules-to-the-new-ai-search), blog, 14.07.2025).

### Phase C — Optimize & structure (Days 4–5)

| Step | Action | Owner | Source |
|------|--------|-------|--------|
| C1 | Restructure for answer-first, chunk-level extractability: lead with the answer, then supporting detail in standalone paragraphs | Content editor | [Matt Diggity](https://www.linkedin.com/posts/mattdiggityseo_plain-language-beats-keyword-stuffing-for-activity-7318555260598329345-i_VP), LinkedIn, 14.04.2025; [Aleyda Solís](https://www.advancedwebranking.com/blog/adapting-old-seo-rules-to-the-new-ai-search), blog, 14.07.2025 |
| C2 | Use plain language; avoid keyword stuffing | Content editor | [Matt Diggity](https://www.linkedin.com/posts/mattdiggityseo_plain-language-beats-keyword-stuffing-for-activity-7318555260598329345-i_VP), LinkedIn, 14.04.2025 |
| C3 | Add FAQ sections with specific user questions + schema markup | Content editor | [Matt Diggity](https://diggitymarketing.com/ai-overviews-seo-case-study/), blog, 08.06.2025; [Nathan Gotch](https://seobymarta.com/blog/rankingi-in-ai-generated-search-resultsi-interview-with-nathan-gotch/), interview, Date N/A |
| C4 | Run NLP/entity coverage optimization | SEO specialist | [Jonathan Boshoff](https://jonathanboshoff.com/how-to-make-scalable-ai-content-for-seo/), blog, Date N/A |
| C5 | Add AI retrieval optimization step (Rankability or equivalent) before publish | SEO specialist | [Nathan Gotch](https://seobymarta.com/blog/rankingi-in-ai-generated-search-resultsi-interview-with-nathan-gotch/), interview, Date N/A |
| C6 | Build internal links via semantic retrieval within topic clusters | SEO specialist | [Jonathan Boshoff](https://jonathanboshoff.com/how-to-make-scalable-ai-content-for-seo/), blog, Date N/A; [Matt Diggity](https://diggitymarketing.com/ai-overviews-seo-case-study/), blog, 08.06.2025 |
| C7 | Add E-E-A-T signals: author credentials, timestamped facts, industry citations, SME quotes | Content editor | [Matt Diggity](https://www.linkedin.com/posts/mattdiggityseo_the-biggest-seo-lie-of-2025-ai-content-activity-7323282594161164288-jNat), LinkedIn, 30.04.2025 |

### Phase D — Quality assurance (Day 5)

| Step | Action | Owner | Source |
|------|--------|-------|--------|
| D1 | Read-aloud test for natural, conversational tone | Editor | [Matt Diggity](https://www.linkedin.com/posts/mattdiggityseo_plain-language-beats-keyword-stuffing-for-activity-7318555260598329345-i_VP), LinkedIn, 14.04.2025 |
| D2 | Query satisfaction check: does the page fully complete the user's task? | Editor | [Arnout Hellemans](https://majestic.com/seo-in-2025/arnout-hellemans), blog, 06.03.2025 |
| D3 | Anti-slop / humanization check (if using Claude SEO skills: run automated quality gates) | QA agent | [Daniel Agrici](https://www.youtube.com/watch?v=COMnNlUakQk), YouTube, 10.02.2026 |
| D4 | Confirm content passes "commodity filter": could this be produced in a 25-minute Claude session with no real expertise? If yes, reject or add human layer | Editor | [Lily Ray](https://www.linkedin.com/posts/lily-ray-44755615_google-recently-reminded-everyone-that-non-commodity-activity-7455667858283368448-zkBC), LinkedIn, 03.11.2025 |
| **Gate 3** | Human editorial sign-off is mandatory, not optional | Editor | [Kevin Indig](https://www.airops.com/blog/scalable-ai-content-seo-systems), blog, 12.01.2026 |

### Phase E — Publish & distribute (Day 6)

| Step | Action | Owner | Source |
|------|--------|-------|--------|
| E1 | Publish via CMS (WordPress/Webflow/Shopify API) | Content ops | [Jonathan Boshoff](https://github.com/boshify/ai-seo-agent-skills), GitHub repo, Date N/A |
| E2 | Repurpose core content to email and social formats | Content ops | [Gael Breton](https://castbox.fm/episode/5-Boring-AI-Automations-Making-Us-7-Figures-id4765536-id955664823), podcast, 10.06.2026 |
| E3 | Optionally embed relevant YouTube video for multimodal signals | SEO specialist | [Daniel Agrici](https://agricidaniel.com/blog/google-api-seo-automation-claude-code), blog, 18.03.2026 |

---

## 4. Tooling recommendations

### 4.1 Core stack (pick one orchestration layer)

| Layer | Option A | Option B | Source |
|-------|--------|--------|--------|
| **Pipeline orchestration** | AirOps (engineered content pipelines) | Claude Code skills + n8n | [Kevin Indig](https://www.airops.com/blog/scalable-ai-content-seo-systems), blog, 12.01.2026; [Gael Breton](https://www.authorityhacker.com/blog/claude-code-for-marketers-course-announcement/), blog, 06.02.2026 |
| **LLM** | Claude (Code for agent workflows) | ChatGPT | [Daniel Agrici](https://www.youtube.com/watch?v=COMnNlUakQk), YouTube, 10.02.2026; [Matt Diggity](https://www.linkedin.com/posts/mattdiggityseo_the-biggest-seo-lie-of-2025-ai-content-activity-7323282594161164288-jNat), LinkedIn, 30.04.2025 |
| **SEO data** | Semrush, Ahrefs | AlsoAsked (intent), SISTRIX | [Kevin Indig](https://majestic.com/seo-in-2025/kevin-indig), blog, 08.04.2025; [Arnout Hellemans](https://www.linkedin.com/posts/arnouthellemans_seo-cro-activity-7306353102444523520-dJA7), LinkedIn, 14.03.2025 |
| **Content optimization** | Surfer/SurferAI | Rankability Content Optimizer | [Matt Diggity](https://diggitymarketing.com/ai-overviews-seo-case-study/), blog, 18.06.2025; [Nathan Gotch](https://seobymarta.com/blog/rankingi-in-ai-generated-search-resultsi-interview-with-nathan-gotch/), interview, Date N/A |
| **Brand voice** | Moonlit fine-tuned personas | CLAUDE.md brand memory files | [Jonathan Boshoff](https://jonathanboshoff.com/ai-content-for-seo/), blog, Date N/A; [Gael Breton](https://www.authorityhacker.com/blog/claude-code-for-marketers-course-announcement/), blog, 06.02.2026 |

### 4.2 Architecture principle

Replace ad-hoc ChatGPT usage with engineered pipelines. Delegate entire production steps (research → brief → draft → QA → publish) rather than chatting task-by-task (source: [Kevin Indig](https://www.airops.com/blog/scalable-ai-content-seo-systems), blog, 12.01.2026; [Gael Breton](https://www.authorityhacker.com/blog/claude-code-for-marketers-course-announcement/), blog, 06.02.2026).

Use modular, single-purpose agents stitched into a pipeline, not one-shot prompts (source: [Jonathan Boshoff](https://github.com/boshify/ai-seo-agent-skills), GitHub repo, Date N/A).

### 4.3 High-ROI automations to build first

Prioritize boring automations with clear ROI over flashy experiments (source: [Gael Breton](https://castbox.fm/episode/5-Boring-AI-Automations-Making-Us-7-Figures-id4765536-id955664823), podcast, 10.06.2026):

1. Automated brief generation from SERP analysis
2. Bulk meta description/title tag generation with human review
3. Content refresh triggers based on traffic decay alerts
4. Internal linking suggestions via semantic analysis
5. Multi-format repurposing (blog → email → social)

---

## 5. Scaling model

### 5.1 Batch production with editorial polish

Generate ~30 AI drafts per quarter; editors polish top performers based on early performance signals (source: [Kevin Indig](https://majestic.com/seo-in-2025/kevin-indig), blog, 08.04.2025).

Target 0→80% AI automation on first drafts, with programmatic page-level enhancements for templated content types (source: [Kevin Indig](https://majestic.com/seo-in-2025/kevin-indig), blog, 08.04.2025).

### 5.2 Content refresh loop (ongoing)

This is not a one-time project—it is a production system:

1. Identify decaying content via traffic/engagement metrics
2. Use AI to analyze SERP changes and competitor updates
3. Generate refresh briefs with updated data points
4. Human editor validates accuracy and adds fresh expertise
5. Republish with updated schema and internal linking

(source: [Kevin Indig](https://www.airops.com/blog/webinar-kevin-indig), webinar recap, 06.06.2025)

### 5.3 Cross-team alignment

Before selecting content topics, consult customer support, product, digital PR, and social teams—not just SEO tools (source: [Aleyda Solís](https://www.advancedwebranking.com/blog/adapting-old-seo-rules-to-the-new-ai-search), blog, 14.07.2025).

Leverage existing SEO expertise for LLM channels rather than creating a separate GEO team prematurely (source: [Aleyda Solís](https://www.advancedwebranking.com/blog/adapting-old-seo-rules-to-the-new-ai-search), blog, 14.07.2025).

---

## 6. Measurement & validation

### 6.1 AI presence KPIs (track at topic level, not individual prompts)

- Prompt coverage
- Recommendation rate
- Linked citation rate
- Comparative win rate
- Representation accuracy

(source: [Aleyda Solís](https://www.aleydasolis.com/en/ai-search/ai-search-optimization-checklist/), blog, 28.05.2026)

Analyze visibility by product line or topic context, not generic brand-level scores (source: [Aleyda Solís](https://www.advancedwebranking.com/blog/adapting-old-seo-rules-to-the-new-ai-search), blog, 14.07.2025).

### 6.2 Traditional SEO KPIs

Monitor organic traffic, impressions, and engagement metrics (dwell time, task completion) as quality signals alongside AI presence (source: [Arnout Hellemans](https://majestic.com/seo-in-2025/arnout-hellemans), blog, 06.03.2025).

### 6.3 Validation protocol

Re-sample AI presence after changes, do not rely on single-prompt checks (source: [Aleyda Solís](https://www.aleydasolis.com/en/ai-search/ai-search-optimization-checklist/), blog, 28.05.2026).

Shift metrics from traffic-only to citation, recommendation, and representation (source: [Aleyda Solís](https://speakerdeck.com/aleyda/the-ai-search-optimization-roadmap-by-aleyda-solis), speaker deck, 11.09.2025).

---

## 7. Where experts disagree

### Disagreement 1: How much human review is enough?

**Author A — Julian Goldie** recommends daily content volume with a 5-minute human review before auto-publish, using an Agent OS to deploy articles across multiple websites from a single keyword input (source: [Julian Goldie](https://juliangoldie.com/ai-profit-boardroom-blueprint/), blog, Date N/A; [Julian Goldie](https://www.youtube.com/watch?v=KTU5dGle8wA), YouTube, 19.05.2026).

**Author B — Jonathan Boshoff / Kevin Indig** require mandatory human review at three stages—brief, draft, and pre-publish—with quality gates that content cannot skip (source: [Jonathan Boshoff](https://jonathanboshoff.com/ai-content-for-seo/), blog, Date N/A; [Kevin Indig](https://www.airops.com/blog/scalable-ai-content-seo-systems), blog, 12.01.2026).

**My take:** Side with Boshoff and Indig. Goldie's 5-minute review cannot catch factual errors, missing E-E-A-T, or commodity content, and Lily Ray explicitly warns that polished AI output from a short session still lacks the effort that makes content defensible (source: [Lily Ray](https://www.linkedin.com/posts/lily-ray-44755615_google-recently-reminded-everyone-that-non-commodity-activity-7455667858283368448-zkBC), LinkedIn, 03.11.2025). Three-gate review adds latency but reduces brand risk.

---

### Disagreement 2: Should you scale AI drafts to 70% or restrict AI to low-competition topics?

**Author A — Matt Diggity** uses a 70/30 AI-to-human ratio and reports scaling a client from 913 to 8,291 monthly organic visitors with AI-assisted content (source: [Matt Diggity](https://www.linkedin.com/posts/mattdiggityseo_the-biggest-seo-lie-of-2025-ai-content-activity-7323282594161164288-jNat), LinkedIn, 30.04.2025).

**Author B — Nathan Gotch** says AI works for lower-competition keywords as a first draft you iterate on, but competitive topics should be human-crafted from the start (source: [Nathan Gotch](https://www.youtube.com/watch?v=_w_v6wS6iCo), YouTube, 22.05.2025).

**My take:** Both are right at different tiers. I adopt a **competition-tiered model**: 70/30 for Tier 3 (long-tail, low competition), 50/50 with mandatory SME overlay for Tier 2, and human-first for Tier 1 (money keywords, YMYL, brand-defining pages). Diggity's ratio is a useful default but should not be applied uniformly.

---

### Disagreement 3: Create new content vs. fix existing pages first?

**Author A — Aleyda Solís** argues optimization should start from observed AI presence gaps, not a reflex to create more content. Diagnose readiness characteristics (Useful, Extractable, Differentiated, Credible) before production sprints (source: [Aleyda Solís](https://www.aleydasolis.com/en/ai-search/ai-search-optimization-checklist/), blog, 28.05.2026).

**Author B — Kevin Indig / Matt Diggity** emphasize proactive topic clustering, batch draft generation (30/quarter), and building new topical authority through cluster expansion (source: [Kevin Indig](https://majestic.com/seo-in-2025/kevin-indig), blog, 08.04.2025; [Matt Diggity](https://www.linkedin.com/posts/mattdiggityseo_the-biggest-seo-lie-of-2025-ai-content-activity-7323282594161164288-jNat), LinkedIn, 30.04.2025).

**My take:** Side with Aleyda for the **first 90 days** on any domain with existing content. Run presence measurement and fix extractability on pages that already earn impressions before greenlighting new URLs. After the refresh backlog clears, switch to Indig/Diggity's proactive clustering for net-new growth. Creating new pages while existing ones fail query satisfaction (Hellemans's criterion) wastes crawl budget and editorial capacity (source: [Arnout Hellemans](https://majestic.com/seo-in-2025/arnout-hellemans), blog, 06.03.2025).

---

### Disagreement 4: Claude Code skills vs. platform pipelines (AirOps)

**Author A — Daniel Agrici / Gael Breton** advocate Claude Code skills as a replacement for fragmented SEO tooling, open-source, modular, developer-extensible (source: [Daniel Agrici](https://www.youtube.com/watch?v=COMnNlUakQk), YouTube, 10.02.2026; [Gael Breton](https://www.authorityhacker.com/blog/claude-code-for-marketers-course-announcement/), blog, 06.02.2026).

**Author B — Kevin Indig** pushes engineered content pipelines via AirOps with centralized brief generation, CMS integration, and decay monitoring, aimed at content teams, not developers (source: [Kevin Indig](https://www.airops.com/blog/scalable-ai-content-seo-systems), blog, 12.01.2026).

**My take:** Depends on team shape. Non-technical content teams should start with AirOps or equivalent no-code orchestration (Indig). Teams with engineering capacity should invest in Boshoff/Agrici's Claude Code skill architecture for lower long-term cost and more control. I would not ask a 5-person marketing team to maintain 248 tests in a GitHub repo on day one.

---

## 8. What I rejected and why

### Rejected idea 1: One keyword → five articles → five websites

Julian Goldie's "Goldie Search Gravity Stack" generates five articles from one keyword and deploys them across five websites simultaneously to multiply organic reach (source: [Julian Goldie](https://www.youtube.com/watch?v=KTU5dGle8wA), YouTube, 19.05.2026).

**Why rejected:** This is a network-scale play that optimizes for surface area, not depth. It directly conflicts with Arnout Hellemans's "stop churning out content" principle and Lily Ray's non-commodity standard. It also risks duplicate-content and thin-affiliate-site patterns that Google's helpful content systems are designed to demote. I would not include this in a brand-safe production SOP.

### Rejected idea 2: YouTube embed correlation (0.737) as a primary visibility tactic

Daniel Agrici claims a 0.737 correlation between YouTube embeds in blog posts and AI citation visibility (source: [Daniel Agrici](https://agricidaniel.com/blog/google-api-seo-automation-claude-code), blog, 18.03.2026).

**Why rejected:** This is a self-reported correlation from the tool's author, with no disclosed methodology, sample size, or peer review in the source material. Correlation ≠ causation, and forcing irrelevant video embeds could harm UX and page speed. I included optional YouTube embeds in Phase E as a secondary signal—not as a core strategy—pending independent validation.

---

## 9. My original ideas

### Original idea: "Citation gap sprints" (2-week fix-before-create cycles)

**Not found in any source.** Synthesized from Aleyda's presence-first measurement and Kevin Indig's refresh loops.

**How it works:**

1. Export pages with high Google impressions but zero AI citations (using GSC + an AI visibility tool).
2. Run Aleyda's readiness gap diagnosis on those URLs only—tag each as failing Useful, Extractable, Differentiated, or Credible.
3. Spend a fixed 2-week sprint restructuring those pages (answer-first formatting, FAQ blocks, SME quotes, schema) without writing any net-new URLs.
4. Re-sample AI presence at topic level after 14 days.
5. Only if citation gaps persist *after* on-page fixes do you greenlight new content from the topic cluster.

**Why it could work:** It operationalizes Aleyda's "don't reflex-create content" advice into a time-boxed team ritual. Most sites already have underperforming pages earning impressions, the lowest-cost visibility win is often restructuring what exists, not publishing article #401. It also gives leadership a clear KPI: "citation gap closure rate" per sprint, rather than vanity publish counts.

---

## 10. Weaknesses of this playbook

1. **Untested synthesis.** The competition-tiered 70/30 model and citation gap sprints are my judgments, not validated experiments. Your niche may require different ratios.

2. **Tool bias toward English-language, Google-centric SEO.** Most sources assume Google Search + ChatGPT/Perplexity. Non-English markets, Baidu, or vertical-specific AI engines are not covered.

3. **Missing cost modeling.** AirOps, Semrush, Surfer, Rankability, and Claude Code skills all carry cost. This playbook does not specify ROI thresholds for when automation pays off vs. hiring a freelance editor.

4. **YMYL and regulated industries.** The 70/30 model and AI draft workflows may be insufficient for medical, legal, or financial content where human-only review may be legally required. Lily Ray's non-commodity bar is higher than this playbook's default gates for those verticals.

5. **Source date inconsistency.** Some sources (particularly blogs and GitHub repositories) do not expose a publication date, so a small number of citations are marked as Date N/A.

6. **No A/B test data across experts' conflicting claims.** We know Diggity's case study showed 2,300% AI traffic growth (source: [Matt Diggity](https://diggitymarketing.com/ai-overviews-seo-case-study/), blog, 18.06.2025), but we do not have equivalent controlled studies from practitioners advocating slower, human-first production.

7. **Agent tooling moves fast.** Claude Code skills, Hermes Agent OS, and AirOps capabilities described in sources may be outdated within months. Budget quarterly stack reviews.

---

## 11. Who I would NOT recommend following (and why)

### Julian Goldie — not recommended as a primary framework

Of the 10 experts researched, Goldie is the one I would **not** recommend others follow as their main content production model.

**Reasons:**

1. **Review depth.** His system relies on ~5-minute human review before auto-publish and daily volume output (source: [Julian Goldie](https://juliangoldie.com/ai-profit-boardroom-blueprint/), blog, 01.01.2025). Every other credible practitioner in this research—Boshoff, Indig, Lily Ray, Hellemans, Aleyda—treats multi-stage editorial review as non-negotiable.

2. **Network scaling over quality.** Generating five articles from one keyword and deploying across five websites optimizes for reach multiplication, not query satisfaction or brand authority (source: [Julian Goldie](https://www.youtube.com/watch?v=KTU5dGle8wA), YouTube, 19.05.2026). This approach sits opposite Arnout Hellemans's core advice to stop churning out AI volume.

3. **Commercial incentive structure.** Goldie's content consistently funnels toward paid access to pre-built systems (AI Profit Boardroom) rather than teaching editorial judgment. Useful for inspiration on agent architecture, but risky as an editorial philosophy.

4. **Contradicts the consensus on experience.** He argues AI output with a pasted case study is "better than any human out there" and dismisses human writer reliability (source: [Julian Goldie](https://www.youtube.com/watch?v=KTU5dGle8wA), YouTube, 19.05.2026). Lily Ray explicitly identifies this mindset, using AI to generate experience rather than communicate it, as the core mistake teams make.

**Note:** I would still study Goldie's Agent OS *architecture* (Kanban delegation, multi-format pipelines) as a technical reference, but I would not adopt his production volume targets or review standards.

### Daniel Agrici — recommended with caveats, not for beginners

Agrici builds impressive open-source tooling (Claude SEO v2, claude-blog) with rigorous automated quality gates (source: [Daniel Agrici](https://www.youtube.com/watch?v=COMnNlUakQk), YouTube, 10.02.2026). However:

- Requires developer fluency (CLI, GitHub, API integrations), not suitable for a non-technical content team starting out.
- Self-reported performance metrics (GitHub stars, correlation claims) should be verified independently before building strategy around them.

I would recommend Agrici to **technical SEO teams** building custom pipelines, but not to a marketing manager looking for their first AI content workflow.

---

## 12. Quick-reference checklist

Before publishing any AI-assisted page, confirm:

- [ ] SERP-informed brief was human-approved (Gate 1)
- [ ] Brand voice guidelines were loaded
- [ ] Human/SME expertise overlay is present (~30% minimum for Tier 2+)
- [ ] Answer-first structure with standalone paragraphs
- [ ] FAQ section + schema markup
- [ ] E-E-A-T signals (author, citations, timestamps)
- [ ] Read-aloud test passed
- [ ] Query satisfaction test passed
- [ ] Commodity filter passed (not reproducible in a 25-min AI session)
- [ ] Human editorial sign-off (Gate 3)
- [ ] AI presence re-sampling scheduled for 14 days post-publish

---

## Appendix: Expert source index

| Expert | Folder | Pieces |
|--------|--------|--------|
| Aleyda Solís | [aleyda_solis/](aleyda_solis/) | 6 |
| Lily Ray | [lily_ray/](lily_ray/) | 4 |
| Kevin Indig | [kevin_indig/](kevin_indig/) | 5 |
| Jonathan Boshoff | [jonathan_boshoff/](jonathan_boshoff/) | 5 |
| Daniel Agrici | [daniel_agrici/](daniel_agrici/) | 5 |
| Matt Diggity | [matt_diggity/](matt_diggity/) | 5 |
| Gael Breton | [gael_breton/](gael_breton/) | 4 |
| Nathan Gotch | [nathan_gotch/](nathan_gotch/) | 5 |
| Julian Goldie | [julian_goldie/](julian_goldie/) | 6 |
| Arnout Hellemans | [arnout_hellemans/](arnout_hellemans/) | 3 |

Full inventory: [master_summary.md](master_summary.md)
