# FitLife Product Analytics: Sentiment Analysis & Roadmap Prioritization

This repository contains a complete, data-driven product strategy lifecycle for FitLife, a Health & Fitness mobile application. The project addresses a common "leaky bucket" problem: high user acquisition but low Day-7 retention (~22%). 

Using Natural Language Processing (NLP), text mining, and structured prioritization frameworks, this project analyzes competitor app reviews to uncover user pain points and design a high-impact, 6-month product roadmap verified by an A/B test strategy.

---

## 📁 Repository Structure

### 1. Data Analytics & Notebooks
* `M1_Sentiment_Analysis.ipynb`: Handles text cleaning and implements VADER Sentiment Analysis to evaluate competitor review distributions across rating brackets.
* `M2_Topic_Analysis.ipynb`: Conducts text preprocessing, lemmatization, and TF-IDF keyword extraction to categorize explicit feature praises and technical complaints.
* `M3_RICE_Prioritization.ipynb`: Employs the RICE scoring framework to mathematically evaluate engineering effort against potential user reach and impact.

### 2. Strategic Reports & Deliverables
* `Milestone_1_Sentiment_Analysis_Report.pdf`: Validates the reliability of the VADER sentiment signals against historical user ratings.
* `Milestone_2_Topic_Extraction_Report.pdf`: Unpacks granular feature sentiment (e.g., finding that *Offline Mode* and *Bug/Technical* issues drive the lowest polarity scores).
* `Milestone_3_Feature_Prioritization_Report.pdf`: Ranks the product backlog, identifying a "Rest timer between sets" as the primary quick-win feature.
* `Milestone_4_Product_Strategy.pdf`: Sets up the rigorous A/B testing framework to measure retention uplifts.

### 3. Execution & Dashboards
* `M4_Product_Dashboard.twbx`: A consolidated Tableau dashboard visualizing sentiment metrics, RICE scores, and experiment parameters.
* `M4_Presentation.pptx`: Strategic slide deck highlighting the journey from raw text data to quantifiable growth metrics.

---

## 🛠️ Tech Stack & Methodologies
* Languages: Python (Pandas, NumPy, NLTK, Matplotlib, Seaborn)
* NLP Tools: VADER Sentiment Analysis, TF-IDF Vectorization, Lemmatization
* Frameworks: RICE Prioritization (Reach, Impact, Confidence, Effort)
* Data Visualization: Tableau Desktop (`.twbx`)
* Experimentation: Two-proportion z-test framework ($\alpha = 0.05$, Power = $80\%$)

---

## 📈 Strategic Outcomes & Roadmap Summary
* The Quick Win: "Rest timer between sets" emerged as the top feature with a RICE score of 4,646 due to high reach and minimal implementation effort (1 person-month).
* The Experiment: A planned 50/50 randomized split A/B test targeting a Day-7 retention increase from 22% to 27% over a 21–28 day tracking window (Sample size: 2,152 total users).
* 6-Month Roadmap: 
    * Month 1: Rest Timer development & Experimentation
    * Month 2: Dark Mode UI Themes implementation
    * Months 3–5: Advanced Nutrition/Meal Planning development
    * Month 6: Voice Guidance & Video Demonstrations rollout
