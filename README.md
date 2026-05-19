# Goal & Age Differential in European Football (Sampling & Confidence Intervals)

## Overview
This project compares player characteristics and performance across several European football leagues during the 2022–2023 season using statistical sampling methods. The analysis evaluates how sample size affects summary statistics and 95% confidence intervals when estimating population means.

## Objective
- Compare league-level distributions of **Age** and **Goals**
- Evaluate whether confidence intervals capture true population means
- Compare results from:
  - A fixed sample size (n = 20)
  - A proportional sample size (n ≈ 10% of league population)

## Data
- Source: **FBref** player statistics (2022–2023 season)
- Each league treated as a population
- Included players appearing in at least 16 matches to reduce bias from limited participation
- Variables included age, goals, assists, minutes played, penalties, yellow cards, and red cards

## Methodology
- Applied **Simple Random Sampling (SRS)** within each league
- Constructed two sampling frameworks:
  1. Fixed sample size (n = 20)
  2. Population-scaled sample size (n ≈ 0.10 × N)
- Computed descriptive statistics and **95% confidence intervals** for Age and Goals
- Compared interval width, variance, and population mean coverage across sample structures

## Key Findings
- Larger proportional samples generally produced narrower confidence intervals
- Fixed n = 20 samples occasionally failed to capture population characteristics, particularly for skewed variables such as Goals
- Results demonstrated how sample size and population variability influence statistical precision and representativeness

## Tools Used
- Microsoft Excel

## Files
- `Final_project.pdf` — full write-up including methodology, summary statistics, confidence intervals, and conclusions
