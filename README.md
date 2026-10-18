# AI-Assisted Insurance Communication Strategy For HDFC life

**Value mapping for unreached segments: a Corporate Internship Project building a data-driven, AI-assisted communication strategy for two underserved life insurance segments, New Job Employees and Away-from-Home individuals.**

---

## 📌 Problem

India's life insurance penetration is about 3.2% of GDP against a global average of 6.8% (IRDAI, 2023; Swiss Re Institute, 2023). The gap is not a product gap but a **communication and targeting gap**: insurers rely on broad, generalised advertising that does not speak to specific life situations.

This project focuses on two segments that are large, financially exposed and digitally active:
- **New Job Employees (NJE):** first-time earners, 10–12 million of whom enter formal employment each year (Ministry of Labour and Employment, 2023)
- **Away-from-Home (AfH) individuals:** internal migrants and first-generation urban professionals supporting families back home (Census of India, 2011)

**Research question:** Which life insurance values drive purchase consideration for these segments, and how can an AI-based tool automate the identification and deployment of value-specific communication?

## 🔎 Approach

Three layers of evidence:
1. **Government secondary data:** IRDAI, Ministry of Labour and Employment, MoSPI (PLFS) and Census of India, to size the segments and validate the gap
2. **Primary research (Value Resonance Mapping):** a Likert-scale questionnaire with separate forms per segment, rating **16 life insurance values** on a five-point scale from 25+ respondents per segment. Scores of 4.0+ marked a value as high-resonance and 4.5+ as priority.
3. **Competitor social media analysis:** publicly available posts from **8 major private life insurers** across Instagram, Facebook and YouTube, classified into six content types, to find gaps in segment-specific targeting

**Analysis methods:** descriptive statistics, gap analysis, Pareto (80/20) prioritisation, NLP sentiment analysis of comments as a cross-check, and AI prompt engineering.

## 📊 Key Findings

- **Competitor gap:** none of the 8 insurers analysed ran content specifically targeting NJE or AfH individuals
- **Both segments:** Family Security and Peace of Mind scored highest (5.0 / 5.0)
- **NJE:** Savings (4.7), Financial Protection (4.3) and Tax Benefits (4.3) followed, reflecting first-time earners navigating tax planning and wealth building
- **AfH:** Convenient Digital Services also scored 5.0, reflecting dependence on mobile-first, remotely accessible financial tools

## 🤖 AI Solution: Social Media Value-Segment Insight Generator

A structured prompt workflow, usable in ChatGPT or Claude, that needs no coding, installation or IT changes. Each week the user only supplies new competitor post data.

| Step | What it does |
|---|---|
| 1. Data input | Accepts brand, platform, date, caption and engagement data in any reasonable format |
| 2. Auto-classification | Assigns each post one of six content types and identifies the insurance values it conveys |
| 3. Gap analysis | Compares competitor patterns with a brand's planned content to find under-served value-segment combinations |
| 4. Recommendations | Produces three prioritised weekly content recommendations with a rationale |
| 5. Caption drafts | Produces 2–3 draft captions per recommendation for human review |

The prompt template has five parts: content type taxonomy, the 16-value taxonomy, segment profiles, the analysis workflow and a fixed output format.

**Results:** about 85% match with manually verified post classifications, and a weekly analysis that takes roughly 45 minutes instead of an estimated 3–5 hours of manual work.

## ⚠️ Limitations

- Small questionnaire sample (25+ per segment) collected through WhatsApp, alumni and digital groups, so it is not statistically representative
- Purchase intent is self-reported, not observed behaviour
- Competitor analysis covers a one-month snapshot of public posts
- AI outputs need human review before publication, and classification accuracy is about 85%, not 100%

## 📁 Repository Contents

- `README.md`: this file
- Add a redacted PDF of the report here only if it has been cleared for public sharing

## 👤 Author

**Arush Pratap Singh**, PGDM 2025–27, Fortune Institute of International Business (FIIB), New Delhi
Corporate Internship Project, Business Development, under faculty mentor Dr. Sahiba Sahny

## 📝 Disclaimer

This is an academic internship project. It is not affiliated with or endorsed by any company named in it, and it contains no confidential company data.
