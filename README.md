# 📄 AI Essay Evaluation System

## 🚀 Project Overview

This project is an AI-assisted essay evaluation system that analyzes student essays and provides automated scoring, feedback, and improvement suggestions.

It uses Google Forms, Google Sheets, n8n, and AI (via API) to create a fully automated workflow without building a traditional backend.

## 🎯 Problem Statement

Manual evaluation of essays is:
- Time-consuming
- Inconsistent
- Lacks detailed feedback

This system solves the problem by providing:
- Structured evaluation
- Consistent scoring
- Instant feedback

## 🧠 Key Features
- 📥 **Essay submission** via Google Forms
- 🤖 **AI-based evaluation** using structured prompts
- 📊 **Category-wise scoring** (Grammar, Structure, etc.)
- ⚠️ **Error detection** (grammar issues, repetition, etc.)
- 💡 **Personalized improvement suggestions**
- 📈 **Dashboard** for performance tracking
- 📄 **Canva-based feedback report**

## 🛠️ Technologies Used
- **Google Forms** → Input collection
- **Google Sheets** → Data storage & dashboard
- **n8n** → Workflow automation
- **AI API (OpenRouter / GPT)** → Essay evaluation
- **Canva** → Report generation

## 🔄 System Workflow
`Google Form` → `Google Sheet` → `n8n Trigger` → `AI API` → `Data Processing` → `Google Sheet Update` → `Dashboard` → `Canva Report`

## 📊 Evaluation Criteria

The essay is evaluated based on:

| Category | Weight |
|----------|--------|
| Grammar & Mechanics | 30% |
| Structure & Organization | 25% |
| Clarity & Coherence | 20% |
| Argument Strength | 15% |
| Tone & Style | 10% |

## 🧩 Features Implemented (Milestones)

### ✅ Milestone 1
- Defined problem statement
- Created evaluation rubric
- Designed workflow diagram
- Set up Google Sheets structure

### ✅ Milestone 2
- Built Google Form
- Integrated n8n workflow
- Connected AI API
- Implemented scoring system
- Automated feedback generation

### ✅ Milestone 3
- Created Google Sheets Dashboard
- Score trend visualization
- Category-wise analysis
- Error frequency tracking

### ✅ Milestone 4
- Tested with multiple essays
- Demonstrated score variation
- Tracked error reduction
- Generated AI-based suggestions
- Created Canva feedback report
- Documented system limitations

## 📸 Screenshots

*(Note: Please save the screenshots you provided into a `screenshots/` directory in this repository with these exact filenames to display them).*

### Google Form
https://docs.google.com/forms/d/e/1FAIpQLSepcpCnbfn6IyZaL9CGH46fwel04b4O6-lTK_ntV3b8LY97oQ/viewform

### Google Sheet
https://docs.google.com/spreadsheets/d/1LOiSW0gSJJfJrujlnLcN-8GDwLKoUp307NIJwsKUm6I/edit?resourcekey=&gid=170073561#gid=170073561

### Dashboard
https://docs.google.com/spreadsheets/d/1LOiSW0gSJJfJrujlnLcN-8GDwLKoUp307NIJwsKUm6I/edit?resourcekey=&gid=13559485#gid=13559485

## ⚙️ How It Works
1. Student submits essay via Google Form.
2. Data is stored in Google Sheets.
3. n8n detects new entry.
4. Essay is sent to AI model via API.
5. AI returns:
   - Scores
   - Errors detected
   - Suggestions
   - Feedback
6. Results are updated in Google Sheets.
7. Dashboard visualizes performance.

## 📈 Output

The system generates:
- Category-wise scores
- Final score
- Error detection
- Improvement suggestions
- Detailed feedback

## ⚠️ Limitations
- AI-generated scores may vary slightly.
- Depends on prompt design.
- Not a replacement for human grading.
- Requires active n8n workflow.

## 🎯 Conclusion

This project demonstrates how AI + automation tools can be combined to build a scalable and efficient essay evaluation system without heavy backend development.
