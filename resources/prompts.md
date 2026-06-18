# Prompt Library for Academic Use

A collection of reusable prompt templates for common teaching and research tasks. Copy, adapt, and use these in ChatGPT, Claude, Gemini, or any other LLM.

> **Tip:** The more context you give, the better the output. Replace all `[bracketed placeholders]` with specific details about your situation.

---

## Teaching Prompts

### Lesson Planning

**Generate a lesson outline:**
```
Create a [duration]-minute lesson plan for a [level] course on [topic].
Students have background in [prior knowledge].
Main learning objective: [specific outcome].
Include: warm-up (5 min), main content delivery, one active learning activity,
and a closing formative check.
Format the plan as a timed table.
```

**Design a flipped classroom activity:**
```
I teach [topic] to [audience]. I want to flip my classroom:
students learn the content at home and practise it in class.
Design:
1. A 10-minute pre-class activity (video, reading, or podcast guide) with 3 questions students must answer.
2. A 30-minute in-class activity that applies the same content.
```

**Create a course overview:**
```
Design a 12-week course outline on [topic] for [audience] at [institution type].
Each week should have a clear theme, one or two key readings, and a suggested activity.
Learning outcomes should cover [list key competencies].
```

---

### Content Creation

**Explain a concept at a specific level:**
```
Explain [concept] to a [year one undergraduate / masters student / non-specialist].
Use plain language, a concrete analogy, and one example they can visualise.
Avoid jargon unless you define it immediately.
```

**Simplify existing text:**
```
Rewrite the following text at a [B2 English / first-year undergraduate / general public] level.
Preserve all key ideas. Reduce sentence length and remove unnecessary technical vocabulary.
[Paste text here]
```

**Generate a case study:**
```
Write a realistic case study on [topic] for use in a [seminar / workshop / problem-based learning session].
Include:
- A scenario (200–300 words) presenting a realistic situation
- 4 discussion questions at different cognitive levels (recall, analysis, evaluation, creation)
- A brief facilitator's note with key teaching points
Target audience: [describe students]
```

**Create a glossary:**
```
Write a glossary of 10 key terms related to [topic], suitable for [audience].
For each term: provide a definition in plain language (2–3 sentences),
give one example of the term in context, and note one common misconception.
```

---

### Assessment Design

**Generate multiple-choice questions:**
```
Write [number] multiple-choice questions on [topic] for a [level] exam.
Each question should:
- Test [understanding / application / analysis] (not just recall)
- Have one clearly correct answer and three plausible distractors
- Target a different aspect of the topic
Provide an answer key with brief explanations.
```

**Create a rubric:**
```
Design a grading rubric for [assignment type] on [topic].
The assignment is [length/format]. Students are [describe level].
Criteria: [list 3–5 criteria, e.g., argument quality, evidence use, structure, writing].
Use a 4-level scale: Excellent / Good / Developing / Beginning.
Format as a table.
```

**Design an AI-resistant assessment:**
```
I teach [topic] and I am concerned students may use AI to complete assignments without engaging with the content.
Design an assessment that:
- Requires application of [specific skill or knowledge]
- Incorporates [personal experience / novel data / oral component / iterative process]
- Is difficult to complete meaningfully with AI alone
- Still measures [the intended learning outcome]
```

---

### Feedback on Student Work

**Generate formative feedback:**
```
Here is a student's [essay / report / code / answer] on [topic].
Please provide formative feedback based on these criteria: [list criteria].
- Be specific: quote passages that illustrate your points.
- Suggest concrete improvements.
- Do not rewrite the work — guide the student to improve it themselves.
- Use an encouraging but honest tone.

Student work:
[Paste text here]
```

**Generate a feedback summary template:**
```
Create a feedback form template for [assignment type] on [topic].
Include sections for:
- Strengths (2–3 bullet points)
- Areas for improvement (2–3 specific points with examples)
- Priority action (one thing to focus on next)
- Overall grade impression (not a specific grade — a general indication)
```

---

## Research Prompts

### Literature Search and Synthesis

**Find key themes in a set of abstracts:**
```
Here are abstracts from [number] papers on [topic].
Identify:
1. The 3–5 main themes or debates across these papers
2. Where the papers agree
3. Where they differ or contradict each other
4. At least two unanswered questions or research gaps

[Paste abstracts]
```

**Synthesise findings:**
```
Here are summaries of [number] papers on [topic].
Write a [number]-paragraph synthesis of the key findings.
- Do not summarise papers individually — synthesise across them.
- Note agreements and disagreements.
- Maintain formal academic register.
- Do not add information not present in the summaries provided.

[Paste summaries]
```

**Identify research gaps:**
```
Based on the following literature review, identify 3 significant research gaps
or unanswered questions that future studies should address.
For each gap, briefly explain why it matters.

[Paste review text]
```

---

### Research Writing

**Expand an outline section:**
```
Expand the following outline into a coherent academic paragraph for a paper in [field].
- Maintain formal academic register.
- Do not add factual claims not present in the outline.
- Keep all technical terms unchanged.
- Aim for [number] words.

Outline:
[Paste outline]
```

**Write an abstract:**
```
Write a structured abstract for the following research paper.
Use this structure: Background, Objective, Methods, Results, Conclusion.
Maximum [number] words. Maintain the technical vocabulary of the original.

Paper content:
[Paste key points or full paper]
```

**Improve clarity of a passage:**
```
Revise the following paragraph to improve clarity and flow.
- Do not change the meaning or add new content.
- Maintain academic register.
- Reduce unnecessary wordiness.
- Keep all technical terms unchanged.

[Paste paragraph]
```

**Respond to reviewer comments:**
```
I received the following reviewer comment on my paper.
Help me:
1. Draft a professional, direct response to the reviewer.
2. Suggest how I might revise the relevant section of the paper to address the concern.

Reviewer comment:
[Paste comment]

Relevant paper section:
[Paste section — optional]
```

---

### Data Analysis

**Generate analysis code:**
```
I have a dataset in [format: CSV / Excel / SPSS / R data file].
The dataset contains these columns: [list columns and what they represent].
My research question is: [state question].

Write [Python / R] code to:
1. Load the data
2. Clean missing values (describe your approach)
3. [Specific analysis steps]
4. Produce [specific outputs: table, visualisation, statistical test results]

Comment the code to explain each step.
```

**Choose a statistical method:**
```
I am studying [research question].
My dependent variable is [describe: type, scale, distribution].
My independent variables are [describe each].
Sample size: [n].
I want to test [describe hypothesis].

What statistical test should I use? Explain why, list the assumptions I need to check,
and describe how I should report the results.
```

**Interpret results:**
```
Here are the results of a [test name] analysis:
[Paste output]

Interpret these results for a non-specialist audience. Explain:
1. What the key numbers mean
2. Whether the results are statistically significant and what that means
3. What limitations apply to this interpretation
```

---

### Reference Management

**Reformat citations:**
```
Reformat the following references in [APA 7th / Vancouver / Chicago author-date / Harvard] style.
Check for completeness and flag any missing information.

[Paste references]
```

**Generate a BibTeX entry:**
```
Create a BibTeX entry for the following paper:
Title: [title]
Authors: [authors]
Year: [year]
Journal: [journal]
Volume: [volume], Issue: [issue], Pages: [pages]
DOI: [doi]
```

---

## Meta-Prompts (Improving Your Prompting)

**Get better prompts:**
```
I want to use AI to [describe your task].
I am [describe your role and context].
Help me write a more effective prompt for this task.
Ask me any clarifying questions you need first.
```

**Critique AI output:**
```
Here is text I generated using an AI tool for [purpose].
Identify:
1. Any factual claims that should be verified
2. Any statements that seem too strong or insufficiently evidenced
3. Missing perspectives or important caveats
4. Anything that would need disciplinary expertise to assess

[Paste AI-generated text]
```

**Refine iteratively:**
```
The following is a draft I created with AI assistance.
I want it to be [more concise / more formal / clearer / more specific about X].
Please revise accordingly, keeping all the key content.

[Paste draft]
```
