# Module 03 — AI Tools for Research

**Duration:** ~4 hours  
**Prerequisites:** [Module 01 — Introduction to AI in Didactics and Research](../01_introduction/)

---

## Learning Objectives

By the end of this module, you will be able to:

- Use AI-powered tools to discover, retrieve, and summarise academic literature.
- Apply AI assistance to research writing tasks (drafting, editing, paraphrasing, translating).
- Leverage AI for data analysis support, including code generation and statistical guidance.
- Manage references and bibliographies more efficiently with AI.
- Critically evaluate AI-generated research content for accuracy and reliability.

---

## 1. AI-Powered Literature Search and Summarisation

### The challenge

Academic literature is growing exponentially. Researchers cannot read everything. AI tools help by:

- Finding relevant papers faster.
- Summarising key findings from large bodies of literature.
- Identifying connections between papers and research gaps.

### Recommended tools

| Tool | Strengths | URL |
|------|----------|-----|
| **Elicit** | AI-guided literature search, auto-extracts key variables | https://elicit.com |
| **Consensus** | Evidence-based search with "yes/no/mixed" consensus indicators | https://consensus.app |
| **Semantic Scholar** | Broad academic search with citation analysis and AI summaries | https://www.semanticscholar.org |
| **Perplexity AI** | Web-based research with citations, good for recent developments | https://www.perplexity.ai |
| **Research Rabbit** | Visual citation mapping and paper discovery | https://www.researchrabbit.ai |
| **Connected Papers** | Visual exploration of papers related to a key reference | https://www.connectedpapers.com |
| **NotebookLM** | Upload your own PDFs and ask questions about them | https://notebooklm.google.com |

### Workflow: AI-assisted literature review

1. **Define your research question** precisely. A well-formulated question yields much better results.
2. **Use Elicit or Consensus** to find key papers with AI-generated summaries.
3. **Use Semantic Scholar** to explore citation networks and find foundational works.
4. **Import PDFs into NotebookLM** to interrogate specific papers and extract key findings.
5. **Use a general LLM** (ChatGPT, Claude) to help synthesise and structure your findings.

### Prompts for literature review

**Finding key themes:**
```
I am conducting a literature review on [topic].
Based on the papers I describe below, identify the main themes,
debates, and unanswered questions in this field.
[Paste summaries or abstracts]
```

**Synthesising findings:**
```
Here are summaries of 8 papers on [topic].
Write a 3-paragraph synthesis of the key findings,
noting where papers agree, where they differ, and what is still uncertain.
[Paste summaries]
```

**Identifying research gaps:**
```
Based on the following literature review, identify at least three
significant gaps or unanswered questions that future research could address.
[Paste your review draft]
```

> ⚠️ **Critical warning:** AI tools sometimes fabricate paper titles, authors, or DOIs. **Always verify every citation** in an authoritative database (Google Scholar, PubMed, Web of Science) before including it in your work.

---

## 2. AI for Systematic Reviews and Meta-Analyses

### What AI can help with

- **PICO framework:** AI can help structure your research question using Population, Intervention, Comparison, Outcome.
- **Inclusion/exclusion criteria:** Draft criteria and refine them with AI feedback.
- **Abstract screening:** Some tools (Rayyan, ASReview) use AI to prioritise abstracts for review.
- **Data extraction:** AI can extract specified variables from paper abstracts (Elicit does this well).
- **Risk of bias:** AI can flag potential methodological weaknesses in study designs.

### Tools for systematic reviews

| Tool | Purpose |
|------|---------|
| **Rayyan** | AI-assisted abstract screening | 
| **ASReview** | Active learning for screening large document sets |
| **Elicit** | Variable extraction from abstracts |
| **Covidence** | Systematic review management (AI features emerging) |

### Limitations

- AI cannot replace human judgment in systematic review decisions.
- AI-extracted data must be verified against original papers.
- AI does not have access to unpublished studies or grey literature by default.

---

## 3. AI for Research Writing

Research writing is one of the most time-consuming parts of academia. AI can assist at every stage.

### Writing stages and AI support

| Stage | How AI can help |
|-------|----------------|
| **Outline** | Generate a draft structure; identify missing sections |
| **First draft** | Expand bullet points into prose; overcome writer's block |
| **Revision** | Identify unclear passages; suggest improvements |
| **Style and tone** | Adjust register for different audiences or journal requirements |
| **Editing** | Fix grammar, improve sentence flow, reduce wordiness |
| **Paraphrasing** | Rephrase your own ideas without changing meaning |
| **Translation** | Translate drafts between languages (verify quality carefully) |
| **Abstract writing** | Generate a structured abstract from a full paper |
| **Cover letters** | Draft journal submission cover letters |

### Effective prompts for research writing

**Drafting from an outline:**
```
Expand the following outline section into a coherent academic paragraph
for a [journal/conference] paper in [field]. Maintain formal academic register.
Do not add information not present in the outline.
[Paste outline section]
```

**Improving clarity:**
```
Revise the following paragraph to improve clarity and flow.
Do not change the meaning or add new content.
Keep all technical terms unchanged.
[Paste paragraph]
```

**Writing an abstract:**
```
Write a structured abstract (Background, Objective, Methods, Results, Conclusion)
for the following research paper. Maximum 250 words.
[Paste key points or full paper]
```

**Responding to reviewers:**
```
I received the following reviewer comment on my paper.
Help me draft a polite, professional response that directly addresses
the concern. Then suggest how I might revise the relevant section of the paper.
[Paste reviewer comment]
```

### What AI should NOT write for you

- The intellectual contribution (your novel ideas, arguments, and interpretation).
- Claims about data you have collected (AI does not have access to your data).
- Conclusions drawn from your specific findings.
- Any text submitted as entirely your own if your institution prohibits AI assistance.

> Always check your target journal's or institution's policy on AI-assisted writing before using AI in manuscripts.

---

## 4. AI for Data Analysis

### Code generation

LLMs are remarkably effective at generating data analysis code in Python, R, and other languages. This is particularly useful for researchers who are not expert programmers.

**Example prompts:**

```
I have a CSV file with columns: [list columns].
Write Python code using pandas to:
1. Load the file
2. Clean missing values
3. Calculate descriptive statistics for each numeric column
4. Plot a histogram for each numeric column
```

```
I am running a linear regression in R.
My dependent variable is [Y] and my independent variables are [X1, X2, X3].
Write R code to: fit the model, check assumptions (residual plots, normality),
and report the results in APA format.
```

```
I have survey data with Likert-scale responses.
Write Python code to calculate Cronbach's alpha
for the following set of items: [list items].
```

### Statistical guidance

AI can explain statistical concepts and help you choose the right methods:

```
I have [describe your data and research question].
What statistical test should I use? Explain why,
and list the assumptions I need to check.
```

```
Explain what a p-value means and why a p-value below 0.05
does not automatically mean my result is important.
```

### Qualitative research support

- Coding and thematic analysis: AI can suggest codes for interview excerpts.
- Interview guide design: AI can draft or critique research instruments.
- Reflexivity prompts: AI can help researchers articulate positionality.

> ⚠️ Never share identifiable participant data with commercial AI tools. Anonymise all data before using AI assistance.

---

## 5. Reference Management with AI

### AI-enhanced reference workflows

- **Zotero + AI plugins:** Extensions like Zotero's "Magic Wand" and third-party plugins help automate metadata extraction.
- **NotebookLM:** Ask questions across your collection of uploaded PDFs.
- **Citation formatting:** Ask any LLM to reformat a reference list in a specific citation style.

**Reformatting citations:**
```
Reformat the following references in APA 7th edition format:
[Paste references]
```

```
Convert this BibTeX entry to Chicago author-date format:
[Paste BibTeX]
```

> **Warning:** AI-formatted citations sometimes contain errors. Always verify against an official style guide or a trusted reference manager.

---

## 6. Hands-On Exercise: AI-Assisted Mini Literature Review

**Task:** Conduct a short literature review on a topic in your field using AI tools.

Steps:

1. Choose a research question in your area (example: *"What is the effect of formative feedback on student learning outcomes in higher education?"*).
2. Use **Elicit** or **Consensus** to find 5–8 relevant papers. Note their titles, authors, and key findings.
3. Verify that each paper exists by searching in Google Scholar or Semantic Scholar.
4. Use a general LLM (ChatGPT, Claude) to help you write a 1-paragraph synthesis of the key findings.
5. Identify one research gap mentioned or implied by the literature.
6. Save your work for submission as [Assignment 03](../../assignments/assignment_03_literature_review.md).

---

## Reflection Questions

1. Which research tasks consume the most time in your workflow? Could AI reduce that time?
2. Have you ever found errors in AI-generated content? How did you catch them?
3. What concerns do you have about using AI in your published research?
4. How would you explain your AI use to collaborators or journal editors?

---

## Key Takeaways

- AI dramatically accelerates literature discovery and summarisation, but all outputs must be verified.
- AI is a powerful writing assistant — best used for drafting and editing, not for generating intellectual contributions.
- Code generation with AI is transformative for researchers who are not expert programmers.
- Academic integrity requires transparency about AI use and verification of all AI-generated content.

---

## Navigation

[← Module 02 — AI Tools for Teaching](../02_ai_tools_for_teaching/) | [Module 04 — Ethics and Critical Thinking →](../04_ethics_and_critical_thinking/)
