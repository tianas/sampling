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

The number of your chosen topic: `3`

Describe the purpose of your survey:
```
The purpose of my survey is to explore how age influences music taste, with a focus on perceptions of popular music. It compares music taste across different age cohorts and keeps track of self-reported preferences in individual music taste throughout their lifetime. I will conduct convenience sampling by recruiting participants online using Prolific.co, which hosts a large database of eligible, verified participants (and, from my research experience, meets U of T's ethics protocols).
```

Describe your target population, sampling frame, sampling units, and observational units:
```
The target population is adult Canadians, i.e., individuals aged 18 and above who are residing in Canada. The sampling frame is the Prolific.co participant pool of individuals who report being 18 years of age or older and are residing in Canada at the time of initial recruitment (as this study will require follow-up reporting over the span of the participants' lifetimes). I will stratify individuals into age groups (e.g., 18-30 years, 31-45 years, 46-60 years, 61+ years) and will set an equal number of participants per age group (_n_=50) to ensure the comparison groups are proportionate. Sampling units are individuals who participate in the survey and reside in Canada within each age stratum. Observational units are the same individuals within the survey population (i.e., the sampling units). Notably, participants will undergo systematic sampling, where they will all be sampled in fixed intervals (e.g., every 10 years as they transition into or near the next age group).
```

Your 5-10 question survey:
```
1. On a scale of 1-7, with 1 being "not at all" and 7 being "very often", how often do you listen to music that was released within the last two years?
2. Which of the following options best describes how you currently discover new music? Select all that apply: (radio, friends/family, social media, streaming algorithms, I do not seek new music)
3. In your opinion, which decade had the best popular music in history? (e.g., 1970s, 1990s, 2010s...)
4. "I find it harder to discover new music I like now than I did ten years ago." (Likert scale selection: "strongly disagree" to "strongly agree")
5. What is/are your favourite genre(s) right now?
6. How much of your current weekly listening consists of music from the genres mentioned in Question 5? (0% to 100%)
7. What is/are your favourite musical artist(s) right now?
8. How much of your current weekly listening consists of music from the artists mentioned in Question 7? (0% to 100%)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type - stratified random sampling (e.g., stratification is done at the province/census metropolitan area level, and info is collected from one randomly selected household member aged 15+).
2. Sample size -  16,149 respondents.
3. Target population - Persons aged 15 years and older living in the ten provinces of Canada, excluding full-time (residing for more than six months) residents of institutions.
4. Sampling frame - Combined landline and cellular telephone numbers from the Census, and various administrative sources with Statistics Canada's dwelling frame. Records on this frame are groups of one or more telephone numbers associated with the same address, or a single telephone number in case a link between a phone number and address couldn't be established.
5. Survey mode(s) - Collected directly from respondents either through an electronic questionnaire or through CATI (computer-assisted telephone interviewing) in either English or French as selected by respondents. 
6. Timeline - 2018-09-04 to 2018-12-28.
7. Response rate - 41.9%.
8. Weights - (1) Person-level estimation weights (WGHT_PER), which ensures the results represent the Canadian population with regard to certain characteristics. (2) Bootstrap weights for design-based variance estimation.
9. Data processing - Automated and manual processing after collection. Write-in responses where either coded based on existing coding categories where a match was possible, grouped into new categories, or left in "other-specify" if there was no match OR if frequencies were too small to create a new category. Where possible, coding followed standard systems used by the GSS and Stats Canada. Organizations in the volunteering and giving sections were coded following the ICNPO.
10. Cleaning, imputation, etc:
- Daily files were combined into a raw survey file. Duplicated, non-response, and out-of-scope records were dropped before processing.
- Out-of-range values were identified by the CATI system. Other edits were performed automatically and manually at various stages of processing, both at macro and micro levels. For example, family relationships were checked to ensure data integrity, and respondent age was checked against birth date. Error detection was also done by the CATI system, which allowed issues to be resolved by the respondent. However, if the interviewer couldn't correctly resolve the detected errors, the interviewer bypassed the edit and forwarded the data to head office for resolution. Head office performed the same checks and other more detailed edits.
- All imputations were made using donor records selected through a score function, and certain characteristics on each recipient were compared with those of the donor record. When a characteristic was the same on both the donor and recipient records, the donor's score increased. The donor record with the highest score was deemed the 'nearest donor' and was selected to fill in missing information of the non respondent individual. In cases where there was more than one donor record with the highest score, one was randomly selected. When donor imputation couldn't be used, mean imputation among a pool of donors was used. This was done in nine steps (Step 1: imputing personal income and family income; Steps 2-4: imputing formal volunteering variables in the master file; Steps 5-6: imputing informal volunteering variables into the master file; Steps 7-9: imputing variables in the donation file and the solicitation methods in the master file. Finally, 18.3% of households were missing family income data, and this was imputed.
12. Limitations, known biases, etc. - One limitation was imperfect coverage (differences between the target population and the surveyed population), for example, households without telephones or households with telephone services not covered by the sampling frame were excluded from the surveyed population, and thus is a known limitation and bias. There was also non-response bias that occurred both at the household level and at the individual level.
13. Link to documentation and any additional sources used: Documentation - https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234, Public Use Microdata File User Guide - https://www150.statcan.gc.ca/n1/pub/45-25-0001/cat5/c33_2018.zip
```

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
- [x] Create a branch called `assignment-2`.
- [x] Ensure that the repository is public.
- [x] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [x] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
