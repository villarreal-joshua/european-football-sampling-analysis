# Goal & Age Differential in European Football (Sampling & Confidence Intervals)

## Overview
This project compares player characteristics and performance across several European football leagues (2022–2023 season) using sampling methods. The goal was to evaluate how different sample sizes affect summary statistics and 95% confidence intervals when estimating population means.

## Objective
- Compare league-level distributions of **Age** and **Goals**
- Assess whether confidence intervals from samples capture the true population mean
- Compare results from:
  - A fixed sample size (n = 20)
  - A proportional sample size (n ≈ 10% of league population)

## Data
- Source: **FBref** player statistics (2022–2023 season)
- Each league treated as a population
- Included players who appeared in **at least 16 matches** to reduce bias from limited participation
- Key variables: Player position, age, minutes played, goals, assists, cards, penalties, etc.

## Methodology
- **Simple Random Sampling (SRS)** used for each league
- Two sampling approaches:
  1. **Sample 1:** n = 20 (constant across leagues)
  2. **Sample 2:** n ≈ 0.10 × N (scaled with league population size)
- Computed descriptive statistics and **95% confidence intervals** for Age and Goals
- Compared confidence interval width and coverage across leagues and sample sizes

## Key Findings
- Larger proportional samples generally produced **narrower confidence intervals**
- Fixed n=20 samples sometimes failed to capture population characteristics (especially for skewed variables like Goals)
- Results highlighted how sample size interacts with population variability and distribution shape

## Files
- `Final_project.pdf` — write-up with results, tables, and conclusions
- (Optional) spreadsheets used for computation

## Tools Used
- Microsoft Excel (sampling, summaries, confidence intervals)
