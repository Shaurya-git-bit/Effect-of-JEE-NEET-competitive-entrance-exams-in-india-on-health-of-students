# The Hidden Cost of Cracking JEE/NEET
### A data-driven look at what India's most competitive exams do to the students who take them

---

I started this project with a simple question: **what actually happens to students who go through JEE/NEET preparation?** Not the success stories that coaching institutes put on their billboards. Not the rank holders featured in newspaper headlines. Everyone else.

So I ran a survey. 335 responses later, the picture is uncomfortable.

---

## What This Study Covers

- Physical and mental health during preparation
- The effect of drop years on student wellbeing
- How parental pressure relates to burnout and long-term satisfaction
- Whether coaching-integrated schools actually produce better outcomes
- What students who reached IIT/AIIMS themselves think about the process

---

## Key Findings

### 1. Even the "Winners" Have Doubts

**73% of IIT/AIIMS students would not recommend this preparation path to others.**

This is not about students who failed. This is about students who made it to the finish line and still look back with hesitation. One respondent who became a doctor and won multiple gold medals in college wrote:

> "It broke my confidence and self esteem in such a way that even though I became a doctor... I still feel I'm not good enough."

<img width="700" height="500" alt="press vs stress and burnout" src="https://github.com/user-attachments/assets/abf5346d-8ee9-4401-b13f-30604062e3c8" />

*Burnout rate climbs sharply with parental pressure. At "Very High" pressure levels, 93% of students reported frequent stress or burnout.*

---

### 2. Parental Pressure Does Not Pay Off

Higher parental pressure is strongly associated with higher burnout AND lower career satisfaction after the exam. The students who faced the most intense pressure at home ended up the least satisfied with where they landed.

This was statistically significant (chi-square p = 0.0006 for burnout, clear downward trend for satisfaction).

<img width="640" height="480" alt="intensity vs satisfaction" src="https://github.com/user-attachments/assets/2f814274-1953-44ac-a86d-5ae4628934fb" />

*Students with low parental pressure reported meaningfully higher career satisfaction than those under very high pressure.*

---

### 3. Coaching Schools Are Not the Advantage Everyone Thinks

This one surprised me.

Students from coaching-integrated schools reached IIT/AIIMS at a rate of **10.6%.** Students from regular schools reached it at **7.2%.** That difference is **statistically insignificant (p = 0.58).**

Meanwhile, coaching-integrated schools had the **highest burnout rate** of any schooling type at 85%.

<img width="2000" height="500" alt="coach_vs_school_type" src="https://github.com/user-attachments/assets/fbafcd89-ef84-4398-b470-88d86366e38f" />

*Across every outcome tier, coaching-integrated schools show no statistically significant advantage over regular schools.*

---

### 4. Holistic Students Come Out Ahead

Students who managed to develop even one non-academic skill during preparation reported significantly higher career satisfaction and social confidence afterwards compared to those who developed none.

This held up statistically (Mann-Whitney U, p < 0.0001) and suggests that the total-sacrifice model of preparation carries real long-term costs.

<img width="1200" height="500" alt="non-academic vs satisfaction" src="https://github.com/user-attachments/assets/df73d93a-ec1a-484a-8020-998040f0d627" />

*Students who developed non-academic skills during prep scored noticeably higher on both career satisfaction and social confidence post-exam.*

---

# In Their Own Words

> "It broke my confidence and self esteem in such a way that even though I became a doctor after getting multiple gold medals during college, I still feel I'm not good enough."
> — IIT/AIIMS graduate

> "Life feels like we are putting brakes on life before turning 18."

> "The exam and the journey takes away your happiness, potential, confidence, sleep, peace and gives you anxiety, panics, bad moods."

> "I hate what I have become after this. I know I will get in this year but how things turned out, I don't love myself anymore for it."

> "I lost everything in my drop year. I got depressed, suicidal. I wouldn't want whatever I suffered on anyone."

> "It took my 4 years, gave me anxiety and insomnia. Exams like these shouldn't be fixated on kids with above average grades — it's murder of their self-esteem."

## Headline Numbers

| Metric | Value |
|---|---|
| Total respondents | 335 |
| Reported frequent burnout | 80% |
| Would not recommend this path (No + Unsure) | 85.5% |
| Regret or unsure about their choice | 74% |
| Reached IIT / AIIMS | 9% |
| Poor physical health during prep (rated 1-2 out of 5) | 63% |
| Low social interaction during prep (rated 1-2 out of 5) | 61% |

---

## Methodology

Data was collected through a Google Form survey shared across multiple JEE/NEET related subreddits including r/JEEPreparation, r/NEET, and r/Indian_Academia between March and April 2025. Responses were voluntary and anonymous.

Statistical tests used: Mann-Whitney U (for comparing scale scores between groups) and Chi-square (for categorical comparisons). All p-values are reported in the notebook.

**Limitations:** This is a self-selected, Reddit-based sample, which means it skews toward English-speaking, digitally active students. It likely over-represents urban demographics. These findings should be interpreted as indicative, not nationally representative.

---

## Repository Contents

```
.
├── Clean_data_-_Form_responses_1.csv   # Cleaned survey data (335 rows)
├── DNA.ipynb                           # Full analysis notebook
├── figures/                            # All charts used in this README
└── README.md                           # This file
```

---

## About

This research was conducted independently during a gap year. It is ongoing, with a paper currently in preparation for submission to a peer-reviewed journal.

If you are interested in this data, feel free to reach out or open an issue on this repository.

---

*If you went through JEE/NEET preparation yourself and want to share your experience, the survey is still open.*
