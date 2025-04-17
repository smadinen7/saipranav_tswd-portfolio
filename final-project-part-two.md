| [home page](https://smadinen7.github.io/saipranav_tswd-portfolio/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Wireframes / storyboards
> Using your sketches developed last week, further develop your story outline and relevant components visually through the use of wireframing / storyboards. Using your outline as a guide, include high-fidelity, individual draft data visualizations of the critical elements of your story you want to share with your reader. Note: you can build these elements out directly in Shorthand this week if you wish.

For Part II, I developed a scroll-based storyboard and began building high-fidelity charts in Tableau. These visuals follow my Part I outline and represent the critical points in the story arc. Each section corresponds to a section of the final Shorthand story and will be refined further in Part III based on user feedback.

**Storyboard Sections:**
1. **Intro** – “Will AI take your job or transform it?” Hero image + one-liner hook.
2. **Adoption Trends** – Bar chart showing AI adoption by industry.
3. **Layoff Impact** – Timeline showing major layoffs attributed to AI (2020–2023).
4. **Job Creation** – Side-by-side bar showing AI-related job creation.
5. **Exposure Risk** – Scatterplot: AI exposure vs average wage (AIOE dataset).
6. **Worker Sentiment** – Stacked bar of attitudes (hopeful, neutral, fearful).
7. **Conclusion** – A summary and call to action with resources for upskilling.

Draft visualizations for Sections 2, 3, and 5 are underway in Tableau and being published to Tableau Public.

**Storyboard Sketch:**  
![Storyboard Sketch](./images/storyboard_ai_jobflow.png)

# User research 

## Target audience
> Include your approach to identifying representative individuals, and who you hope to reach with your story. 

The story is designed for early-career professionals and graduate students in tech, data, and business fields who are preparing to enter or evolve within a job market increasingly influenced by AI.

For interviews, I identified three individuals:
- A CMU grad student in analytics (early 20s)
- A CS graduate working in product (early 20s)
- A product manager in fintech (late 20s)

They reflect the audience who would benefit from clarity around job risks, AI adoption trends, and action steps.

## Interview script
> List the goals from your research, and the questions you intend to ask. 

The primary goals of my interviews were:
- To assess whether the visuals and narrative are clear and meaningful
- To identify which elements are most helpful or confusing
- To gather suggestions for improvement

| Goal                                | Questions to Ask                                                             |
|-------------------------------------|------------------------------------------------------------------------------|
| Understand user engagement          | What part of the story felt most relevant or memorable to you?              |
| Test clarity of visuals             | Were any visualizations difficult to understand or interpret?               |
| Assess emotional resonance          | Did anything surprise you or change how you think about AI and jobs?        |
| Identify improvement opportunities  | What could make the visuals or story more engaging and helpful for you?     |

I used these questions to guide a 10–15 minute conversational interview while screen-sharing early visuals and wireframes.

## Interview findings
> Detail the findings from your interviews.  Do not include PII.  Capture specific insights where possible.

| Questions                            | Interview 1 (CMU student)                  | Interview 2 (CS grad)                    | Interview 3 (Fintech PM)                  |
|--------------------------------------|--------------------------------------------|------------------------------------------|-------------------------------------------|
| Most relevant section?               | Exposure risk scatterplot                   | Layoff timeline                           | New job creation bar chart                 |
| Most confusing visual?               | Timeline lacked context                     | Wanted filters for industries             | Scatterplot needed clearer labeling        |
| Surprise or insight?                 | Surprised that high-paying jobs were high risk | Didn't know AI roles didn't require coding | Felt more optimistic after seeing gains    |
| Suggestions for improvement          | Use color-coded job types                   | Include call-to-action                    | Include clearer tooltips and callouts      |

# Identified changes for Part III
> Document the changes you plan on implementing next week to address any issues identified.  

| Research synthesis                           | Anticipated changes for Part III                                              |
|----------------------------------------------|-------------------------------------------------------------------------------|
| Timeline visualization lacked clarity        | Simplify to 5–6 major layoff events, color-code by industry                   |
| Scatterplot labeling was weak                | Add clearer labels and example occupations (with tooltips in Tableau)         |
| Lack of interactivity in visuals             | Add optional filters for industry or job role in Tableau (if feasible)        |
| Missing conclusion or takeaway               | Add a call-to-action section with practical advice and resource links         |

> ...include any final thoughts you have here. 

The user feedback validated the structure and message of my story, but also pointed out areas where clarity and engagement could be improved. The scatterplot and timeline, while valuable, need simplification and more annotations. All interviewees wanted something actionable at the end, which I’ll implement in Part III.

# Moodboards / personas
> If you did this optional part, include details here.  Otherwise remove this section

**Moodboard:**  
*(to be added)*

## References
- AI Occupational Exposure Dataset (2023), GitHub  
- AI Job Market Insights Dataset (2023), Kaggle  
- Layoffs Dataset (2020–2023), Kaggle  
- Tech Layoff Tracker (2024), TrueUp.io  

## AI acknowledgements
ChatGPT was used to:
- Brainstorm interview script questions  
- Suggest data storytelling structure  
- Assist in refining the tone and organization of this README  

All interviews, sketches, visualizations, and writing were completed independently.
