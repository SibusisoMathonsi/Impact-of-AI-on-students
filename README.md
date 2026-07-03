# Impact of AI on Students: Analyzing Academic Performance and AI Adoption Trends
> *Analyzed a dataset of 14,000+ students to determine how Generative AI usage patterns, proficiency, and institutional policies correlate with academic performance, assignment satisfaction, and stress levels.*

---

## ⚙️ Project Type Flags
- [x] Exploratory Data Analysis (EDA)
- [x] SQL Analysis / Querying
- [ ] Dashboard / Data Visualization
- [ ] Data Pipeline / ETL
- [ ] Predictive Modelling / Machine Learning
- [x] Data Cleaning / Wrangling
- [ ] End-to-End (multiple of the above)

---

## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Objectives](#2-objectives)
3. [Project Scope & Tools](#3-project-scope--tools)
4. [Repository Structure](#4-repository-structure)
5. [Data Workflow](#5-data-workflow)
6. [Data Model & Schema](#6-data-model--schema)
7. [ERD - Entity Relationship Diagram](#7-erd--entity-relationship-diagram)
8. [Analysis & Metrics](#8-analysis--metrics)
9. [Key Insights](#9-key-insights)
10. [Recommendations](#10-recommendations)
11. [Assumptions & Limitations](#11-assumptions--limitations)
12. [Future Enhancements](#12-future-enhancements)
13. [Deliverables](#13-deliverables)
14. [Author](#14-author)

---

## 1. Project Overview

**Context:** Universities are currently grappling with how Generative AI affects student learning. While some institutions are banning AI tools, others are actively encouraging them, but data on how these policies actually impact student outcomes is scarce.

**Problem Statement:** Educational institutions need to understand whether Generative AI usage is acting as a tool for academic enhancement or a shortcut that negatively impacts learning, and how institutional policies affect student well-being.

**Approach:** I analyzed a comprehensive dataset of over 14,000 student records using MySQL. I utilized SQL aggregations, CTEs, and Window Functions to track AI usage hours, segment primary use cases (e.g., Ideation vs. Direct Answer Generation), and compare pre- and post-semester GPAs across different academic majors.

**Outcome:** The analysis revealed distinct correlations between how students use AI (proficiency and use case) and their academic outcomes. It also highlighted that institutional AI policies significantly impact student stress levels, providing actionable data for university administrators to refine their academic integrity guidelines.

---

## 2. Objectives

- **Primary Objective:** Quantify the relationship between weekly GenAI usage hours and changes in student academic performance (Pre-Semester vs. Post-Semester GPA).
- **Secondary Objective 1:** Identify the most common primary use cases for GenAI across different academic majors and year of study.
- **Secondary Objective 2:** Evaluate how different institutional AI policies (e.g., "Allowed with Citation" vs. "Strict Ban") impact student stress levels and assignment satisfaction scores.

> 💡 *Every SQL query and analytical decision in this project traces back to one of these objectives.*

---

## 3. Project Scope & Tools

### Scope

| Dimension | Details |
|-----------|---------|
| **In Scope** | 14,000+ student records covering demographics, AI usage metrics (hours, tools, proficiency), academic performance (GPA, satisfaction), and institutional policies. |
| **Out of Scope** | Longitudinal tracking beyond a single semester; qualitative interview data; actual LMS (Canvas/Blackboard) login data. |
| **Time Period** | Single semester snapshot (2023/2024 academic year). |
| **Granularity** | Row-level data representing individual student survey responses and self-reported metrics. |

### Tools & Technologies

| Category | Tool(s) Used |
|----------|-------------|
| Data Storage | MySQL (Relational Database) |
| Data Processing | SQL (Querying, Aggregations, CTEs, Window Functions) |
| Analysis | Custom SQL scripts for descriptive statistics and segmentation |
| Visualization | GitHub Markdown (Data storytelling) |
| Version Control | Git / GitHub |
| Documentation | Markdown |

---

## 4. Repository Structure
