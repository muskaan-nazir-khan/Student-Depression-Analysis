# Student-Depression-Analysis

This project focuses on analyzing the key factors contributing to depression among students using survey-based data. The analysis was performed using SQL for data preparation and Tableau for interactive visualization. The objective is to uncover patterns in mental health indicators such as sleep duration, academic pressure, study satisfaction, screen time, and financial stress — ultimately helping educational institutions identify at-risk students and build proactive support systems.

<img width="741" alt="student depression dashboard" src="https://github.com/user-attachments/assets/fe39de80-1701-4699-b06b-020e62292e03" />


In the SQL stage, I imported and cleaned the survey data by standardizing categorical values, removing null or invalid records, and joining relevant tables. Key attributes such as Sleep Duration, Study Hours, Academic Pressure, Study Satisfaction, and Financial Stress were extracted and structured for deeper analysis. The cleaned data was exported into Tableau for visualization.

In the Tableau stage, I designed an interactive dashboard presenting segmented visual insights across various stressors. Each chart visualizes how student counts are distributed across different levels of sleep, study, academic pressure, and financial situations. This dashboard allows institutions to understand trends at a glance and apply filters by factor type to analyze specific subgroups

# Key Insights:
~ Sleep Duration(SD) Patterns:

1.Students getting 7–8 hours or more than 8 hours of sleep each have a count of 128, which is higher than those with 5–6 hours or less than 5 hours (both at 123).

2.Despite the assumption that longer sleep improves mental health, the equal distribution suggests that oversleeping may be linked to low energy or depressive                 symptoms rather than recovery

~ Study Hours(SH) Distribution:

1.The number of students gradually increases with study hours, peaking at 10 hours (53 students), and staying high from 8–12 hours (45–46 students).

2.This trend suggests that moderate-to-high study engagement correlates with larger student groups, but it may also point to academic stress buildup in those                   studying beyond 8–10 hours.

~ Study Satisfaction(SS) Levels:

1.Study Satisfaction score 4 has the highest count (116 students), indicating that a good portion of students are reasonably satisfied.

2.However, over 180 students reported scores of 1 and 2, meaning that almost one-third of students are dissatisfied with their study experience, potentially a                  red flag for mental health risks.

~Academic Pressure(AP) Trends:

1.The majority of students report moderate academic pressure (AP-3, 125 students).

2.High-pressure scores AP-5 (98 students) and AP-4 (92) indicate that close to 200 students experience high academic stress, which is a significant mental health               risk factor.

~ Financial Stress(FS) Distribution:

1. Low financial stress (FS-1) is reported by 110 students, which is the highest count among all levels.

2. Stress levels FS-2 to FS-5 remain consistently around 94–102 students, implying that while financial stress is present, it's not the dominant pressure for most                students.

# Recommendations:
~ Mental wellness programs should target students with low study satisfaction (SS-1 and SS-2) and high academic pressure (AP-4/5), since these groups represent those at potential mental health risk

~ Sleep monitoring and awareness workshops should be introduced. Students getting less than 6 hours or more than 8 hours of sleep might need counseling to improve daily routines and manage stress

~ Consider offering time management support to students with low study hours (0–3), as they may be underperforming or demotivated. These students may benefit from tutoring or peer mentorship

~ Even though financial stress is moderate, providing access to financial aid counseling can further ease stressors for students scoring FS-4 or FS-5

~ Prioritize academic counseling and workload balance for students scoring high on academic pressure (AP-4/5), as they likely experience burnout and performance anxiety

This project demonstrates how combining SQL with Tableau can turn sensitive student mental health data into actionable insights, enabling administrators and counselors to identify at-risk groups and respond with data-driven support strategies
