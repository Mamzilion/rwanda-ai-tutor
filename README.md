# Rwanda AI Tutor

A bilingual (English / Kinyarwanda) AI tutor for Rwandan secondary school learners,
grounded only in official REB textbooks. It cites the page it used, gives hints before
answers, and says so when the answer is not in the material.

> Status: work in progress — IndabaX Cameroon internship challenge (deadline: 1 December 2026).

## Planned features
- RAG pipeline over Senior 4 textbooks (text, tables, equations, scanned pages)
- Tutor that gives hints first, explains mistakes, adapts to the learner's age
- Questions and explanations in English and Kinyarwanda
- Responsive web app and Flutter mobile app with offline chapters
- Roles: administrator, teacher, student
- Cloud model (Gemini) and local open model (Ollama), compared
- Evaluation: 30 curriculum questions, 20 bilingual items, 25 red-team prompts

## Repository structure
| Folder | Content |
|---|---|
| `docs/` | Workplan, risk register, memo, architecture |
| `data/` | Source textbooks and extracted content |
| `backend/` | FastAPI API and RAG pipeline |
| `web/` | React web app |
| `mobile/` | Flutter mobile app |
| `eval/` | Test set, rubric, red-team log, results |

## Authors
- MAMA Daniel Dilane — [GitHub](https://github.com/Mamzilion)