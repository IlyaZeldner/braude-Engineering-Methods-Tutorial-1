#Ilya Zeldner - Software Engineering Methods (Course 61756) - Tutorial 1
**Braude College of Engineering**  
**Academic Year:** 2026-2027  
**Topic:** System Architecture, Use Case Behavioral Modeling, and Requirements Engineering (FR / NFR)

---

## 📌 Overview & Objectives
This repository contains the official lab exercise specification, architectural guides, modeling templates, and reference materials for **Laboratory Exercise 1: Smart Campus Parking, LPR, and EV Network**.

The pedagogical objective of this lab is to transition students from passive AI consumers to **Systems Architects & Tech Leads**:
1. Auditing AI-generated outputs for architectural flaws (dependency inversions, misplaced hardware boundaries, hallucinated database operations).
2. Implementing a modern **Docs-as-Code** workflow using Markdown, Mermaid.js, and PlantUML.
3. Managing system models inside **Visual Paradigm 18.1** and establishing full **Requirements Traceability (RTM)** to **BDD Acceptance Tests**.

---

## 📁 Repository Directory Structure

```text
├── 📄 תרגול 1.docx                          # Main Lab Exercise Specification Document
│
├── 📁 01_התקנות_וסביבת_פיתוח/              # Environment Setup & Toolchain Installation Guides
│   ├── מדריך מקיף לIntelliJ IDEA.docx       # IntelliJ IDEA Ultimate & BellSoft Liberica Full JDK 25
│   ├── מדריך לקופילוט.docx                 # GitHub Student Pack, Copilot activation & credit limits
│   ├── התקנת LM Studio והגדרת מודל ה AI.docx # Offline local fallback (Qwen2.5-Coder-7B-Instruct)
│   ├── VP.docx                             # Visual Paradigm 18.1 installation & Evaluation license
│   └── PlantUML.zip                        # Pre-configured PlantUML OpenAPI Plugin for Visual Paradigm
│
├── 📁 02_מדריכי_הנדסה_ומידול/              # Modeling Standards & Methodology Tutorials
│   ├── עבודה עם Mermaid.js.docx            # In-IDE live flowchart rendering and syntax rules
│   ├── md.docx                             # Markdown documentation syntax guide
│   ├── עבודה עם planuml.docx               # Strict PlantUML text architecture guidelines
│   └── עבודה עם USE CASE ו VP.docx         # Detailed Use Case specs (Flow of Events & Exceptions)
│
├── 📁 03_דוגמאות_ייחוס_ומודלים/            # Benchmark Reference Models (Smart Scooter Domain)
│   ├── MARKDOWN_AND_MERMAID_SHOWCASE.md    # Comprehensive syntax & advanced diagrams showcase
│   ├── mer_example.md                      # Validated reference Mermaid Use Case model
│   ├── pantUml_example.puml                # Reference PlantUML code with proper system boundary
│   └── plantBtoVS.puml                     # Validated code directly importable into Visual Paradigm
│
└── 📁 04_תבניות_להגשה_STUDENT_TEMPLATES/   # Mandatory Deliverable Templates
    ├── REQUIREMENTS_TEMPLATE.md            # Markdown starter template (Mermaid, Edge Cases, RTM, BDD)
    └── Summary_Report_Template.docx        # Word summary report template with verification screenshot placeholders
```

---

## ⚙️ Mandatory Student Prerequisites (Complete Before Lab)

To ensure effective hands-on engineering during the 3-hour session, complete the following setup on your laptops prior to arrival:

1. **IntelliJ IDEA Ultimate & Liberica Full JDK 25:**
   * Verify your active JetBrains Academic License via your `@braude.ac.il` email.
   * Ensure **BellSoft Liberica Full JDK 25** (bundled with JavaFX) is configured as the Project SDK.
2. **Required IntelliJ Plugins:**
   * Install via `Settings -> Plugins -> Marketplace`: **GitHub Copilot**, **Mermaid**, **PlantUML Integration** (`plantuml4idea`), and **Continue**.
3. **Visual Paradigm 18.1 & PlantUML Plugin:**
   * Install Visual Paradigm 18.1 under the 30-day **Evaluation** license.
   * Extract `PlantUML.zip` into `%appdata%\VisualParadigm\plugins\PlantUML`.
   * Verify that `Project -> Import -> PlantUML...` appears in the top menu.
4. **AI Workspace & Offline Fallback:**
   * Ensure GitHub Copilot is logged in. Remember the academic quota is **1,500 credits/month**.
   * If your GitHub verification is pending, set up **LM Studio** with `Qwen2.5-Coder-7B-Instruct` locally.

---

## 📦 Final Submission Format (Moodle)

Submissions are completed in pairs. Submit a single ZIP archive named:
`ex1_ID1_ID2.zip`

The archive must contain exactly three root files (no nested subfolders):
1. `REQUIREMENTS.md` – Finalized Mermaid diagram, resolved edge cases, RTM (3+ FR, 3+ NFR), and BDD tests.
2. `SystemModel.vpp` – Complete Visual Paradigm 18.1 project with detailed Flow of Events & Exceptions.
3. `Summary_Report.docx` – Team credentials, verification screenshots, and architectural reflection.

---
**Course Lead:** Dr. Anat Dahan | **Lab Instructor & System Architecture:** ILya Zeldner