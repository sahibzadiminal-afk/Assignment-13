# ICA-F26 • The Prices Desk
## Assignment 3: Two Averages, One Argument

**Student:** Sahibzadi Minal Ghori  
**Rep:** 37170

### Submission contents
1. `0_cover.md` — cover and data note
2. `1_attempt.md` — referee note with O/E/C labels
3. `2_work.ipynb` — reproducible cleaning, calculations, and sensitivity analysis
4. `3_log_reflection.md` — interpretation audit, classmate dialogue, and reflection
5. `teaching_prices_clean_corrected.csv` — cleaned dataset derived from the supplied original
6. `teaching_prices_messy_original.csv` — unchanged source file

### Data provenance and cleaning summary
The supplied original file is the source of truth. It contains 97 rows, four item labels (including a capitalization variant), two cities, and 12 weekly dates from 1 January to 19 March 2026. The previous cleaned file was not used because it contained a different set of items and dates (2025) and could not have been derived from this original.

The corrected file removes 1 exact duplicate row, standardizes the capitalization of item names, parses the comma-formatted `1,250` as numeric 1250, and retains the missing price as missing. It does **not** silently replace suspicious values. The value 9,999 is retained and flagged for sensitivity analysis; 1,250 and 108.5 are also marked for review. The teaching-data label says these are illustrative data, not actual PBS observations.

### Important limitation
The assignment refers to a “Week 2 cleaned file.” No separate Week 2 file was supplied. For the requested with/without flagged-value comparison, this submission uses the supplied original dataset after transparent cleaning and uses 9,999 as the flagged extreme value. This is an explicit proxy, not a claim that it is the missing Week 2 file.

### Attempt-before-AI integrity note
This document set was prepared with AI assistance after the original and cleaned files were uploaded. The referee note is a draft based on the data, not a timestamped record of work completed before AI assistance. Do not represent it as a genuine pre-AI artifact.
