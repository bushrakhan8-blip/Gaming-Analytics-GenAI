# 🤖 AI-Assisted Gaming Data Analysis

## Overview
An individual project exploring how **Generative AI** tools (ChatGPT / Google Gemini) can be integrated into a data analysis workflow. Using the same gaming dataset from previous project, this project demonstrates how AI can assist with SQL generation, data summarisation, and automated report writing — while critically evaluating the accuracy of AI outputs.

## Dataset
Three tables from the gaming dataset:
- `games_description` — game metadata including genre, publisher, and release year
- `games_revenue` — sales data with unit prices and purchase counts
- `games_reviews` — player feedback, engagement hours, and review counts

## Tasks Completed
- **Automated Summarisation** — used Generative AI to analyse game release year trends and identify the most common publishers from the dataset
- **AI-Generated SQL for Data Cleaning** — prompted AI to write SQL statements correcting genre inconsistencies (`Actioned` → `Action`, `Strategies` → `Strategy`), then validated and refined the outputs
- **AI-Generated SQL for Data Merging** — used AI to generate JOIN statements merging all three tables on `game_id`, with prompt refinement where needed
- **Automated Report Generation** — prompted AI to produce a structured analysis report identifying the top 5 games by revenue and reviews within each genre, and cross-referencing overlap between both rankings
- **AI Learnings & Reflections** — documented best practices around prompt engineering, output validation, and the limitations of using Generative AI in data analysis

## Tools & Skills
`MySQL` · `ChatGPT / Google Gemini` · `Prompt Engineering` · `SQL Data Cleaning` · `SQL Joins` · `AI-Assisted Reporting` · `Output Validation`
