# Professor's Teaching, Research, and Academic Workbench

A practical, editable collection of software, trustworthy starting points, and reusable AI prompts for university teaching and research. Adapt it to your discipline, Virtual University of Pakistan (VU) workflows, and current university policies.

> **Important:** Verify tools, prices, access, and institutional approval before adopting them. Use official VU systems and approved channels for course delivery, assessment, and student records. Never upload confidential student data, unpublished research, examination questions, credentials, or personal information to an AI service unless your institution explicitly permits it.

## Contents

- [Start with your core toolkit](#start-with-your-core-toolkit)
- [Software and services by task](#software-and-services-by-task)
- [Academic research and writing resources](#academic-research-and-writing-resources)
- [Reusable prompts for professors](#reusable-prompts-for-professors)
- [Responsible AI and academic integrity](#responsible-ai-and-academic-integrity)
- [A simple weekly workflow](#a-simple-weekly-workflow)
- [How to contribute](#how-to-contribute)

## Start with your core toolkit

Start with tools you already have access to, then add only what solves a real need.

| Need | Useful starting point | Notes |
|---|---|---|
| Course delivery and student communication | VU-approved LMS and official university channels | Follow current VU guidance for course materials, announcements, grading, and student support. |
| Documents and spreadsheets | Microsoft 365 or LibreOffice | Check institutional licensing and compatibility before choosing. |
| Reference management | [Zotero](https://www.zotero.org/) | Organize citations and bibliographies; check every imported citation against its source. |
| Academic identity | [ORCID](https://orcid.org/) | Maintain a persistent researcher identifier and accurate public profile. |
| Literature discovery | [Google Scholar](https://scholar.google.com/), [OpenAlex](https://openalex.org/), [Crossref](https://search.crossref.org/) | Search more than one source; verify publication details and peer-review status. |
| Writing and collaboration | [Overleaf](https://www.overleaf.com/) for LaTeX; institutional word-processing tools | Use the format required by your journal, department, or co-authors. |
| Programming and reproducible analysis | [Jupyter](https://jupyter.org/), [Google Colab](https://colab.research.google.com/), [RStudio](https://posit.co/download/rstudio-desktop/) | Do not upload sensitive or restricted datasets to hosted services without approval. |
| Slides and visual materials | PowerPoint, LibreOffice Impress, [Canva for Education](https://www.canva.com/education/) | Check accessibility, image licensing, and institutional account eligibility. |
| Video and screen recording | [OBS Studio](https://obsproject.com/) | Obtain consent before recording people; check university policy for lecture recording. |
| Interactive learning activities | [H5P](https://h5p.org/) | Confirm compatibility with your LMS and accessibility requirements. |
| Version control and open teaching materials | [GitHub](https://github.com/) | Keep private, sensitive, or student-identifiable information out of public repositories. |

## Software and services by task

### Teaching and course preparation

- **Course organization:** your institution's LMS; use its official gradebook and communication features.
- **Lesson design:** a document editor, presentation software, and a calendar/task manager already supported by your institution.
- **Engagement:** H5P or LMS-native quizzes and forums, after checking accessibility and LMS compatibility.
- **Recording:** OBS Studio or an institution-approved recording tool. Provide captions or a transcript where possible.
- **Accessibility:** built-in document accessibility checkers, captions, readable contrast, descriptive links, and heading structure.

### Research and scholarly writing

- **References:** Zotero; use a consistent citation style and verify each record.
- **Discovery:** Google Scholar, OpenAlex, Crossref, and discipline-specific databases available through your library or HEC access.
- **Researcher profile:** ORCID; keep affiliations and outputs current.
- **Writing:** Word or LibreOffice for common formats; Overleaf for collaborative LaTeX workflows.
- **Data and code:** Jupyter, RStudio, GitHub, and institution-approved storage. Document methods, versions, and data provenance.
- **Similarity checking:** use only university-authorized services and interpret reports carefully; a similarity score alone does not establish plagiarism.

### Meetings and administration

- Use university-approved email, calendar, video-conferencing, cloud storage, and document-signing tools.
- Keep a decision and action log for meetings. Share notes only with the intended audience.
- Use a password manager and multifactor authentication where available. Never put passwords or access tokens in prompts, documents, or public repositories.

## Academic research and writing resources

- [Higher Education Commission of Pakistan (HEC)](https://www.hec.gov.pk/) — official higher-education information and services. Check the current site for applicable policies and programs.
- [HEC National Digital Library](https://www.digitallibrary.edu.pk/) — check availability and access through your institution.
- [Crossref Search](https://search.crossref.org/) — look up DOI and publication metadata; confirm details with the publisher.
- [OpenAlex](https://openalex.org/) — open scholarly metadata for discovery and analysis.
- [DOAJ](https://doaj.org/) — directory of open-access journals; listing is one screening signal, not a guarantee of journal quality.
- [COPE](https://publicationethics.org/) — publication-ethics guidance for authors, editors, and publishers.
- [ORCID](https://orcid.org/) — researcher identifier and profile.
- [Zotero documentation](https://www.zotero.org/support/) — setup, collections, citations, and collaboration guidance.

**Research hygiene:** Confirm journal scope, publisher identity, peer-review process, fees, indexing claims, and current journal status independently. Verify references, DOIs, quotations, and statistics from original sources before citing them.

## Reusable prompts for professors

Replace bracketed fields with non-sensitive information. Treat AI output as a draft: check facts, references, calculations, accessibility, and alignment with your course outcomes. Do not ask a model to make final grading, admissions, disciplinary, or other consequential decisions.

### 1. Plan a class session

> Help me plan a [duration]-minute class session for [course and level] on [topic]. The learning outcomes are [outcomes]. Students already know [prior knowledge]. Create a timed plan with an opening question, explanation, active-learning activity, formative check, and closing summary. Include materials and an accessible alternative. Flag assumptions and do not invent citations.

### 2. Explain a difficult concept

> Explain [concept] to [student level] using clear language and one accurate example relevant to [discipline/context]. Then give a more advanced explanation, identify common misconceptions, and write three questions that check understanding. Mark anything that depends on local course content as [VERIFY].

### 3. Create a formative quiz

> Draft [number] formative questions about [topic] for [level], aligned to these learning outcomes: [outcomes]. Include a mix of [question types], answer key, brief rationale, and difficulty label. Check that each question has one defensible answer where applicable. These are practice questions, not a secure examination.

### 4. Draft a transparent rubric

> Create a rubric for [assignment] aligned with these outcomes: [outcomes]. Use [number] criteria and [number] performance levels. Describe observable evidence at each level, avoid vague personality judgments, and total [points]. Return a table and flag criteria that need instructor review.

### 5. Give feedback on student work

> Help me draft constructive feedback on this anonymized excerpt: [text]. Use the rubric criteria [criteria]. First identify strengths, then the two most useful next steps, with specific examples. Do not assign a grade or infer the student's identity, motivation, or ability. I will review and personalize the feedback.

### 6. Improve lecture notes

> Organize these notes into a clear outline for [course/level]: [notes]. Preserve the meaning, separate established facts from my opinions, identify unclear claims as [CHECK], and suggest where a verified source or example is needed. Do not fabricate references.

### 7. Build a reading guide

> Create a reading guide for this instructor-provided text/topic: [text or topic]. Include a short purpose statement, five guiding questions, key terms with draft definitions, and a post-reading activity. Do not claim details about a text you have not been given.

### 8. Support inclusive teaching

> Review this activity for possible barriers for students with different access needs, language backgrounds, bandwidth, and prior knowledge: [activity]. Suggest practical alternatives that preserve the learning outcome. Do not assume a student's needs; recommend asking students and following institutional accessibility guidance.

### 9. Summarize a paper I provide

> Using only the abstract or text below, summarize the research question, method, sample/data, main findings, limitations, and what the authors do not establish. Separate the authors' claims from your interpretation. If information is missing, say so. Text: [paste permitted text].

### 10. Prepare a literature-search plan

> Help me design a literature search about [research question] in [field]. Suggest synonyms, Boolean search strings, inclusion/exclusion criteria, and databases I should consider. Do not claim to have searched databases or provide unverified citations. Note where I should consult a subject librarian.

### 11. Edit academic prose

> Edit the following paragraph for clarity, grammar, and flow while preserving my argument and voice. Do not add evidence or citations. Return (1) a revised version and (2) a concise list of substantive changes or ambiguities for me to review: [paragraph].

### 12. Draft an academic email

> Draft a concise, respectful email to [role] about [purpose]. Include these facts: [facts]. Request [specific action] by [date]. Do not invent commitments, policy, or details. Keep the tone [tone].

### 13. Plan a research project

> Turn this research idea into a planning checklist: [idea]. Include a refined question, possible design options, data and ethics considerations, risks, milestones, and questions for a supervisor or ethics committee. Do not decide whether ethics approval is required; flag that I must confirm institutional requirements.

### 14. Turn meeting notes into actions

> Convert these non-confidential meeting notes into a table with action, owner (if stated), deadline (if stated), and open question. Do not guess missing owners or dates. Notes: [notes].

### 15. Check a syllabus for alignment

> Compare these learning outcomes, weekly topics, and assessments: [content]. Make a table showing apparent alignment, gaps, overload, and questions for instructor review. Do not assert compliance with a particular accreditation or university policy unless I provide the relevant standard.

### General instruction to append

> If information is missing, ask up to three clarifying questions. Distinguish facts from suggestions, cite only sources I provide or sources you can actually verify, and label uncertain statements [VERIFY].

## Responsible AI and academic integrity

- Follow current VU, departmental, funder, publisher, and ethics-review requirements. Policies can change; consult the official current version.
- Do not submit confidential, personal, identifiable, unpublished, copyrighted, or restricted material to an external tool unless authorized.
- Disclose and document AI assistance when required. AI-generated text is not a source; cite the original, verifiable sources instead.
- Verify every quotation, citation, DOI, statistic, equation, and factual claim. Models can produce plausible but false material.
- Preserve student agency and privacy. Do not use AI as the sole evaluator or decision-maker for students.
- Make assessment expectations explicit, including permitted and prohibited AI assistance.
- Check generated materials for bias, accessibility, accuracy, and fit for your students.

## A simple weekly workflow

1. Review the LMS, calendar, and course announcements; identify urgent student needs.
2. Choose the week's learning outcomes and align activities and assessment to them.
3. Prepare one core lesson outline and one low-bandwidth/accessibility alternative.
4. Check references, links, citations, and permissions before publishing.
5. Set aside protected research time; record searches, methods, decisions, and next steps.
6. Review student work with your rubric and provide human-reviewed, actionable feedback.
7. End the week by recording what worked, what needs adjustment, and next week's top priorities.

## How to contribute

Add resources that are useful, reputable, accessible, and relevant to university teaching or research. Include the official link, purpose, cost/access notes where known, and any privacy or accessibility considerations. Prefer primary or official sources, avoid promotional claims, and re-check links and policies periodically. Do not add student data, credentials, or copyrighted material without permission.
