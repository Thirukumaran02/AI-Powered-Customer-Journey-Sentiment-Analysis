# AI-Powered-Customer-Journey-Sentiment-Analysis

Project Overview

This project aims to analyze customer feedback from multiple sources (reviews, surveys, social media, and support tickets) and map it to different stages of the customer journey. By applying AI-powered sentiment analysis, the project helps organizations identify pain points, improve customer experience, and make data-driven business decisions.

Objectives


1.Collect and preprocess customer feedback data from various channels.

2.Perform sentiment analysis using NLP and AI models to classify feedback (positive, negative, neutral).

3.Map sentiments to customer journey stages (onboarding, purchase, delivery, after-sales).

4.Design a dashboard/visualization to provide actionable insights.

5.Deliver an action plan for improving customer satisfaction and reducing churn.

Tech Stack


1.Programming Language: Python

2.Libraries & Frameworks: Pandas, NumPy, Scikit-learn, NLTK / SpaCy, Transformers (Hugging Face)

3.Data Visualization: Power BI / Matplotlib / Seaborn

4.Database: SQL / PostgreSQL

5.Project Management: Jira

6.Version Control: GitHub

AI-Powered Customer Journey & Sentiment Analysis Dashboard

with Jira, Python, Snowflake, Google Colab, Power BI, and GitHub

Step 1 — Planning with Jira

Created a project board in Jira.

Defined epics: Data Preparation, Modeling, Dashboard, Deployment.

Broke down into stories/tasks: dataset prep, Snowflake schema, NLP modeling, KPI design, dashboard build, GitHub push.

Used Jira to track progress like a real IT project.

Step 2 — Dataset Preparation (Python)

Collected Amazon reviews dataset (CSV).

Cleaned text: removed duplicates, nulls, emojis, special characters.

Standardized formats (date, product ID, language).

Finalized dataset ready for database ingestion.

Step 3 — Data Loading into Snowflake

Designed schema for amazon_reviews.

Created tables in Snowflake.

Loaded cleaned CSV data using COPY INTO.

Ensured staging area and data warehouse were properly structured.

Step 4 — Analysis with Google Colab (Python NLP + SQL)

Connected Google Colab to Snowflake.

Performed sentiment analysis (VADER / ML models).

Classified reviews into customer journey stages (Purchase, Delivery, Support).

Calculated business KPIs (NPS, CSAT, churn risk).

Used Colab for experimentation and visualization.

Step 5 — Storing Analyzed Data in Snowflake

Enriched reviews with new columns: sentiment, journey_stage, sentiment_score, etc.

Saved the processed results back into Snowflake tables.

Created views for KPIs, sentiment breakdown, and stage analysis.

Step 6 — Power BI Dashboard
6.1 Data Modeling

Connected Power BI directly to Snowflake.

Created relationships between fact tables (reviews) and dimension tables (products, time, language).

6.2 Transformations

Applied Power Query transformations: filtering, KPI aggregations, DAX calculations.

Built visuals:

KPI cards (NPS, CSAT, % Positive Sentiment)

Sentiment trends over time

Funnel charts (Awareness → Purchase → Delivery → Support)

Heatmap of sentiment by product & region

Word clouds for top complaints

Step 7 — Source Code & Versioning in GitHub

Uploaded Python scripts, SQL queries, Power BI file, and documentation into a public/private GitHub repository.

Structured repo with clear folders:

src/ for scripts

sql/ for queries

dashboard/ for Power BI reports

docs/ for write-ups and architecture diagrams

Ensured reproducibility and collaboration readiness.
