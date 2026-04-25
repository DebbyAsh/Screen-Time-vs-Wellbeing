# Screentime and Wellness
## 📑 Table of Contents
- [Introduction](#Introduction)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Methodology](#methodology)
  - [Data Preprocessing](#data-preprocessing)
  - [Visualizations](#visualizations)
  - [Feature Extraction](#feature-extraction)
  - [Modeling](#modeling)
  - [Evaluation](#evaluation)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Future Work](#future-work)

## Introduction
This project explores the relationship between daily screen time and mental wellness using real-world behavioral data.
The analysis examines how screen exposure influences:
- sleep quality
- stress
- productivity
- exercise
- social life
- overall mental wellness



## Problem Statement
How does daily screen time and its composition between work and leisure use affect mental wellness, and can we accurately predict an individual's mental wellness index from their digital habits and lifestyle factors?"
More specifically, this work addresses three connected questions:
**The core problem:** Screen time is rising globally, but its relationship with mental health is poorly understood at the individual level. Simply saying "screens are bad" ignores how people use them, how much sleep they have, how stressed they are, and how active they are. There's no clear, data-driven picture of which factors matter most.
**The analytical question:** Which digital and lifestyle variables (stress, sleep, exercise, social time, screen type) are most strongly associated with mental wellness, and how do they interact?
**The predictive question:** Can a machine learning model accurately predict a person's mental wellness index (0–100) from these measurable factors well enough to be practically useful?

## Dataset
The dataset comprises of 15 variables
|Field                           | Description                                               |
|--------------------------------|-----------------------------------------------------------|
|1. user_id                      |   Participant                                             |
|2. IDage                        |   Age in years                                            |
|3. gender                       |  Male / Female / Non-binary                               |
|4. occupation                   |  Employed / Student / Self-employed / Unemployed / Retired|
|5. work_mode                    |    Remote / Hybrid / In-person                            |
|6. screen_time_hours            |  Total daily screen time (hours)                          |
|7. work_screen_hours            |   Work-related screen time                                |
|8. leisure_screen_hours         |  Leisure / entertainment screen time                      |
|9. sleep_hours                  |  Nightly sleep duration                                   |
|10. sleep_quality_1_5           |   Self-reported sleep quality (1–5)                       |
|11. stress_level_0_10           |  Self-reported stress (0–10)                              |
|12. productivity_0_100          |  Self-reported productivity (0–100)                       |
|13. exercise_minutes_per_week   | Weekly exercise (minutes)                                 |
|14. social_hours_per_week       | Face-to-face social time (hours)                          |
|15. mental_wellness_index_0_100 | Target , composite wellness score                         |
## Methodology 
