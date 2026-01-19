# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: #3

Describe the purpose of your survey:
```
write your answer here...
This survey investigates how music taste and perceptions of “popular music” vary across age groups, and how individuals believe their own music preferences have changed over their lifetime. The goal is to separate (a) differences between cohorts (e.g., teens vs. middle-aged adults) from (b) within-person change (retrospective shifts in taste over time).


Describe your target population, sampling frame, sampling units, and observational units:
```
write your answer here...
```
Target population:
All people aged 15+ living in Canada (private households), regardless of student status.

Sampling frame:
A practical, mixed frame combining (1) a Canadian online research panel with demographic targeting (age, province, language), plus (2) the University of Toronto participant pool (students/staff/community members) as a supplementary frame. Because the UofT pool will not represent Canada, it will be treated as supplemental and flagged for separate analysis or down-weighting.

Sampling units:
Individuals (one completed questionnaire per person).

Observational units:
Individuals (the respondent). Retrospective questions create multiple “time points” per person (e.g., their taste at age 15, 25, etc.), but the unit remains the respondent.

Overall sampling strategy:
Stratified probability-style sampling by age group to ensure enough respondents in each cohort (e.g., 15–17, 18–24, 25–34, 35–44, 45–54, 55–64, 65+). Within each age stratum, recruit approximately equal numbers (disproportionate allocation) to improve comparisons; then apply post-stratification weights to align the final sample with known population age/sex/province totals (from Census estimates). This strategy is justified because age is the key explanatory variable, and balanced strata reduce variance and improve subgroup comparisons.

Your 5-10 question survey:
```
1. What is your age?  (open numeric) 
   Optional: Which age group best describes you? (15–17, 18–24, 25–34, 35–44, 45–54, 55–64, 65+)

2. In the past 30 days, how often have you listened to music? 
   (Never, Less than weekly, 1–2 days/week, 3–5 days/week, Daily)

3. Which THREE genres do you listen to most often right now? (select up to 3)
   (Pop, Rock, Hip-hop/Rap, R&B/Soul, Electronic/Dance, Country, Jazz, Classical, Metal, Indie/Alternative, K-pop, Latin, Folk, Other: ____)

4. Thinking about “popular music today” (current mainstream hits), how much do you agree with each statement?
   a. “Popular music today is high quality.” 
   b. “Popular music today feels repetitive.” 
   c. “Popular music today is better than popular music when I was younger.”
   (5-point Likert: Strongly disagree → Strongly agree)

5. At what age did you feel most connected to new popular music releases? 
   (Under 13, 13–17, 18–24, 25–34, 35–44, 45–54, 55+)

6. Compared to when you were 15–17 years old, how has your music taste changed overall?
   (No change, Small change, Moderate change, Large change, Completely different, Not applicable/Don’t remember)

7. Retrospective “top genre” check: For each age period, what genre did you listen to most? 
   a) 15–17  b) 18–24  c) 25–34  d) 35–44  e) 45+ 
   (same genre list as Q3 + “Don’t remember”)

8. What influences your music choices the most right now? (select up to 2)
   (Friends/family, Social media, Radio/TV, Streaming recommendations, Live events, Personal mood/mental focus, Cultural identity, Other: ____)


## Part B - Survey Evaluation:

Identify and describe survey features:

```
write your answer here
```
1. Sample type.
Cross-sectional probability sample with stratified design province and CMA strata and two-stage selection household then one person.
Includes a rejective sampling element subsampling among non-volunteers to manage prevalence and burden.

2. Sample size.
StatCan reports a field sample of about 50,000 units, with about 40,000 invitation letters for the electronic questionnaire and an expected completion of about 24,000 questionnaires. The same documentation reports an overall response rate of 41.9 percent, which implies an achieved completed sample on the order of about 21,000. This is approximate because the exact final respondent count is not stated in the excerpt.

3. Target population.
People aged 15 plus living in private households in the 10 provinces, excluding full-time institutional residents, and excluding territories.

4. Sampling frame.
Frame combines landline and cell phone numbers from Census and administrative sources linked with Statistics Canada’s dwelling frame. Records are groups of phone numbers associated with an address, or a single number if address linkage is unavailable.

5. Survey modes.
Electronic questionnaire self-completed online.
CATI computer-assisted telephone interviewing.

6. Timeline.
Collection dates. 2018-09-04 to 2018-12-28.
Reference period. Past 12 months preceding interview date.

7. Response rate.
Overall response rate. 41.9 percent.

8. Weights.
Person-level analysis weight. WGHT_PER basic person weight.
Bootstrap weights provided for design-based variance estimation.
Weighting includes adjustments related to rejective sampling and calibration so estimates represent the target population. Documentation also notes adjustment so the weighted income distribution matches the 2017 CIS distribution by province.

9. Data processing.
Processing used SSPE generalized processing steps and utilities. Edits performed automatically and manually, including family, consistency, and flow edits. The CATI instrument included built-in edits and range checks.

10. Cleaning and imputation.
Imputation primarily via donor imputation nearest-neighbour style using a score function, with mean imputation when donor imputation was not possible.
Imputation described as occurring in nine steps including income, volunteering variables, and donation file variables.
Income. Personal income questions were not asked. Income obtained via tax linkage 2017 T1FF for 81.9 percent of respondents and remaining missing income imputed.

11. Sources of error.
Sampling error handled via bootstrap variance estimation.
Non-sampling error including coverage error for example households without telephones, non-response, response errors, and processing errors.

12. Limitations and known biases.
Telephone coverage limitations. Households without telephones or not covered by the frame are excluded from the surveyed population, which can bias results if excluded groups differ systematically.
Low response rate 41.9 percent increases risk of nonresponse bias even with weighting adjustments.
Population coverage limits. Excludes territories and full-time institutional residents.
Potential mode effects online versus phone, plus recall and social desirability bias for volunteering and donating topics.

13. Documentation and additional sources.

## References
[1] Statistics Canada. General Social Survey (GSS), Cycle 33: Giving, Volunteering and Participating, 2018. Survey metadata and methodology (IMDB). Accessed 2026-01-18. 
[2] Statistics Canada. General Social Survey on Giving, Volunteering and Participating, 2018 (Cycle 33). Public Use Microdata File (PUMF) documentation and user guide. Accessed 2026-01-18. 


## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 14 January 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
