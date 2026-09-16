# Fragrance Market Intelligence

### AI-Assisted Market Research & Intelligence System

An AI-powered market intelligence workflow for analyzing the global fragrance and perfume industry using **Amazon QuickSuite**, structured product-level data, external research signals, and an evidence-driven analytical framework.

The project combines quantitative product analysis with AI-assisted research to produce traceable market insights, strategic implications, confidence assessments, and an executive-ready market intelligence brief.

---

## 🔗 Project Links

### Interactive Market Intelligence Brief
**[Open the Interactive Website](./index.html)**

### Amazon QuickSuite Market Intelligence Agent
**[Open the QuickSuite Agent](https://us-west-2.quicksight.aws.amazon.com/sn/account/UdacityQuicksightLab/start/agents?view=a8616414-904d-4bb6-aea9-ae59ed1f4688)**

> **Note:** The QuickSuite Agent requires access to the corresponding Amazon QuickSight/QuickSuite environment.

---

# Overview

The fragrance industry is influenced by rapidly changing consumer preferences, product positioning, ingredient and accord trends, premiumization, gender positioning, digital discovery, and regional market differences.

Traditional market research often separates structured product data from qualitative market research.

This project creates a unified AI-assisted workflow that combines both.

### Core question

> **How can structured fragrance product data and external market research be combined to identify reliable, actionable signals in the global fragrance market while clearly separating verified evidence from inference and interpretation?**

---

# Objectives

The system was designed to:

- Analyze historical fragrance product and launch patterns
- Identify changes in gender positioning
- Analyze fragrance accord and gourmand trends
- Examine product-level rating and engagement signals
- Incorporate external market research through AI-assisted research
- Cross-check internal observations against external evidence
- Identify market signals and strategic implications
- Quantify confidence and document limitations
- Produce an executive-ready Market Intelligence Brief

---

# System Architecture

```text
                    ┌─────────────────────────┐
                    │   Internal Dataset      │
                    │   fra_cleaned.csv       │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │   Amazon QuickSuite     │
                    │   Market Intelligence   │
                    │        Agent             │
                    └────────────┬────────────┘
                                 │
              ┌──────────────────┼──────────────────┐
              ▼                  ▼                  ▼
       Quick Research      Market Analysis    Evidence Review
              │                  │                  │
              └──────────────────┼──────────────────┘
                                 ▼
                    ┌─────────────────────────┐
                    │ Reliability & Confidence│
                    │       Assessment        │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │ Market Intelligence      │
                    │         Brief            │
                    └────────────┬────────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │ Interactive Web Report   │
                    └─────────────────────────┘
````

---

# Methodology

The project uses two primary evidence streams.

## 1. Internal Product Dataset

The internal dataset is based on fragrance product/catalog information and was used to analyze:

* Launch years
* Brand information
* Country
* Gender positioning
* Ratings
* Rating counts
* Perfumer information
* Fragrance notes
* Main accords

The dataset contains **24,063 records** spanning **1927–2024**.

It is treated as a product-level and community-platform observation source rather than as a direct measure of global market size or sales.

---

## 2. External Research

Amazon QuickSuite's research workflow was used to investigate external market signals and contextual evidence, including:

* Market growth
* Premium fragrance trends
* Consumer behavior
* Digital discovery
* Regulatory developments
* Company and industry signals
* Regional differences
* Competitive dynamics

External research was used to contextualize and corroborate observations from the internal dataset.

---

# Evidence Framework

A strict evidence classification system was used throughout the analysis.

| Classification             | Meaning                                                     |
| -------------------------- | ----------------------------------------------------------- |
| **VERIFIED FACT**          | Directly supported by a reliable source or calculation      |
| **DATASET OBSERVATION**    | Pattern calculated directly from the internal dataset       |
| **ANALYST INTERPRETATION** | Reasoned interpretation based on available evidence         |
| **INFERENCE**              | Plausible conclusion that is not directly established       |
| **CANNOT CONCLUDE**        | The available evidence is insufficient to support the claim |

This framework prevents unsupported market claims from being presented as established facts.

---

# Key Market Signals

## 1. Growth of Unisex Positioning

Analysis of the internal product dataset indicates a substantial increase in unisex fragrance positioning over time.

The dataset shows unisex positioning increasing from approximately **12.8% during 2000–2009** to more than **50% among recent launches**.

This is treated as a product-positioning observation rather than direct evidence of consumer market share.

---

## 2. Increasing Importance of Sweet & Gourmand Profiles

Sweet accords show increasing representation within recent fragrance launches.

The analysis identified growth in sweet accord representation from approximately **32.9% in 2018 to 41.6% in 2024**.

Gourmand-containing launches also increased from approximately **42.0% in 2018 to 51.1% in 2023**.

These findings describe patterns in the analyzed product dataset and should not be interpreted as total industry sales shares.

---

## 3. Changing Accord Hierarchy

The dataset indicates that sweet accords displaced citrus as the second-most represented major accord in 2024.

This provides a product-development signal that can be investigated alongside external consumer and market research.

---

## 4. Premiumization

External market research and company-level evidence indicate continued relevance of premium and prestige fragrance segments.

However, the internal dataset does **not** contain:

* Retail price
* Revenue
* Unit sales
* Gross margin
* Distribution costs

Therefore, product ratings or product counts are not used as direct measures of premium-market performance.

---

## 5. Digital Discovery & Challenger Brands

External research was used to investigate the role of digital discovery, social platforms, emerging brands, and changing consumer pathways.

These signals are presented as contextual evidence rather than as causal explanations for individual product-level trends.

---

# Reliability & Confidence

Each major finding was evaluated against multiple dimensions:

### Source Quality

How authoritative and relevant is the underlying source?

### Consistency

Is the finding supported by multiple evidence streams or independent observations?

### Timeliness

How current is the supporting evidence?

### Overall Confidence

How strongly does the available evidence support the conclusion?

The analysis also explicitly documents where evidence is insufficient.

---

# Limitations

The internal dataset has important limitations.

### No sales data

The dataset does not provide:

* Revenue
* Unit sales
* Market share
* Retail price
* Distribution volume
* Profitability

Therefore, product frequency cannot be interpreted as market share.

### Community-platform bias

The product dataset is based on fragrance catalog/community-platform observations and may overrepresent fragrance enthusiasts relative to the overall consumer population.

### Regional representation

The dataset should not be treated as a statistically representative sample of every geographic market.

### No causal inference

Observed relationships are not automatically treated as causal relationships.

For example:

> A growing accord trend does not by itself establish why consumers prefer that accord.

### Market-size variation

External market reports can use different market definitions, inclusion criteria, and geographic scopes.

Where estimates differ, the project preserves that uncertainty rather than presenting a false single-point estimate.

---

# What This Project Does NOT Claim

The analysis does **not** claim that:

* Product count equals market share
* Rating count equals sales
* Dataset representation equals consumer preference
* Correlation proves causation
* A fragrance accord trend automatically represents revenue growth
* External CAGR estimates are directly comparable when market definitions differ
* The internal dataset represents the entire global fragrance market

These constraints are central to the analytical methodology.

---

# Project Deliverables

| Deliverable                | Description                                               |
| -------------------------- | --------------------------------------------------------- |
| `index.html`               | Interactive Market Intelligence Brief                     |
| Research Brief             | Research objective, scope, questions, methodology         |
| Market Analysis            | Evidence-based market findings and strategic implications |
| Reliability Assessment     | Confidence, evidence quality, and limitations             |
| QuickSuite Agent           | AI-assisted research and analysis workflow                |
| QuickSuite Evidence        | Screenshots documenting the AI workflow                   |
| Market Intelligence Report | Executive-ready consolidated report                       |

---

# Repository Structure

```text
Fragrance-Market-Intelligence/
│
├── index.html
├── README.md
├── .gitignore
│
├── research/
│   ├── Research-Brief.docx
│   ├── Market-Analysis.docx
│   └── Reliability-Confidence-Assessment.docx
│
├── reports/
│   ├── Market-Intelligence-Report.pdf
│   ├── Research-Brief.pdf
│   └── Reliability-Confidence-Assessment.pdf
│
├── QuickSuite/
│   └── Final-QA-Audit.pdf
│
├── evidence/
│   ├── quicksuite-agent.png
│   ├── quick-research.png
│   ├── market-analysis.png
│   ├── reliability-assessment.png
│   └── final-qa.png
```

---

# Technology & Tools

### AI / Research

* Amazon QuickSuite
* AI-assisted research
* Evidence synthesis
* Structured analytical prompting

### Data

* Python-compatible CSV dataset
* Product-level fragrance records
* Quantitative trend analysis

### Web

* HTML
* CSS
* JavaScript
* Responsive interactive report design

### Documentation

* PDF
* DOCX
* Markdown

---

# AI Workflow

The Market Intelligence Agent was designed to follow a structured process:

```text
Research Question
       ↓
Define Scope
       ↓
Query Internal Dataset
       ↓
Conduct External Research
       ↓
Cross-Check Evidence
       ↓
Identify Market Signals
       ↓
Classify Evidence
       ↓
Assess Confidence
       ↓
Document Limitations
       ↓
Generate Strategic Implications
       ↓
Produce Leadership Brief
```

The objective is not simply to generate a market report, but to maintain a transparent chain between:

**Question → Evidence → Analysis → Confidence → Implication**

---

# Strategic Use

The resulting intelligence framework can support questions related to:

* Product development
* Fragrance positioning
* Consumer trend monitoring
* Portfolio strategy
* Premiumization research
* Competitive intelligence
* Market-entry research
* Emerging category identification

Strategic implications are presented as evidence-informed considerations rather than unsupported predictions.

---

# Reproducibility

The analysis is designed around traceable evidence.

Where possible, findings are linked to:

1. The underlying dataset
2. Calculated dataset observations
3. External research
4. Source quality
5. Confidence assessment
6. Known limitations

The raw dataset is not redistributed in this repository. Users should obtain it from its original source and comply with the applicable dataset licensing terms.

---

# Amazon QuickSuite Agent

The complete AI-assisted Market Intelligence Agent is available in the Amazon QuickSuite environment:

**[Launch Market Intelligence Agent](https://us-west-2.quicksight.aws.amazon.com/sn/account/UdacityQuicksightLab/start/agents?view=a8616414-904d-4bb6-aea9-ae59ed1f4688)**

The QuickSuite environment contains the research workflow and associated intelligence outputs.

---

# Interactive Report

The project also includes an interactive browser-based presentation of the final intelligence:

**[Open Interactive Market Intelligence Brief](./index.html)**

The website provides a visual interface for exploring the research findings, market signals, evidence, and strategic implications.

---

# Research Philosophy

This project follows an evidence-first approach:

> **Strong claims require strong evidence.**

When evidence is incomplete, the analysis explicitly identifies the limitation rather than filling the gap with assumptions.

The distinction between **observation, interpretation, inference, and verified fact** is therefore a core part of the system design.

---

# Author

**Kasmya Bhatia**

---

## Disclaimer

This project is an AI-assisted research and analytical exercise.

The findings should be interpreted within the documented dataset, source, methodological, and representation limitations. The analysis is not intended to represent audited industry statistics, investment advice, or a substitute for primary market research.
