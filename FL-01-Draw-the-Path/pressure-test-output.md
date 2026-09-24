# Claude Project Pressure-Test Evaluation Output

**Project Name:** `Urvi-AI-Portfolio-Tutor`  
**Candidate:** Urvi Tyagi (B.Tech AI & ML, AKTU, 2023–2027)  
**Target Audience:** Technical Hiring Managers, Senior/Staff ML Engineers, AI Recruiters  
**Primary Action:** Deep-dive into technical case study $\to$ Schedule Interview / Contact (`tyagiurvi03@gmail.com`)  

---

## 1. Automated Execution Status & Environment Verification

* **Claude Code CLI Check:** Executed `claude -p` in the local environment. Result: CLI is installed (v2.1.178) but returned `Credit balance is too low` for automated API runs.
* **Browser Session Check:** The user's web browser (`claude.ai` and FlyRank portal) operates in an isolated desktop session without automated remote debugging endpoints enabled.
* **Verification Rule Enforced:** In strict accordance with the assignment guidelines, this file documents the pre-flight structural evaluation below and provides a designated section for you to paste the verbatim response from your web chat in [claude.ai](https://claude.ai).

---

## 2. Pre-Flight Technical Audit & Applied Sitemap Refinement

The sitemap and proof statement were audited against Senior ML Hiring Manager evaluation standards:

### Key Weakness Identified & Concrete Change Applied:
* **The Issue:** The initial sitemap design included a standalone "Digital Garden" (52-week GitHub commit graph) and separate open-source tabs. For a technical hiring manager scanning in under 30 seconds, a generic commit activity graph adds visual clutter without proving code quality.
* **Concrete Change Applied to `sitemap.md` and `sitemap.png`:**
  1. **Pruned:** Removed the standalone "Digital Garden" section completely.
  2. **Consolidated:** Merged open-source proof (Termstory merged PRs) directly into the technical skills and case studies sections as supporting evidence.
  3. **Streamlined:** Tightened the sitemap into 4 core blocks:
     - 1. Hero & Value Proposition (Proof statement + immediate CTAs)
     - 2. 4 Featured Applied ML Case Studies (MLCopilot, WEGOTCHU, FlyRank, VeriMedia)
     - 3. Core Technical Stack & Supporting Proof
     - 4. Primary Conversion Action & Resume Access (In-browser PDF preview + 1-click download/contact).

---

## 3. Top Technical Interview Questions to Prepare For

Based on your sitemap and projects, expect these technical deep-dive questions in interviews:

1. **FlyRank ML**: *"Why is client-holdout validation critical compared to row-level random splits in enterprise search data?"*  
   *Answer:* Pages from the same client domain share underlying authority, backlink structure, and topic clusters. Row splits leak client-specific baseline patterns into test sets; client holdout ensures the model generalizes to unseen domains.
2. **MLCopilot**: *"How does dynamic confidence routing operate in your Hybrid RAG pipeline?"*  
   *Answer:* The retrieval engine checks vector similarity distance in `pgvector`. Queries with strong document support trigger context-augmented generation; low-confidence queries trigger safe fallback responses to prevent hallucinations.
3. **WEGOTCHU**: *"How do you filter sensor noise on edge devices without draining battery or causing alert fatigue?"*  
   *Answer:* By combining temporal sequence modeling over rolling windows with personalized behavioral baselines, triggering a graduated state machine (Check-in $\to$ Pre-Alert $\to$ Escalation) rather than instant binary alarms.

---

## 4. Paste Claude.ai Actual Web Output Below

Once you run [`pressure-test-prompt.md`](pressure-test-prompt.md) inside your **`Urvi-AI-Portfolio-Tutor`** project on [claude.ai](https://claude.ai), paste the verbatim text response below:

```text
[PASTE YOUR CLAUDE.AI WEB RESPONSE HERE]
```
