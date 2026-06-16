# 🎨 CSE Newsletter Content Automation System

> Production-grade Claude workflow for generating professional newsletter-ready HTML content for Career Opportunities, Learning Resources and Insightful Updates.

> [!WARNING]
> This repository is proprietary and intended exclusively for the internal use of the CSE Newsletter Committee, PDEU. Redistribution, public sharing, or unauthorized modification of repository contents is strictly prohibited under the repository [LICENCE](LICENCE).

---

## 📌 Overview

The **CSE Newsletter Content Automation System** is an internal editorial automation workflow developed for the **CSE Newsletter Committee, Pandit Deendayal Energy University (PDEU).**

This system transforms raw information such as:

* Internship Opportunities
* Job Openings
* Fellowships
* Research Programs
* Scholarships
* Learning Resources
* Certifications
* Workshops
* AI & Technology Updates
* Industry News

into professionally formatted, publication-ready HTML newsletter pages using a standardized design template.

The workflow uses **Claude Projects** as an AI-powered research, editing, fact-checking and content-generation pipeline.

---

# 🎯 Objective

Traditionally, newsletter content creation involves:

1. Finding opportunities
2. Visiting links
3. Reading job descriptions
4. Extracting information
5. Writing summaries
6. Formatting content
7. Designing layouts

This process is repetitive and time-consuming.

This project automates everything except final design review.

---

# 🚀 What This Workflow Does

Given:

* Raw opportunity information
* Career links
* Internship descriptions
* Resource URLs
* News articles
* Event announcements

Claude automatically:

✅ Extracts information <br/>
✅ Researches missing details <br/>
✅ Verifies information <br/>
✅ Creates professional newsletter content <br/>
✅ Organizes sections <br/>
✅ Populates the HTML template <br/>
✅ Produces final publication-ready HTML

---

# 🏗 Workflow Architecture

```text
Raw Content
     │
     ▼
Claude Project
     │
     ├── Information Extraction
     │
     ├── Research & Fact Verification
     │
     ├── Content Refinement
     │
     ├── Category Detection
     │
     ├── Section Generation
     │
     └── HTML Population
     │
     ▼
Newsletter HTML DOC
     │
     ▼
Clone this repo and add proper Logo & QR path
     │
     ▼     
Open in browser & print as a pdf     
```

---

# 📂 Repository Structure

```text
CSE-Newsletter-PDEU_Content-Automation/
│
├── Assets/
│   ├── PDEU Logo
│   ├── School of Technology Logo
│   ├── Newsletter Logo
│   ├── Social Icons
│   └── QR Assets
│
├── Claude-Project_Automation/
│   └── Project-Instructions.md
│
├── Templates/
│   ├── CareerUpdates.html
│   ├── LearningResources.html
│   └── InsightfulUpdates.html
│
├── NL-Database/
│
├── LICENCE
└── README.md
    
```

---

# 📰 Supported Categories

## 💼 Career Opportunities

Includes:

* Internships
* Full-Time Jobs
* Fellowships
* Apprenticeships
* Research Internships
* Hiring Drives
* Graduate Programs

---

## 📚 Learning Resources

Includes:

* Courses
* Certifications
* Workshops
* Bootcamps
* Training Programs
* Learning Platforms

---

## 💡 Insightful Updates

Includes:

* AI News
* Technology Trends
* Research Breakthroughs
* Product Launches
* Industry Reports
* Community Updates

---

# ⚙️ Claude Project Setup

## Step 1

Create a new Claude Project.

Suggested Name:

```text
CSE Newsletter Automation System
```

---

## Step 2

Upload the following files:

```text
CareerUpdates.html
LearningResources.html
InsightfulUpdates.html
```

These templates become Claude's design references.

---

## Step 3

Paste the complete Project Instructions provided in this repository into [Claude Project Instructions](Claude-Project_Automation/Project-Instructions.md).

---

## Step 4

Save the project.

Your automation system is ready.

---

# 📥 Input Format

Provide raw information.

Example:

```text
🌟 Goldman Sachs

Asset & Wealth Management
ACM Engineering Associate

Apply:
https://example.com

Job Description:
Full-stack engineering role involving Java,
MongoDB, Angular and React.
```

You should also provide:

```text
Only URL
```

Example:

```text
https://careers.company.com/job/12345
```

Claude must extract all available information automatically.

---

<div align="center">

**Developed by [Yashvardhan Jani](https://github.com/YashvardhanJani) with ❤️ for** <br/>
**CSE Newsletter Committee, PDEU** <br/>

---

© 2026 CSE Newsletter Committee, PDEU. All Rights Reserved.

</div>

