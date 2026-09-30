# econ5200-lab04-outlier-pipeline
# Outlier Detection on California Housing

## Objective
I set out to find unusual records in the California Housing dataset by comparing three outlier-detection methods and deciding which one fits this data best.

## Methodology
- I diagnosed and fixed three bugs in an existing outlier-detection pipeline.
- I used an `OutlierDetector` class that supports three methods: modified Z-score, Tukey fences, and Isolation Forest. The class checks its settings before running and reports a summary of what it flagged.
- I ran the modified Z-score and Tukey fences on the MedInc (median income) column.
- I ran Isolation Forest on all 9 columns.
- I compared the flagged records across the three methods to see where they agreed.
- I wrote a method-selection memo explaining which method I would use and why.
- I built an interactive outlier method explorer for comparing the methods side by side.

## Key Findings
- The modified Z-score flagged [YOUR VALUE] records on MedInc.
- Tukey fences flagged [YOUR VALUE] records on MedInc.
- Isolation Forest flagged [YOUR VALUE] records across all 9 columns.
- All three methods agreed on [YOUR VALUE] records.
- In my method-selection memo, I recommended [YOUR VALUE].
